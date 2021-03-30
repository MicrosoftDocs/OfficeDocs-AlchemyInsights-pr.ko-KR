---
title: Azure AD 조인 문제 해결
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/24/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003246"
- "6157"
ms.openlocfilehash: 0e9f7c95cf522340e9976f668c1d1a9eaff71910
ms.sourcegitcommit: db908b3da2c7a6508a77bf4f2c80afb294fadbd1
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/29/2021
ms.locfileid: "51403874"
---
# <a name="troubleshoot-azure-ad-join-issues"></a><span data-ttu-id="e5f50-102">Azure AD 조인 문제 해결</span><span class="sxs-lookup"><span data-stu-id="e5f50-102">Troubleshoot Azure AD join issues</span></span>

1. <span data-ttu-id="e5f50-103">장치 등록을 처음 설정하는 경우 Azure AD에 대한 제어 하에서 디바이스를 다운로드하는 방법을 안내하는 [Azure Active Directory의](https://docs.microsoft.com/azure/active-directory/devices/overview) 장치 관리 소개를 검토해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e5f50-103">If you are setting up device registrations for the first time, ensure that you have reviewed [Introduction to device management in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/devices/overview) that will guide you on how to get Devices under the control to Azure AD.</span></span> 
1. <span data-ttu-id="e5f50-104">장치를 Azure AD에 직접 등록하고 Intune에 등록하는 경우 [Intune을](https://docs.microsoft.com/mem/intune/enrollment/device-enrollment) 구성하고 먼저 라이선스를 [](https://docs.microsoft.com/mem/intune/fundamentals/licenses-assign) 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e5f50-104">If you are registering devices into Azure AD directly and enrolling them into Intune, you will need to ensure that you have [configured Intune](https://docs.microsoft.com/mem/intune/enrollment/device-enrollment) and have the [licensing](https://docs.microsoft.com/mem/intune/fundamentals/licenses-assign) in place first.</span></span>
1. <span data-ttu-id="e5f50-105">Azure AD에서 작업을 수행할 수 있는 권한이 부여된지 확인</span><span class="sxs-lookup"><span data-stu-id="e5f50-105">Ensure you are authorized to perform operations in Azure AD.</span></span> <span data-ttu-id="e5f50-106">Azure AD의 전역 관리자만 장치 등록에 대한 설정을 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e5f50-106">Only a global administrator in Azure AD can manage settings for device registrations.</span></span>
1. <span data-ttu-id="e5f50-107">Azure AD 조인 구현을 위해 Azure AD 가입 [계획을 참조하세요.](https://docs.microsoft.com/azure/active-directory/devices/azureadjoin-plan)</span><span class="sxs-lookup"><span data-stu-id="e5f50-107">To do Azure AD join implementation, see [Plan Azure AD Join](https://docs.microsoft.com/azure/active-directory/devices/azureadjoin-plan).</span></span>

<span data-ttu-id="e5f50-108">Azure AD 가입의 일반적인 문제를 해결하려면 Azure Ad 가입 [FAQ를](https://docs.microsoft.com/azure/active-directory/devices/faq#azure-ad-join-faq) 참조하고 Windows 10 Pro 디바이스에 대한 자세한 내용은 Windows 10 Pro 머신을 Azure AD에 가입할 수 [없습니다. - Microsoft 커뮤니티로](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_install-mso_win10-mso_365hp/unable-to-join-windows-10-pro-machine-to-azure-ad/abb1ca7d-b317-45ec-a628-e1c10eae2900) 업그레이드해야 를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e5f50-108">For more details on resolving  common issues with Azure AD join see [Azure Ad Join FAQ](https://docs.microsoft.com/azure/active-directory/devices/faq#azure-ad-join-faq) and for Windows 10 pro device, see [Unable to join Windows 10 Pro machine to Azure AD - Need to upgrade to - Microsoft Community](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_install-mso_win10-mso_365hp/unable-to-join-windows-10-pro-machine-to-azure-ad/abb1ca7d-b317-45ec-a628-e1c10eae2900)</span></span>
