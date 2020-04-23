---
title: Velké seznamy SharePointu
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "407"
- "530001"
ms.assetid: ee07bf74-7aeb-4c47-8f5d-f496d6c09d79
ms.openlocfilehash: e85686788c60d365a00970e9ffe58e97512894a3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767278"
---
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a><span data-ttu-id="96a4b-102">Práce s velkými seznamy a knihovnami v SharePointu</span><span class="sxs-lookup"><span data-stu-id="96a4b-102">Work with large lists and libraries in SharePoint</span></span>

<span data-ttu-id="96a4b-103">SharePoint seznamy a knihovny může obsahovat až 30 milionů položek, ale pokud mají více než 5 000 položek, může se při pokusu o práci s nimi zobrazit prahovou hodnotu zobrazení seznamu.</span><span class="sxs-lookup"><span data-stu-id="96a4b-103">SharePoint lists and libraries can contain up to 30 million items, but when they have more than 5,000 items, you might see a List View Threshold error when you try to work with them.</span></span> <span data-ttu-id="96a4b-104">Tato mezní hodnota slouží k udržování výkonu služby.</span><span class="sxs-lookup"><span data-stu-id="96a4b-104">This threshold is in place to maintain performance of the service.</span></span> <span data-ttu-id="96a4b-105">Nejde změnit.</span><span class="sxs-lookup"><span data-stu-id="96a4b-105">It can't be changed.</span></span> <span data-ttu-id="96a4b-106">Chcete-li se vyhnout dosažení této prahové hodnoty:</span><span class="sxs-lookup"><span data-stu-id="96a4b-106">To avoid hitting this threshold:</span></span>

<span data-ttu-id="96a4b-107">**Používejte moderní**</span><span class="sxs-lookup"><span data-stu-id="96a4b-107">**Use modern**</span></span>

<span data-ttu-id="96a4b-108">Pohledy zobrazující mnoho položek fungují nejlépe v moderním prostředí.</span><span class="sxs-lookup"><span data-stu-id="96a4b-108">Views showing many items work best in the modern experience.</span></span> <span data-ttu-id="96a4b-109">[Použijte moderní prostředí,](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) abyste se vyhnuli chybám, které se mohou zobrazit v klasickém prostředí.</span><span class="sxs-lookup"><span data-stu-id="96a4b-109">[Use the modern experience](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) to avoid errors you might see in the classic experience.</span></span>

<span data-ttu-id="96a4b-110">**Přidání indexů**</span><span class="sxs-lookup"><span data-stu-id="96a4b-110">**Add indexes**</span></span>

<span data-ttu-id="96a4b-111">Pokud filtrujete nebo řadíte podle sloupce, který nemá index, může se zobrazit chybová zpráva.</span><span class="sxs-lookup"><span data-stu-id="96a4b-111">When you filter or sort by a column that doesn't have an index, you might see an error message.</span></span> <span data-ttu-id="96a4b-112">[Přidejte index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) ručně z **nastavení seznamu** v nabídce nastavení a potom **indexované sloupce**.</span><span class="sxs-lookup"><span data-stu-id="96a4b-112">[Add an index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manually from **List Settings** in the settings menu, then **Indexed Columns**.</span></span>

<span data-ttu-id="96a4b-113">**Úprava zobrazení seznamu**</span><span class="sxs-lookup"><span data-stu-id="96a4b-113">**Edit the list view**</span></span>

<span data-ttu-id="96a4b-114">Pokud při práci s rozsáhlým seznamem dojde k chybě, [upravte zobrazení seznamu](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span><span class="sxs-lookup"><span data-stu-id="96a4b-114">If an error occurs when working with a large list, [edit your list view](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span></span>

<span data-ttu-id="96a4b-115">Následující čtyři změny odstraní chyby prahové hodnoty zobrazení seznamu.</span><span class="sxs-lookup"><span data-stu-id="96a4b-115">The following four changes will remove list view threshold errors.</span></span> <span data-ttu-id="96a4b-116">Proveďte všechny čtyři změny, abyste odstranili všechny chyby.</span><span class="sxs-lookup"><span data-stu-id="96a4b-116">Make all four changes to remove all errors.</span></span> <span data-ttu-id="96a4b-117">Pokud se stále zobrazuje počet chyb, [zaškrtněte políčko Spravovat velké seznamy a knihovny](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span><span class="sxs-lookup"><span data-stu-id="96a4b-117">If you are still getting errors, check [Manage large lists and libraries](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span></span>

1. <span data-ttu-id="96a4b-118">Vyberte **Žádné** z obou **První řazení podle sloupce** a Potom **seřadit podle sloupce**.</span><span class="sxs-lookup"><span data-stu-id="96a4b-118">Select **None** from both **First sort by the column** and **Then sort by the column**.</span></span>
2. <span data-ttu-id="96a4b-119">Vyberte **Žádné** z **obou První skupina podle sloupce** a potom **seskupit podle sloupce**.</span><span class="sxs-lookup"><span data-stu-id="96a4b-119">Select **None** from both **First group by the column** and **Then group by the column**.</span></span>
3. <span data-ttu-id="96a4b-120">V části **Součty** vyberte **Žádné** pro všechny sloupce.</span><span class="sxs-lookup"><span data-stu-id="96a4b-120">Select **None** for all columns in the **Totals** section.</span></span>
4. <span data-ttu-id="96a4b-121">Odznačte všechny sloupce kromě jednoho pro zobrazení v části **Sloupce.**</span><span class="sxs-lookup"><span data-stu-id="96a4b-121">Deselect all but one column for display from the **Columns** section.</span></span>

