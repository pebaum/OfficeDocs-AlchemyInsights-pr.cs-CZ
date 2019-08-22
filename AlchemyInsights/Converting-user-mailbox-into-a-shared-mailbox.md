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
ms.openlocfilehash: ab34b8939b95b29bedb797f640dd744bc783adef
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496392"
---
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a><span data-ttu-id="f86f7-102">Převést poštovní schránky uživatele na sdílené poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="f86f7-102">Convert a user mail box into a shared mailbox</span></span>

<span data-ttu-id="f86f7-103">Pokud uživatel nemá licenci pro Exchange, lze převést pouze poštovní schránky uživatele na sdílené poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="f86f7-103">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="f86f7-104">Po převedení poštovní schránky bude pokračovat Chcete-li zobrazit v seznamu aktivních uživatelů, protože tento seznam obsahuje sdílené poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="f86f7-104">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="f86f7-105">Nicméně převedené poštovní schránky se také zobrazí v seznamu sdílené poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="f86f7-105">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="f86f7-106">Pokud se pokusíte převést poštovní schránky v konzole pro správu serveru Exchange a převod se nezdaří, vymažte mezipaměť prohlížeče a soubory cookie a akci opakujte.</span><span class="sxs-lookup"><span data-stu-id="f86f7-106">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="f86f7-107">Pokud stále nefunguje, zkuste převést poštovní schránky v prostředí Exchange Management Shell spusťte následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="f86f7-107">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="f86f7-108">Další informace o převodu poštovní schránka je k dispozici v [Převést poštovní schránky uživatele na sdílené poštovní schránky](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span><span class="sxs-lookup"><span data-stu-id="f86f7-108">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span></span>
  
