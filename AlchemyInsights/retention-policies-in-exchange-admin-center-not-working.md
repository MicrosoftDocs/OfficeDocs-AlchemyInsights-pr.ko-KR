---
title: Exchange 관리 센터의 보존 정책이 작동 하지 않음
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "308"
- "3100007"
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: e2fb22f872be0eefc3b4b78b18cd09baffa66cda
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742439"
---
# <a name="retention-policies-in-exchange-admin-center"></a>Exchange 관리 센터의 보존 정책

 **문제:** Exchange 관리 센터에서 새로 만들어지거나 업데이트 된 보존 정책이 사서함 이나 항목에 적용 되지 않으면 보관 사서함으로 이동 되거나 삭제 되지 않습니다. 
  
 **근본 원인:**
  
- **관리 되는 폴더 도우미가** 사용자 사서함을 처리 하지 않았기 때문일 수 있습니다. 관리 되는 폴더 도우미는 8 일 마다 한 번씩 클라우드 기반 조직의 모든 사서함을 처리 하려고 시도 합니다. 보존 태그를 변경 하거나 사서함에 다른 보존 정책을 적용 하는 경우 관리 되는 폴더 지원에서 사서함을 처리할 때까지 기다리거나, 관리 되는 폴더 도우미를 실행 하 여 특정 사서함을 처리할 수 있습니다. 이 cmdlet을 실행 하는 것은 보존 정책이 나 보존 태그 설정을 테스트 하거나 문제를 해결 하는 데 유용 합니다. 자세한 내용을 보려면 [관리 되는 폴더 도우미 실행](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist)을 참조 하세요.
    
  - **해결 방법:** 다음 명령을 실행 하 여 특정 사서함에 대 한 관리 되는 폴더 도우미를 시작 합니다.
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- 사서함에 대 한 **보존 상태** 를 **사용 하도록 설정** 된 경우에도이 문제가 발생할 수 있습니다. 사서함이 보존 상태에 있는 경우에는 해당 시간 동안 사서함에 대 한 보관 정책이 처리 되지 않습니다. 보존 설정에 대 한 자세한 informaton [사서함 보존 보류](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold)를 참조 하세요.
    
    **솔루션**
    
  - [Exo powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps)의 특정 사서함에 대 한 보존 설정의 상태를 확인 합니다.
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - 다음 명령을 실행 하 여 특정 사서함의 보존 상태를 **사용 하지 않도록 설정** 합니다.
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - 이제 관리 되는 폴더 도우미를 다시 실행 합니다.
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 **참고:** 사서함이 10mb 보다 작으면 관리 되는 폴더 도우미가 사서함을 자동으로 처리 하지 않습니다.
 
Exchange 관리 센터의 보존 정책에 대 한 자세한 내용은 다음 항목을 참조 하십시오.
- [보존 태그 및 보존 정책](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)
- [사서함에 보존 정책 적용](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy)
- [보존 태그 추가 또는 제거](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/add-or-remove-retention-tags)
- [사서함의 보류 유형을 식별하는 방법](https://docs.microsoft.com/office365/securitycompliance/identify-a-hold-on-an-exchange-online-mailbox)
