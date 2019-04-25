---
title: Office 365 ATP (Advanced Threat Protection) 관련 문제 해결
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: dbdfe2ddcc4afd4477f66ffd060ddb7093af8fd6
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420310"
---
# <a name="troubleshoot-issues-with-office-365-atp"></a><span data-ttu-id="067fc-102">Office 365 ATP 문제 해결</span><span class="sxs-lookup"><span data-stu-id="067fc-102">Troubleshoot issues with Office 365 ATP</span></span>

- <span data-ttu-id="067fc-103">**전자 메일 메시지 배달이 지연 되는지**여부</span><span class="sxs-lookup"><span data-stu-id="067fc-103">**Notice delays with email message delivery**?</span></span> <span data-ttu-id="067fc-104">ATP 안전한 첨부 파일 정책에 대해 동적 배달 옵션을 사용해 보세요.</span><span class="sxs-lookup"><span data-stu-id="067fc-104">Try using the Dynamic Delivery option for your ATP Safe Attachments policies.</span></span> <span data-ttu-id="067fc-105">이렇게 하면 악성 파일에서 받는 사람을 보호 하는 동안 전자 메일 메시지 배달이 지연 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="067fc-105">This will avoid email message delivery delays while protecting recipients from malicious files.</span></span>
- <span data-ttu-id="067fc-106">가양성 **또는 거짓 네거티브를 보고**하시 겠어요?</span><span class="sxs-lookup"><span data-stu-id="067fc-106">**Do you want to report false positives or false negatives**?</span></span> <span data-ttu-id="067fc-107">이 링크를 사용 하 여 분석을 위해 파일을 제출 합니다.[https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span><span class="sxs-lookup"><span data-stu-id="067fc-107">Use this link to submit your file for analysis: [https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span></span>
- <span data-ttu-id="067fc-108">**조직의 사용자 간에 전송 되는 전자 메일에 대해 ATP 안전한 링크 보호를 사용 하도록 설정할 수 있는지 확인 해야 합니다**.</span><span class="sxs-lookup"><span data-stu-id="067fc-108">**Did you know that you can enable ATP Safe Links protection for email sent between people in your organization**?</span></span> <span data-ttu-id="067fc-109">다음 단계를 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="067fc-109">Follow these steps:</span></span>
    1. <span data-ttu-id="067fc-110">https://protection.office.com으로 이동 하 여 로그인 합니다.</span><span class="sxs-lookup"><span data-stu-id="067fc-110">Go to https://protection.office.com, and sign in.</span></span>
    2. <span data-ttu-id="067fc-111">**위협 관리** > **정책** > **안전한 링크로**이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="067fc-111">Go to **Threat management** > **Policy** > **Safe Links**.</span></span>
    3. <span data-ttu-id="067fc-112">**특정 받는 사람에 게 적용 되는 정책**아래에서 정책을 편집 (또는 추가) 합니다.</span><span class="sxs-lookup"><span data-stu-id="067fc-112">Under **Policies that apply to specific recipients**, edit (or add) a policy.</span></span>
    4. <span data-ttu-id="067fc-113">**조직 내에서 보낸 메시지에 안전한 링크 적용을**선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="067fc-113">Select **Apply safe links to messages sent within the organization**.</span></span>
    5. <span data-ttu-id="067fc-114">정책을 저장 하 고 변경 내용이 데이터 센터를 통해 작동 하는 데 30 분 정도 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="067fc-114">Save your policy, and allow about 30 minutes for your changes to work their way through your datacenter.</span></span>
- <span data-ttu-id="067fc-115">ATP에 대 한 자세한 도움말을 보려면 [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="067fc-115">To get more help with ATP, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span></span>