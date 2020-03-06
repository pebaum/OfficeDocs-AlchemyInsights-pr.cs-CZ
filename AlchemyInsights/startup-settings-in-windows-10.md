---
title: Nastavení spouštění ve Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001691"
- "3768"
ms.openlocfilehash: b4854944d8cbd9bd83fdea609007c15d39c8eb75
ms.sourcegitcommit: c55eea624d960d2dd17ac4aa5a4c23e34e6443b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/04/2020
ms.locfileid: "42408970"
---
# <a name="startup-settings-in-windows-10"></a>Nastavení spouštění ve Windows 10

**Změna automatického spouštění aplikací při spuštění**

1. Přejděte [na Nastavení > aplikace > spuštění](ms-settings:startupapps?activationSource=GetHelp).

2. Ujistěte se, že všechny aplikace, které chcete spustit při spuštění je **zapnuta**.

**Přidání aplikace, která se spustí automaticky při spuštění**

1. Klikněte nebo klepněte na **Start** a najděte aplikaci, kterou chcete spustit při spuštění.

2. Klikněte pravým tlačítkem myši na aplikaci, klikněte na **Další**a potom klikněte na **Otevřít umístění souboru**. Otevře se umístění, kde se uloží zástupce aplikace. Pokud neexistuje žádná možnost pro umístění otevřít soubor, znamená to, že aplikace nelze spustit při spuštění.

3. Po otevření umístění souboru stiskněte **klávesu s logem Windows + R**, zadejte **příkaz shell:startup**a klepněte na tlačítko **OK**. Otevře se složka Po spuštění.

4. Zkopírujte a vložte zástupce aplikace z umístění souboru do složky Po spuštění.

**Pokročilé možnosti spuštění (včetně nouzového režimu, nastavení UEFI a spuštění z jiného zařízení)**

1. Uložte svou práci a zavřete všechny otevřené dokumenty, protože tyto kroky restartují počítač.

2. Přejděte na [nastavení > aktualizace & obnovení > zabezpečení](ms-settings:recovery?activationSource=GetHelp).

3. V části **Rozšířené spuštění**klepněte na tlačítko **Restartovat .** 

4. Po restartování počítače na obrazovce Zvolte možnost:

    - Pokud chcete spustit ze zařízení, jako je jednotka USB, **klikněte**na Použít zařízení .

    - Chcete-li zadat nastavení rozhraní UEFI (někdy nazývané nastavení systému BIOS), klepněte na **tlačítko Poradce při potížích s > pokročilými možnostmi > nastavení firmwaru Rozhraní UEFI**. 

    - Chcete-li přejít do nouzového režimu nebo změnit upřesňující **** nastavení spouštění, klepněte na tlačítko **Poradce při potížích s > rozšířenými možnostmi > nastavení mj.** Můžete být vyzváni k zadání [obnovovacího klíče nástroje BitLocker](https://support.microsoft.com/help/4026181/windows-10-find-my-bitlocker-recovery-key). Po opětovném restartování počítače klikněte na nastavení spuštění, které chcete použít.