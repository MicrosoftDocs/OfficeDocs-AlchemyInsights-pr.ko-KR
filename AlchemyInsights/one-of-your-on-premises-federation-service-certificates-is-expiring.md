---
title: 만료된 On-premises Federation Service 인증서 중 하나
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 45a679e83aa8f07d65d2e7e84d7eb2a2b5a721e8
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51810058"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>만료된 On-premises Federation Service 인증서 중 하나

이 문제를 해결하기 위해 다음 단계를 수행합니다.
  
- 컴퓨터에 Microsoft Azure Active Directory 모듈을 Windows PowerShell 설치합니다(모듈이 아직 설치되지 않은 경우). 이 작업을 위해 [Azure Active Directory PowerShell for Graph로 이동하세요. ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)
    
- 페더링 사용자가 [Microsoft 365, Azure 또는 Intune에](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)로그인할 때 AD FS에서 "사이트에 액세스하는 데 문제가 발생했습니다." 오류의 "시나리오 1: AD FS 토큰 서명 인증서 만료" 섹션의 단계를 따릅니다.
    
- [Microsoft 365, Azure 또는 Intune에서](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)페더전된 도메인의 설정을 업데이트하거나 복구하는 방법의 단계를 따릅니다.
    
페더링 인증서 갱신에 대한 자세한 내용은 O365 및 Azure AD에 대한 인증서 [갱신을 참조하세요.](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs)
  

