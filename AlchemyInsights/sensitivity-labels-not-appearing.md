---
title: 민감도 레이블 표시 안 함
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 67719380aea0481f96c03fa591542e8e5a6e6993
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048658"
---
# <a name="sensitivity-labels-not-appearing"></a><span data-ttu-id="a664f-102">민감도 레이블 표시 안 함</span><span class="sxs-lookup"><span data-stu-id="a664f-102">Sensitivity labels not appearing</span></span>

<span data-ttu-id="a664f-103">민감도 레이블을 사용 하면 중요 한 콘텐츠를 분류 하 고 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a664f-103">Sensitivity labels allow you to classify and help protect your sensitive content.</span></span> <span data-ttu-id="a664f-104">분류 > 민감도 레이블의 365 Microsoft 365 보안 센터 또는 Office 365 보안 & 준수 센터에서 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a664f-104">They can be created in the Microsoft 365 compliance center, Microsoft 365 security center, or Office 365 Security & Compliance Center under Classification > Sensitivity labels.</span></span> <span data-ttu-id="a664f-105">이 기능에 대해 자세히 알아보려면 [민감도 레이블 개요](https://docs.microsoft.com/office365/securitycompliance/sensitivity-labels)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="a664f-105">To learn more about this feature, see [Overview of sensitivity labels](https://docs.microsoft.com/office365/securitycompliance/sensitivity-labels).</span></span>

<span data-ttu-id="a664f-106">민감도 레이블이 구성 되었지만 Office 앱에 나타나지 않는 경우 다음을 확인 하세요.</span><span class="sxs-lookup"><span data-stu-id="a664f-106">If you configured your sensitivity labels but they aren't appearing in the Office apps, check the following:</span></span>

- <span data-ttu-id="a664f-107">민감도 레이블이 원하는 사용자 및 그룹에 [게시](https://docs.microsoft.com/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a664f-107">Confirm that the sensitivity label has been [published](https://docs.microsoft.com/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) to the users and groups that you want.</span></span>

- <span data-ttu-id="a664f-108">사용자가 민감도 레이블을 지 원하는 앱을 사용 하 고 있는지 확인 하 고, [문서의 민감도 레이블을](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?ad=US&ui=en-US&rs=en-US#bkmk_whereavailable)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="a664f-108">Confirm that the user is using an app that supports sensitivity labels - see [sensitivity labels in your document](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?ad=US&ui=en-US&rs=en-US#bkmk_whereavailable).</span></span>

- <span data-ttu-id="a664f-109">[Azure Information Protection 레이블을 마이그레이션하](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels)는 경우 [여기](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels)에 나열 된 고려 사항을 고려해 야 합니다.</span><span class="sxs-lookup"><span data-stu-id="a664f-109">If you're [migrating Azure Information Protection labels](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), be aware of the considerations listed [here](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).</span></span>

- <span data-ttu-id="a664f-110">DLP (데이터 손실 방지) 지원: 현재는 보존 레이블만 DLP 정책의 조건으로 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a664f-110">Data loss prevention (DLP) support: Currently, only retention labels can be used as a condition in DLP policies.</span></span>  <span data-ttu-id="a664f-111">DLP 정책의 민감도 레이블에 대 한 지원은 아직 사용할 수 없지만 작업 하 고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a664f-111">Support for sensitivity labels in a DLP policy is not available yet but we're working on it.</span></span>

- <span data-ttu-id="a664f-112">민감도 레이블에서 암호화를 사용 하도록 설정 하는 경우 다음 중 하나를 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a664f-112">When encryption is enabled on a sensitivity label, you can choose either to:</span></span>
    - <span data-ttu-id="a664f-113">지금 권한 할당</span><span class="sxs-lookup"><span data-stu-id="a664f-113">Assign permissions now</span></span>
    - <span data-ttu-id="a664f-114">사용자가 권한을 할당하도록 허용</span><span class="sxs-lookup"><span data-stu-id="a664f-114">Let users assign permissions</span></span>


<span data-ttu-id="a664f-115">가능한 문제에 대 한 자세한 내용은 [민감도 레이블의 알려진 문제](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="a664f-115">For more information on possible issues, see [Known issues with sensitivity labels](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).</span></span>