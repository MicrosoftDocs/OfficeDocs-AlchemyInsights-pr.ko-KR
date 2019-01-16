---
title: 정품 인증에 실패 워크플로 누락
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 33b92c2cae1f641b0cd88c82fd4ae5e8632d76c2
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28299568"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="cc933-102">정품 인증에 실패 워크플로 누락</span><span class="sxs-lookup"><span data-stu-id="cc933-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="cc933-103">Microsoft SharePoint 사이트 모음, 목록 또는 라이브러리에 (예: "승인-SharePoint 2010") 전역적으로 재사용 가능한 워크플로 추가할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="cc933-104">이 문제를 해결 하려면 다음이 단계를 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="cc933-105">SharePoint Designer 2013의 사이트 모음의 루트 웹사이트를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="cc933-106">**사이트 개체** **워크플로**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="cc933-107">**워크플로** 리본 메뉴의 **새로 만들기** 섹션에서 **다시 사용할 수 있는 워크플로**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="cc933-p101">**다시 사용할 수 있는 워크플로 만들기** 양식 이름을 입력 \* \* *Repair2010* \* \*. **플랫폼 유형**대 한 **SharePoint 2010 워크플로**클릭 한 다음 **확인**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-p101">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*. For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="cc933-110">**워크플로** 리본 메뉴의 **저장** 섹션에서 **게시**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="cc933-p102">**워크플로** 리본 메뉴의 **관리** 섹션에서 **전역적으로 게시**를 선택 합니다. 확인 대화 상자에서 **확인**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="cc933-p103">웹 브라우저에서 사이트 모음의 루트 웹사이트 찾은 다음 **사이트 설정** 에 액세스 \> **사이트 모음 기능**입니다. 다음 **워크플로** 기능을 설정/해제 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="cc933-115">· 기능이 *활성화 됨* 이면 **비활성화를** 클릭 하 고 **활성화**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="cc933-116">· *비활성화 됨* 의 기능을 사용 하는 경우에 **활성화**를 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="cc933-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="cc933-117">자세한 내용은 다음 [문서](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="cc933-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

