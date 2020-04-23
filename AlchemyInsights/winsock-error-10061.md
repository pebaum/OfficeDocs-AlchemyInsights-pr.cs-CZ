---
title: 1554 Chyba rozhraní Winsock 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e8f62d97efc937518ef766b45e1747e83b7f99c3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766162"
---
# <a name="winsock-error-10061"></a>Chyba rozhraní Winsock 10061

Tento kód chyby znamená, že společnost Microsoft nemohla vytvořit soket TCP (připojení) s cílovým hostitelem. Nejpravděpodobnější příčinou této chyby je problém s konfigurací brány firewall. Chcete-li problém vyřešit, zkontrolujte tato nastavení:

- Ověření konfigurace brány firewall pomocí informací v [adresách URL a rozsahu IP adres společnosti Microsoft 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)

- Pokud je chyba specifická pro ochranu Exchange Online Protection (EOP), měli jste být dříve upozorněni na změnu [IP adres ochrany Exchange Online](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

- Ověřte, zda váš poskytovatel internetových služeb (ISP) neblokuje port.

- Ověřte nastavení inteligentního hostitele a cílového serveru v konektorech.

Všimněte si, že Microsoft 365 neblokuje *příchozí* připojení tímto způsobem.
