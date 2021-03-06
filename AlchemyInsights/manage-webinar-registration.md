---
title: 웹비나 등록 관리
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
- "11512"
- "9006672"
ms.openlocfilehash: 0db6f434fa74970ac6083501ab26762cc6b7885f
ms.sourcegitcommit: 1eee2412dfb8b1f10a3aa28dd1086a0c589cdba0
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2021
ms.locfileid: "52798650"
---
# <a name="manage-webinar-registration"></a>웹비나 등록 관리

Teams PowerShell 명령을 사용하여 Teams 웨비나에 등록할 수 있는 사용자를 관리합니다. Teams Powershell을 설치하려면 [Teams PowerShell](/microsoftteams/teams-powershell-install)을 참조하세요. 

기본적으로 *WhoCanRegister* 는 사용하도록 설정되고 **모든 사용자** 로 설정됩니다. 

모임 초대에서 모든 사용자에 대한 등록을 허용하는 옵션이 표시되지 않으면 *WhoCanRegister* 설정을 다시 실행하고 24시간 기다리세요. *WhoCanRegister* 를 다시 실행하려면 Powershell 명령을 사용하세요.

`Set-CsTeamsMeetingPolicy -WhoCanRegister Everyone`

**참고**: 모임 설정에서 익명 참가가 해제된 경우 익명 사용자는 웨비나에 참가할 수 없습니다. 자세한 내용을 알아보고 이 설정을 사용하도록 설정하려면 [Microsoft Teams에서 모임 설정 관리](/microsoftteams/meeting-settings-in-teams)를 참조하세요.

모임 등록을 끄려면 *AllowMeetingRegistration* 을 **False** 로 설정합니다.

웨비나에 등록할 수 있는 사용자를 구성하는 방법에 대한 자세한 내용은 [웨비나에 등록할 수 있는 사용자 구성](/microsoftteams/set-up-webinars?source=docs#configure-who-can-register-for-webinars)을 참조하세요. Microsoft Lists의 설정에 대한 자세한 내용은 [Microsoft Lists에 대한 컨트롤 설정](/sharepoint/control-lists)을 참조하세요.
