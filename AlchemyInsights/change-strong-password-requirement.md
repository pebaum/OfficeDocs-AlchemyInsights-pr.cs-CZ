---
title: Změnit požadavek na silné heslo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: a054735a0c139c90d76098297bb9984d37464d3b
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706554"
---
# <a name="change-strong-password-requirement"></a>Změna požadavku na silné heslo

Společnost Microsoft ve výchozím nastavení vyžaduje silná hesla. 

Pomocí prostředí PowerShell můžete pomocí tohoto příkazu zakázat silná hesla pro konkrétní uživatele:<br>
*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordVyžaduje $false*

- [Další informace o zásadách hesel](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Jak se připojit k Microsoftu 365 pomocí PowerShellu](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Další informace o příkazech PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
