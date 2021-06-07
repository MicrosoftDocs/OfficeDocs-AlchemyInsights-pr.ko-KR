---
title: Teams 웨비나 사용
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11513"
- "9006672"
ms.openlocfilehash: 5a732e6746e9fd23e54a0b2ffeabb59623012a0e
ms.sourcegitcommit: 9de78b30602f917d58705057cdcce31fec349969
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/04/2021
ms.locfileid: "52760856"
---
# <a name="enable-teams-webinars"></a>Teams 웨비나 사용

웨비나는 기본적으로 사용하도록 설정됩니다. Teams PowerShell 명령을 사용하여 Teams 웨비나를 예약하고 등록할 수 있는 사용자를 관리할 수 있습니다.

- 모임을 만들 수 있는 모든 사용자는 웨비나 모임도 만들 수도 있습니다. Teams 웨비나를 예약할 수 있는 사용자를 관리하려면 *AllowMeetingRegistration* 을 사용합니다. 
- 기본적으로 *WhoCanRegister* 사용하도록 설정되고 **Everyone** 로 설정됩니다. 모임 등록을 끄려면 *AllowMeetingRegistration* 을 **False** 로 설정합니다.

이러한 설정을 변경하려면 [Teams PowerShell](/microsoftteams/teams-powershell-install)을 설치해야 합니다. 또한 모임 정책이 Teams 웨비나에 적용됩니다. 예를 들어 모임 설정에서 익명 참가가 해제된 경우 익명 사용자는 웨비나에 참가할 수 없습니다.

웨비나에 등록할 수 있는 사용자를 구성하는 방법에 대한 자세한 내용은 [웨비나에 등록할 수 있는 사용자 구성](/microsoftteams/set-up-webinars?source=docs#configure-who-can-register-for-webinars)을 참조하세요. Microsoft Lists의 설정에 대한 자세한 내용은 [Microsoft Lists에 대한 컨트롤 설정](/sharepoint/control-lists)을 참조하세요.