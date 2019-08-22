---
title: SSN에 대 한 DLP 규칙이 작동 하지 않음
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 757136c39700f12f40f839b29277a59b0e436f03
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529866"
---
# <a name="dlp-issues-with-social-security-numbers"></a>주민 등록 번호 관련 DLP 문제

Office 365에서 중요 한 정보 유형을 사용 하는 경우 **SSN (사회 보장 번호** )이 포함 된 콘텐츠에 대해 **DLP (데이터 손실 방지)** 가 작동 하지 않는 문제를 겪고 있습니까? 해당 하는 경우 콘텐츠에 DLP 정책에서 찾는 항목에 대 한 필요한 정보가 포함 되어 있는지 확인 합니다. 
  
예를 들어, 신뢰 수준이 85% 인 SSN 정책의 경우 다음이 평가 되며 규칙을 트리거하기 위해 검색 되어야 합니다.
  
- **[서식:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 자리 숫자, 서식이 지정 되거나 서식 없는 패턴으로 표시 될 수 있습니다.

- **[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** 다음의 네 가지 패턴에서 SSNs를 검색 하는 함수는 다음과 같습니다.

  - Func_ssn는 대시 또는 공백을 사용 하 여 서식이 지정 된 2011 이전의 고급 서식 (ddd-dd-dddd 또는 ddd dd dd)을 사용 하 여 SSNs를 찾습니다.

  - Func_unformatted_ssn는 형식이 지정 되지 않은 2011 이전 형식으로 서식이 지정 된 SSNs를 찾습니다 (ddddddddd).

  - Func_randomized_formatted_ssn는 대시 또는 공백으로 서식이 지정 된 post-2011 SSNs를 찾습니다 (ddd-dd-dddd 또는 ddd dd dddd).

  - Func_randomized_unformatted_ssn는 형식 없는 2011 SSNs를 찾고, 서식이 없는 9 자리 숫자 (ddddddddd)를 찾습니다.

- **[검사 값:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** 아니요, 체크섬이 없습니다.

- **[정의:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** DLP 정책은 300 문자에 근접 한 경우이 유형의 중요 한 정보를 검색 한다는 것을 85% 확신 합니다.

  - [Func_ssn 함수가](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) 해당 패턴과 일치 하는 콘텐츠를 찾습니다.

  - [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn)의 키워드가 발견되었습니다. 키워드의 예에는 *사회 보안, 주민 보안 #, Soc Sec, SSN이* 포함 됩니다. 예를 들어 다음 샘플은 DLP SSN 정책에 대해 트리거됩니다. **ssn: 489-36-8350**
  
콘텐츠에 대해 SSNs를 검색 하는 데 필요한 사항에 대 한 자세한 내용은이 문서의 다음 섹션에서 [중요 한 정보 유형이 SSNs에 대해 어떤 모양 인지](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn) 를 참조 하세요.
  
기본 제공 되는 다른 중요 한 정보 유형을 사용 하는 경우 [중요 한 정보 유형이 찾는 항목](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for) 에 대 한 자세한 내용은 다음 문서를 참조 하십시오.
  