---
title: How to Plan Picks in Worksheets
description: If your warehouse is set up to require both pick and shipment processing, the warehouse can choose to operate so that the lines on shipment documents are not automatically transformed into pick instructions, but are made available instead to the pick worksheet.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9483eda38a9db7cd50d7167b45d0c6b6d21ace8c
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-plan-picks-in-worksheets"></a><span data-ttu-id="5b16f-103">How to: Plan Picks in Worksheets</span><span class="sxs-lookup"><span data-stu-id="5b16f-103">How to: Plan Picks in Worksheets</span></span>
<span data-ttu-id="5b16f-104">If your warehouse is set up to require both pick and shipment processing, the warehouse can choose to operate so that the lines on shipment documents are not automatically transformed into pick instructions, but are made available instead to the pick worksheet.</span><span class="sxs-lookup"><span data-stu-id="5b16f-104">If your warehouse is set up to require both pick and shipment processing, the warehouse can choose to operate so that the lines on shipment documents are not automatically transformed into pick instructions, but are made available instead to the pick worksheet.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="5b16f-105">If warehouse pick instructions have already been created, and you would like to combine them into one efficient pick instruction, then you must delete the individual warehouse picks.</span><span class="sxs-lookup"><span data-stu-id="5b16f-105">If warehouse pick instructions have already been created, and you would like to combine them into one efficient pick instruction, then you must delete the individual warehouse picks.</span></span> <span data-ttu-id="5b16f-106">The lines to be picked can now be listed in the worksheet.</span><span class="sxs-lookup"><span data-stu-id="5b16f-106">The lines to be picked can now be listed in the worksheet.</span></span>  

<span data-ttu-id="5b16f-107">In the pick worksheet, you can set up pick lists for employees that minimise the time the employee has to move about the warehouse picking items.</span><span class="sxs-lookup"><span data-stu-id="5b16f-107">In the pick worksheet, you can set up pick lists for employees that minimize the time the employee has to move about the warehouse picking items.</span></span> <span data-ttu-id="5b16f-108">There are fields that contain information about the quantities of items available in the cross-dock bins. This is useful in cross docking situations to plan your work assignments, because the program will always propose a pick from a cross-dock bin before any other bin, regardless of the unit of measure.</span><span class="sxs-lookup"><span data-stu-id="5b16f-108">There are fields that contain information about the quantities of items available in the cross-dock bins. This is useful in cross docking situations to plan your work assignments, because the program will always propose a pick from a cross-dock bin before any other bin, regardless of the unit of measure.</span></span> <span data-ttu-id="5b16f-109">The lines in the worksheet can come from a number of source documents and be sorted by item, shelf number, source document, due date, or ship-to address.</span><span class="sxs-lookup"><span data-stu-id="5b16f-109">The lines in the worksheet can come from a number of source documents and be sorted by item, shelf number, source document, due date, or ship-to address.</span></span>  

