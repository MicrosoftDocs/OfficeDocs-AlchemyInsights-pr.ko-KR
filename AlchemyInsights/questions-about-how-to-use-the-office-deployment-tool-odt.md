---
title: ODT (Office 배포 도구)를 사용 하는 방법에 대 한 질문
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 96d3f70f554f71c43d6458ec8debc099cd9fb040
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43698064"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>ODT (Office 배포 도구)를 사용 하는 방법에 대 한 질문

Office 배포 도구를 [Microsoft 다운로드 센터](https://go.microsoft.com/fwlink/p/?LinkID=626065)에서 다운로드합니다.
  
파일을 다운로드한 후에 Office 배포 도구 실행 파일(setup.exe) 및 샘플 구성 파일(configuration.xml)이 포함된 자동 압축 풀기 실행 파일을 실행합니다.
  
 **클라이언트 컴퓨터에서 엔터프라이즈 제품에 대 한 Microsoft 365 앱을 제외 하거나 제거 하려면:**
  
Enterprise 용 Microsoft 365 앱을 설치할 때 특정 제품을 제외할 수 있습니다. 이렇게 하려면 ODT를 사용하여 Office를 설치하기 위한 단계를 수행하되 구성 파일에 ExcludeApp 요소를 포함합니다. 예를 들어이 구성 파일은 Publisher를 제외한 모든 Microsoft 365 앱 (enterprise 제품)을 설치 합니다.
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Office 배포 도구 개요](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

