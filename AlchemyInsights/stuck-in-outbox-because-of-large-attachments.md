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
ms.openlocfilehash: 4f69de167dc51961fa7cf71b4d73ca7ee3ed4d55
ms.sourcegitcommit: 57fb994ddd3854d06faa67680c971b003b06bf83
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/13/2020
ms.locfileid: "43241245"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Oprava zpráv, které uvízly ve složce Pošta k poště pošta

Doporučujeme začít spuštěním scénáře ["Mám potíže s odesíláním, přijímáním nebo hledáním e-mailových zpráv"](https://aka.ms/SaRA-OutlookSendReceive) z nástroje [Microsoft Support and Recovery Assistant.](https://diagnostics.office.com/#/)

Když se zpráva zasekne ve složce Pošta k odeslání, nejpravděpodobnější příčinou je velká příloha nebo není povolena možnost "Odeslat okamžitě po připojení".

**Odebrání velké přílohy**

1. V Outlooku vyberte **Odeslat a přijmout** > **práci offline**. 
2. V navigačním podokně vyberte **Položku Pošta k poště .** Odtud můžete: 
    - Odstraňte zprávu (vyberte ji a pak vyberte **Odstranit**).
    - Přetáhněte zprávu do složky Koncepty, poklepáním ji otevřete a přílohu odeberte, vyberte ji a pak vyberte **Odstranit**).
3. Pokud se zobrazí chyba, která říká, že se aplikace Outlook pokouší zprávu přenést, zavřete aplikaci Outlook. Odchod může chvíli trvat. Pokud se Outlook nezavře, stiskněte Ctrl+Alt+Delete a vyberte **Spustit Správce úloh**. Ve Správci úloh vyberte kartu **Procesy,** posuňte se dolů na soubor outlook.exe a vyberte **Ukončit proces**.
4. Po zavření aplikace Outlook restartujte a opakujte kroky 2 a 3. 
5. Po odebrání přílohy klikněte na **Odeslat a přijmout** > **práci offline** a pokračovat v práci online. 

Zprávy se také zaseknou ve složce Pošta k odeslání, když kliknete na **Odeslat**, ale nejste připojeni. Klikněte na **Odeslat a přijmout** a podívejte se na tlačítko **Pracovat offline.** Pokud je modrá, jste odpojeni. Kliknutím se připojíte (tlačítko zbělá) a klepněte na **tlačítko Odeslat vše**.
 
**Povolit okamžité odeslání po připojení**
 
1. Na kartě Soubor klikněte na **Možnosti**.

2. V dialogovém okně Možnosti aplikace Outlook klepněte na tlačítko **Upřesnit**.

3. V části Odeslat a přijmout klepnutím povolte **možnost Odeslat okamžitě po připojení**. Klikněte na **OK**.
 
Podrobné informace naleznete v:
- [Video: Odeslání nebo odstranění zablokované e-mailu](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [E-mail zůstane ve složce Pošta k odeslání, dokud ručně nezahájíte operaci odesílání a přijímání v Outlooku](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
