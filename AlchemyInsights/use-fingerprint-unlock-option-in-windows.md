---
title: Použití možnosti odemknutí otiskem prstu ve Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001689"
- "3765"
ms.openlocfilehash: 8a5059c722c306ad79811140062cec7f52f31766
ms.sourcegitcommit: 00e4266575438f55bdc18db05ed54aafcb75a3c9
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/11/2020
ms.locfileid: "42588309"
---
# <a name="use-fingerprint-unlock-option-in-windows-10"></a>Použití možnosti odemknutí otiskem prstu ve Windows 10

**Povolení otisku prstu Windows Hello**

Chcete-li odemknout systém Windows 10 pomocí otisku prstu, musíte nastavit otisk prstu Windows Hello přidáním (nechat systém Windows naučit se rozpoznat) alespoň jeden prst. 

1. Přejděte na **Nastavení > účty > možnosti přihlášení** (nebo klikněte [sem).](ms-settings:signinoptions?activationSource=GetHelp) V seznamu budou uvedeny dostupné možnosti přihlášení. Příklady:

    ![Možnosti přihlášení.](media/sign-in-options.png)

2. Klikněte nebo klepněte na **Windows Hello Fingerprint**a potom klikněte na **Nastavit**. V okně nastavení Windows Hello klikněte na **Začínáme**. Snímač otisků prstů se aktivuje a budete vyzváni k umístění prstu na snímač:

   ![Snímač otisků prstů.](media/fingerprint-sensor.png)

3. Postupujte podle pokynů, které vás budou žádat, abyste opakovaně naskenovali prst. Po dokončení budete mít možnost přidat další prsty, které budete chtít použít pro přihlášení. Až se příště přihlásíte k Windows 10, budete mít možnost k tomu použít otisk prstu.

**Windows Hello Fingerprint není k dispozici jako možnost přihlášení**

Pokud se otisk prstu Windows Hello nezobrazuje jako možnost v **možnostech přihlášení**, znamená to, že systém Windows neví o žádné čtečce/skeneru otisků prstů připojeném k počítači nebo že systémová politika brání jeho použití (pokud je například váš počítač spravován vaším pracovištěm). Postup řešení potíží: 

1. Vyberte tlačítko **Start** na hlavním panelu a vyhledejte **Správce zařízení**.

2. Kliknutím nebo klepnutím otevřete **Správce zařízení**.

3. Ve Správci zařízení rozbalte biometrická zařízení kliknutím na jeho dvojitou šipku.

   ![Biometrická zařízení.](media/biometric-devices.png)

4. Snímač otisků prstů by měl být uveden jako biometrické zařízení, například skener Synaptics WBDI:

   ![Biometrická zařízení.](media/biometric-devices-expanded.png)

5. Pokud se skener otisků prstů nezobrazuje a skener je integrován do počítače, přejděte na web výrobce počítače. V části technická podpora modelu počítače vyhledejte skener, který můžete nainstalovat, ovladač pro Windows 10.

6. Pokud je skener oddělený od počítače (připojeného přes USB), přejděte na web výrobce skeneru a vyhledejte a nainstalujte software ovladače zařízení Windows 10 pro model skeneru, který máte.
