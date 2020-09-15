---
title: 사용자에 게 SharePoint 및 OneDrive에 대 한 액세스 권한 부여
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
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a7e9c0b7ffa5c11a2e24ee5fda6491f049f985f1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47677213"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="a8b95-102">사용자에 게 SharePoint 및 OneDrive에 대 한 액세스 권한 부여</span><span class="sxs-lookup"><span data-stu-id="a8b95-102">Give users access to SharePoint and OneDrive</span></span>

> [!NOTE]
> <span data-ttu-id="a8b95-103">이전에 액세스 한 여러 사용자가 OneDrive 또는 SharePoint 사이트를 사용할 수 없는 경우 일시적인 서비스 문제가 있을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> [<span data-ttu-id="a8b95-104">서비스 상태 대시보드 확인</span><span class="sxs-lookup"><span data-stu-id="a8b95-104">Check the service health dashboard</span></span>](https://portal.office.com/adminportal/home#/servicehealth)
  
<span data-ttu-id="a8b95-105">조직의 사용자가 SharePoint 및 OneDrive에 로그인 하 고 사용할 수 있도록 하려면 계정을 추가 하 고 SharePoint 및 OneDrive에 대 한 액세스 권한을 부여 하는 라이선스가 있는지 확인 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-105">If you want people in your organization to be able to sign in and use SharePoint and OneDrive, you need to add accounts for them and make sure they have a license that gives them access to SharePoint and OneDrive.</span></span> <span data-ttu-id="a8b95-106">사용자를 추가 하는 가장 쉬운 방법은 Microsoft 365 관리 센터에 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-106">The easiest way to add users is in the Microsoft 365 admin center.</span></span>
  
1. <span data-ttu-id="a8b95-107">[Microsoft 365 관리 센터에서 활성 사용자 페이지로](https://portal.office.com/adminportal/home#/users)이동한 다음 **사용자 추가**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-107">Go to the [Active users page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/users), and then click **Add a user**.</span></span>
    
2. <span data-ttu-id="a8b95-108">사용자에 대 한 정보를 입력 하 고 **제품 라이선스**에 라이선스가 할당 되 고 **SharePoint Online** 이 선택 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-108">Fill in the information for the user, and make sure that under **Product licenses**, a license is assigned and **SharePoint Online** is selected.</span></span> 
    
<span data-ttu-id="a8b95-109">조직에서 외부 공유를 허용 하는 경우 사용자는 SharePoint 및 OneDrive 콘텐츠를 조직 외부의 사용자와 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-109">Note that if you allow external sharing in your organization, users can share SharePoint and OneDrive content with people outside the organization.</span></span> <span data-ttu-id="a8b95-110">이러한 외부 사용자 라이선스를 제공할 필요는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-110">You don't need to give these external users licenses.</span></span> <span data-ttu-id="a8b95-111">또한 공유가 "기존 외부 사용자만"으로 설정 되지 않은 경우 계정을 추가할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-111">You also don't need to add accounts for them, unless sharing is set to "Only existing external users."</span></span> <span data-ttu-id="a8b95-112">이 경우 조직의 디렉터리에 없는 사용자는 Azure AD 관리 센터에서 게스트 사용자로 추가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a8b95-112">In that case, if the people aren't in your organization's directory, you need to add them as guest users in the Azure AD admin center.</span></span>
  

