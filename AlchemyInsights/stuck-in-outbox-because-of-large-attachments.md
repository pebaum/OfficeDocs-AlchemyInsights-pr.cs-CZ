---
title: Uvíznout ve složce Pošta k odeslání z důvodu rozsáhlých příloh
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
ms.openlocfilehash: d5fb20fcc146be67c5a04de0640ed4efd625311a
ms.sourcegitcommit: 8004ee243b5c68ff9532224a2e6c69dda0abbd0b
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/10/2019
ms.locfileid: "37441299"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Oprava zpráv, které uvízly ve složce Pošta k odeslání

Doporučujeme začít spuštěním scénáře ["Mám problémy s odesíláním, přijímáním a hledáním e-mailových zpráv"](https://aka.ms/SaRA-OutlookSendReceive) z nástroje [společnosti Microsoft pro podporu a obnovení](https://diagnostics.office.com/#/) .

Pokud zpráva uvízne ve složce Pošta k odeslání, nejpravděpodobnější příčiny jsou následující:
- Velké přílohy.
- Možnost **Odeslat okamžitě po připojení** není povolena.

Odebrání velkých příloh: 

1. V aplikaci Outlook vyberte možnost **Odeslat a přijmout** > **offline**. 
2. V navigačním podokně vyberte položku **Pošta k odeslání**. Odtud můžete: 
    - Odstraňte zprávu (vyberte ji a pak vyberte možnost **Odstranit**).
    - Přetáhněte zprávu do složky Koncepty, poklepáním ji otevřete a odeberte přílohu a vyberte možnost **Odstranit**.
3. Pokud se zobrazí chybová zpráva oznamující, že se aplikace Outlook pokouší odeslat zprávu, ukončete aplikaci Outlook. Ukončení může chvíli trvat. Pokud se aplikace Outlook nezavře, stiskněte klávesy CTRL + ALT + DELETE a vyberte možnost **Spustit Správce úloh**. Ve Správci úloh vyberte kartu **procesy** , přejděte na položku Outlook. exe a vyberte možnost **Ukončit proces**.
4. Po ukončení aplikace Outlook ji restartujte a opakujte kroky 2 a 3. 
5. Po odebrání přílohy můžete klepnutím na tlačítko **Odeslat a přijmout** > **pracovat offline** a pokračovat v práci online. 

Po klepnutí na tlačítko **Odeslat**se zprávy také zablokují ve složce Faxy k odeslání, ale nejste připojeni. Klepněte na tlačítko **Odeslat a přijmout** a podívejte se na tlačítko **pracovat offline** . Je-li modrá, jste odpojeni. Vyberte, chcete-li se připojit (tlačítko změní bílou) a klepněte na **poslat vše**.
 
Povolení **okamžitého odeslání při připojení**:
 
- Vyberte možnost**Rozšířené****Možnosti** >   **souboru** > .
V části **Odeslat a přijmout** vyberte možnost **odeslat ihned po připojení**a pak klepněte na **tlačítko OK**.
 
Úplné podrobnosti naleznete v tématech:
- [Video: odeslání nebo odstranění zablokované e-mailové zprávy](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [E-mail zůstane ve složce Faxy k odeslání, dokud ručně nespustíte operaci odesílání a přijímání v aplikaci Outlook](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
