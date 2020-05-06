---
title: Exchange PowerShell a zastaralé základní ověřování
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "4577"
ms.openlocfilehash: 24d59860732b42e8d62da8c1a8c37f2018a0d126
ms.sourcegitcommit: 264b782ac2fba8ffd84524180dc4f7d60b45e9a4
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/04/2020
ms.locfileid: "44015682"
---
# <a name="exchange-powershell-and-basic-authentication-deprecation"></a>Exchange PowerShell a zastaralé základní ověřování

Nejnovější informace o tom, jak se připojit k PowerShellu pro Exchange Online bez použití základního ověřování, najdete [tady](https://aka.ms/psbasicauth).

Mějte prosím na paměti, že základní ověřování musí být na klientském počítači nadále povolené.
Nový modul PowerShell V2 používá k navázání připojení u všech rutin V2 založených na rozhraní REST moderní ověřování. Kromě rutin V2 vám také umožňuje přístup ke starším rutinám vzdáleného PowerShellu (RPS), které vyžadují navázání relace vzdáleného PowerShellu. Navázání relace RPS na počítači s Windows vyžaduje, aby bylo na klientském počítači povolené ověřování WinRM BasicAuth, i když modul k ověření služby používá mechanismus moderního ověřování. K přenosu tokenů moderního ověřování se používá kanál základního ověřování WinRM. Pokud je na klientském počítači základní ověřování WinRM zakázané, budou nové rutiny V2 dál fungovat (ale ne starší rutiny RPS).
