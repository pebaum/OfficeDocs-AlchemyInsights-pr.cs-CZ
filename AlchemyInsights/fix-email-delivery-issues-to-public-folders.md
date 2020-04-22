---
title: Řešení problémů s doručováním e-mailů do veřejných složek s povoleným poštou
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: e261fe60843555fa45927b0a6b36e1ccf79fb028
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716345"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a><span data-ttu-id="4bfdb-102">Řešení problémů s doručováním e-mailů do veřejných složek s povoleným poštou</span><span class="sxs-lookup"><span data-stu-id="4bfdb-102">Fix email delivery issues to mail-enabled public folders</span></span>

<span data-ttu-id="4bfdb-103">Pokud externí odesílatelé nemohou odesílat zprávy do veřejných složek s podporou pošty a odesílatelům se zobrazí chyba: **nelze najít (550 5.4.1),** ověřte, zda je e-mailová doména pro veřejnou složku nakonfigurována jako interní přenosová doména namísto autoritativní domény:</span><span class="sxs-lookup"><span data-stu-id="4bfdb-103">If external senders can't send messages to your mail-enabled public folders, and the senders receive the error: **couldn't be found (550 5.4.1)**, verify the email domain for the public folder is configured as an internal relay domain instead of an authoritative domain:</span></span>

1. <span data-ttu-id="4bfdb-104">Otevřete [Centrum pro správu Exchange (EAC).](https://docs.microsoft.com/Exchange/exchange-admin-center)</span><span class="sxs-lookup"><span data-stu-id="4bfdb-104">Open the [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span></span>

2. <span data-ttu-id="4bfdb-105">Přejděte na Přijaté domény **toku** \> **pošty**, vyberte přijatou doménu a klepněte na tlačítko **Upravit**.</span><span class="sxs-lookup"><span data-stu-id="4bfdb-105">Go to **Mail flow** \> **Accepted domains**, select the accepted domain, and then click **Edit**.</span></span>

3. <span data-ttu-id="4bfdb-106">Pokud je typ domény nastaven na **autoritativní**, změňte na stránce vlastností, která se otevře, změňte hodnotu na **Interní přenos** a klepněte na tlačítko **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="4bfdb-106">In the properties page that opens, if the domain type is set to **Authoritative**, change the value to **Internal relay** and then click **Save**.</span></span>

<span data-ttu-id="4bfdb-107">Pokud se externím odesílatelům zobrazí **chyba, ke které nemáte oprávnění (550 5.7.13),** spusťte v [prostředí Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) následující příkaz, abyste viděli oprávnění pro anonymní uživatele ve veřejné složce:</span><span class="sxs-lookup"><span data-stu-id="4bfdb-107">If external senders receive the error **you don't have permission (550 5.7.13)**, run the following command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) to see the permissions for anonymous users in the public folder:</span></span>

<span data-ttu-id="4bfdb-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Například `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span><span class="sxs-lookup"><span data-stu-id="4bfdb-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` For example, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span></span>

<span data-ttu-id="4bfdb-109">Chcete-li externím uživatelům povolit odesílání e-mailů do této veřejné složky, přidejte uživatelskému uživateli anonymní přístupové právo CreateItems.</span><span class="sxs-lookup"><span data-stu-id="4bfdb-109">To allow external users to send email to this public folder, add the CreateItems access right to the user Anonymous.</span></span> <span data-ttu-id="4bfdb-110">Například `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span><span class="sxs-lookup"><span data-stu-id="4bfdb-110">For example, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span></span>
