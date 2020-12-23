---
title: 콘텐츠 검색/내보내기 중에 결과가 반환되지 않습니다.
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3200003"
- "7463"
ms.openlocfilehash: 8786f11f170edb151879235e19caa38b50f3f06e
ms.sourcegitcommit: 3d662e1a1440ba74b5347896347d03bb8c8f3af5
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/22/2020
ms.locfileid: "49727229"
---
# <a name="no-results-returned-during-content-searchexport"></a><span data-ttu-id="3eecd-102">콘텐츠 검색/내보내기 중에 결과가 반환되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="3eecd-102">No results returned during Content Search/Export</span></span>

<span data-ttu-id="3eecd-103">다음과 같은 eDiscovery 시나리오에 문제가 있는 경우</span><span class="sxs-lookup"><span data-stu-id="3eecd-103">If you are experiencing issues with the following eDiscovery scenarios:</span></span>

- <span data-ttu-id="3eecd-104">콘텐츠 검색/내보내기에서 데이터 또는 예기치 않은 데이터가 반환되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="3eecd-104">Content Search/Export returns no data or unexpected data</span></span>
- <span data-ttu-id="3eecd-105">eDiscovery 검색 또는 내보내기 실패</span><span class="sxs-lookup"><span data-stu-id="3eecd-105">eDiscovery Search or Export fails</span></span>

<span data-ttu-id="3eecd-106">특정 관리자가 설정하고 모든 관리자에게 전달되지 않은 특정 준수 보안 필터 때문일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3eecd-106">This may be due to certain Compliance Security Filters that were setup by a specific Admin and not been communicated to all Admins.</span></span>

<span data-ttu-id="3eecd-107">이 문제를 해결하기 위해 이러한 문제를 유발할 수 있는 준수 보안 필터가 없는지 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="3eecd-107">To resolve this, check if there are any Compliance Security Filters that may be causing these issues:</span></span>

1. <span data-ttu-id="3eecd-108">보안 및 준수 센터 Powershell에 연결</span><span class="sxs-lookup"><span data-stu-id="3eecd-108">Connect to Security and Compliance Center Powershell</span></span>
2. <span data-ttu-id="3eecd-109">다음 commandlet을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="3eecd-109">Run the following commandlets:</span></span>

    `$org = “yourdomain.com”`

    `Get-ComplianceSecurityFilter -Organization $org`

<span data-ttu-id="3eecd-110">준수 보안 필터에 대한 자세한 내용은 콘텐츠 검색에 대한 사용 권한 [필터링을 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/permissions-filtering-for-content-search)</span><span class="sxs-lookup"><span data-stu-id="3eecd-110">For additional information on Compliance Security Filters, see [Permissions Filtering for Content Search](https://docs.microsoft.com/microsoft-365/compliance/permissions-filtering-for-content-search)</span></span>
