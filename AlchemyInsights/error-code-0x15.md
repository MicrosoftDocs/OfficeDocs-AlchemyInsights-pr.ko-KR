---
title: 오류 코드 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: RDS (원격 데스크톱 서비스) 배포에서 Office 2013을 정품 인증 하는 동안 오류가 발생 하는 경우 레지스트리를 편집 하 여 ADAL을 사용 하도록 설정 하는 것이 좋습니다.
ms.openlocfilehash: 468d13e59602cf173ed2e17af44c66babfc28703
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506852"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="36216-103">원격 데스크톱 서비스에서 Office 2013 정품 인증을 진행 하는 동안 오류 발생</span><span class="sxs-lookup"><span data-stu-id="36216-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="36216-104">RDS (원격 데스크톱 서비스) 배포에서 Office 2013을 정품 인증 하는 동안 오류가 발생 하는 경우 레지스트리를 편집 하 여 ADAL을 사용 하도록 설정 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="36216-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="36216-105">**레지스트리 키**</span><span class="sxs-lookup"><span data-stu-id="36216-105">**Registry key**</span></span>|<span data-ttu-id="36216-106">**유형**</span><span class="sxs-lookup"><span data-stu-id="36216-106">**Type**</span></span>|<span data-ttu-id="36216-107">**값**</span><span class="sxs-lookup"><span data-stu-id="36216-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="36216-108">HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="36216-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="36216-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="36216-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="36216-110">1 </span><span class="sxs-lookup"><span data-stu-id="36216-110">1</span></span>  <br/> |

<span data-ttu-id="36216-111">자세한 내용은 [Windows 장치에서 Office 2013에 대 한 최신 인증 사용](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="36216-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="36216-112">Microsoft 365 Apps for enterprise 및 Office 2016에서는 ADAL이 기본적으로 사용 하도록 설정 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="36216-112">ADAL is enabled by default in Microsoft 365 Apps for enterprise and Office 2016.</span></span> <span data-ttu-id="36216-113">이전에는 RDS (원격 데스크톱 서비스)를 터미널 서비스 라고 합니다.</span><span class="sxs-lookup"><span data-stu-id="36216-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  