---
title: eDiscovery 내보내기
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 67e59182a5053111a08f5fb2be814931a1aa815d
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277942"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>EDiscovery 내보내기 도구를 설치 하거나 실행할 수 없습니까?

EDiscovery 내보내기 도구를 설치 하거나 실행 하 여 검색 결과를 다운로드할 수 없는 경우 다음 항목을 확인 합니다.
  
- 사용 중인 컴퓨터가 다음 사전 요구 사항을 충족 합니다.

  - 32비트 및 64비트 버전의 Windows 7 이상 버전

  - Microsoft .NET Framework 4.7

  - 지원되는 브라우저:

  - Microsoft Edge

    또는

  - Internet Explorer 10 이상 버전

    Google Chrome 및 Mozilla Firefox와 같은 다른 브라우저는 지원 되지 않습니다.

- 조직은 Azure의 끝점 ( ** \* blob.core.windows.net** )에 연결할 수 있습니다 (와일드 카드는 내보내기 작업에 대 한 고유 식별자를 나타냄).

- Microsoft 365 보안 및 준수 센터에서 내보내기 역할이 할당 &amp; 되었습니다. 기본적으로이 역할은 eDiscovery 관리자 역할 그룹에만 할당 됩니다. [EDiscovery 사용 권한 할당](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions)을 참조 하세요.

자세한 내용은 [Export Content Search results](https://docs.microsoft.com/microsoft-365/compliance/export-search-results)를 참조 하세요.

10만 개 이상의 사서함을 내보내는 경우에는 다음 Powershell을 사용 하 여 내보내기 결과를 다운로드 해야 합니다 (  [10만 개 이상의 사서함에서 결과 내보내기](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes)).