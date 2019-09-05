---
title: 네트워크 드라이브에 SharePoint 라이브러리 매핑
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 12/17/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 4b8245c3-a179-4524-ae83-0c22d539c202
ms.openlocfilehash: c7b16cb448684d3f68be84fda4d9de201b953ffb
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/04/2019
ms.locfileid: "36734891"
---
# <a name="map-a-sharepoint-library-to-a-network-drive"></a><span data-ttu-id="3b5cd-102">네트워크 드라이브에 SharePoint 라이브러리 매핑</span><span class="sxs-lookup"><span data-stu-id="3b5cd-102">Map a SharePoint library to a network drive</span></span>

<span data-ttu-id="3b5cd-103">라이브러리를 네트워크 드라이브로 매핑하는 기능은 일시적 이며 Internet Explorer를 통해서만 지원 됩니다.</span><span class="sxs-lookup"><span data-stu-id="3b5cd-103">Mapping a library as a network drive is temporary and supported only through Internet Explorer.</span></span> <span data-ttu-id="3b5cd-104">가끔 Internet Explorer에서 SharePoint 사이트를 열고 **로그인 상태 유지** 를 선택 하 여 세션이 만료 되지 않도록 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="3b5cd-104">You must occasionally open the SharePoint site in Internet Explorer and select **Stay signed in** to prevent the session from expiring.</span></span> <span data-ttu-id="3b5cd-105">대신 [파일을 주문형](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e)으로 제공 하는 [새 OneDrive 동기화 클라이언트](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88) </a> 와 SharePoint 파일을 동기화 합니다.</span><span class="sxs-lookup"><span data-stu-id="3b5cd-105">Instead, [sync SharePoint files with the new OneDrive sync client](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> which provides [Files On-Demand](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e).</span></span> <span data-ttu-id="3b5cd-106">로컬 저장소 공간을 사용 하지 않고 OneDrive의 모든 파일에 액세스 합니다.</span><span class="sxs-lookup"><span data-stu-id="3b5cd-106">Access all your files in OneDrive without using local storage space.</span></span>

<span data-ttu-id="3b5cd-107">[새 OneDrive 동기화 클라이언트를 사용](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)하지 않고 드라이브를 매핑하도록 선택한 경우 아래 문서의 단계를 수행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="3b5cd-107">If you choose to map a drive instead of [using the new OneDrive sync client](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88), ensure you follow the steps in the article below.</span></span> 


<span data-ttu-id="3b5cd-108">**매핑된 네트워크 드라이브를 구성 하 고 문제를 해결 하는 방법**</span><span class="sxs-lookup"><span data-stu-id="3b5cd-108">**How to configure and troubleshoot mapped network drives**</span></span>


<span data-ttu-id="3b5cd-109">[SharePoint Onlines에 연결 되는 매핑된 네트워크 드라이브 문제 해결을](https://docs.microsoft.com/sharepoint/support/administration/troubleshoot-mapped-network-drives)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="3b5cd-109">See [Troubleshoot mapped network drives that connect to SharePoint Onlines](https://docs.microsoft.com/sharepoint/support/administration/troubleshoot-mapped-network-drives).</span></span>

<span data-ttu-id="3b5cd-110">참고: Windows 8 또는 Windows 7이 포함 된 Internet Explorer 10을 사용 하는 경우 드라이브를 매핑하면 **액세스 거부** 또는 **경로에 액세스할 수 없는** 경우이 문제를 해결 하려면 [이 핫픽스](https://support.microsoft.com/help/2846960) 를 설치 합니다.</span><span class="sxs-lookup"><span data-stu-id="3b5cd-110">NOTE:  If you use Internet Explorer 10 with Windows 8 or Windows 7, and receive **Access denied** or **Path is not accessible** when mapping a drive, install [this hotfix](https://support.microsoft.com/help/2846960) to resolve this problem.</span></span> 
