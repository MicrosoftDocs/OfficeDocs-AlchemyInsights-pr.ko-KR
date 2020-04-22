---
title: 계정이 잘못 된 상태 메시지에 있는 Office 앱 수정
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: ac760b417ad98b9d5bb6be4b92e60074ab93ceb3
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43708693"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="2d86c-102">Office 앱 문제 해결 "계정이 잘못 된 상태입니다." 오류</span><span class="sxs-lookup"><span data-stu-id="2d86c-102">Fixing the Office apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="2d86c-103">이 오류를 해결 하려면 영향을 받는 컴퓨터에서 다음 옵션을 사용해 보십시오.</span><span class="sxs-lookup"><span data-stu-id="2d86c-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="2d86c-104">Office 앱을 열고 모든 계정에서 **파일** > **계정** > **로그 아웃**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d86c-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="2d86c-105">유효한 라이선스가 있는 사용자 계정을 사용 하 여 다시 로그인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d86c-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="2d86c-106">자세한 내용은 [Office의 계정](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2d86c-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="2d86c-107">Windows Credential Manager를 사용 하 여 [Office 자격 증명을 지웁니다](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) .</span><span class="sxs-lookup"><span data-stu-id="2d86c-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="2d86c-108">**참고:** Office 2016의 레지스트리 경로가 16.0로 변경 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2d86c-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="2d86c-109">예를 들어 \Software\Microsoft\Office\16.0\Common\Identity</span><span class="sxs-lookup"><span data-stu-id="2d86c-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="2d86c-110">Office 2013을 사용 하 여 Office 365에 연결 하는 동안 오류가 발생 하는 경우 Office 클라이언트에 대 한 [최신 인증을 사용 하도록 설정](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d86c-110">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="2d86c-111">자세한 내용은 [Microsoft 365, Azure 또는 Intune에 로그인 할 수 없는 비 브라우저 앱 문제를 해결](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1)하는 방법을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2d86c-111">For more information, see [How to troubleshoot non-browser apps that can't sign in to Microsoft  365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>

