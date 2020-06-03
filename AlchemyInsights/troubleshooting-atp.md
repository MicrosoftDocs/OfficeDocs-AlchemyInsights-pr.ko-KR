---
title: Office 365 Advanced Threat Protection 문제 해결
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1039
ms.assetid: ''
ms.openlocfilehash: 7391b3c126d55213881f6b71cb6b5fc72bc68d0f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/02/2020
ms.locfileid: "44512596"
---
# <a name="troubleshooting-office-365-advanced-threat-protection"></a><span data-ttu-id="ea67a-102">Office 365 Advanced Threat Protection 문제 해결</span><span class="sxs-lookup"><span data-stu-id="ea67a-102">Troubleshooting Office 365 Advanced Threat Protection</span></span>

- <span data-ttu-id="ea67a-103">메시지 배달이 지연 되는 것을 알 수 있나요?</span><span class="sxs-lookup"><span data-stu-id="ea67a-103">Do you notice delays in message delivery?</span></span> <span data-ttu-id="ea67a-104">ATP 안전한 첨부 파일 정책에서 [동적 배달](https://docs.microsoft.com/microsoft-365/security/office-365-security/dynamic-delivery-and-previewing) 옵션을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-104">Use the [Dynamic Delivery](https://docs.microsoft.com/microsoft-365/security/office-365-security/dynamic-delivery-and-previewing) option in your ATP Safe Attachments policy.</span></span> <span data-ttu-id="ea67a-105">이를 통해 악성 파일에서 받는 사람을 보호 하는 동안 메시지 지연을 방지할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-105">This will help avoid message delays while protecting recipients from malicious files.</span></span>

- <span data-ttu-id="ea67a-106">가양성 또는 거짓 네거티브를 Microsoft에 보고 하 고 싶으십니까?</span><span class="sxs-lookup"><span data-stu-id="ea67a-106">Do you want to report false positives or false negatives to Microsoft?</span></span> <span data-ttu-id="ea67a-107">이 [링크](https://www.microsoft.com/wdsi/filesubmission/) 를 사용 하 여 분석을 위해 파일을 제출 합니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-107">Use this [link](https://www.microsoft.com/wdsi/filesubmission/) to submit files for analysis.</span></span>

- <span data-ttu-id="ea67a-108">조직 내의 받는 사람 간에 전송 되는 내부 전자 메일에 대해 안전한 링크 보호를 사용 하도록 설정할 수 있는지 확인 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-108">Did you know that you can enable Safe Links protection for internal email sent between recipients within your organization?</span></span> <span data-ttu-id="ea67a-109">다음 단계를 따릅니다:</span><span class="sxs-lookup"><span data-stu-id="ea67a-109">Follow these steps:</span></span>

  1. <span data-ttu-id="ea67a-110">로 이동 하 [https://protection.office.com](https://protection.office.com) 고 전역 관리자 또는 보안 관리자 계정으로 로그인 합니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-110">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

  2. <span data-ttu-id="ea67a-111">왼쪽 탐색 창의 **위협 관리**에서 **정책** \> **안전한 링크**를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-111">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Links**.</span></span>

  3. <span data-ttu-id="ea67a-112">**전체 조직에 적용 되는 정책** 섹션에서 정책을 선택 하 고 **편집**을 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-112">In the **Policies that apply to the entire organization** section, select the policy and click **Edit**.</span></span>

  4. <span data-ttu-id="ea67a-113">**설정**아래에서 **조직 내에서 보낸 메시지에 안전한 링크 적용**을 사용 하도록 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="ea67a-113">Under **Settings**, enable **Apply safe links to messages sent within the organization**.</span></span>
