---
title: 파일 이름과 동일
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 31a578800468e9f3a69fff4f6e2e1945943c779c
ms.sourcegitcommit: 8f97342d8b46ab05f1e89018473caad9d35431df
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/19/2019
ms.locfileid: "35800051"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>필수 Alchemy 헤더 H1, H2's이 작동 하지 않습니다.
Alchemy 작성을 위한 모범 사례 및 지침:

1. **Alchemy Insights를 폴더에 중첩 하지 마세요**-url 구조가 손상 됩니다. 여기서는이 문제를 해결 하 고 있습니다.
1. **AlchemyInsights** 폴더의 파일에는 공백 하이픈을 포함 하는 소문자 파일 이름이 포함 되어야 합니다. ***사용 방법-설정-소송-보존***
    1. [Alchemy 파트너 포털](https://alchemyportal.azurewebsites.net) 의 사용자 정의 필드에 규칙 ID 또는 버킷 id를 포함 합니다. ex. ***사용자 지정: 100021***
1. 이 파일의 맨 위에 있는 메타 데이터의 나머지 부분을 서식 파일로 사용 합니다.
1. [Alchemy 파트너 포털](https://alchemyportal.azurewebsites.net)에서 **고객 통찰력 제목** 섹션으로 이동한 다음 해당 내용을 H1 제목에 대 한 시작 점으로 사용 합니다. 
    > [!NOTE]
    > Alchemy Insights는 맨 위에 단일 H1만 포함 되거나 프로덕션에서 중단 됩니다. H2s은 렌더링 되지 않으므로 별도의 섹션을 나타내기 위해 **굵게** 또는 기타 규칙을 사용 합니다.
1. 다음으로, Alchemy 규칙 페이지의 Customer Insights 섹션에 있는 초안 자료를 사용 하 여 본문 텍스트를 입력 합니다.
    1. 글머리 기호 목록이 양호 함
    1. 번호 매기기 목록만 너무 많이 있음
    1. **굵게** 및 *기울임꼴로* 표시 되는-정상
    1. 링크는 항상 내부 링크가 아니라 **UI 요소에 대**한 **"웹 연결"/외부** 또는 딥 링크 중 하나 여야 합니다.
    1. 이때 그림은 공식적으로 지원 되는 것은 아니지만 로드맵에 있습니다.

이는 실제로 너무 긴 시간입니다. 모범 사례는 약 400 자---------------------------------

콘텐츠가 준비 되 면 라이브 분기로 가져옵니다. 그런 다음 [Alchemy 파트너 포털로](https://alchemyportal.azurewebsites.net) 이동 하 여 url 필드에 파일 이름을 입력 합니다. 