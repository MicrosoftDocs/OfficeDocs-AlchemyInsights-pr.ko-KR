---
title: 조건부 액세스 정책
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002357"
- "4583"
ms.openlocfilehash: af95627d07d41add54f03c9254562b9be4e05d9b
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51817286"
---
# <a name="conditional-access-policies"></a><span data-ttu-id="eb14e-102">조건부 액세스 정책</span><span class="sxs-lookup"><span data-stu-id="eb14e-102">Conditional Access policies</span></span>

<span data-ttu-id="eb14e-103">조건부 액세스는 사용자 환경의 앱 액세스에 대한 제어할 수 있도록 해 주는 Azure AD의 기능입니다. 이 기능은 특정 조건을 기반으로 하며 중앙 위치에서 관리됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb14e-103">Conditional Access is a capability of Azure AD that enables you to enforce controls on the access to apps in your environment, all based on specific conditions and managed from a central location.</span></span>

<span data-ttu-id="eb14e-104">[Azure AD 조건부 액세스](https://docs.microsoft.com/azure/active-directory/conditional-access/)에 대해 자세히 알아보세요.</span><span class="sxs-lookup"><span data-stu-id="eb14e-104">Learn more about [Azure AD Conditional Access](https://docs.microsoft.com/azure/active-directory/conditional-access/).</span></span>  

<span data-ttu-id="eb14e-105">**참고**: 2019년 10월 21일 이후에 테넌트를 생성했으며 MFA에 대한 메시지가 예기치 않게 표시될 경우 테넌트에서 [보안 기본값](https://aka.ms/securitydefaults)을 사용하도록 설정했을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb14e-105">**Note**: If your tenant was created after October 21st, 2019 and you're unexpectedly getting prompted for MFA, you likely have [security defaults](https://aka.ms/securitydefaults) enabled in your tenant.</span></span>

<span data-ttu-id="eb14e-106">**보안 기본값을 관리하려면**</span><span class="sxs-lookup"><span data-stu-id="eb14e-106">**To Manage security defaults**</span></span>

1. <span data-ttu-id="eb14e-107">전역 관리자 자격 증명을 사용하여 [관리 센터](https://go.microsoft.com/fwlink/p/?linkid=834822)에 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="eb14e-107">Sign in to the [admin center](https://go.microsoft.com/fwlink/p/?linkid=834822) with your Global admin credentials.</span></span>

2. <span data-ttu-id="eb14e-108">[Azure Active Directory 속성](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties)으로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="eb14e-108">Go to [Azure Active Directory Properties](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties).</span></span>

3. <span data-ttu-id="eb14e-109">페이지 맨 아래에서 **보안 기본값 관리** 를 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="eb14e-109">At the bottom of the page, click **Manage Security defaults**.</span></span>

4. <span data-ttu-id="eb14e-110">보안 기본값을 사용하도록 설정하려면 **예** 를 클릭하고, 사용하지 않도록 설정하려면 **아니요** 를 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="eb14e-110">Click **Yes** to enable security defaults or **No** to disable security defaults.</span></span>
