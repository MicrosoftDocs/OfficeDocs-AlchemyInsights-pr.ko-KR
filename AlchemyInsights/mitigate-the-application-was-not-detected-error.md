---
title: 응용 프로그램이 검색되지 않음 오류 완화
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810489"
---
# <a name="mitigate-the-application-was-not-detected-error"></a><span data-ttu-id="23f74-102">"응용 프로그램이 검색되지 않았습니다" 오류 완화</span><span class="sxs-lookup"><span data-stu-id="23f74-102">Mitigate "The application was not detected" error</span></span>

<span data-ttu-id="23f74-103">Intune에서 보고되는 "설치가 완료된 후 응용 프로그램이 검색되지 않았습니다." 앱 설치 오류가 모든 주요 OS 플랫폼(Windows, iOS, Android)에서 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-103">The app installation error, “The application was not detected after installation completed successfully,” reported by Intune, may occur on all major OS platforms (Windows, iOS and Android).</span></span>

<span data-ttu-id="23f74-104">이 오류를 발생시키는 가장 일반적인 시나리오는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-104">The most common scenarios that generate this error include:</span></span>

- <span data-ttu-id="23f74-105">초기 배포 후 앱이 Intune 외부에서(타사 앱 스토어) 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-105">The app has been updated outside of Intune (from a third-party app store) after the initial deployment.</span></span> <span data-ttu-id="23f74-106">예를 들어 Google Chrome과 같은 일부 응용 프로그램이 자동 업데이트될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-106">For example some applications such as Google Chrome may perform auto updates.</span></span>
- <span data-ttu-id="23f74-107">사용자가 최초 설치 후 앱을 제거했습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-107">A user has uninstalled the app after the initial install.</span></span>

<span data-ttu-id="23f74-108">이 문제를 완화하려면 먼저 영향을 받는 장치에 대한 검토를 수행하여 오류가 발생하는 시나리오를 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-108">To mitigate this issue, first perform a review of the affected devices to determine the scenario in which the error occurs.</span></span>

- <span data-ttu-id="23f74-109">앱이 Intune 외부에서 업데이트된 경우 응용 프로그램 버전을 무시하도록 앱 배포를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-109">If the app has been updated outside of Intune, the app deployment can be set to ignore the application version.</span></span> <span data-ttu-id="23f74-110">설정하려면 **앱 구성 > 앱 정보**에서 **앱 버전 무시**를 **예**로 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-110">To do so, under **App Configuration > App Information**, set **Ignore App** version to **Yes**.</span></span>
- <span data-ttu-id="23f74-111">클라이언트를 대상으로 하는 경우 응용 프로그램을 "필수"로 배포하고 최신 버전을 배포하는 것이 적적할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-111">When targeting the client, it may be appropriate to deploy the application as “required,” and to ensure that the latest version is deployed.</span></span>
- <span data-ttu-id="23f74-112">또는 iOS 플랫폼에서 새 응용 프로그램 버전이 사용할 수 있게 되는 대로 자동으로 업데이트하도록 구성할 수 있는 Apple Volume Purchase 프로그램에 연결된 **자동 업데이트** 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23f74-112">Alternatively, on the iOS platform, it is possible to use the **autoupdate** functionality associated with the Apple Volume Purchase Program, which can be configured to automatically update to new application versions as they become available.</span></span>

<span data-ttu-id="23f74-113">앱 설치 문제 해결에 대한 자세한 내용은 [앱 설치 문제 해결](https://docs.microsoft.com/intune/troubleshoot-app-install)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="23f74-113">For more information about troubleshooting app installation issues, please see [Troubleshoot app installation issues](https://docs.microsoft.com/intune/troubleshoot-app-install).</span></span>
