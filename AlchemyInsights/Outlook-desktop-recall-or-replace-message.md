---
title: Outlook 데스크톱 전자 메일 메시지 회수 또는 교체
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: d64332778f9132aff6a9660bb0d522f4e16b753c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687516"
---
# <a name="recall-or-replace-an-outlook-email-message"></a><span data-ttu-id="178aa-102">Outlook 전자 메일 메시지 회수 또는 교체</span><span class="sxs-lookup"><span data-stu-id="178aa-102">Recall or replace an Outlook email message</span></span>

- <span data-ttu-id="178aa-103">관리자는 **PowerShell을 사용 하 여 사용자를 대신 하 여 메시지를 회수할**수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-103">As the admin, you can **recall messages on behalf of users using PowerShell**.</span></span> <span data-ttu-id="178aa-104">관리 센터에서 메시지를 회수할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-104">You can't recall messages from the admin center.</span></span>
- <span data-ttu-id="178aa-105">**조직의 사용자에 게 전송 된 메시지만 회수할**수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-105">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="178aa-106">예를 들어, 메시지가 Gmail 주소로 전송 된 경우에는 회수할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-106">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="178aa-107">**PC에서 Outlook 2016에서 보낸 메시지만 회수할**수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-107">You can **only recall messages sent from Outlook 2016 on the PC**.</span></span> <span data-ttu-id="178aa-108">사용자가 Outlook for Mac 또는 웹용 Outlook을 사용 하 여 메시지를 보낼 경우에는 회수할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-108">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>

<span data-ttu-id="178aa-109">전자 메일 메시지를 회수 하거나 교체 하려면:</span><span class="sxs-lookup"><span data-stu-id="178aa-109">To recall or replace an email message:</span></span>

1. <span data-ttu-id="178aa-110">Outlook 창 왼쪽의 폴더 창에서 보낸 편지함 폴더를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-110">In the folder pane on the left of the Outlook window, select the Sent Items folder.</span></span>
1. <span data-ttu-id="178aa-111">회수 하려는 메시지를 두 번 클릭 하 여 엽니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-111">Double-click the message you want to recall to open it.</span></span>
1. <span data-ttu-id="178aa-112">**메시지** 탭을 선택 하 고 **작업** > **회수 메시지**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-112">Select the **Message** tab, and then select **Actions** > **Recall This Message**.</span></span>
1. <span data-ttu-id="178aa-113">**이 메시지의 읽지 않은 복사본 삭제** 또는 **읽지 않은 복사본 삭제**를 선택 하 고 새 메시지로 바꾼 후 **확인**을 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-113">Select **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, and then select **OK**.</span></span>
1. <span data-ttu-id="178aa-114">대체 메시지를 보내는 경우 메시지를 작성 한 다음 **보내기를**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-114">If you're sending a replacement message, compose the message, and then select **Send**.</span></span>
1. <span data-ttu-id="178aa-115">메시지 회수의 성공 또는 실패는 Outlook의 받는 사람 설정에 따라 달라 집니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-115">The success or failure of a message recall depends on the recipient's settings in Outlook.</span></span> <span data-ttu-id="178aa-116">회수를 확인 하는 단계는 [이 문서](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="178aa-116">For steps to check on the recall, see [this article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="178aa-117">조직에서 전자 메일 메시지 검색 및 삭제</span><span class="sxs-lookup"><span data-stu-id="178aa-117">Search for and delete email messages in your organization</span></span>

- <span data-ttu-id="178aa-118">전역 관리자가 아닌 경우 메시지를 검색 하려면 eDiscovery 관리자 역할 또는 준수 검색 관리 역할에 계정을 추가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-118">If you're not a global admin, your account must be added to the eDiscovery Manager role or Compliance Search management role to search for messages.</span></span> <span data-ttu-id="178aa-119">메시지를 삭제 하려면 조직 관리 역할 그룹 또는 검색 및 삭제 관리 역할에 참가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-119">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="178aa-120">이러한 역할에 대 한 사용 권한은 [보안 및 준수 센터](https://go.microsoft.com/fwlink/?linkid=2083731)에 할당 됩니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-120">Permissions for these roles are assigned in the [Security and compliance center](https://go.microsoft.com/fwlink/?linkid=2083731).</span></span>
- <span data-ttu-id="178aa-121">삭제할 메시지를 찾을 [콘텐츠 검색을 만듭니다](https://docs.microsoft.com/office365/securitycompliance/content-search) .</span><span class="sxs-lookup"><span data-stu-id="178aa-121">[Create a content search](https://docs.microsoft.com/office365/securitycompliance/content-search) to find the message to delete.</span></span>
- <span data-ttu-id="178aa-122">[보안 및 준수 센터 PowerShell에 연결](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps)합니다.</span><span class="sxs-lookup"><span data-stu-id="178aa-122">[Connect to Security and Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span>

<span data-ttu-id="178aa-123">다단계 인증을 사용 하는 경우 [multi-factor authentication을 사용 하 여 Microsoft 365 보안 및 준수 센터 PowerShell에 연결](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="178aa-123">If you're using multi-factor authentication, see [Connect to Microsoft 365 security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span>