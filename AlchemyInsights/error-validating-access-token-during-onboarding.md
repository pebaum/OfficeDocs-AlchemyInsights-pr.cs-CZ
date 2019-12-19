---
title: Při ověřování chyby přístupového tokenu při kontrole služby Desktop Analytics došlo k chybě.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2536"
- "9000657"
ms.openlocfilehash: 7472af5c4e19e5697b5fb4802ed1cbb2c74f1d19
ms.sourcegitcommit: f1fad2129d09660ec42dbce03ce2c6b4cfc9555a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/18/2019
ms.locfileid: "40741142"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a>Při kontrole přístupového tokenu došlo k chybě při ověřování plochy

Tato chyba je obvykle dodržena při vypršení ověřovacího tokenu. Aktualizace stránky obvykle aktualizuje token. Tento problém však může přetrvávat v případě, že u účtu, který je použit pro palubní službu Analytics, jsou použity zásady podmíněného přístupu. Chcete-li zjistit, zda u účtu používaného pro službu Desktop Analytics došlo k chybám, zkontrolujte protokoly Azure AD-in v Azure portálu.

Další informace o podmíněném přístupu naleznete v [plánu nasazení podmíněného přístupu](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).