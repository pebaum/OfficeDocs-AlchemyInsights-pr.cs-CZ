---
title: Přesunutí e-mailových zpráv do poštovní schránky Archivu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 35c11f1bfb7c61b28a64f0128c29ddf7b4fce939
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511033"
---
# <a name="move-email-to-the-archive-mailbox"></a>Přesunutí e-mailu do archivní poštovní schránky

1. Zkontrolujte, zda byla povolena **poštovní schránka Archivu.** Pokud ne, použijte kroky v [tomto článku](https://docs.microsoft.com/microsoft-365/compliance/enable-archive-mailboxes) povolit archivní poštovní schránky.

2. Chcete-li automaticky archivovat zprávy do archivní poštovní schránky, musí být značka uchovávání informací s akcí **Přesunout do archivace** nastavena tak, **aby se automaticky použila na značku celé poštovní schránky (výchozí).** Pomocí pokynů vytvořte značku: [Archivovat výchozí značku](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).

3. Dále přidejte značku **Archiv** do zásad uchovávání informací. V Centru pro správu Exchange zvolte **Zásady uchovávání informací** > přidat **značku Přesunout do archivace** do zásady > **Uložit**.

4. Nyní [přiřaďte zásady uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) k poštovní schránce konkrétního uživatele. Stejné zásady budou použity pro **primární** i **archivní** poštovní schránku.

Může být nutné vynutit spuštění Pomocníka pro spravované složky (MFA) a použít nové nastavení poštovní schránky uživatele. Spuštěním následujícího příkazu při [připojení k EXO PowerShellu](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) spusťte Pomocníka pro spravované složky pro určitou poštovní schránku:
  
Start-ManagedFolderAssistant -Identita<name of the mailbox>

Další informace o nastavení zásad archivace naleznete v [tématu Nastavení zásad archivace a odstranění poštovních schránek](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  