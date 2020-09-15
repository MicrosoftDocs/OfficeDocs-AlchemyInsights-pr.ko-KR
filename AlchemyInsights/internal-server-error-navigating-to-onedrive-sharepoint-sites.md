---
title: 성능 문제-SharePoint 또는 OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 99d99b22c7ec5e3bde6a89dc2da8e08c2162bf65
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47677176"
---
# <a name="internal-server-error-when-navigating-to-sharepoint-or-onedrive-sites"></a><span data-ttu-id="9585d-102">Sharepoint 또는 OneDrive 사이트로 이동 하는 동안 내부 서버 오류가 발생 했습니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-102">Internal server error when navigating to Sharepoint or OneDrive sites</span></span>

<span data-ttu-id="9585d-103">SharePoint 또는 OneDrive 사이트로 이동 하려고 하면 사용자에 게 500 내부 서버 오류가 수신 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-103">Users may receive a 500 internal server error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="9585d-104">사이트를 탐색 하기 전에 브라우저 캐시를 지워야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-104">Please attempt to clear the browser cache before navigating to the site.</span></span>


1. <span data-ttu-id="9585d-105">Microsoft Edge 브라우저에서 더 보기 > 설정으로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-105">In the Microsoft Edge browser, go to More...> Settings</span></span>

2. <span data-ttu-id="9585d-106">검색 지우기 데이터에서 **지우려는 작업** 선택을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-106">Under Clear browsing data, select **Choose what to clear**</span></span>

3. <span data-ttu-id="9585d-107">쿠키 및 저장 된 웹 사이트 데이터 확인란을 선택 하 고 **지우기를**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-107">Select the Cookies and saved website data check box and select **Clear**.</span></span>

<span data-ttu-id="9585d-108">참고: Firefox, Chrome 등의 다른 브라우저를 사용 하는 경우에는 이러한 단계가 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-108">Note: These steps may differ when using other browsers such as Firefox or Chrome.</span></span>

<span data-ttu-id="9585d-109">이렇게 해도 문제가 해결 되지 않으면 [메시지 센터로](https://portal.office.com/adminportal/home#/MessageCenter)이동 하 여 테 넌 트에서 활성 유지 관리가 진행 되 고 있는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-109">If this does not resolve the issue, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

<span data-ttu-id="9585d-110">마지막으로 [서비스 상태](https://portal.office.com/adminportal/home#/servicehealth) 페이지를 방문 하 여 발생할 수 있는 권고/인시던트가 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="9585d-110">Finally , ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

