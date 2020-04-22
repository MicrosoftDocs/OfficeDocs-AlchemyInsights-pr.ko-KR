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
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a>Office 앱 문제 해결 "계정이 잘못 된 상태입니다." 오류

이 오류를 해결 하려면 영향을 받는 컴퓨터에서 다음 옵션을 사용해 보십시오.

- Office 앱을 열고 모든 계정에서 **파일** > **계정** > **로그 아웃**을 선택 합니다. 유효한 라이선스가 있는 사용자 계정을 사용 하 여 다시 로그인 합니다. 자세한 내용은 [Office의 계정](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9)을 참조하세요.
- Windows Credential Manager를 사용 하 여 [Office 자격 증명을 지웁니다](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) .<br>
  **참고:** Office 2016의 레지스트리 경로가 16.0로 변경 되었습니다. 예를 들어 \Software\Microsoft\Office\16.0\Common\Identity\
- Office 2013을 사용 하 여 Office 365에 연결 하는 동안 오류가 발생 하는 경우 Office 클라이언트에 대 한 [최신 인증을 사용 하도록 설정](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) 합니다.

자세한 내용은 [Microsoft 365, Azure 또는 Intune에 로그인 할 수 없는 비 브라우저 앱 문제를 해결](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1)하는 방법을 참조 하세요.

