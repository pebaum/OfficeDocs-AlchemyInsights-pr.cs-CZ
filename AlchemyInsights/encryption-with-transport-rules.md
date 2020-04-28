---
title: Šifrování pomocí pravidel přenosu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5154"
ms.openlocfilehash: 3f16c7e7be99a50cd57f47ea2801b3022c4aec95
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915088"
---
# <a name="encryption-with-transport-rules"></a>Šifrování pomocí pravidel přenosu

V [Centru pro správu Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC) můžete v pravidlech toku pošty používat funkce šifrování zpráv Office (OME) ke spouštění šifrování zpráv. U podmínky Pravidlo přenosu vyberte možnost **Použít šifrování zpráv Office 365 a ochranu práv**.

- Další informace najdete v článku [Definování pravidla toku pošty pro šifrování](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

- V PowerShellu použijte rutinu [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) a nastavte parametr *ApplyOME* na $true.
