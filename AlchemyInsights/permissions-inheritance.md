---
title: 사용 권한 상속
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: bb5c440a-ca70-4dc6-b517-688e80551101
ms.openlocfilehash: f086bd7312772b399146cd81261f147364d64665
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47741957"
---
# <a name="how-permissions-inheritance-works-in-sharepoint"></a><span data-ttu-id="083ea-102">SharePoint에서 사용 권한 상속이 작동 하는 방식</span><span class="sxs-lookup"><span data-stu-id="083ea-102">How permissions inheritance works in SharePoint</span></span>

<span data-ttu-id="083ea-103">기본적으로 SharePoint의 사용 권한은 계층 구조에서 위쪽 으로부터 상속 됩니다.</span><span class="sxs-lookup"><span data-stu-id="083ea-103">By default, permissions in SharePoint are inherited from higher up in the hierarchy.</span></span> <span data-ttu-id="083ea-104">따라서 파일은 해당 폴더에서 사용 권한을 상속 하며, 사이트에서 사용 권한을 상속 하며, 사이트 모음에서 사용 권한을 상속 합니다.</span><span class="sxs-lookup"><span data-stu-id="083ea-104">So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site, which inherits its permissions from the site collection.</span></span>
  
<span data-ttu-id="083ea-105">고유한 사용 권한을 제거 하 고 상속을 복원 하는 방법에 대 한 자세한 내용은 [목록 또는 라이브러리의 사용 권한 편집 및 관리](https://go.microsoft.com/fwlink/?linkid=869946)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="083ea-105">For info about removing unique permissions and restoring inheritance, see [Edit and manage permissions for a list or library](https://go.microsoft.com/fwlink/?linkid=869946).</span></span>
  

