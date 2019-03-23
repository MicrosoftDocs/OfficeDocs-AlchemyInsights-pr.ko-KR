---
title: 1491-검색이 예상 대로 반환 되지 않음-결과
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 1491
ms.assetid: ''
ms.openlocfilehash: 517d9b75fc3aef09c0c2d5870aa695cc0ab10f06
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776087"
---
# <a name="content-search-not-returning-expected-results"></a>콘텐츠 검색에서 필요한 결과를 반환 하지 않음

Office 365 Security & 준수 센터에서 콘텐츠 검색을 실행 하면 예기치 않은 검색 결과가 나타날 수 있습니다. 검색 결과에 영향을 줄 수 있는 다음과 같은 사항을 고려 하십시오.

- **콘텐츠 위치 및 검색 조건**: 적절 한 콘텐츠 위치 및 검색 조건을 선택 했는지 확인 합니다. 여러 위치에서 큰 검색을 실행 한 경우에는 여러 검색으로 분할 하는 것이 좋습니다.

- **부분적으로 인덱싱된 항목**: 사서함에서 [부분적으로 인덱싱된 항목이](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) 예상 검색 결과에 포함 됩니다. 그러나 SharePoint 및 OneDrive의 사이트에서 부분적으로 인덱싱된 항목은 검색 예상에 포함 되지 않습니다.

- **검색 실패**: 10만 사서함을 초과 하 여 많은 수의 사서함을 검색 하는 경우 CS008-009 및 CS012-002와 같은 오류 코드를 사용 하 여 검색 오류를 가져올 수 있습니다. 이 경우 실패 한 콘텐츠 위치에 대해서만 검색을 다시 시도 합니다. 자세한 내용은 [이 문서](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) 를 참조 하세요.
