---
title: Identifikace událostí odstranění zpráv v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 797a4b1146862faf91d2b9e8d74feade90f71650
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716489"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Protokoly auditování odstraněných e-mailových zpráv

Od ledna 2019 společnost Microsoft ve výchozím nastavení zapíná protokolování auditu poštovní schránky. V opačném případě chcete zkontrolovat odstranění událostí zprávy pro konkrétního uživatele, je třeba ručně povolit akce odstranění pro auditování. Pokud je protokolování auditu poštovní schránky již povoleno pro vaši organizaci nebo pro konkrétního uživatele, postupujte podle následujících kroků.

1. Přihlášení do [Centra dodržování předpisů pro zabezpečení & microsoftu 365](https://protection.office.com/)

2. Klepněte na tlačítko **Hledat a šetření** a vyberte možnost Hledání protokolu **auditu**.

3. Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum.** Zadejte uživatelské jméno uživatele, kterého chcete prozkoumat (uživatele, který položky odstranil). V poli **Aktivity** vyberte **Odstraněná zpráva ze složky Odstraněná pošta** a **Přesunuté zprávy do složky Odstraněná pošta**.

4. Klepněte na **tlačítko Hledat**.

Ve výsledcích vyberte záznam auditu. V informačním rámečku podrobnosti klikněte na **Další informace**. Další informace o odstraněné položce (například řádek předmětu a umístění položky při jeho odstranění) se zobrazí v poli **Ovlivněné položky.** Vlastnost **ClientInfoString** zobrazí, pokud k odstranění došlo v outlooku, outlooku na webu (dříve označované jako Outlook Web App) nebo v jakémkoli jiném zařízení.

Další informace naleznete v [tématu Určení, kdo nastavil předávání e-mailů pro poštovní schránku](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Poznámka:** Odstraněné položky nelze načíst pomocí funkce protokolu auditu. Informace o načtení odstraněných zpráv v Outlooku na webu najdete [v tématu Obnovení odstraněných položek v Outlook Web Appu](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).
