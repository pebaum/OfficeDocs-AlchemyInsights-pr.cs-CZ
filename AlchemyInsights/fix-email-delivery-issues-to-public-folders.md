---
title: Odstraňuje problémy doručení e-mailu do poštovní veřejných složek
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: f7b5e5a230d26870d5e95e8762b5874f73723c6d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36525091"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a><span data-ttu-id="0b220-102">Odstraňuje problémy doručení e-mailu do poštovní veřejných složek</span><span class="sxs-lookup"><span data-stu-id="0b220-102">Fix email delivery issues to mail-enabled public folders</span></span>

<span data-ttu-id="0b220-103">Pokud externích odesílatelů nelze odeslat zprávy do veřejné složky poštovní a odesílatelé zobrazí chybová zpráva: **nebyl nalezen (550 5.4.1)**, ověřte e-mailovou doménu pro veřejné složky je nakonfigurován jako domény vnitřní relay namísto autoritativní domény:</span><span class="sxs-lookup"><span data-stu-id="0b220-103">If external senders can't send messages to your mail-enabled public folders, and the senders receive the error: **couldn't be found (550 5.4.1)**, verify the email domain for the public folder is configured as an internal relay domain instead of an authoritative domain:</span></span>

1. <span data-ttu-id="0b220-104">Otevřete [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span><span class="sxs-lookup"><span data-stu-id="0b220-104">Open the [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span></span>

2. <span data-ttu-id="0b220-105">Přejít na **toku pošty** \> **přijaté domény**přijaté domény vyberte a klepněte na tlačítko **Upravit**.</span><span class="sxs-lookup"><span data-stu-id="0b220-105">Go to **Mail flow** \> **Accepted domains**, select the accepted domain, and then click **Edit**.</span></span>

3. <span data-ttu-id="0b220-106">Ve vlastnostech stránky otevře, pokud typ domény je nastavena na **autoritativní**, změňte hodnotu na **vnitřní relay** a klepněte na tlačítko **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="0b220-106">In the properties page that opens, if the domain type is set to **Authoritative**, change the value to **Internal relay** and then click **Save**.</span></span>

<span data-ttu-id="0b220-107">Pokud externí odesílatelé obdržet chyba **že nemáte oprávnění (550 5.7.13)**, spusťte následující příkaz v [Prostředí Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) Chcete-li zobrazit oprávnění pro anonymní uživatele ve veřejné složce:</span><span class="sxs-lookup"><span data-stu-id="0b220-107">If external senders receive the error **you don't have permission (550 5.7.13)**, run the following command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) to see the permissions for anonymous users in the public folder:</span></span>

<span data-ttu-id="0b220-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Například `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span><span class="sxs-lookup"><span data-stu-id="0b220-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` For example, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span></span>

<span data-ttu-id="0b220-109">Pokud chcete povolit externí uživatelé odeslat e-mail této veřejné složky, přidejte přístup CreateItems právo na anonymní uživatele.</span><span class="sxs-lookup"><span data-stu-id="0b220-109">To allow external users to send email to this public folder, add the CreateItems access right to the user Anonymous.</span></span> <span data-ttu-id="0b220-110">Například `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span><span class="sxs-lookup"><span data-stu-id="0b220-110">For example, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span></span>
