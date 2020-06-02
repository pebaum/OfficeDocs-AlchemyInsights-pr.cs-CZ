---
title: Oprava problémů s instalací DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 8195b0e3fada6da033b2d95b1fc6600e7fa3341e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506767"
---
# <a name="fix-dkim-setup-issues"></a>Oprava problémů s instalací DKIM

Pokud narazíte na problémy s povolením DKIM pro vaši vlastní doménu, postupujte takto:

- Většina problémů s nastavením DKIM souvisí s nesprávnými záznamy DNS. Ověřte, zda je záznam DKIM CNAME **(nikoli** záznam TXT) správně formátován. Další informace naleznete v tomto [tématu](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).

- Po vytvoření nebo aktualizaci záznamů SLUŽBY DKIM DNS v hostitelské službě DNS pro vaši doménu (obvykle váš registrátor domény) počkejte, až se záznamy DNS rozšíří.

- Pokud nemůžete vytvořit záznamy DKIM DNS v Centru pro správu, můžete nahradit \<CustomDomain\> vlastní doménou (například contoso.com) a spustit tento příkaz v [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true` .
