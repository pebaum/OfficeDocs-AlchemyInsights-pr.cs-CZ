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
ms.openlocfilehash: a5ad81e97df0ed5c337a622126173df94af80bb8
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713639"
---
# <a name="move-email-to-the-archive-mailbox"></a>Přesunutí e-mailu do archivní poštovní schránky

1. Zkontrolujte, zda byla povolena **archivní poštovní schránka.** Pokud ne, povolte poštovní schránku archivu pomocí kroků v [tomto článku.](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)

2. Chcete-li zprávy archivovat automaticky do poštovní schránky archivu, musí být značka uchovávání informací s akcí **Přesunout do archivu** nastavena tak, aby byla **automaticky použita na celou značku poštovní schránky (výchozí).** Pomocí zde uvedených kroků vytvořte značku: [Archivovat výchozí značku](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).

3. Dále přidejte značku **Archiv** do zásad uchovávání informací. V Centru pro správu Exchange zvolte **zásady uchovávání informací** > přidat **značku Přesunout do archivace** do zásady > **Uložit**.

4. Nyní [přiřaďte zásady uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) k poštovní schránce konkrétního uživatele. Stejné zásady budou použity pro **primární** i **archivní** poštovní schránky.

Může být nutné vynutit spuštění Pomocníka pro spravované složky (MFA) a použití nového nastavení v poštovní schránce uživatele. Spusťte následující příkaz, když [jste připojeni k exo powershellu,](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) a spusťte Pomocníka pro spravované složky pro určitou poštovní schránku:
  
Start-ManagedFolderAssistant -Identita<name of the mailbox>

Další informace o nastavení zásad archivu naleznete v [tématu Nastavení zásad archivu a odstranění poštovních schránek](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  