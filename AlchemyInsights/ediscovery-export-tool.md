---
title: eDiscovery 내보내기
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 67e59182a5053111a08f5fb2be814931a1aa815d
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277942"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a><span data-ttu-id="0e6d9-102">EDiscovery 내보내기 도구를 설치 하거나 실행할 수 없습니까?</span><span class="sxs-lookup"><span data-stu-id="0e6d9-102">Can't install or run the eDiscovery Export Tool?</span></span>

<span data-ttu-id="0e6d9-103">EDiscovery 내보내기 도구를 설치 하거나 실행 하 여 검색 결과를 다운로드할 수 없는 경우 다음 항목을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="0e6d9-103">If you can't install or run the eDiscovery Export Tool to download search results, check the following things:</span></span>
  
- <span data-ttu-id="0e6d9-104">사용 중인 컴퓨터가 다음 사전 요구 사항을 충족 합니다.</span><span class="sxs-lookup"><span data-stu-id="0e6d9-104">The computer you're using meets these pre-requisites:</span></span>

  - <span data-ttu-id="0e6d9-105">32비트 및 64비트 버전의 Windows 7 이상 버전</span><span class="sxs-lookup"><span data-stu-id="0e6d9-105">32- or 64-bit versions of Windows 7 and later versions</span></span>

  - <span data-ttu-id="0e6d9-106">Microsoft .NET Framework 4.7</span><span class="sxs-lookup"><span data-stu-id="0e6d9-106">Microsoft .NET Framework 4.7</span></span>

  - <span data-ttu-id="0e6d9-107">지원되는 브라우저:</span><span class="sxs-lookup"><span data-stu-id="0e6d9-107">A supported browser:</span></span>

  - <span data-ttu-id="0e6d9-108">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="0e6d9-108">Microsoft Edge</span></span>

    <span data-ttu-id="0e6d9-109">또는</span><span class="sxs-lookup"><span data-stu-id="0e6d9-109">Or</span></span>

  - <span data-ttu-id="0e6d9-110">Internet Explorer 10 이상 버전</span><span class="sxs-lookup"><span data-stu-id="0e6d9-110">Internet Explorer 10 and later versions</span></span>

    <span data-ttu-id="0e6d9-111">Google Chrome 및 Mozilla Firefox와 같은 다른 브라우저는 지원 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0e6d9-111">Other browsers, such as Google Chrome and Mozilla Firefox aren't supported.</span></span>

- <span data-ttu-id="0e6d9-112">조직은 Azure의 끝점 ( \*\* \* blob.core.windows.net\*\* )에 연결할 수 있습니다 (와일드 카드는 내보내기 작업에 대 한 고유 식별자를 나타냄).</span><span class="sxs-lookup"><span data-stu-id="0e6d9-112">Your organization can connect to the endpoint in Azure, which is **\*.blob.core.windows.net** (the wildcard represents a unique identifier for your export job).</span></span>

- <span data-ttu-id="0e6d9-113">Microsoft 365 보안 및 준수 센터에서 내보내기 역할이 할당 &amp; 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0e6d9-113">You're assigned the Export role in the Microsoft 365 Security &amp; Compliance Center.</span></span> <span data-ttu-id="0e6d9-114">기본적으로이 역할은 eDiscovery 관리자 역할 그룹에만 할당 됩니다.</span><span class="sxs-lookup"><span data-stu-id="0e6d9-114">By default, this role is only assigned to the eDiscovery Manager role group.</span></span> <span data-ttu-id="0e6d9-115">[EDiscovery 사용 권한 할당](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="0e6d9-115">See [Assign eDiscovery permissions](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions).</span></span>

<span data-ttu-id="0e6d9-116">자세한 내용은 [Export Content Search results](https://docs.microsoft.com/microsoft-365/compliance/export-search-results)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="0e6d9-116">For more information, see [Export Content Search results](https://docs.microsoft.com/microsoft-365/compliance/export-search-results).</span></span>

<span data-ttu-id="0e6d9-117">10만 개 이상의 사서함을 내보내는 경우에는 다음 Powershell을 사용 하 여 내보내기 결과를 다운로드 해야 합니다 (  [10만 개 이상의 사서함에서 결과 내보내기](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes)).</span><span class="sxs-lookup"><span data-stu-id="0e6d9-117">If you are exporting more than 100K mailboxes, you will need to use the following Powershell to download the Export results:  [Exporting results from more than 100K mailboxes](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).</span></span>