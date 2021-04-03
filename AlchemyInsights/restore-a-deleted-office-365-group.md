---
title: 삭제된 Microsoft 365 그룹 복원
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
ms.custom:
- "98"
- "1200024"
ms.assetid: bc0396ea-c426-4d1d-bb89-ced602d06fb6
ms.openlocfilehash: 6f640093cd099f20d3a95eede5c141ad74838b0b
ms.sourcegitcommit: 7b2e5078dd65f11af6650e692a7ea48e91f544e0
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/02/2021
ms.locfileid: "51505692"
---
# <a name="restore-a-deleted-microsoft-365-group"></a><span data-ttu-id="f4c23-102">삭제된 Microsoft 365 그룹 복원</span><span class="sxs-lookup"><span data-stu-id="f4c23-102">Restore a deleted Microsoft 365 group</span></span>

<span data-ttu-id="f4c23-103">삭제 후 30일 이내에 삭제된 Microsoft 365 그룹 또는 Microsoft Teams를 복원할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f4c23-103">You can restore a deleted Microsoft 365 group or Microsoft Teams within 30 days from the deletion.</span></span>

1. <span data-ttu-id="f4c23-104">Microsoft 365 관리 센터에 로그인하고 삭제된 그룹 및 팀을 나열하려면 [Microsoft 365 관리 센터로 이동하세요.](https://aka.ms/RestoreDeletedGroup)</span><span class="sxs-lookup"><span data-stu-id="f4c23-104">To login to Microsoft 365 admin center and list the deleted groups and teams, go to the [Microsoft 365 admin center](https://aka.ms/RestoreDeletedGroup).</span></span>

    <span data-ttu-id="f4c23-105">**참고:** 테넌트 관리자 또는 그룹 관리자 역할에 할당된 계정을 사용하여 로그인합니다.</span><span class="sxs-lookup"><span data-stu-id="f4c23-105">**Note:** Log in using the account that is assigned to either the tenant administrator or the groups admin role.</span></span>

1. <span data-ttu-id="f4c23-106">복원할 삭제된 Microsoft 365 그룹/Teams를 선택하고 그룹 **복원을 클릭합니다.**</span><span class="sxs-lookup"><span data-stu-id="f4c23-106">Select the deleted Microsoft 365 group/Teams to be restored and click **restore group**.</span></span>

    <span data-ttu-id="f4c23-107">충돌하는 SMTP 주소로 인해 그룹을 복원할 수 없는 경우 다음 명령을 사용하여 충돌을 일으키는 개체를 찾고 SMTP 주소를 제거합니다.</span><span class="sxs-lookup"><span data-stu-id="f4c23-107">If the group can't be restored because of a conflicting SMTP address, use following command to find the object that’s causing conflict and remove the SMTP address:</span></span>

    `Get-Recipient -Filter "EmailAddresses -eq '<conflictingsmtpaddress>'"`

    <span data-ttu-id="f4c23-108">**참고:** 경우에 따라 그룹 및 모든 데이터를 복원하는 데 24시간이 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f4c23-108">**Note:** In some cases, it might take as long as 24 hours for the group and all of its data to be restored.</span></span>

    <span data-ttu-id="f4c23-109">자세한 내용을 보거나 PowerShell을 사용하여 그룹을 복원하는 방법에 대한 자세한 내용은 삭제된 [Microsoft 365 그룹 복원을 참조하세요.](https://go.microsoft.com/fwlink/?linkid=867802)</span><span class="sxs-lookup"><span data-stu-id="f4c23-109">For more info, or to learn how to restore groups using PowerShell, see [Restore a deleted Microsoft 365 group](https://go.microsoft.com/fwlink/?linkid=867802).</span></span>