---
title: 사용자가 악성 이메일을 받았습니까
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
- "9002907"
- "5594"
- "3100017"
- "2578"
ms.openlocfilehash: 425f9ba488fd69b8c5ea29636bccccd995bf48fd
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51815252"
---
# <a name="did-your-users-receive-malicious-email"></a><span data-ttu-id="64d7f-102">사용자가 악성 이메일을 받았습니까?</span><span class="sxs-lookup"><span data-stu-id="64d7f-102">Did your users receive malicious email?</span></span>

- <span data-ttu-id="64d7f-103">이제 [보안 및 규정 센터의 관리자 제출](https://sip.protection.office.com/reportsubmission)을 사용하여 Microsoft에 악의적인 전자 메일을 보고할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-103">You can now report the malicious email to Microsoft using the [Admin Submissions in Security & Compliance Center](https://sip.protection.office.com/reportsubmission).</span></span>

<span data-ttu-id="64d7f-104">[관리자 제출](https://sip.protection.office.com/reportsubmission)에 제출된 메시지가 검색되고 **세부 정보** 에 표시된 다음 결과가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-104">Messages that are submitted in [admin submissions](https://sip.protection.office.com/reportsubmission) are scanned, and the following results shown in the **details** flyout:</span></span>

- <span data-ttu-id="64d7f-105">전송 시 보낸 사람의 전자 메일 인증에 오류가 있는 경우입니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-105">If there was a failure in the sender's email authentication at the time of delivery.</span></span>
- <span data-ttu-id="64d7f-106">메시지의 평가 결과에 영향을 주거나 재정의할 수 있는 정책 조회에 대한 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-106">Information about any policy hits that could have affected or overridden the verdict of a message.</span></span>
- <span data-ttu-id="64d7f-107">메시지에 포함된 URL 또는 파일이 악의적인지 여부를 확인하는 현재 데토네이션 결과입니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-107">Current detonation results to see if the URLs or files contained in the message were malicious or not.</span></span>
- <span data-ttu-id="64d7f-108">채점자 피드백</span><span class="sxs-lookup"><span data-stu-id="64d7f-108">Feedback from graders</span></span>

<span data-ttu-id="64d7f-109">재정의가 발견되면 몇 분 후에 다시 검색이 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-109">If an override was found, the rescan should complete in several minutes.</span></span> <span data-ttu-id="64d7f-110">전자 메일 인증에 문제가 없는 경우 또는 전송이 재정의의 영향을 받지 않았다면 성적에 대한 피드백은 최대 하루가 소요됩니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-110">If there wasn't a problem in email authentication or if the delivery wasn't affected by an override, then the feedback from graders could take up to a day.</span></span>

<span data-ttu-id="64d7f-111">메시지, URL 또는 파일(차단되거나 차단되지 않은 파일)에 최종 평가 결과에 동의하지 않는 경우 다시 검색하기 위해 하루 후에 메시지를 다시 제출합니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-111">If you disagree with the final verdict on a message, URL or file (blocked vs. not blocked), submit the message again after a day for rescan.</span></span> <span data-ttu-id="64d7f-112">메시지를 다시 제출한 후에 평가 결과가 변경될 가능성이 높습니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-112">The chances are high that the verdict would change after submitting the message again.</span></span>

<span data-ttu-id="64d7f-113">그 동안 [이 문서](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messages-in-your-organization)의 지침에 따라 사용자 받은 편지함에서 악성 전자 메일을 제거할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-113">Meanwhile, you can remove malicious email from user inboxes by following the instructions in [this article](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messages-in-your-organization).</span></span>

- <span data-ttu-id="64d7f-114">Office 365용 Microsoft Defender 고객은 다음을 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-114">Customers with Microsoft Defender for Office 365 can:</span></span>
    - <span data-ttu-id="64d7f-115">[위협 탐색기를 사용하여 의심스러운 전자 메일 검색 및 삭제](https://docs.microsoft.com/microsoft-365/security/office-365-security/investigate-malicious-email-that-was-delivered)</span><span class="sxs-lookup"><span data-stu-id="64d7f-115">use [Threat Explorer to Find and Delete Suspicious email](https://docs.microsoft.com/microsoft-365/security/office-365-security/investigate-malicious-email-that-was-delivered)</span></span>
    - <span data-ttu-id="64d7f-116">[안전한 링크를 사용하여 악성 URL에 액세스 차단](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)</span><span class="sxs-lookup"><span data-stu-id="64d7f-116">[use Safe Links to block access](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) to a malicious URL</span></span>
    - <span data-ttu-id="64d7f-117">악성 URL을 클릭하고 액세스한 사용자 추적: [피싱 URL 및 평가 결과 데이터 보기](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer) & [Get-UrlTrace](https://docs.microsoft.com/powershell/module/exchange/get-urltrace)</span><span class="sxs-lookup"><span data-stu-id="64d7f-117">track users who clicked and accessed malicious URLs: [View phishing URL and click verdict data](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer) & [Get-UrlTrace](https://docs.microsoft.com/powershell/module/exchange/get-urltrace)</span></span>
    - <span data-ttu-id="64d7f-118">수동으로 [자동 조사 시작](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)</span><span class="sxs-lookup"><span data-stu-id="64d7f-118">manually [start an Automated Investigation](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)</span></span>

<span data-ttu-id="64d7f-119">[악성 URL 및 파일로부터 보호](https://docs.microsoft.com/microsoft-365/security/office-365-security/protect-against-threats) 지침에 따라 악성 파일 및 URL로부터 보호 받을 수 이습니다.</span><span class="sxs-lookup"><span data-stu-id="64d7f-119">You can also protect against malicious files and URLs by following the instructions in [Protection from malicious URLs and files](https://docs.microsoft.com/microsoft-365/security/office-365-security/protect-against-threats).</span></span>