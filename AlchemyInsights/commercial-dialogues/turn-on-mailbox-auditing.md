---
title: 사서함 감사 켜기
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: aa0ff925ae891d28e31394ec66eb17c2d9710008
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464934"
---
# <a name="turn-on-mailbox-auditing"></a>사서함 감사 켜기

단일 사용자 또는 전체 조직에 대한 사서함 감사를 켜기 위해 Remote PowerShell에서 다음 cmdlet을 실행합니다.

- **단일 사용자**: Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true
- **조직**: Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true

자세한 내용은 사서함 감사 [관리를 참조합니다.](https://go.microsoft.com/fwlink/?linkid=2103668)