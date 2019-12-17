---
title: 워크플로 전자 메일이 전송 되지 않음
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 76b64323c9d34d49e9c6bd77c2cc7eff6d7c5402
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049379"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="a4d16-102">SharePoint 목록 또는 라이브러리에 대해 워크플로 전자 메일이 전송 되지 않음</span><span class="sxs-lookup"><span data-stu-id="a4d16-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="a4d16-103">워크플로의 전자 메일이 모든 사용자에 게 보내지지 않거나 특정 사용자 에게만 전송 되지 않거나 **전자 메일 메시지를 보낼 수 없습니다. 라는 오류가 표시 됩니다. 전자 메일의 받는 사람이 올바른지 확인**합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d16-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="a4d16-104">해당 사이트 모음의 **모든** 사용자 권한 그룹 (사용자 정보 목록)에 사용자가 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d16-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="a4d16-105">직접 URL 예제: https://<tenant>/sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="a4d16-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="a4d16-106">사용자가 없는 경우 사용자가 페이지에 로그인 되어 있는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d16-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="a4d16-107">외부 사용자 인 경우 초대가 수락 되었는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d16-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="a4d16-108">사용자가 사용 권한 그룹에 있는 경우 전자 메일 주소가 올바른지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d16-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="a4d16-109">사용자의 전자 메일 주소가 여기에서 설정 되어 있지 않으면 해당 사용자에 대 한 샘플 알림을 만들어 SharePoint의 사용자 프로필에서이 사이트 모음으로 해당 사용자 계정을 강제로 동기화 합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d16-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="a4d16-110">워크플로의 전자 메일은 사이트 모음 관리자에 게 전송 되 고 다른 사용자에 게는 전달 되지 않으며 \*\* <span>https:</span>/client.xvc.sp.utilities.utility.sendemail에 사용할 수\*\*없는 것으로 표시 됩니다 _vti_bin.</span><span class="sxs-lookup"><span data-stu-id="a4d16-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="a4d16-111">[SharePoint 그룹에 전자 메일을 보낼 때 액세스 거부](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="a4d16-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="a4d16-112">또한 **제한 된 액세스 사용자 권한 잠금 모드** 사이트 모음 기능이 활성화 되어 있지 않은지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="a4d16-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="a4d16-113">관련 항목</span><span class="sxs-lookup"><span data-stu-id="a4d16-113">Related topics</span></span>
<span data-ttu-id="a4d16-114">SharePoint Online에서 Microsoft Flow를 시도 하 고 싶으십니까?</span><span class="sxs-lookup"><span data-stu-id="a4d16-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="a4d16-115">흐름 만들기</span><span class="sxs-lookup"><span data-stu-id="a4d16-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="a4d16-116">SharePoint 및 흐름</span><span class="sxs-lookup"><span data-stu-id="a4d16-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


