---
title: SharePoint에서 사이트를 영구적으로 삭제
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.custom: ''
ms.assetid:
- "5200006"
- "4391"
ms.openlocfilehash: 263317339d965d173a5a038fa006e0ce6f8476cc
ms.sourcegitcommit: da04e79b6072321caa16a6ceea6eb5f15de22394
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/25/2020
ms.locfileid: "42955165"
---
# <a name="permanently-delete-a-site-in-sharepoint"></a><span data-ttu-id="878d6-102">SharePoint에서 사이트를 영구적으로 삭제</span><span class="sxs-lookup"><span data-stu-id="878d6-102">Permanently delete a site in SharePoint</span></span>

<span data-ttu-id="878d6-103">삭제된 사이트의 URL을 다시 사용하거나 (사이트를 다시 작성하기 위해) 더 이상 사용하지 않는 사이트를 영구적으로 삭제하려면 새 SharePoint 관리 센터에서 **영구 삭제**를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="878d6-103">To reuse a URL from a deleted site (to recreate a site), or to permanently delete a site because it's no longer in use, you can use **Permanently Delete** from the New SharePoint Admin Center.</span></span> 

1. <span data-ttu-id="878d6-104">[새 SharePoint 관리 센터의 삭제된 사이트 페이지](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true)로 이동하고 조직에 대한 관리자 권한이 있는 계정으로 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="878d6-104">Go to the [Deleted sites page of the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) and sign in with an account that has admin permissions for your organization.</span></span> 

2. <span data-ttu-id="878d6-105">왼쪽 열에서 사이트를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="878d6-105">In the left column, select a site.</span></span> 

3. <span data-ttu-id="878d6-106">**영구 삭제**를 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="878d6-106">Click **Permanently Delete**.</span></span> 

<span data-ttu-id="878d6-107">**참고**: 그룹 연결 사이트는 새 SharePoint 관리 센터에서 영구적으로 삭제할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="878d6-107">**Note**: Group-connected sites cannot be permanently deleted from the New SharePoint Admin Center.</span></span> <span data-ttu-id="878d6-108">대신 [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite)를 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="878d6-108">[Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite) will need to be used instead.</span></span>  

<span data-ttu-id="878d6-109">자세한 내용은 [사이트 영구 삭제](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="878d6-109">For more info, see [Permanently delete a site](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site).</span></span> 
