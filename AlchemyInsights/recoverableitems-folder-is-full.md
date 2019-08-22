---
title: 1336 RecoverableItems 폴더가 꽉 찼습니다.
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 8a5859ba29d847606e8b44d169c3cd6a26364744
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36509749"
---
# <a name="the-recoverable-items-folder-is-full"></a>복구 가능한 항목 폴더가 꽉 참

Office 365에서 Exchange Online 사서함의 경우 복구 가능한 항목 폴더에 대 한 기본 저장 제한은 30gb입니다. 사서함이 소송 보존, eDiscovery 365 보류에 있는 경우 복구 가능한 항목 폴더의 저장소 제한은 자동으로 100로 증가 합니다.

복구 가능한 항목 폴더가 저장 제한에 도달 하면 사서함 기능은 다음과 같은 방식으로 영향을 받습니다.

- 사용자가 사서함에서 항목을 삭제할 수 없습니다.

- 관리 되는 폴더 도우미는 보존 태그 또는 관리 되는 폴더 설정을 기반으로 항목을 삭제할 수 없습니다.

- 단일 항목 복구를 사용 하도록 설정 하거나 보류 중인 사서함의 경우에는 쓰기 페이지 보호 프로세스에서 사용자가 편집한 항목의 버전을 유지 관리할 수 없습니다.

- 사서함 감사 로깅이 사용 하도록 설정 된 사서함의 경우 복구 가능한 항목 폴더의 감사 하위 폴더에는 사서함 감사 로그 항목을 저장할 수 없습니다.

보류 중인 사서함의 경우 관리자는 Exchange Online PowerShell의 `Search-Mailbox -SearchDumpsterOnly -DeleteContent` 명령을 사용 하 여 복구 가능한 항목 폴더의 항목을 삭제할 수 있습니다. 자세한 내용은 다음 항목을 참조하세요.

- [메시지 검색 및 삭제](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [검색 사서함](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

보류 중인 사서함의 경우 관리자는 복구 가능한 항목 폴더에서 항목을 삭제 하기 전에 보류를 제거 해야 합니다. 자세한 내용은 [보류 중인 클라우드 기반 사서함의 복구 가능한 항목 폴더에서 항목 삭제](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold)를 참조 하세요.

복구 가능한 항목 폴더가 가득 차지 않도록 하기 위해 관리자는 보류 중인 사서함에 대 한 복구 가능한 항목 폴더의 저장 제한을 증가 시켜 복구 가능한 항목 폴더의 항목을 사용자의 보관으로 이동 하는 사서함 보존 정책을 설정할 수 있습니다. 사서함별. [보류 중인 사서함에 대 한 복구 가능한 항목 할당량 증가를](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold)참조 하세요.
