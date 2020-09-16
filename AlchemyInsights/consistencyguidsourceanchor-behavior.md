---
title: ConsistencyGuid/sourceAnchor 동작
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: adac469328485696d1ee1532aa3d6828af0642eb
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47756289"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>ConsistencyGuid/sourceAnchor 동작

Azure AD Connect (버전 1.1.524.0 and after)를 이제 Msds-alloweddnssuffixesexadnomk-ConsistencyGuid를 sourceAnchor 특성으로 사용할 수 있습니다. 이 기능을 사용 하는 경우 Azure AD Connect에서는 자동으로 동기화 규칙을 다음과 같이 구성 합니다.
  
- 사용자 개체의 sourceAnchor 특성으로 Msds-alloweddnssuffixesexadnomk-ConsistencyGuid을 사용 합니다. ObjectGUID는 다른 개체 형식에 사용 됩니다.
    
- Msds-alloweddnssuffixesexadnomk-ConsistencyGuid 특성이 채워지지 않는 지정 된 온-프레미스 AD 사용자 개체의 경우 Azure AD Connect는 해당 objectGUID 값을 온-프레미스 Active Directory의 Msds-alloweddnssuffixesexadnomk-ConsistencyGuid 특성에 다시 씁니다. Msds-alloweddnssuffixesexadnomk-ConsistencyGuid 특성이 채워지면 Azure AD Connect에서이 개체를 Azure AD로 내보냅니다.
    
 **참고:** 온-프레미스 AD 개체를 Azure AD Connect로 가져온 후 (AD 커넥터 공간으로 가져오고 메타 버스에 투영 됨) 해당 sourceAnchor 값을 변경할 수 없습니다. 지정 된 온-프레미스 AD 개체에 대해 sourceAnchor 값을 지정 하려면 Azure AD Connect로 가져오기 전에 해당 Msds-alloweddnssuffixesexadnomk 특성을 구성 합니다. 
  
원본 앵커 및 ConsistencyGuid에 대 한 자세한 내용은 [AZURE AD Connect: 디자인 개념](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts) 을 참조 하세요.
  

