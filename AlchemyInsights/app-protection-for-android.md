---
title: Microsoft Intune의 Android 앱 보호 정책 설정
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003997"
- "7057"
ms.openlocfilehash: 327df6e0a901037cd929cb845f805466d9bd4eff
ms.sourcegitcommit: 81c86027933c06db08d264918f2698d9c9a1659a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/20/2020
ms.locfileid: "49373947"
---
# <a name="android-app-protection-policy-settings-in-microsoft-intune"></a><span data-ttu-id="d048d-102">Microsoft Intune의 Android 앱 보호 정책 설정</span><span class="sxs-lookup"><span data-stu-id="d048d-102">Android app protection policy settings in Microsoft Intune</span></span>

<span data-ttu-id="d048d-103">Android 장치용 앱 보호 정책 설정에는 다음과 같은 세 가지 범주가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d048d-103">There are three categories of app protection policy settings for Android devices:</span></span>

<span data-ttu-id="d048d-104">**데이터 보호** 는 데이터를 다른 응용 프로그램에 복사 하거나 붙여 넣을 수 있는지 여부 또는 앱에서 스크린샷을 가져올 수 있는 경우와 같이 회사 데이터가 처리 되는 방식을 제어 합니다.</span><span class="sxs-lookup"><span data-stu-id="d048d-104">**Data protection** controls how company data is handled, such as, whether data can be copied or pasted to a different app or whether a screenshot can be taken of the app.</span></span> <span data-ttu-id="d048d-105">또한이 설정은 회사 데이터에 대 한 암호화를 적용 하 고 연락처 목록이 나 웹 브라우저와 같은 네이티브 장치 앱과 동기화 할 수 있는 특정 데이터를 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="d048d-105">The settings also enforce encryption on company data and manage whether certain data can be synced with the native device apps, like the contact list or web browser.</span></span> <span data-ttu-id="d048d-106">자세한 내용은 [Data protection](https://go.microsoft.com/fwlink/?linkid=2135259)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d048d-106">To learn more, see [Data protection](https://go.microsoft.com/fwlink/?linkid=2135259).</span></span>

<span data-ttu-id="d048d-107">**액세스 요구 사항** 에서는 사용자가 앱에 액세스할 수 있는 방법을 안내 합니다.</span><span class="sxs-lookup"><span data-stu-id="d048d-107">**Access requirements** guides how users can access an app.</span></span> <span data-ttu-id="d048d-108">예를 들어 앱에 액세스 하려면 PIN 또는 지문을 입력 해야 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d048d-108">For example, an app could require the user to enter a PIN or fingerprint to access it.</span></span> <span data-ttu-id="d048d-109">자세한 내용은 [액세스 요구 사항을](https://go.microsoft.com/fwlink/?linkid=2135260)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d048d-109">To learn more, see [Access requirements](https://go.microsoft.com/fwlink/?linkid=2135260).</span></span>

<span data-ttu-id="d048d-110">**조건부 실행** 은 응용 프로그램에 대 한 로그인 보안 설정 (예: 잠금 전 최대 PIN 시도 횟수 또는 앱 실행에 필요한 최소 운영 체제)을 제어 합니다.</span><span class="sxs-lookup"><span data-stu-id="d048d-110">**Conditional launch** governs the sign-in security settings for an app, such as, the maximum PIN attempts before lockout or the minimum operating system needed to run the app.</span></span> <span data-ttu-id="d048d-111">자세한 내용은 [조건부 시작](https://go.microsoft.com/fwlink/?linkid=2135507)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="d048d-111">To learn more, see [Conditional launch](https://go.microsoft.com/fwlink/?linkid=2135507).</span></span>
