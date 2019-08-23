---
title: 전자 메일 메시지 회수 또는 교체
ms.author: daeite
author: daeite
manager: joallard
ms.date: 05/15/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: d5952041f6f2fd736e975abf06cc22880d21a089
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36553438"
---
# <a name="recall-or-replace-an-email-message-in-office-365"></a>Office 365에서 전자 메일 메시지 회수 또는 교체

- **조직의 사용자에 게 전송 된 메시지만 회수할**수 있습니다. 예를 들어, 메시지가 Gmail 주소로 전송 된 경우에는 회수할 수 없습니다.
- **PC 용 Outlook 2016에서 보낸 메시지만 회수할**수 있습니다. 사용자가 Outlook for Mac 또는 웹용 Outlook을 사용 하 여 메시지를 보낼 경우에는 회수할 수 없습니다.
- 관리자 인 경우 **PowerShell을 사용 하 여 사용자를 대신 하 여 메시지를 회수할**수 있습니다. 관리 센터에서 메시지를 회수할 수 없습니다. 자세한 내용을 보려면 아래로 스크롤하여 "조직의 전자 메일 메시지 검색 및 삭제"로 이동 합니다.

**보낸 전자 메일 메시지 회수 또는 교체**

1. Outlook 창 왼쪽의 폴더 창에서 보낸 편지함 폴더를 선택 합니다.
2. 회수할 메시지를 엽니다. 메시지를 열려면 두 번 클릭 해야 합니다. 메시지를 읽기 창에 표시 하도록 선택 해도 메시지를 회수할 수 없습니다.
3. 메시지 탭에서 **작업** > **회수 메시지**를 선택 합니다.
4. **이 메시지의 읽지 않은 복사본 삭제** 또는 **읽지 않은 복사본 삭제를 선택 하 고 새 메시지로 바꾼**다음 **확인**을 선택 합니다.
5. 대체 메시지를 보내는 경우 메시지를 작성 한 다음 **보내기를**선택 합니다.
6. 메시지 회수의 성공 또는 실패는 Outlook의 받는 사람 설정에 따라 달라 집니다.

회수를 확인 하는 방법에 대 한 자세한 내용은 [보낸 전자 메일 메시지 회수 또는 바꾸기를](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0)참조 하십시오.

***조직에서 전자 메일 메시지 검색 및 삭제*** 조직에서 전자 메일 메시지를 검색 하 고 삭제 하려면 전역 관리자 인 경우 가장 간편 합니다. 전역 관리자가 아닌 경우에는 eDiscovery 관리자 역할 그룹 또는 준수 검색 관리 역할에 계정을 추가 해야 합니다. 메시지를 삭제 하려면 조직 관리 역할 그룹 또는 검색 및 삭제 관리 역할에 참가 해야 합니다. 이러한 역할에 대 한 사용 권한은 [보안 & 준수 센터](https://protection.office.com/)에서 할당 됩니다.

1. 삭제할 메시지를 찾을 [콘텐츠 검색을 만듭니다](https://docs.microsoft.com/office365/securitycompliance/content-search) .
2. [보안 & 준수 센터 PowerShell에 연결](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps)합니다. 

MFA를 사용 하는 경우 [multi-factor authentication을 사용 하 여 Office 365 보안 & 준수 센터 PowerShell에 연결](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps)을 참조 하세요. 
