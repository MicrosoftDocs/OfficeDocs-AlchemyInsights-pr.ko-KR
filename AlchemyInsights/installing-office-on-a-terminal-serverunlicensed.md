---
title: 터미널 서버에 office 설치-사용 허가 되지 않음
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 6e952513679c9ac66f8de2b43d6d243cf17ff789
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010620"
---
# <a name="installing-office-on-a-terminal-server"></a>터미널 서버에 Office 설치

이전의 터미널 서비스를 사용 하 여 RDS (원격 데스크톱 서비스)를 사용한 Windows Server에 Microsoft 365 Apps for enterprise를 배포 하는 데 필요한 작업입니다.
  
- Office 365 Enterprise E3 또는 Enterprise e 3과 같은 microsoft 365 앱 for enterprise를 포함 하는 Microsoft 365 구독이 있어야 합니다. Microsoft 365 비즈니스용 business 및 Microsoft 365 Apps Premium 요금제에는 Microsoft 365 앱 for enterprise가 포함 되어 있지 않습니다.

- [공유 컴퓨터 활성화](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation)를 사용 하도록 설정 해야 합니다.

Microsoft 365 관리 센터에서 RDS에 Microsoft 365 앱을 설치 하려면 ***기본 설치 설정을 사용 하는***경우에는 다음 단계를 수행 합니다.

> [!TIP]
> [Microsoft 지원 및 복구 도우미](https://aka.ms/SaRA_OfficeSCA_M365Portal) 를 다운로드 하 고 실행 하 여 공유 컴퓨터 활성화 모드에서 Microsoft 365 Apps For enterprise office를 설치할 수도 있습니다.
  
1. 보유 하 고 있는 Microsoft 365 구독을 확인 합니다. [방법 알아보기](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. 필요한 경우 다른 Microsoft 365 구독으로 전환 합니다. [방법 알아보기](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. 다른 Microsoft 365 구독을 사용 하 여 Office가 RDS 서버에 이미 설치 되어 있는 경우 제거 합니다. 예를 들어 제어판으로 이동 하 여 \> 프로그램을 제거 합니다. 문제가 발생 하는 경우 [Microsoft 지원 및 복구 도우미를](https://aka.ms/SARA-OfficeUninstall-Alchemy) 사용 하 여 제거 합니다.

4. RDS 서버에서 관리자 계정으로 Microsoft 365 관리 센터에 로그인 하 고 [microsoft 365 앱 for enterprise를 설치](https://portal.office.com/OLS/MySoftware.aspx)합니다.

5. Office를 설치한 후에는 열거나 Office 응용 프로그램에 ***로그인 하지 마세요*** .

6. RDS 서버에서 다음 단계를 수행 하 여 레지스트리를 편집 하 여 공유 컴퓨터 활성화를 사용 하도록 설정 합니다.

1. 화면 왼쪽 아래에 있는 Windows 단추를 마우스 오른쪽 단추로 클릭 하 고 실행을 선택 합니다. 열기 상자에 **regedit**를 입력 하 고 확인을 선택 합니다.

2. 레지스트리 편집기를 사용 하 여 장치를 변경할 수 있는지 묻는 메시지가 표시 되 면 예를 선택 합니다.

3. 레지스트리 편집기에서 HKEY_LOCAL_MACHINE \SOFTWARE\Microsoft \Office\ClickToRun\Configuration.에 설정 1을 사용 하 여 **Sharedcomputerlicensing** 의 문자열 값을 추가 합니다.

7. RDS 서버에서 ***최종 사용자로 로그인*** 하 고 [Microsoft 365 for enterprise 앱에 대해 공유 컴퓨터 활성화가 사용 하도록 설정 되어 있는지 확인](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded)합니다.

Office 배포 도구를 사용 하 여 필수 구성 요소, 설치 지침 및 사용자 지정 설치에 대 한 지침에 대 한 자세한 내용은 [Deploy Microsoft 365 Apps for enterprise for a Remote 데스크톱 Services](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services)를 참조 하세요.
  
공유 컴퓨터 활성화와 관련 된 오류를 해결 하려면 [엔터프라이즈에 대 한 Microsoft 365 앱에 대 한 공유 컴퓨터 활성화의 문제 해결](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation)을 참조 하십시오.
  