<span data-ttu-id="5b16f-110">If you sort by due date, you can choose to delete from the worksheet all lines except those that need immediate attention.</span><span class="sxs-lookup"><span data-stu-id="5b16f-110">If you sort by due date, you can choose to delete from the worksheet all lines except those that need immediate attention.</span></span> <span data-ttu-id="5b16f-111">The less urgent lines are not deleted as such, but just sent back to the **Pick Selection** worksheet.</span><span class="sxs-lookup"><span data-stu-id="5b16f-111">The less urgent lines are not deleted as such, but just sent back to the **Pick Selection** worksheet.</span></span> <span data-ttu-id="5b16f-112">When you create the pick, the lines have already been sorted by due date, and you can choose to assign the pick to a particular employee.</span><span class="sxs-lookup"><span data-stu-id="5b16f-112">When you create the pick, the lines have already been sorted by due date, and you can choose to assign the pick to a particular employee.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="5b16f-113">Picking for warehouse shipment of items that are assembled to the sales order being shipped follows the same steps as for regular warehouse picks for shipment, as described in this topic.</span><span class="sxs-lookup"><span data-stu-id="5b16f-113">Picking for warehouse shipment of items that are assembled to the sales order being shipped follows the same steps as for regular warehouse picks for shipment, as described in this topic.</span></span> <span data-ttu-id="5b16f-114">However, the number of pick lines per quantity to ship may be many to one because you pick the components, not the assembly item.</span><span class="sxs-lookup"><span data-stu-id="5b16f-114">However, the number of pick lines per quantity to ship may be many to one because you pick the components, not the assembly item.</span></span>  
>   
>  <span data-ttu-id="5b16f-115">The warehouse pick lines are created for the value in the **Remaining Quantity** field on the lines of the assembly order that is linked to the sales order line that is being shipped.</span><span class="sxs-lookup"><span data-stu-id="5b16f-115">The warehouse pick lines are created for the value in the **Remaining Quantity** field on the lines of the assembly order that is linked to the sales order line that is being shipped.</span></span> <span data-ttu-id="5b16f-116">This ensures that all components are picked in one action.</span><span class="sxs-lookup"><span data-stu-id="5b16f-116">This ensures that all components are picked in one action.</span></span>  
>   
>  <span data-ttu-id="5b16f-117">For more information, see “Handling Assemble-to-Order Items in Warehouse Shipments” in Warehouse Shipment.</span><span class="sxs-lookup"><span data-stu-id="5b16f-117">For more information, see “Handling Assemble-to-Order Items in Warehouse Shipments” in Warehouse Shipment.</span></span>  
>   
>  <span data-ttu-id="5b16f-118">For information about picking components for assembly orders generally, including situations where the assembly item is not due on a sales shipment, see [How to: Pick for Assembly or Production in Advanced Warehouse Configurations](warehouse-how-to-pick-for-internal-operations-in-advanced-warehousing.md).</span><span class="sxs-lookup"><span data-stu-id="5b16f-118">For information about picking components for assembly orders generally, including situations where the assembly item is not due on a sales shipment, see [How to: Pick for Assembly or Production in Advanced Warehouse Configurations](warehouse-how-to-pick-for-internal-operations-in-advanced-warehousing.md).</span></span>  

## <a name="to-plan-picks-in-the-worksheet"></a><span data-ttu-id="5b16f-119">To plan picks in the worksheet</span><span class="sxs-lookup"><span data-stu-id="5b16f-119">To plan picks in the worksheet</span></span>  
1.  <span data-ttu-id="5b16f-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Pick Worksheet**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5b16f-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Pick Worksheet**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="5b16f-121">Choose the **Get Whse. Documents** action.</span><span class="sxs-lookup"><span data-stu-id="5b16f-121">Choose the **Get Whse. Documents** action.</span></span>  
3.  <span data-ttu-id="5b16f-122">Select the shipments for which you want to prepare a pick.</span><span class="sxs-lookup"><span data-stu-id="5b16f-122">Select the shipments for which you want to prepare a pick.</span></span> <span data-ttu-id="5b16f-123">You can now sort the lines to some degree, but the sorting you do here will not be carried through to the pick instruction.</span><span class="sxs-lookup"><span data-stu-id="5b16f-123">You can now sort the lines to some degree, but the sorting you do here will not be carried through to the pick instruction.</span></span> <span data-ttu-id="5b16f-124">You can also delete some of the lines to make a more effective pick.</span><span class="sxs-lookup"><span data-stu-id="5b16f-124">You can also delete some of the lines to make a more effective pick.</span></span> <span data-ttu-id="5b16f-125">For instance, if there are a number of lines with items in cross-dock bins, you might want to create a pick for all the lines associated with these lines.</span><span class="sxs-lookup"><span data-stu-id="5b16f-125">For instance, if there are a number of lines with items in cross-dock bins, you might want to create a pick for all the lines associated with these lines.</span></span> <span data-ttu-id="5b16f-126">The cross-docked items will be shipped, along with the other items on the shipments, and the cross-dock bins will have space for more incoming items.</span><span class="sxs-lookup"><span data-stu-id="5b16f-126">The cross-docked items will be shipped, along with the other items on the shipments, and the cross-dock bins will have space for more incoming items.</span></span>  
4.  <span data-ttu-id="5b16f-127">Choose the **Create Pick** action, and fill in the **Create Pick** request window.</span><span class="sxs-lookup"><span data-stu-id="5b16f-127">Choose the **Create Pick** action, and fill in the **Create Pick** request window.</span></span> <span data-ttu-id="5b16f-128">The sorting you request here will order the pick lines you create.</span><span class="sxs-lookup"><span data-stu-id="5b16f-128">The sorting you request here will order the pick lines you create.</span></span> <span data-ttu-id="5b16f-129">For example, you can create one pick for each zone and sort the lines by bin ranking within each pick.</span><span class="sxs-lookup"><span data-stu-id="5b16f-129">For example, you can create one pick for each zone and sort the lines by bin ranking within each pick.</span></span>  
5.  <span data-ttu-id="5b16f-130">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Picks**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5b16f-130">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Picks**, and then choose the related link.</span></span> <span data-ttu-id="5b16f-131">The **Picks** window opens.</span><span class="sxs-lookup"><span data-stu-id="5b16f-131">The **Picks** window opens.</span></span>  
6.  <span data-ttu-id="5b16f-132">You can now find the pick assignment you just created by selecting the pick with the highest number.</span><span class="sxs-lookup"><span data-stu-id="5b16f-132">You can now find the pick assignment you just created by selecting the pick with the highest number.</span></span>  
7.  <span data-ttu-id="5b16f-133">In the pick, you can still alter, if necessary, the assigned user ID and the way the lines are sorted.</span><span class="sxs-lookup"><span data-stu-id="5b16f-133">In the pick, you can still alter, if necessary, the assigned user ID and the way the lines are sorted.</span></span>  
8.  <span data-ttu-id="5b16f-134">Choose the **Print** action to print the pick instructions.</span><span class="sxs-lookup"><span data-stu-id="5b16f-134">Choose the **Print** action to print the pick instructions.</span></span>  
9. <span data-ttu-id="5b16f-135">After you have performed the pick, choose the **Register** action.</span><span class="sxs-lookup"><span data-stu-id="5b16f-135">After you have performed the pick, choose the **Register** action.</span></span>  

