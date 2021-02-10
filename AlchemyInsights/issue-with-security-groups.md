---
title: 보안 그룹 관련 문제
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/09/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8252"
- "9004397"
ms.openlocfilehash: 1198b79c3301bd2752a7385a6ba6746c8f0c2b5b
ms.sourcegitcommit: 22eaf0a151ab95414476f596db8d318b6540ff31
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/09/2021
ms.locfileid: "50162945"
---
# <a name="issue-with-security-groups"></a><span data-ttu-id="710a7-102">보안 그룹 관련 문제</span><span class="sxs-lookup"><span data-stu-id="710a7-102">Issue with security groups</span></span>

<span data-ttu-id="710a7-103">**네트워크 오류 AADDS104가 발생하는 경우**</span><span class="sxs-lookup"><span data-stu-id="710a7-103">**If you are getting Network Error AADDS104**</span></span>

<span data-ttu-id="710a7-104">잘못된 네트워크 보안 그룹 규칙은 AD DS(Azure Active Directory Domain Services)에 대한 네트워크 오류의 가장 일반적인 원인입니다.</span><span class="sxs-lookup"><span data-stu-id="710a7-104">Invalid network security group rules are the most common cause of network errors for Azure Active Directory Domain Services (AD DS).</span></span> <span data-ttu-id="710a7-105">가상 네트워크의 네트워크 보안 그룹에서 특정 포트 및 프로토콜에 대한 액세스를 허용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="710a7-105">The network security group for the virtual network must allow access to specific ports and protocols.</span></span> <span data-ttu-id="710a7-106">이러한 포트가 차단된 경우 Azure 플랫폼에서는 관리 도메인을 모니터링하거나 업데이트할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="710a7-106">If these ports are blocked, the Azure platform can't monitor or update the managed domain.</span></span> <span data-ttu-id="710a7-107">Azure AD와 Azure AD DS 간의 동기화도 영향을 받습니다.</span><span class="sxs-lookup"><span data-stu-id="710a7-107">The synchronization between the Azure AD and Azure AD DS is also impacted.</span></span> <span data-ttu-id="710a7-108">서비스 중단을 방지하기 위해 기본 포트를 열어 두어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="710a7-108">Ensure you keep the default ports open to avoid interruption in service.</span></span>

<span data-ttu-id="710a7-109">네트워크 보안 그룹 구성 문제에 대한 일반적인 알림을 이해하고 해결하려면 [보안 그룹 추가 및 확인](https://docs.microsoft.com/azure/active-directory-domain-services/alert-nsg#verify-and-edit-existing-security-rules)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="710a7-109">To understand and to resolve common alerts for network security group configuration issues, see [Add and Verify Security Groups](https://docs.microsoft.com/azure/active-directory-domain-services/alert-nsg#verify-and-edit-existing-security-rules).</span></span>
