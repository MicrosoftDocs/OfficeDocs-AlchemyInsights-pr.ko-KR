---
title: API를 사용하는 응용 프로그램 개발 문제
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/25/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004343"
- "7755"
ms.openlocfilehash: 26d732819b64efa4fb84da44cc2a279368aa28b0
ms.sourcegitcommit: 605a73b159d30634b064c1b63b0e734ceb3fdec8
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/25/2021
ms.locfileid: "49951928"
---
# <a name="issues-developing-applications-with-apis"></a><span data-ttu-id="1ed48-102">API를 사용하는 응용 프로그램 개발 문제</span><span class="sxs-lookup"><span data-stu-id="1ed48-102">Issues developing applications with APIs</span></span>

<span data-ttu-id="1ed48-103">Azure Active Directory Graph API 사용을 시작하거나 [Azure AD Graph API](https://docs.microsoft.com/azure/active-directory/develop/microsoft-graph-intro) 빠른 시작 가이드를 참조하거나 대화형 Azure AD Graph API 참조 [설명서를 봐야 합니다.](https://docs.microsoft.com/previous-versions/azure/ad/graph/api/api-catalog)</span><span class="sxs-lookup"><span data-stu-id="1ed48-103">To begin using the Azure Active Directory Graph API, see the [Azure AD Graph API quickstart guide](https://docs.microsoft.com/azure/active-directory/develop/microsoft-graph-intro) , or view the [interactive Azure AD Graph API reference documentation](https://docs.microsoft.com/previous-versions/azure/ad/graph/api/api-catalog).</span></span>

<span data-ttu-id="1ed48-104">**Azure ADAL(Active Directory 인증 라이브러리) 및 Azure AD Graph API(AAD Graph)에 대한 지원 종료**</span><span class="sxs-lookup"><span data-stu-id="1ed48-104">**End of support for Azure Active Directory Authentication Library (ADAL) and Azure AD Graph API (AAD Graph)**</span></span>

<span data-ttu-id="1ed48-105">**2020년 6월 30일부터** 더 이상 ADAL 및 Azure AD Graph에 새로운 기능이 추가되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-105">**Starting June 30th, 2020**, we will no longer add any new features to ADAL and Azure AD Graph.</span></span> <span data-ttu-id="1ed48-106">기술 지원 및 보안 업데이트를 계속 제공하지만 더 이상 기능 업데이트를 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-106">We will continue to provide technical support and security updates but will no longer provide feature updates.</span></span>

<span data-ttu-id="1ed48-107">**2022년 6월 30일부터** ADAL 및 Azure AD Graph에 대한 지원이 종료될 예정으로, 더 이상 기술 지원 또는 보안 업데이트를 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-107">**Starting June 30th, 2022**, we will end support for ADAL and Azure AD Graph and will no longer provide technical support or security updates.</span></span>

<span data-ttu-id="1ed48-108">기존 OS 버전에서 ADAL을 사용하는 앱은 이 시간 이후에도 계속 작동하지만 기술 지원 또는 보안 업데이트는 제공되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-108">Apps using ADAL on existing OS versions will continue to work after this time but will not get any technical support or security updates.</span></span>

<span data-ttu-id="1ed48-109">이 시간 이후 Azure AD Graph를 사용하는 앱은 더 이상 Azure AD Graph 끝점에서 응답을 수신하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-109">Apps using Azure AD Graph after this time may no longer receive responses from the Azure AD Graph endpoint.</span></span>

<span data-ttu-id="1ed48-110">**ADAL 마이그레이션**</span><span class="sxs-lookup"><span data-stu-id="1ed48-110">**ADAL Migration**</span></span>

<span data-ttu-id="1ed48-111">최신 기능 및 보안 업데이트가 있는 [MSAL(Microsoft 인증](https://docs.microsoft.com/azure/active-directory/develop/v2-overview)라이브러리)으로 업데이트하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-111">We recommend updating to the [Microsoft Authentication Library (MSAL)](https://docs.microsoft.com/azure/active-directory/develop/v2-overview), which has the latest features and security updates.</span></span>

<span data-ttu-id="1ed48-112">Microsoft 앱을 사용하는 경우 Microsoft가 지원 종료 기한까지 응용 프로그램을 MSAL로 마이그레이션하는 중이라는 것을 알고 MSAL의 지속적인 보안 및 기능 개선을 통해 혜택을 받을 수 있도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-112">If you're using Microsoft apps, know that Microsoft is in the process of migrating its applications to MSAL by the end-of-support deadline, ensuring they'll benefit from MSAL's ongoing security and feature improvements.</span></span>

1. <span data-ttu-id="1ed48-113">[ADAL FAQ를 읽습니다.](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq)</span><span class="sxs-lookup"><span data-stu-id="1ed48-113">[Read the ADAL FAQ](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq).</span></span>
1. <span data-ttu-id="1ed48-114">플랫폼에 따라 앱을 마이그레이션하는 [방법에 대해 자세히 알아보고,](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq)</span><span class="sxs-lookup"><span data-stu-id="1ed48-114">[Learn about how to migrate apps on a per-platform basis](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq).</span></span>
1. <span data-ttu-id="1ed48-115">ADAL을 사용하는 앱을 이해하는 데 도움이 필요한 경우 모든 앱의 소스 코드를 검토하는 것이 좋습니다. 해당하는 경우 ISV 또는 앱 공급자에게 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-115">If you need help understanding which of your apps use ADAL, we recommend you review all of your apps' source code, and if applicable, reach out to any ISVs or app providers.</span></span> <span data-ttu-id="1ed48-116">Microsoft 지원 서비스에서 테넌트에 있는 모든 비 Microsoft ADAL 앱 목록을 제공할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-116">Microsoft support can also provide you with a list of all non-Microsoft ADAL apps in your tenant.</span></span>

<span data-ttu-id="1ed48-117">**AAD 그래프 마이그레이션**</span><span class="sxs-lookup"><span data-stu-id="1ed48-117">**AAD Graph Migration**</span></span>

<span data-ttu-id="1ed48-118">Azure AD Graph를 사용하는 응용 프로그램의 경우 지침에 따라 Azure AD Graph 앱을 [Microsoft Graph로 마이그레이션합니다.](https://docs.microsoft.com/graph/migrate-azure-ad-graph-overview?view=graph-rest-1.0&preserve-view=true)</span><span class="sxs-lookup"><span data-stu-id="1ed48-118">For applications that are using Azure AD Graph, follow our guidance to migrate [Azure AD Graph apps to Microsoft Graph](https://docs.microsoft.com/graph/migrate-azure-ad-graph-overview?view=graph-rest-1.0&preserve-view=true).</span></span>

1. <span data-ttu-id="1ed48-119">[마이그레이션 검사 목록은 시작 지점을 제공합니다.](https://docs.microsoft.com/graph/migrate-azure-ad-graph-planning-checklist)</span><span class="sxs-lookup"><span data-stu-id="1ed48-119">[Our migration checklist provides a getting started point](https://docs.microsoft.com/graph/migrate-azure-ad-graph-planning-checklist).</span></span> 
1. <span data-ttu-id="1ed48-120">Azure 앱 등록 포털에는 AAD Graph를 사용하는 응용 프로그램이 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-120">Your Azure app registration portal shows which applications are using AAD Graph.</span></span> <span data-ttu-id="1ed48-121">모든 앱의 소스 코드를 검토하고 해당하는 경우 ISV 또는 앱 공급자에게 연결해보는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-121">We recommend you review all of your apps' source code, and if applicable, reach out to any ISVs or app providers.</span></span> <span data-ttu-id="1ed48-122">Microsoft 지원 서비스에서 테넌트의 모든 AAD Graph 사용 목록을 제공할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-122">Microsoft support can also provide you with a list of all AAD Graph usage in your tenant.</span></span>
1. <span data-ttu-id="1ed48-123">앱에서 Microsoft Graph의 데이터에 액세스하려면 사용자 또는 관리자가 동의 프로세스를 통해 올바른 사용 권한을 부여해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-123">For your app to access data in Microsoft Graph, the user or administrator must grant it the correct permissions via a consent process.</span></span> <span data-ttu-id="1ed48-124">Microsoft Graph 사용 권한 [참조에는](https://docs.microsoft.com/graph/permissions-reference?context=graph%2Fapi%2Fbeta&view=graph-rest-beta&preserve-view=true) 각 주요 Microsoft Graph API 집합과 연결된 사용 권한이 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-124">The [Microsoft Graph permissions reference](https://docs.microsoft.com/graph/permissions-reference?context=graph%2Fapi%2Fbeta&view=graph-rest-beta&preserve-view=true) lists the permissions associated with each major set of Microsoft Graph APIs.</span></span> <span data-ttu-id="1ed48-125">또한 사용 권한을 사용하는 방법에 대한 지침도 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="1ed48-125">It also provides guidance about how to use the permissions.</span></span>