<span data-ttu-id="5b16f-136">If the bins have been numbered in a way that mirrors the physical layout of the warehouse, the lines sorted by bin code allow the picker to pick for a number of shipments in one round of the warehouse.</span><span class="sxs-lookup"><span data-stu-id="5b16f-136">If the bins have been numbered in a way that mirrors the physical layout of the warehouse, the lines sorted by bin code allow the picker to pick for a number of shipments in one round of the warehouse.</span></span> <span data-ttu-id="5b16f-137">The worker takes the required number of items for each shipment line out of each bin and places them along with the other items for the particular shipment.</span><span class="sxs-lookup"><span data-stu-id="5b16f-137">The worker takes the required number of items for each shipment line out of each bin and places them along with the other items for the particular shipment.</span></span> <span data-ttu-id="5b16f-138">A picker can save a great deal of time by picking for several shipments in one visit to a bin.</span><span class="sxs-lookup"><span data-stu-id="5b16f-138">A picker can save a great deal of time by picking for several shipments in one visit to a bin.</span></span>  

<span data-ttu-id="5b16f-139">Another effective sorting option is bin ranking, if the physical layout of the warehouse is more according to bin ranking than bin code.</span><span class="sxs-lookup"><span data-stu-id="5b16f-139">Another effective sorting option is bin ranking, if the physical layout of the warehouse is more according to bin ranking than bin code.</span></span>  

<span data-ttu-id="5b16f-140">In the pick worksheet, you can also sort by ship-to address, enabling you to assemble and ship the orders to far-away customers first.</span><span class="sxs-lookup"><span data-stu-id="5b16f-140">In the pick worksheet, you can also sort by ship-to address, enabling you to assemble and ship the orders to far-away customers first.</span></span>  

## <a name="see-also"></a><span data-ttu-id="5b16f-141">See Also</span><span class="sxs-lookup"><span data-stu-id="5b16f-141">See Also</span></span>
[<span data-ttu-id="5b16f-142">Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="5b16f-142">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="5b16f-143">Inventory</span><span class="sxs-lookup"><span data-stu-id="5b16f-143">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="5b16f-144">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="5b16f-144">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="5b16f-145">[Assembly Management](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="5b16f-145">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="5b16f-146">Design Details: Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="5b16f-146">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="5b16f-147">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="5b16f-147">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
