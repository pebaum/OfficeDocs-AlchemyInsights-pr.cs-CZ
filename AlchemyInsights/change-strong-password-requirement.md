---
title: Požadavek na silné heslo změnit
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 53affd2a347c004e7b21b353c2b3df98bc30a585
ms.sourcegitcommit: a7e5ca472000dfec471950bafd12eee8d7144f74
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/16/2019
ms.locfileid: "35701577"
---
# <a name="change-strong-password-requirement"></a>Požadavek na silné heslo změnit

Silná hesla jsou ve výchozím nastavení požadována. 

Pomocí prostředí PowerShell můžete zakázat silných hesel pro konkrétní uživatele pomocí tohoto příkazu:<br>
*Sada MsolUser – UserPrincipalName <UserPrincipalName> -StrongPasswordRequired $false*

- [Další informace o zásady hesla](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Jak se připojit ke O365 pomocí prostředí PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Další informace týkající se příkazů prostředí PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)