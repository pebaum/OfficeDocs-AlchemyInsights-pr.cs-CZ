---
title: Přesunutí e-mailových zpráv do poštovní schránky archivu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 5592bc7d4566e3498c33bbf9488db7f46ec58842
ms.sourcegitcommit: 8864b5789d9905916039081b53530c7e6d8bc529
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/10/2019
ms.locfileid: "36822155"
---
# <a name="move-email-to-the-archive-mailbox"></a>Přesunout e-mail do archivní poštovní schránky

1. Potvrďte, že byla povolena **archivační poštovní schránka** . Pokud tomu tak není, povolte pomocí kroků popsaných v [tomto článku](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) archivační schránku.

2. Chcete-li automaticky archivovat zprávy do archivní poštovní schránky, je nutné nastavit značku uchování s akcí **přesunutí do archivu** , která bude **automaticky použita na celou poštovní schránku (výchozí)**. Pomocí kroků zde Vytvořte tag: [Archivovat výchozí tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).

3. Potom přidejte tag **Archivovat** do zásad uchovávání informací. V centru pro správu serveru Exchange vyberte možnost **zásady uchovávání informací** > přidejte do zásady příkaz **přesunout do archivní značky** > **Uložit**.

4. Nyní [přiřaďte zásadu uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) do poštovní schránky konkrétního uživatele. Stejná zásada bude použita pro **primární** i **archivační** schránku.

Pravděpodobně bude nutné vynutit spuštění pomocníka pro správu (MFA) a použití nového nastavení v poštovní schránce uživatele. Po [připojení k prostředí EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) spusťte následující příkaz pro spuštění pomocníka pro spravovanou složku pro určitou poštovní schránku:
  
Počáteční-ManagedFolderAssistant-identita<name of the mailbox>

Další informace o nastavení zásad archivace naleznete v tématu [nastavení zásad archivace a odstranění pro poštovní schránky](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  