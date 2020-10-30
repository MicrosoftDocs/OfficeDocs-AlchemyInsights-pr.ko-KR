---
title: 강력한 암호 요구 사항 변경
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 8ce331275e066b5a4f177ae27178ec726f90762f
ms.sourcegitcommit: aa35d2e1829f7d07f64fb891bf73b1fd80f0864c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/30/2020
ms.locfileid: "48804429"
---
# <a name="change-strong-password-requirement"></a><span data-ttu-id="04e4c-102">강력한 암호 요구 사항 변경</span><span class="sxs-lookup"><span data-stu-id="04e4c-102">Change strong password requirement</span></span>

<span data-ttu-id="04e4c-103">Microsoft는 기본적으로 강력한 암호를 요구 합니다.</span><span class="sxs-lookup"><span data-stu-id="04e4c-103">Microsoft requires strong passwords by default.</span></span>

<span data-ttu-id="04e4c-104">PowerShell을 사용 하 여 다음 명령을 사용 하 여 특정 사용자에 대해 강력한 암호를 사용 하지 않도록 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="04e4c-104">Using PowerShell, you can disable strong passwords for specific users with these commands:</span></span>

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

<span data-ttu-id="04e4c-105">모든 사용자에 대해 강력한 암호를 사용 하지 않도록 설정 하려면 다음을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="04e4c-105">To disable strong passwords for all users, use:</span></span>

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [<span data-ttu-id="04e4c-106">암호 정책에 대 한 추가 정보</span><span class="sxs-lookup"><span data-stu-id="04e4c-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="04e4c-107">PowerShell을 사용 하 여 Microsoft 365에 연결 하는 방법</span><span class="sxs-lookup"><span data-stu-id="04e4c-107">How to connect to Microsoft 365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="04e4c-108">PowerShell Get-msoluser 명령에 대 한 추가 정보</span><span class="sxs-lookup"><span data-stu-id="04e4c-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
