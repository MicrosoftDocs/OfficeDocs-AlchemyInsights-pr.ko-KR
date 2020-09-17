---
title: Microsoft Intune의 DEP 등록 문제 해결
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d32afde-47ab-4b1e-a669-662e5dbdc213
ms.custom:
- "783"
- "6200002"
ms.openlocfilehash: 50aab6e1e3c0d74d2e305e0bdd47c92b3a27c79f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47797302"
---
# <a name="troubleshoot-issues-with-dep-enrollment-in-microsoft-intune"></a><span data-ttu-id="b5014-102">Microsoft Intune의 DEP 등록 문제 해결</span><span class="sxs-lookup"><span data-stu-id="b5014-102">Troubleshoot issues with DEP enrollment in Microsoft Intune</span></span>

<span data-ttu-id="b5014-103">아래에 나열 된 리소스를 검토 하 여 지금 문제를 해결 하세요.</span><span class="sxs-lookup"><span data-stu-id="b5014-103">Review the resources listed below to resolve your issue now.</span></span>
  
1. <span data-ttu-id="b5014-104">DEP 장치를 등록할 수 없고 MFA (Multi-factor Authentication)가 사용 하도록 설정 된 경우 MFA를 사용 하지 않도록 설정 하세요.</span><span class="sxs-lookup"><span data-stu-id="b5014-104">If DEP device is unable to enroll and MFA (Multi-Factor Authentication) is enabled, please disable MFA.</span></span> <span data-ttu-id="b5014-105">현재 MFA는 DEP 등록에 대해 지원 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b5014-105">Currently MFA is not supported for DEP enrollment</span></span>

2. <span data-ttu-id="b5014-106">[Intune 문제 해결 포털](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) 을 사용 하 여 일반적인 등록 오류를 진단 하 고 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="b5014-106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="b5014-107">자세한 내용을 보려면 [이 문서](https://docs.microsoft.com/intune/help-desk-operators) 를 검토 하세요.</span><span class="sxs-lookup"><span data-stu-id="b5014-107">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

3. <span data-ttu-id="b5014-108">다음 문서를 검토 하 여 각 등록 및 확인을 방지 하는 일반적인 오류 목록: [문제 해결 가이드](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) 및 [문서 문제 해결](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune)</span><span class="sxs-lookup"><span data-stu-id="b5014-108">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune)</span></span>

4. <span data-ttu-id="b5014-109">[장치 등록 프로그램에 대해 알아봅니다](https://docs.microsoft.com/intune/device-enrollment-program-enroll-ios).</span><span class="sxs-lookup"><span data-stu-id="b5014-109">[Learn about device enrollment program](https://docs.microsoft.com/intune/device-enrollment-program-enroll-ios).</span></span>
