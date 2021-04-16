---
title: 포털에서 장치 기록 복제
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: e6f477807823e68965ce966faf0a6f50f9472f3d
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51814522"
---
# <a name="duplicate-device-record-in-the-portal"></a>포털에서 장치 기록 복제

장치의 구성 관리 사이트에서 공동 관리 상황에 대한 보고가 정확하지 않으면 포털에서 2개의 장치 기록을 볼 수 있습니다. 장치의 공동 관리 상태를 확인 하려면 구성 관리자 콘솔에서 장치에서 **공동 관리** 열을 검토 합니다. 열이 표시 되지 않는 경우 열 머리글을 마우스 오른쪽 단추로 클릭하고 목록에서 선택하여 추가 할 수 있습니다.

공동 관리 값은 **네** 여야 합니다. 값이 **아니오****면 클라이언트 장치에서 Configuration Manager 클라이언트 애플릿을 열고 일반 탭에서** 공동 관리 속성을 확인 합니다.

- 값이 **사용함** 인 경우에는 관리 지점과 클라이언트 통신에 문제가 있음을 의미합니다. 장치에서 **CcmMessaging.log** 를 검토하여 잠재적인 연결 문제를 조사 하세요.

- 값이 **사용 안함** 이고, 장치가 Intune에 등록 되어 있는 경우 장치에서 **CoManagementHandler.log** 를 검토하여 장치가 공동 관리 정책을 받았는지 확인하세요.
