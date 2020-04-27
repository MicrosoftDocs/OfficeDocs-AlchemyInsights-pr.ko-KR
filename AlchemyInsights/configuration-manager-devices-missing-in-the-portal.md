---
title: 포털에 누락된 Configuration Manager 장치
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: 7a11ad3c6970be2c52a7cf0696bd3810b9bd665a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789907"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a><span data-ttu-id="1ef74-102">포털에 누락된 Configuration Manager 장치</span><span class="sxs-lookup"><span data-stu-id="1ef74-102">Configuration Manager devices missing in the portal</span></span>

<span data-ttu-id="1ef74-103">장치 동기화가 작동하려면 서비스 연결 지점 역할을 호스팅하는 온-프레미스 서버에서 [필수 인터넷 끝점](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints)을 연결할 수 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="1ef74-103">For device sync to work, [required internet endpoints](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) must be reachable from the on-premise server hosting the Service Connection Point role.</span></span> <span data-ttu-id="1ef74-104">장치 동기화 문제를 해결하려면 서비스 연결 지점에 있는 **CMGatewaySyncUploadWorker.log**를 검토하세요.</span><span class="sxs-lookup"><span data-stu-id="1ef74-104">To troubleshoot device sync, please review the **CMGatewaySyncUploadWorker.log** located on the service connection point.</span></span>

<span data-ttu-id="1ef74-105">[Microsoft 끝점 관리자에서 테넌트 연결](https://docs.microsoft.com/configmgr/tenant-attach/)에 대해서 자세히 알아보세요.</span><span class="sxs-lookup"><span data-stu-id="1ef74-105">Learn more about [Tenant attach in Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span></span>
