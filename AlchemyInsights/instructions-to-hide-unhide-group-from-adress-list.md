---
title: 주소 목록에서 그룹을 숨기거나 숨기기지 않는 지침
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 4d55866700b9b8494f1f692cd3b865116b96a1bc
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51831884"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a>주소 목록(GAL)에서 Microsoft 365 그룹 숨기기

Outlook 또는 OWA와 같은 Exchange 클라이언트의 GAL(주소 목록)에서 Microsoft 365 그룹을 숨기기 위해 EXO 셸에서 다음 명령을 사용하세요.

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Microsoft 365 그룹이 Exchange 클라이언트에 표시되지 않는 것을 숨기기 위해 EXO 셸에서 다음 명령을 사용 합니다.

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

