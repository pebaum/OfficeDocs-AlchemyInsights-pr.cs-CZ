---
title: Řešení bezpečnostního tipu pro kontroly odhalování podvodů
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.custom:
- "275"
- "3100004"
ms.openlocfilehash: 74913492a086de688067d588e95dd87e6946743b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44504976"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a>Řešení bezpečnostního tipu pro kontroly odhalování podvodů

Pokud se vám zobrazuje bezpečnostní tip s nápisem "Odesílatel selhal v kontrolách zjišťování podvodů a nemusí být tím, kým se zdá být", odesílatel neprošel kontrolou ověřování DKIM nebo SPF. Nejlepší způsob, jak to vyřešit, je pro odesílatele, aby se sami. Pokud odesílatel odesílá vaším jménem, musíte je autorizovat přidáním IP adresy odesílatele do záznamu SPF.
  
Další informace najdete [v tématu Řešení červeného (podezřelého) bezpečnostního tipu pro kontroly odhalování podvodů.](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/)
  
Zde jsou některé další odkazy, které mohou pomoci:
  
- [Jak společnost Microsoft používá rámec zásad odesílatele (SPF) k zabránění falšování identity](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-office-365-uses-spf-to-prevent-spoofing)

- [Nastavení SPF, aby se zabránilo falšování identity](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-spf-in-office-365-to-help-prevent-spoofing)
