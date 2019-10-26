---
title: Access services 퇴직
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 197366882468ebc87fc26f2fe2733371790d1871
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/25/2019
ms.locfileid: "36747790"
---
# <a name="access-services-retirement"></a><span data-ttu-id="291e4-102">Access services 퇴직</span><span class="sxs-lookup"><span data-stu-id="291e4-102">Access services retirement</span></span>

<span data-ttu-id="291e4-103">처음에 발표 된 것 처럼 3 월 2017 일에 온 것 처럼, 지난 해 전에 Access Services를 통한 통신은 Office 365에서 만료 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired from Office 365.</span></span> <span data-ttu-id="291e4-104">이 프로세스의 다음 단계는 SharePoint 목록을 기본 데이터 저장소로 사용 하는 Access 웹 데이터베이스를 제거 하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

<span data-ttu-id="291e4-105">**어떤 영향을 줍니까?**</span><span class="sxs-lookup"><span data-stu-id="291e4-105">**How does this affect me?**</span></span>

<span data-ttu-id="291e4-106">2019 년 6 월부터 시작 하 여 SharePoint Online에서 새 Access 데이터베이스 만들기를 중지 하 고 서비스 및 나머지 모든 앱을 4 월 2020까지 종료 합니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

<span data-ttu-id="291e4-107">**이 변경 사항을 준비 하려면 어떻게 해야 하나요?**</span><span class="sxs-lookup"><span data-stu-id="291e4-107">**What do I need to do to prepare for this change?**</span></span>

<span data-ttu-id="291e4-108">조직의 Access 웹 데이터베이스에 대 한 전환 계획을 만드는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-108">We encourage you to create a transition plan for your organization’s Access web databases.</span></span> <span data-ttu-id="291e4-109">관리자는 [SharePoint access 앱 검색](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) 프로그램을 사용 하 여 사이트에서 사용 중인 Access 앱의 인벤토리를 가져올 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-109">Admins can use the [SharePoint Access app scanner](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) to obtain an inventory of the Access apps that sites are using.</span></span>

<span data-ttu-id="291e4-110">Access 웹 데이터베이스 데이터를 마이그레이션하는 방법에는 여러 가지가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="291e4-111">로컬 Access 데이터베이스 (. ACCDB) 또는 Excel 파일에 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="291e4-112">또한 웹 및 모바일 장치용 코드 없는 비즈니스 솔루션을 만드는 대체 플랫폼으로 Microsoft PowerApps를 탐색 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="291e4-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>