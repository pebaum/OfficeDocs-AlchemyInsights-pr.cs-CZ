---
title: Opravit problémy s instalací DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 4d6dadbcbf71fe6e9ea56d6a82a7d8ababdd38ef
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34764933"
---
# <a name="fix-dkim-setup-issues"></a>Opravit problémy s instalací DKIM

Pokud máte problémy s vaší vlastní domény povolení DKIM, použijte následující kroky:

- Většinu potíží při instalaci DKIM souvisejí nesprávné záznamy DNS. Ověřte, zda že záznam DKIM CNAME (**není** záznam TXT) je správně formátován. Další informace najdete v tomto [tématu](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

- Můžete vytvořit nebo aktualizovat své záznamy DKIM DNS na DNS hostitelem vaší domény (obvykle váš Registrátor domény), DNS záznamy k šíření čekat.

- Pokud záznamy DKIM DNS nelze vytvořit ve středisku pro správce, můžete nahradit \<CustomDomain\> s vaší vlastní domény (například contoso.com) a spusťte tento příkaz v [Prostředí Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.
