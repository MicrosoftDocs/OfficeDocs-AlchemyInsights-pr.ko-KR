---
title: 주소 목록에서 그룹을 숨기 거 나 숨기기 취소 하기 위한 지침
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: d0e0285701f1a5f308bdc682abaddf5cc2d34120
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768932"
---
# <a name="hide-office-365-group-from-address-list-gal"></a><span data-ttu-id="b4a85-102">주소 목록 (GAL)에서 Office 365 그룹 숨기기</span><span class="sxs-lookup"><span data-stu-id="b4a85-102">Hide Office 365 group from address list (GAL)</span></span>

<span data-ttu-id="b4a85-103">Outlook 또는 OWA와 같은 Exchange 클라이언트의 주소 목록 (GAL)에서 Office 365 그룹을 숨기려면 EXO shell에서 다음 명령을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="b4a85-103">To hide an Office 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="b4a85-104">Office 365 그룹을 Exchange 클라이언트에 표시 하지 않도록 숨기려면 EXO shell에서 다음 명령을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="b4a85-104">To hide the Office 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

