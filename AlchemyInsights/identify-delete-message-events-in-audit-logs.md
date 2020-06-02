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
ms.openlocfilehash: 641c0216491186aeb423a13854c6b39ee005e5df
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508981"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Protokoly auditu pro odstraněné e-mailové zprávy

Počínaje lednem 2019 microsoft ve výchozím nastavení zapíná protokolování auditu poštovní schránky. V opačném případě chcete-li zkontrolovat události odstranění zprávy pro konkrétního uživatele, je třeba ručně povolit akce odstranění pro auditování. Pokud je protokolování auditu poštovní schránky již pro vaši organizaci nebo pro konkrétního uživatele povoleno, postupujte podle následujících kroků.

1. Přihlaste se do [Centra dodržování předpisů zabezpečení microsoftu 365 &](https://protection.office.com/)

2. Klepněte na tlačítko **Hledat a vyšetřování** a vyberte možnost Hledat v protokolu **auditu**.

3. V polích **Počáteční datum** a **Koncové datum** vyberte rozsah dat. Zadejte uživatelské jméno pro uživatele, který chcete prozkoumat (uživatel, který odstranil položky). V poli **Aktivity** vyberte **položku Odstraněná zpráva ze složky Odstraněná pošta** a **Přesunuté zprávy do složky Odstraněná pošta**.

4. Klepněte na tlačítko **Hledat**.

Ve výsledcích vyberte záznam auditu. V informačním rámečku podrobnosti klepněte na tlačítko **Další informace**. Další informace o odstraněné položce (například řádek předmětu a umístění položky při jeho odstranění) se zobrazí v poli **AffectedItems.** Vlastnost **ClientInfoString** zobrazí, pokud k odstranění došlo v aplikaci Outlook, Outlook na webu (dříve označované jako Outlook Web App) nebo jiné zařízení.

Další informace naleznete v [tématu Určení, kdo nastavil předávání e-mailů pro poštovní schránku](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-if-a-user-deleted-email-items).

**Poznámka:** Odstraněné položky nelze načíst pomocí funkce protokolu auditu. Pokud chcete načíst odstraněné zprávy v Outlooku na webu, [přečtěte si tématu Obnovení odstraněných položek v Outlook Web Appu](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).
