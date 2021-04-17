---
title: Microsoft 365 그룹에 보낸 메시지를 모든 구성원이 수신하지 않음
ms.author: pebaum
author: pebaum
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
- "5995"
ms.openlocfilehash: 29adc5a7b8b74280cb3fcd6369dc4fc3a3e8e957
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51823793"
---
# <a name="messages-sent-to-a-microsoft-365-group-are-not-received-by-all-members"></a><span data-ttu-id="4a395-102">Microsoft 365 그룹에 보낸 메시지를 모든 구성원이 수신하지 않음</span><span class="sxs-lookup"><span data-stu-id="4a395-102">Messages sent to a Microsoft 365 group are not received by all members</span></span>

<span data-ttu-id="4a395-103">모든 그룹 구성원이 구독하여 전자 메일을 수신하는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="4a395-103">Ensure that all group members have subscribed to receive the emails.</span></span> <span data-ttu-id="4a395-104">[Outlook에서 그룹 팔로우하기](https://support.microsoft.com/office/e147fc19-f548-4cd2-834f-80c6235b7c36)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="4a395-104">See [Follow a group in Outlook](https://support.microsoft.com/office/e147fc19-f548-4cd2-834f-80c6235b7c36).</span></span>  

<span data-ttu-id="4a395-105">그룹 전자 메일을 구독하는 구성원의 메시지 상태를 확인하려면 [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps&preserve-view=true)에서 다음 명령을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="4a395-105">To check the message status of members who have subscribed to group emails, run the following command on [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps&preserve-view=true):</span></span>

`Get-UnifiedGroup <GroupName> | Get-UnifiedGroupLinks -LinkType Subscribers`

<span data-ttu-id="4a395-106">다음 EXO PowerShell 명령을 사용하여 모든 그룹 구성원이 받은 편지함에 Microsoft 365 그룹으로 보낸 전자 메일을 수신하도록 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="4a395-106">Use the following EXO PowerShell command to configure all group members to receive emails sent to Microsoft 365 group in their inbox:</span></span>

`$Group = "Address of [Microsoft 365 Groups]"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`

<span data-ttu-id="4a395-107">예를 들면 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="4a395-107">For example:</span></span>

`$Group = "testg@contoso.onmicrosoft.com"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`