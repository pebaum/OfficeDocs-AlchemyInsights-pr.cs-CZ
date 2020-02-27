---
title: Vytvoření e-mailu zachytit vše
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001524"
- "3732"
ms.openlocfilehash: 35f31c1662547d57c2fc9978ffb495ac29abcc01
ms.sourcegitcommit: 67015549afcbe05f3b77ea314e2ef7e0e439f9f2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/26/2020
ms.locfileid: "42286104"
---
# <a name="create-an-email-catch-all"></a>Vytvoření e-mailu zachytit vše

Použití úlovku vše je silně odrazováno. Je lepší poskytnout odrazit zpět odesílateli nechat odesílatele vědět, že jejich zpráva nemohla být doručena, jak je určeno, aby mohli přijmout opatření. Monitorovanou poštovní schránku můžete také omezit tak, aby zachytila pouze dříve platné e-mailové adresy. 

Každý úlovek všechny poštovní schránky obdrží hodně spamu a může nakonec vyplnit, pokud nejsou pečlivě sledovány. (Existují limity pro příjem.) 

Pokud se rozhodnete pokračovat, postupujte takto:

1. Vytvořte skupinu dynamické distribuce & obsahovat "Všechny typy příjemců".

2. Vytvořte vyhrazenou poštovní schránku pro zachycení e-mailů, například catchall@domain.com.

3. Pro konkrétní doménu nastavte DomainType na "InternalRelay". Pokud později odeberete všechny catch, nezapomeňte nastavit doménu zpět na autoritativní.

4. Vytvořte pravidlo přenosu toku pošty následujícím způsobem:

    - Pokud odesílatel je "Mimo organizaci"
    - Přesměrovat zprávu na Catchall@domain.com
    - S výjimkou případů, kdy je příjemce členem allusers@domain.com (Distribuční skupina obsahuje všechny členy)
    - Zajistit ověření přidání nových poštovních schránek do skupiny dynamické distribuce.
