---
title: Převod poštovní schránky uživatele na sdílené poštovní schránky?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 4da54121763fd33aa111f3bb3c26963cd271dc51
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32374316"
---
<span data-ttu-id="b6bff-102">Pokud uživatel nemá licenci pro Exchange, lze převést pouze poštovní schránky uživatele na sdílené poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="b6bff-102">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="b6bff-103">Po převedení poštovní schránky bude pokračovat Chcete-li zobrazit v seznamu aktivních uživatelů, protože tento seznam obsahuje sdílené poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="b6bff-103">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="b6bff-104">Nicméně převedené poštovní schránky se také zobrazí v seznamu sdílené poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="b6bff-104">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="b6bff-105">Pokud se pokusíte převést poštovní schránky v konzole pro správu serveru Exchange a převod se nezdaří, vymažte mezipaměť prohlížeče a soubory cookie a akci opakujte.</span><span class="sxs-lookup"><span data-stu-id="b6bff-105">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="b6bff-106">Pokud stále nefunguje, zkuste převést poštovní schránky v prostředí Exchange Management Shell spusťte následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="b6bff-106">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="b6bff-107">Další informace o převodu poštovní schránka je k dispozici v [Převést poštovní schránky uživatele na sdílené poštovní schránky](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span><span class="sxs-lookup"><span data-stu-id="b6bff-107">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span></span>
  
