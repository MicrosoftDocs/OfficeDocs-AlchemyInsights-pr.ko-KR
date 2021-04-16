---
title: 삭제된 공용 폴더 복원
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: d5480389c3bf50cee9fe30f7ec8d8ff28ef694ca
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51809445"
---
# <a name="restore-a-deleted-public-folder"></a><span data-ttu-id="d8333-102">삭제된 공용 폴더 복원</span><span class="sxs-lookup"><span data-stu-id="d8333-102">Restore a deleted public folder</span></span>

<span data-ttu-id="d8333-103">**공용 폴더에서 삭제된 항목을 복원하려면**:</span><span class="sxs-lookup"><span data-stu-id="d8333-103">**To restore deleted items from a public folder**:</span></span>

- <span data-ttu-id="d8333-104">[Outlook 2016에서](https://aka.ms/pfrec)메일이 없는 공용 폴더에서 삭제된 항목을 복구할 수 없습니다를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="d8333-104">See [You can't recover deleted items from a non-mail public folder in Outlook 2016](https://aka.ms/pfrec).</span></span>
 
<span data-ttu-id="d8333-105">삭제된 공용 폴더(모든 **형식)를 복원하려면**:</span><span class="sxs-lookup"><span data-stu-id="d8333-105">**To restore a deleted public folder (of any type)**:</span></span> 

- <span data-ttu-id="d8333-106">다음 EXO PowerShell 명령을 사용하시기 바랍니다.</span><span class="sxs-lookup"><span data-stu-id="d8333-106">Please use following EXO PowerShell command:</span></span>

    <span data-ttu-id="d8333-107">구문:</span><span class="sxs-lookup"><span data-stu-id="d8333-107">Syntax:</span></span>

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    <span data-ttu-id="d8333-108">예: 다음 명령은 Subfolder1을 복원하고 \Parent1 아래에 를 습니다.</span><span class="sxs-lookup"><span data-stu-id="d8333-108">Example: The following command will restore Subfolder1 and place it under \Parent1:</span></span>

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

<span data-ttu-id="d8333-109">자세한 [내용은 삭제된](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) 공용 폴더 복원을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="d8333-109">See [Restore a deleted public folder](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) for more details.</span></span>
