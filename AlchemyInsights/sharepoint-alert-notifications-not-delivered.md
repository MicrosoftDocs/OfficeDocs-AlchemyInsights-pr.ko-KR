---
title: SharePoint 경고 알림이 배달 되지 않음
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: 363f3c79a3b62f3017e6c873f1be3dd195cab883
ms.sourcegitcommit: 5296874062b16f945d9a7a7a9ab29ec53686310b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/21/2020
ms.locfileid: "44343099"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a><span data-ttu-id="c8a8c-102">SharePoint 경고 알림이 배달 되지 않음</span><span class="sxs-lookup"><span data-stu-id="c8a8c-102">SharePoint alert notifications not delivered</span></span>

<span data-ttu-id="c8a8c-103">가끔씩 경고가 발생할 수 있으므로 전자 메일에서 정크 폴더를 확인 하세요.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-103">Please check the JUNK folder in your email, as sometimes alerts might go there.</span></span>

<span data-ttu-id="c8a8c-104">**모든 경고가 배달 되지** 않거나 특정 파일이 나 라이브러리의 **개별 알림이** 배달 되지 않는 경우를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-104">Determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="c8a8c-105">**개별 알림이 배달 되지 않음**: 특정 파일 또는 라이브러리의 개별 경고가 배달 되지 않으면 삭제 하 고 다시 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-105">**Individual alerts are not delivered**: If an individual alert from a specific file or library is not delivered, you can attempt to delete and recreate it.</span></span> <span data-ttu-id="c8a8c-106">경고를 다시 만들려면 [SharePoint 알림 관리, 보기 또는 삭제](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-106">See [Manage, view, or delete SharePoint alerts](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) to recreate the alert.</span></span>
- <span data-ttu-id="c8a8c-107">**모든 경고가 배달 되지 않음**: 여러 파일 또는 라이브러리의 모든 경고가 배달 되지 않으면 [서비스 상태 대시보드](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) 를 방문 하 여 SharePoint 또는 Exchange에서 발생할 수 있는 모든 권고/사고를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-107">**All alerts are not delivered**: If all alerts from multiple files or libraries are not delivered, visit the [Service Health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="c8a8c-108">이 문제는 Exchange를 통한 전자 메일의 SharePoint 알림 기능 또는 지연으로 인해 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-108">The issue could be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="c8a8c-109">또한 다른 전자 메일이 배달 되는지 여부를 확인 하는 것이 중요 하 고, 그렇지 않은 경우 Exchange 지연으로 인 한 문제일 가능성이 높습니다.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-109">It will also be important to note whether other email is being delivered, and if not, the issue is likely with Exchange delays.</span></span>

<span data-ttu-id="c8a8c-110">경고에 대 한 FAQ:</span><span class="sxs-lookup"><span data-stu-id="c8a8c-110">FAQ on alerts:</span></span>

- <span data-ttu-id="c8a8c-111">메일 그룹에 알림을 보낼 수는 없으므로 보안 및 O365 그룹만 지원 됩니다.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-111">It is not possible to send alerts to Distribution Group, only Security and O365 groups are supported.</span></span>
- <span data-ttu-id="c8a8c-112">경고 전자 메일 템플릿은 사용자 지정할 수 없습니다. 이러한 사항을 구현 하려면 Microsoft FLOW 또는 SharePoint Designer 워크플로를 사용 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="c8a8c-112">You cannot customize alert email templates; you need to use Microsoft FLOW or SharePoint Designer Workflow to achieve those.</span></span>

## <a name="related-topics"></a><span data-ttu-id="c8a8c-113">관련 항목</span><span class="sxs-lookup"><span data-stu-id="c8a8c-113">Related Topics</span></span>

<span data-ttu-id="c8a8c-114">SharePoint Online에서 Microsoft Flow를 시도 하 고 싶으십니까?</span><span class="sxs-lookup"><span data-stu-id="c8a8c-114">Want to try Microsoft Flow in SharePoint Online?</span></span>

- [<span data-ttu-id="c8a8c-115">흐름 만들기</span><span class="sxs-lookup"><span data-stu-id="c8a8c-115">Create Flow</span></span>](https://support.office.com/article/a9c3e03b-0654-46af-a254-20252e580d01)

- [<span data-ttu-id="c8a8c-116">SharePoint 및 흐름</span><span class="sxs-lookup"><span data-stu-id="c8a8c-116">SharePoint and Flow</span></span>](https://flow.microsoft.com//blog/sharepoint-and-flow/)
