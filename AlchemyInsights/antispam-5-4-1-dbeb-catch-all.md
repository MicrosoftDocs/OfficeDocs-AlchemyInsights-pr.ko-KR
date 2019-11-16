---
title: 스팸 방지 5.4.1 DBEB catch-all
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001209"
- "3167"
ms.openlocfilehash: 4f531a063d63aff239ef7dead869bb526e17fb35
ms.sourcegitcommit: 2591e1f56e8943bddb9d3b77ba5b494ac49d4f30
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/15/2019
ms.locfileid: "38672439"
---
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a><span data-ttu-id="aad07-102">오류 코드 550 5.4.1 릴레이 액세스 거부에 대 한 배달 문제 수정</span><span class="sxs-lookup"><span data-stu-id="aad07-102">Fix delivery issues for error code 550 5.4.1 Relay Access Denied</span></span>

<span data-ttu-id="aad07-103">이 문제는 전자 메일 주소가 Office 365 네트워크에 들어갈 때 [bouncebacks을 방지 하기 위해 유효한 지](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) 확인할 때 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-103">This problem occurs when [checking to see if an email address is valid to prevent bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) when entering the Office 365 network.</span></span> <span data-ttu-id="aad07-104">다음을 시도합니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-104">Try the following:</span></span>

1. <span data-ttu-id="aad07-105">문제가 전체 도메인 또는 단일 전자 메일 주소에 적용 되는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-105">Determine whether the problem is specific to an entire domain or a single email address:</span></span>
    - <span data-ttu-id="aad07-106">전체 도메인: 도메인을 동기화 해야 하는 경우가 있습니다. [도메인을 Internal로 설정한 다음 다시 신뢰할](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains)수 있도록 설정 해 봅니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-106">Entire domain: Sometimes the domain needs to be synchronized; try [setting the domain to Internal and then back to Authoritative](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span></span>
    - <span data-ttu-id="aad07-107">단일 전자 메일 주소: 주소를 동기화 해야 하는 경우도 있습니다. smtp 프록시 주소를 변경한 다음 다시 변경 하면 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-107">Single email address: Sometimes the address needs to be synchronized; changing the smtp proxy address and then changing it back can help.</span></span>
2. <span data-ttu-id="aad07-108">문제가 그룹 또는 공용 폴더와 관련 된 것인지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-108">Determine whether the problem is specific to a group or public folder.</span></span> <span data-ttu-id="aad07-109">일부 개체 유형의 경우 Azure Active Directory에서 개체를 수동으로 만들어야 할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-109">For some object types, the objects may need to be manually created in Azure Active Directory.</span></span>

<span data-ttu-id="aad07-110">추가 도움이 필요한 경우 지원 티켓을 열고 문제 범위 (includidng 개체 유형)를 지정 하 여 더 효율적으로 지원할 수 있도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="aad07-110">If you need additional help, please open a support ticket and specify the scope of the issue (includidng the type of object you're sending to) so we can assist you better.</span></span>