---
title: 오류 404 문제 해결-파일을 찾을 수 없음
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 1b15444c-367b-4523-8e08-1c77bbea7524
ms.openlocfilehash: 6c23d7c482e3beb900d6e0e2ba596c1ab1db8d7e
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2019
ms.locfileid: "40050675"
---
# <a name="troubleshoot-error-404-file-not-found"></a><span data-ttu-id="685cf-102">오류 404 문제 해결-파일을 찾을 수 없음</span><span class="sxs-lookup"><span data-stu-id="685cf-102">Troubleshoot Error 404, File not found</span></span>

<span data-ttu-id="685cf-103">사용자가 SharePoint 또는 OneDrive의 사이트 또는 파일에 액세스 하려고 할 때 오류 404이 수신 됩니다.</span><span class="sxs-lookup"><span data-stu-id="685cf-103">An Error 404 is received when users are attempting to access a site or file in SharePoint or OneDrive.</span></span> <span data-ttu-id="685cf-104">이 오류는 일반적으로 사이트 또는 파일 또는 그룹의 이름을 바꾸거나 이동 하거나 삭제 하기 때문에 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="685cf-104">This is often caused by a site or file or group getting renamed, moved or deleted.</span></span> <span data-ttu-id="685cf-105">예를 들어, 루트 사이트 모음에 액세스 하는 동안 404 오류가 발생 하 여 해당 사용자가 삭제 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="685cf-105">For example: Users will experience a 404 Error attempting to access the Root Site Collection and it has been deleted.</span></span>

<span data-ttu-id="685cf-106">이름이 바뀌거나 삭제 된 사이트에 대 한 404 오류를 해결 하려면 다음을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="685cf-106">To resolve Error 404 for a Site that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="685cf-107">클래식 관리 센터에 있는 클래식 사이트의 경우에 [는 삭제 된 사이트 모음 복원을](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="685cf-107">For classic sites that exist in the Classic Admin Center, see [Restore a deleted site collection](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection).</span></span>


<span data-ttu-id="685cf-108">새 SharePoint 관리 센터에 있는 최신 사이트 (통신, 그룹 연결 또는 기타 사이트)의 경우에는 [새 sharepoint 관리 센터에서 삭제 된 사이트 보기 및 복원을](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="685cf-108">For modern sites (communication, group-connected, or other sites) that exist in the new SharePoint admin center, see [View and restore deleted sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection).</span></span>

<span data-ttu-id="685cf-109">이름이 바뀌거나 삭제 된 파일 (또는 다른 항목)에 대 한 404 오류를 해결 하려면 다음을 수행 합니다.</span><span class="sxs-lookup"><span data-stu-id="685cf-109">To resolve Error 404 for a File (or other item) that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="685cf-110">SharePoint 또는 OneDrive 사이트로 이동 하 여 사이트 콘텐츠에서 휴지통을 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="685cf-110">Go to the SharePoint or OneDrive site and view the Recycle Bin from the Site contents.</span></span> <span data-ttu-id="685cf-111">[SharePoint 사이트의 휴지통에 있는 항목 복원을](https://support.office.com/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="685cf-111">See, [Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span></span>

<span data-ttu-id="685cf-112">로깅이 사용 하도록 설정 된 경우 감사 로그를 검색할 수 있는 항목을 여전히 찾을 수 없는 경우에는 [Office 365 보안 & 준수 센터에서 감사 로그를 검색](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c)하세요.</span><span class="sxs-lookup"><span data-stu-id="685cf-112">If you are still unable to find the item you can search the audit log if logging is enabled see, [Search the audit log in the Office 365 Security & Compliance Center](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span></span>
