---
title: Windows 10에서 Bluetooth 문제 해결
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001475"
- "3506"
ms.openlocfilehash: f20bf4a642e019c7901e988a027e0220f0f1b07b
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51812938"
---
# <a name="fix-bluetooth-problems-in-windows-10"></a><span data-ttu-id="8dbf6-102">Windows 10에서 Bluetooth 문제 해결</span><span class="sxs-lookup"><span data-stu-id="8dbf6-102">Fix Bluetooth problems in Windows 10</span></span>

<span data-ttu-id="8dbf6-103">Bluetooth 아이콘이 누락되거나 Bluetooth 수 없는 경우 문제 해결사에서 Bluetooth 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-103">If the Bluetooth icon is missing or Bluetooth can't be turned on or off, you may want to run the Bluetooth troubleshooter.</span></span> <span data-ttu-id="8dbf6-104">[문제 해결 설정 을](ms-settings:troubleshoot) **열고** Bluetooth **찾기** 및 해결에서 문제 해결을 클릭하고 문제 해결사 **실행을 클릭합니다.**</span><span class="sxs-lookup"><span data-stu-id="8dbf6-104">[Open the Troubleshoot settings](ms-settings:troubleshoot), click **Bluetooth** under **Find and fix other problems**, click **Run the troubleshooter**.</span></span>

<span data-ttu-id="8dbf6-105">Bluetooth 아이콘이 없지만 장치 Bluetooth 아이콘이 나타나면 다음을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-105">If you don't see the Bluetooth icon, but Bluetooth does appear in Device Manager:</span></span>

1. <span data-ttu-id="8dbf6-106">장치 관리자에서 를 **Bluetooth.**</span><span class="sxs-lookup"><span data-stu-id="8dbf6-106">In Device Manager, click **Bluetooth**.</span></span> <span data-ttu-id="8dbf6-107">를 누른 후(또는 마우스 오른쪽 단추로 클릭) Bluetooth 장치 제거를 **클릭합니다.**</span><span class="sxs-lookup"><span data-stu-id="8dbf6-107">Press and hold (or right-click) the Bluetooth adapter name and click **Uninstall device**.</span></span>

2. <span data-ttu-id="8dbf6-108">Windows 장치를 종료하고 몇 초간 기다렸다가 다시 니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-108">Shut down your Windows device, wait a few seconds, and then turn it back on.</span></span> <span data-ttu-id="8dbf6-109">Windows에서 드라이버를 다시 설치하려고 합니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-109">Windows will try to reinstall the driver.</span></span>

<span data-ttu-id="8dbf6-110">최근에 Windows 10 업데이트를 설치하거나 Windows 10으로 업그레이드한 경우 드라이버 업데이트를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-110">If you recently installed Windows 10 updates or upgraded to Windows 10, you may want to check for driver updates:</span></span>

1. <span data-ttu-id="8dbf6-111">장치 관리자에서 Bluetooth **를** 클릭한 다음 Bluetooth 어댑터 이름(단어 "radio"를 포함할 수 있습니다)을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-111">In Device Manager, click **Bluetooth**, and then click the Bluetooth adapter name (which may include the word "radio").</span></span>

2. <span data-ttu-id="8dbf6-112">Bluetooth 누른 후 마우스 오른쪽 단추로 클릭한 다음 업데이트된 드라이버 소프트웨어에 대해 자동으로 드라이버 검색 업데이트를  >  **클릭합니다.**</span><span class="sxs-lookup"><span data-stu-id="8dbf6-112">Press and hold (or right-click) the Bluetooth adapter, and then click **Update driver** > **Search automatically for updated driver software**.</span></span> <span data-ttu-id="8dbf6-113">단계를 수행한 다음 닫기 **를 클릭합니다.**</span><span class="sxs-lookup"><span data-stu-id="8dbf6-113">Follow the steps, then click **Close**.</span></span>

      - <span data-ttu-id="8dbf6-114">Windows에서 새 Bluetooth 드라이버를 찾을 수 없는 경우 PC 제조업체의 웹 사이트를 방문하여 최신 Bluetooth 드라이버를 다운로드합니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-114">If Windows can't find a new Bluetooth driver, visit the PC manufacturer's website and download the latest Bluetooth driver from there.</span></span>

    - <span data-ttu-id="8dbf6-115">드라이버를 다운로드한 후 드라이버 소프트웨어에 대한 내 컴퓨터 찾아보기를 클릭하고 드라이버 파일이 저장된 위치를 찾아보기> 확인 다음으로 이동한 후 단계에 따라  >    >     >  설치합니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-115">After you download it, click **Update driver** > **Browse my computer for driver software** > **Browse** for the location where the driver files are stored > **OK** > **Next**, and follow the steps to install.</span></span>

3. <span data-ttu-id="8dbf6-116">업데이트된 드라이버를 설치한 후 컴퓨터를 다시 시작한 다음 연결 문제가 해결되지 않는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="8dbf6-116">After installing the updated driver, restart the machine, and then check whether that fixes the connection issue.</span></span>

<span data-ttu-id="8dbf6-117">문제 해결 방법에 대한 자세한 내용은 Bluetooth Windows 10에서 문제 Bluetooth [수정을 참조하세요.](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems)</span><span class="sxs-lookup"><span data-stu-id="8dbf6-117">For more details of how to troubleshoot Bluetooth problems, please see the full article, [Fix Bluetooth problems in Windows 10](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems).</span></span>
