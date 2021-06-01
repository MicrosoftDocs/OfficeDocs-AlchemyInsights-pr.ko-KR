---
title: Exchange Online PowerShell의 마이크로 지연 또는 제한
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 204e0248bc2f07f14fa789d1d2999495910ee034
ms.sourcegitcommit: d2108b13acc44e26b65f9a2739cbce9bf98959a5
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/28/2021
ms.locfileid: "52702132"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a><span data-ttu-id="05451-102">Exchange Online PowerShell의 마이크로 지연 또는 제한</span><span class="sxs-lookup"><span data-stu-id="05451-102">Micro delays or throttling in Exchange Online PowerShell</span></span>

<span data-ttu-id="05451-103">Exchange Online에서 스크립트와 cmdlet을 실행할 때 "마이크로 지연이 적용 됨"이라는 경고 혹은 지연이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="05451-103">You might see "Micro delay applied" warnings or delays when you run scripts and cmdlets in Exchange Online.</span></span> <span data-ttu-id="05451-104">이 문제를 해결하는 방법에 대한 몇 가지 제안 사항은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="05451-104">Here are a few suggestions how to solve this:</span></span>

- <span data-ttu-id="05451-105">Microsoft의 진단을 실행하여 테넌트의 PowerShell 제한 정책을 완화하세요.</span><span class="sxs-lookup"><span data-stu-id="05451-105">Please run our diagnostics to relax your tenant's PowerShell throttling policies.</span></span> <span data-ttu-id="05451-106">이 해결 방법은 대부분의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="05451-106">This solution will solve the problem for most.</span></span>
- <span data-ttu-id="05451-107">여전히 문제가 해결되지 않은 경우, REST API를 기반으로 하며 성능이 크게 향상된 CMDlets을 포함하는 [Exchange Online v2 PowerShell 모듈](/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps&preserve-view=true)을 사용하세요.</span><span class="sxs-lookup"><span data-stu-id="05451-107">If issue still not solved, use the [Exchange Online v2 PowerShell module](/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps&preserve-view=true), which includes CMDlets that are based on REST API and are significantly more performant.</span></span> <span data-ttu-id="05451-108">이는 자주 사용하는 많은 Get-Cmdlet에는 훌륭한 솔루션이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="05451-108">This might be a great solution for a lot of Get- CMDlets that are frequently used.</span></span>
- <span data-ttu-id="05451-109">V2 모듈에서 다루지 않는 Cmdlet을 사용해야 하는 경우, Exchange Online에서 PowerShell 제한 사항을 해결하는 방법에 대해 다루는 [Office 365에서 사용자 수가 많은 경우 PowerShell cmdlet을 실행](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="05451-109">If you need to use CMDlets that are not covered in the v2 module, please see [Running PowerShell cmdlets for large numbers of users in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), which talks about how to get around PowerShell throttling limits in Exchange Online.</span></span>
