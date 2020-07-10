---
title: 인쇄 스풀러 문제 해결됨
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/8/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5151"
- "9002659"
ms.openlocfilehash: 53b1c9a8efa3cc978af8b602c8ed90430042186a
ms.sourcegitcommit: 4265a9e79db6c2a396aa80ec0ebd467bbaadf366
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/08/2020
ms.locfileid: "45083980"
---
# <a name="print-spooler-issue-is-resolved"></a><span data-ttu-id="10274-102">인쇄 스풀러 문제 해결됨</span><span class="sxs-lookup"><span data-stu-id="10274-102">Print spooler issue is resolved</span></span>

<span data-ttu-id="10274-103">장치를 Windows 10 **OS 빌드 19041.329**로 업데이트한 경우 특정 프린터에서 인쇄가 되지 않는 문제가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="10274-103">If your device was updated with Windows 10  **OS Build 19041.329**, you might have observed an issue where certain printers fail to print.</span></span> <span data-ttu-id="10274-104">인쇄를 하려고 할 때 인쇄 스풀러가 오류가 일으키거나 예기치 않게 종료될 수 있으며, 영향을 받는 프린터에서 출력이 전송되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="10274-104">The print spooler might throw an error or close unexpectedly when attempting to print, and no output comes from the affected printer.</span></span> <span data-ttu-id="10274-105">이 문제는 OS 빌드 **19041.331**, [KB4567523](https://support.microsoft.com/help/4567523/windows-10-update-kb4567523)에서 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="10274-105">This issue is resolved in OS Build  **19041.331**, [KB4567523](https://support.microsoft.com/help/4567523/windows-10-update-kb4567523).</span></span>  

<span data-ttu-id="10274-106">**진행 중인 조사**</span><span class="sxs-lookup"><span data-stu-id="10274-106">**Ongoing investigation**</span></span>

<span data-ttu-id="10274-107">일부 장치의 LSASS(Local Security Authority Subsystem Service) 파일(**Isass**)에서 ‘중요 시스템 프로세스인 C:\WINDOWS\system32\Isass.exe에 오류가 발생했으며 상태 코드는 c0000008입니다.</span><span class="sxs-lookup"><span data-stu-id="10274-107">The Local Security Authority Subsystem Service (LSASS) file (**Isass.exe**) might fail on some devices with the error message, "A critical system process, C:\WINDOWS\system32\Isass.exe, failed with status code c0000008.</span></span> <span data-ttu-id="10274-108">지금 컴퓨터를 재시작해야 합니다’라는 오류 메시지가 포함된 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="10274-108">The machine must now be restarted".</span></span>  <span data-ttu-id="10274-109">**Microsoft는 문제 해결을 위해 노력 중이며 예정된 릴리스에서 업데이트를 제공할 예정입니다.**</span><span class="sxs-lookup"><span data-stu-id="10274-109">**Microsoft is working on a resolution and will provide an update in an upcoming release.**</span></span>

<span data-ttu-id="10274-110">자세한 내용은 [Windows 10 버전 2004에서 알려진 문제](https://docs.microsoft.com/windows/release-information/status-windows-10-2004#442msgdesc)를 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="10274-110">For more information, please check out  [Windows 10 Version 2004 known issues](https://docs.microsoft.com/windows/release-information/status-windows-10-2004#442msgdesc).</span></span>