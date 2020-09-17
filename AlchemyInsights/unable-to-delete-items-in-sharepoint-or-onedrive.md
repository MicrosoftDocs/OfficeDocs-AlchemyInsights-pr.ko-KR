---
title: SharePoint 또는 OneDrive에서 항목을 삭제할 수 없음
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: fd12115214cc28b822cf7fa57fe9b86f76f7beb1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806117"
---
# <a name="unable-to-delete-items"></a>항목을 삭제할 수 없음

보존 정책에 의해이 문제가 발생 하는 해당 보류를 사용 하지 않도록 설정 하거나 제외 해야 합니다. 보존 정책이 제거 된 후에는 변경 내용이 적용 되는 데 최대 24 시간이 걸릴 수 있습니다. 해당 항목에 대 한 [보존 정책](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) 설정이 없는지 확인 합니다.

사이트의 저장 한도를 초과 하 여 사이트 [할당량](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) 을 높이 거 나 항목을 삭제 했을 수 있습니다.

항목이 다른 사용자에 게 [체크 아웃](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) 되지 않았는지 확인 합니다.

마지막으로 관리자는 stubborn 항목 강제 삭제와 같은 복잡 한 관리 작업을 수행 하는 데 사용할 수 있는 PowerShell 명령 라이브러리가 포함 된 [SharePoint 패턴 및 사례](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP)를 사용할 수 있습니다.
- [PNP 파일 제거](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [PNP 폴더 제거](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [PNP 목록 항목 제거](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [PNP 목록 제거](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [PNP 필드 제거 (열)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)