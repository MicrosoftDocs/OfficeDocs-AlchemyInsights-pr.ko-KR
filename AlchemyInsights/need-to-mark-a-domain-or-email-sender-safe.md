---
title: 도메인 또는 전자 메일을 보낸 사람을 안전한 사용자로 표시해야 하나요?
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
- "9002921"
- "5673"
ms.openlocfilehash: a1c4c4d2fadaf75eda9b5b322aca35c32dfee8ea
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51792138"
---
# <a name="need-to-mark-a-domain-or-email-sender-safe"></a><span data-ttu-id="b0e80-102">도메인 또는 전자 메일을 보낸 사람을 안전한 사용자로 표시해야 하나요?</span><span class="sxs-lookup"><span data-stu-id="b0e80-102">Need to mark a domain or email sender safe?</span></span>

- <span data-ttu-id="b0e80-103">**수신 허용 - 보낸 사람 목록의 사용은** 조직을 스팸, 피싱 및 스푸핑 공격에 노출시키기 때문에 권장하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b0e80-103">Use of **safe sender lists is not recommended** since it opens up your organization to spam, phish, and spoofing attacks.</span></span>
- <span data-ttu-id="b0e80-104">그러나 비즈니스 요구 사항이 있는 경우, **[메일 흐름 규칙](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** 을 사용할 것을 **권장** 합니다.</span><span class="sxs-lookup"><span data-stu-id="b0e80-104">However, if there is a business requirement, we **recommend** using **[Mail Flow Rules](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** for this.</span></span> <span data-ttu-id="b0e80-105">당사의 지침은 보낸 사람 인증(보내는 도메인이 스푸핑 공격을 당하고 있지 않은지 확인)을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="b0e80-105">Our guidance ensures sender authentication (verifies sending domain is not being spoofed).</span></span> <span data-ttu-id="b0e80-106">**참고**: 스팸 필터링에 대한 예외가 조직을 보안 공격에 노출시킬 수 있으므로, 안전한 보낸 사람 목록을 사용하여 가양성을 관리하는 것은 권장하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b0e80-106">**Note**: We don't recommend managing false positives by using safe sender lists, because exceptions to spam filtering can open your organization to security attacks.</span></span> <span data-ttu-id="b0e80-107">사용자가 스팸 또는 정크 메일로 잘못 표시된 메시지를 받는 경우, **[메시지와 파일을 Microsoft에 보고하세요](https://protection.office.com/reportsubmission)**.</span><span class="sxs-lookup"><span data-stu-id="b0e80-107">If your user(s) receive messages incorrectly marked as spam or junk email, please **[Report messages and files to Microsoft](https://protection.office.com/reportsubmission)**.</span></span>
- <span data-ttu-id="b0e80-108">스팸 방지 정책에서 Outlook에서의 수신 허용 - 보낸 사람, 허용된 보낸 사람 목록 혹은 허용된 도메인 목록은 보낸 사람이 모든 스팸, 스푸핑, 피싱 보호, 보낸 사람 인증(SPF, DKIM, DMARC)을 우회하기 때문에 **사용하지 않아야 합니다**.</span><span class="sxs-lookup"><span data-stu-id="b0e80-108">Safe Senders in Outlook, Allowed sender list, or allowed domain list in anti-spam policies **should be avoided** because senders bypass all spam, spoof, and phish protection, and sender authentication (SPF, DKIM, DMARC).</span></span> <span data-ttu-id="b0e80-109">이 방법은 임시 테스트에만 사용하는 것이 가장 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="b0e80-109">This method is best used for temporary testing only.</span></span>
