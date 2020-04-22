---
title: 터미널 서버에 office를 설치 하는 문제에 대 한 해결 방법
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 85f24284-af6f-4624-b6be-901a4a9206eb
ms.openlocfilehash: da69592fd0f55a4bfce45d271aeca5cde1f659b2
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43712680"
---
# <a name="solutions-for-issues-around-installing-office-on-a-terminal-server"></a><span data-ttu-id="00f40-102">터미널 서버에 office를 설치 하는 문제에 대 한 해결 방법</span><span class="sxs-lookup"><span data-stu-id="00f40-102">Solutions for issues around installing office on a Terminal Server</span></span>

<span data-ttu-id="00f40-103">공유 컴퓨터 활성화를 사용 하려면 Microsoft 365 for enterprise 앱이 포함 된 구독이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="00f40-103">To use shared computer activation, you must have a subscription that includes Microsoft 365 Apps for enterprise.</span></span>
  
- <span data-ttu-id="00f40-104">공유 컴퓨터 활성화가 사용 하도록 설정 되어 있는지 확인</span><span class="sxs-lookup"><span data-stu-id="00f40-104">Verify that shared computer activation is enabled</span></span>
- <span data-ttu-id="00f40-105">정품 인증에 성공 했는지 확인</span><span class="sxs-lookup"><span data-stu-id="00f40-105">Verify that activation succeeded</span></span>
- <span data-ttu-id="00f40-106">공유 컴퓨터 활성화에 대 한 오류 메시지를 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="00f40-106">Review error messages for shared computer activation:</span></span>
- <span data-ttu-id="00f40-107">"사용자의 계정에서 찾은 제품은 공유 컴퓨터 시나리오에서 Office를 정품 인증 하는 데 사용할 수 없습니다."</span><span class="sxs-lookup"><span data-stu-id="00f40-107">"The products we found in your account cannot be used to activate Office in shared computer scenarios"</span></span>
  
<span data-ttu-id="00f40-108">이 오류는 Microsoft 365 앱 for enterprise를 포함 하는 구독이 없다는 것을 의미 합니다.</span><span class="sxs-lookup"><span data-stu-id="00f40-108">This error means that you don't have a subscription that includes Microsoft 365 Apps for enterprise.</span></span>

<span data-ttu-id="00f40-109">"허가 되지 않은 제품"</span><span class="sxs-lookup"><span data-stu-id="00f40-109">"Unlicensed Product"</span></span>

- <span data-ttu-id="00f40-110">사용자에 게 Microsoft 365 앱 for enterprise 라이선스가 할당 되어 있는지 확인 하세요.</span><span class="sxs-lookup"><span data-stu-id="00f40-110">Check that the user is assigned a license for Microsoft 365 Apps for enterprise.</span></span>
- <span data-ttu-id="00f40-111">사용자가 자신의 사용자 계정으로 로그인 했는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="00f40-111">Check that the user signs in with their user account.</span></span>
- <span data-ttu-id="00f40-112">공유 컴퓨터와 인터넷 사이에 연결이 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="00f40-112">Check that there is connectivity between the shared computer and the Internet.</span></span>

<span data-ttu-id="00f40-113">다른 문제 해결 팁에 대 한 자세한 내용은 [공유 컴퓨터 정품 인증과 관련 한 문제 해결](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus) 을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="00f40-113">For other troubleshooting tips, please see: [Troubleshoot issues with shared computer activation](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus)</span></span>