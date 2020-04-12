---
title: Přilepená ve složce Pošta k poště kvůli velkým přílohám
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
- "9002385"
- "4645"
ms.openlocfilehash: 35fe9ae76ca77faa43796b288af09be8525cb6df
ms.sourcegitcommit: 929f8accdca2b8e5be170e0fc8edd527581453d4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/12/2020
ms.locfileid: "43232623"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Oprava zpráv, které uvízly ve složce Pošta k poště pošta

Doporučujeme začít spuštěním scénáře ["Mám potíže s odesíláním, přijímáním nebo hledáním e-mailových zpráv"](https://aka.ms/SaRA-OutlookSendReceive) z nástroje [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) v ohroženém počítači.

Když se zpráva zasekne ve složce Pošta k odeslání, nejpravděpodobnější příčinou je velká příloha nebo není povolena možnost "Odeslat okamžitě po připojení".

**Odebrání velké přílohy**

1. Klepněte na tlačítko **Odeslat a přijmout** > **práci offline**. 
2. V navigačním podokně klikněte na **Pošta k poště předem**. Odtud můžete: 
    - Odstraňte zprávu. Stačí ji vybrat a klepnout na **tlačítko Odstranit**.
    - Přetáhněte zprávu do **složky konceptů**, poklepáním zprávu otevřete a přílohu odstraňte (klikněte na ni a klikněte na **Odstranit**).
3. Pokud se zobrazí chyba, že se aplikace Outlook pokouší zprávu přenést, zavřete aplikaci Outlook. Odchod může chvíli trvat. Pokud se Outlook nezavře, stiskněte **Ctrl+Alt+Delete** a klikněte na **Spustit Správce úloh**. Ve Správci úloh vyberte kartu **Procesy,** přejděte dolů na soubor outlook.exe a klepněte na tlačítko **Ukončit proces**.
4. Po zavření aplikace Outlook restartujte aplikaci Outlook a opakujte kroky 2-3. 
5. Po odebrání přílohy klikněte na **Odeslat a přijmout** > **práci offline,** abyste odznačili tlačítko a pokračovali v práci online. 

Zprávy se také zaseknou ve složce Pošta k odeslání, když kliknete na **Odeslat**, ale nejste připojeni. Klikněte na **Odeslat a přijmout** a podívejte se na tlačítko **Pracovat offline.** Pokud je modrá, jste odpojeni. Kliknutím se připojíte (tlačítko zbělá) a klepněte na **tlačítko Odeslat vše**.
 
**Povolit okamžité odeslání po připojení**
 
1. Na kartě Soubor klikněte na **Možnosti**.

2. V dialogovém okně Možnosti aplikace Outlook klepněte na tlačítko **Upřesnit**.

3. V části Odeslat a přijmout klepnutím povolte **možnost Odeslat okamžitě po připojení**. Klikněte na **OK**.
 
Podrobné informace naleznete v:
- [Video: Odeslání nebo odstranění zablokované e-mailu](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [E-mail zůstane ve složce Pošta k odeslání, dokud ručně nezahájíte operaci odesílání a přijímání v Outlooku](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
