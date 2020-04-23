---
title: Řešení problémů s nastavením DKIM
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
ms.openlocfilehash: d725eb0d46dcbf1b5b6d77ca9f59fcafa5298bf1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43717555"
---
# <a name="fix-dkim-setup-issues"></a>Řešení problémů s nastavením DKIM

Pokud narazíte na problémy s povolením DKIM pro vlastní doménu, použijte následující kroky:

- Většina problémů s nastavením DKIM souvisí s nesprávnými záznamy DNS. Ověřte, zda je záznam DKIM CNAME **(nikoli** záznam TXT) správně formátován. Další informace naleznete v tomto [tématu](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

- Po vytvoření nebo aktualizaci záznamů DKIM DNS v hostitelské službě DNS pro vaši doménu (obvykle doménového registrátora) počkejte, až se záznamy DNS rozšíří.

- Pokud nemůžete vytvořit záznamy DKIM DNS v Centru pro \<správu, můžete nahradit vlastní doménu\> vlastní doménou (například contoso.com) a spustit tento příkaz v Exchange Online [PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.
