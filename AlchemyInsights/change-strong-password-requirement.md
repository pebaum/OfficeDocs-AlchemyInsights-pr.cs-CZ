---
title: Požadavek na silné heslo změnit
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
ms.openlocfilehash: f8790a26ec7c5de57f5dbfc9e1c162767c599f03
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36518752"
---
# <a name="change-strong-password-requirement"></a>Požadavek na silné heslo změnit

Společnost Microsoft vyžaduje silná hesla ve výchozím nastavení. 

Použití prostředí PowerShell, můžete zakázat silných hesel pro konkrétní uživatele pomocí tohoto příkazu:<br>
*Sada MsolUser – UserPrincipalName <UserPrincipalName> -StrongPasswordRequired $false*

- [Další informace o zásady hesla](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Jak se připojit k Office 365 pomocí prostředí PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Další informace týkající se příkazů prostředí PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)