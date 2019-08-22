---
title: Office 앱에 로그인 하는 문제
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2574"
ms.openlocfilehash: 3622a3408b25b43090e9414ae5ffcfc2760264ee
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938262"
---
# <a name="issues-signing-in-to-office-apps"></a><span data-ttu-id="e2afd-102">Office 앱에 로그인 하는 문제</span><span class="sxs-lookup"><span data-stu-id="e2afd-102">Issues signing in to Office apps</span></span>

<span data-ttu-id="e2afd-103">Office 앱의 로그인 문제를 해결 하려면 다음을 시도 합니다.</span><span class="sxs-lookup"><span data-stu-id="e2afd-103">To fix sign-in issues with Office apps, try the following:</span></span>

- <span data-ttu-id="e2afd-104">Windows 설정을 사용 하 여 영향을 받는 계정을 제외한 모든 작업 계정을 제거 하 여 **회사 또는 학교 액세스**> 합니다.</span><span class="sxs-lookup"><span data-stu-id="e2afd-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="e2afd-105">Windows Credential Manager를 사용 하 여 [Office 자격 증명을 지웁니다](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) .</span><span class="sxs-lookup"><span data-stu-id="e2afd-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="e2afd-106">**참고:** Office 2016의 레지스트리 경로가 16.0로 변경 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="e2afd-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="e2afd-107">(예: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="e2afd-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="e2afd-108">Office 앱을 열고 **파일** > **계정** > **로그 아웃**을 선택 합니다. 유효한 라이선스가 있는 사용자 계정을 사용 하 여 로그인 합니다.</span><span class="sxs-lookup"><span data-stu-id="e2afd-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="e2afd-109">자세한 내용은 [Office의 계정을](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="e2afd-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="e2afd-110">Mac의 경우 [Office 2016 For mac app에 로그인 할 수 없습니다](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="e2afd-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>
- <span data-ttu-id="e2afd-111">Office 2013을 사용 하 여 Office 365에 연결 하는 동안 오류가 발생 하면 Office 클라이언트에 대 한 최신 인증을 사용 하도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="e2afd-111">If the errors occurs while connecting to Office 365 using Office 2013, enable modern authentication for Office client.</span></span>

<span data-ttu-id="e2afd-112">자세한 내용은 다음을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e2afd-112">For more information, see:</span></span>
- [<span data-ttu-id="e2afd-113">Office 365, Azure 또는 Intune에 로그인 할 수 없음</span><span class="sxs-lookup"><span data-stu-id="e2afd-113">You can't sign in to Office 365, Azure, or Intune</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [<span data-ttu-id="e2afd-114">Office 2016 빌드 16.0.7967 Windows 10에서 업데이트 후 로그인 시 연결 문제가 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="e2afd-114">Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10</span></span>](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- [<span data-ttu-id="e2afd-115">"Office에서 조직의 다른 계정이 이미이 컴퓨터에 로그인 되어 있습니다." 라는 문제가 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="e2afd-115">"Sorry, another account from your organization is already signed in on this computer" in Office</span></span>](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [<span data-ttu-id="e2afd-116">ADFS를 사용할 때 Office 최신 인증의 로그인 문제 해결</span><span class="sxs-lookup"><span data-stu-id="e2afd-116">Troubleshoot sign-in issues with Office modern authentication when you use ADFS</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)