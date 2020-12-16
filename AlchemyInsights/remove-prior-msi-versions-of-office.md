---
title: 이전 버전의 Office MSI 제거
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/15/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003886"
- "6940"
ms.openlocfilehash: 26ab610cb204149536bd23c830a1b8558892a7c0
ms.sourcegitcommit: c033720921cb9a06b9560eedef4f1935e69a846b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2020
ms.locfileid: "49680626"
---
# <a name="remove-prior-msi-versions-of-office"></a><span data-ttu-id="9f682-102">이전 버전의 Office MSI 제거</span><span class="sxs-lookup"><span data-stu-id="9f682-102">Remove prior MSI versions of Office</span></span>

<span data-ttu-id="9f682-103">Office 365 ProPlus를 설치하기 전에 이전 버전의 Office MSI(Windows Installer)를 제거하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="9f682-103">I recommend removing prior Windows Installer (MSI) versions of Office before installing Office 365 ProPlus.</span></span> <span data-ttu-id="9f682-104">이 작업을 하는 방법에는 다음이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9f682-104">Here's how to do this:</span></span>

1. <span data-ttu-id="9f682-105">MSI를 사용하여 Office를 설치한 경우 ODT(Office 배포 도구)를 사용하여 Office를 설치할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9f682-105">If you used MSI to install Office, you can use the Office Deployment Tool (ODT) to uninstall Office.</span></span> <span data-ttu-id="9f682-106">사용자 파일에서 RemoveMSI **요소를** configuration.xml있습니다.</span><span class="sxs-lookup"><span data-stu-id="9f682-106">You can use the RemoveMSI element in your **configuration.xml** file.</span></span>
1. <span data-ttu-id="9f682-107">이 문서의 지침을 따르는 경우: [Office 365 보안](https://go.microsoft.com/fwlink/p/?linkid=2077143) & 준수 센터.</span><span class="sxs-lookup"><span data-stu-id="9f682-107">Follow the instruction in this article: [Office 365 Security & Compliance Center.](https://go.microsoft.com/fwlink/p/?linkid=2077143)</span></span>