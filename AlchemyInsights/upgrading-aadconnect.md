---
title: 932 AADConnect inovace
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 07de6f8df7bfda2060977c7d5bc6a01766bf3c0a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35365884"
---
# <a name="upgrade-azure-ad-connect"></a>Inovace Azure AD připojit

Standardně je povoleno automatické inovace pro Azure AD připojit, což pomůže zajistit, že používáte nejnovější verzi. Chcete-li ověřit nastavení automatického upgradu, použijte rutiny **Get-ADSyncAutoUpgrade** v prostředí PowerShell Azure AD. Rutiny vrátí jednu z následujících hodnot:

- **Povoleno**: je povolen automatický upgrade.

- **Zakázáno**: automatický upgrade je zakázáno.

- **Suspended**: systém je již oprávněni přijímat automatické upgrady. Nelze nastavit tuto hodnotu; systém je nastaven.

Další informace naleznete v tématu [automatické inovace](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).

Chcete-li stáhnout nejnovější verzi Azure AD připojit, přejděte na [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).
