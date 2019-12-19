---
title: 공용 폴더에 액세스할 수 없음
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: a9305b175e1ca0b992c014a73705447d67e037bc
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959500"
---
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="38400-102">Outlook에서 공용 폴더에 연결할 수 없음</span><span class="sxs-lookup"><span data-stu-id="38400-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="38400-103">소수의 사용자가 공용 폴더 액세스가 작동 하지 않는 경우 다음을 시도해 보세요.</span><span class="sxs-lookup"><span data-stu-id="38400-103">If public folder access isn't working for few users, try the following:</span></span>

<span data-ttu-id="38400-104">EXO PowerShell에 연결 하 고 문제 사용자 계정에 대해 DefaultPublicFolderMailbox를 구성 하 여 작업 중인 사용자 계정에 대해 일치 시킵니다.</span><span class="sxs-lookup"><span data-stu-id="38400-104">Connect to EXO PowerShell, and configure the DefaultPublicFolderMailbox on the problem user account to match one on a working user account.</span></span>

<span data-ttu-id="38400-105">예제:</span><span class="sxs-lookup"><span data-stu-id="38400-105">Example:</span></span>

<span data-ttu-id="38400-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox, EffectivePublicFolderMailbox</span><span class="sxs-lookup"><span data-stu-id="38400-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="38400-107">Set-Mailbox ProblemUser-DefaultPublicFolderMailbox \<값을 이전 명령>에서</span><span class="sxs-lookup"><span data-stu-id="38400-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="38400-108">변경 내용이 적용 되려면 한 시간 이상 기다립니다.</span><span class="sxs-lookup"><span data-stu-id="38400-108">Wait at least one hour for the change to take effect.</span></span>