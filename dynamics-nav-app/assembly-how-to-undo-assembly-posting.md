---
title: How to Undo Assembly Posting
description: Sometimes you may need to undo a posted assembly order, for example when the order was posted with mistakes that must be corrected, or because it should not have been posted in the first place and must be rolled back.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3ba93dd182aa1591f5d24398d4b749942d38bb4b
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-undo-assembly-posting"></a><span data-ttu-id="b671b-103">How to: Undo Assembly Posting</span><span class="sxs-lookup"><span data-stu-id="b671b-103">How to: Undo Assembly Posting</span></span>
<span data-ttu-id="b671b-104">Sometimes you may need to undo a posted assembly order, for example when the order was posted with mistakes that must be corrected, or because it should not have been posted in the first place and must be rolled back.</span><span class="sxs-lookup"><span data-stu-id="b671b-104">Sometimes you may need to undo a posted assembly order, for example when the order was posted with mistakes that must be corrected, or because it should not have been posted in the first place and must be rolled back.</span></span>

<span data-ttu-id="b671b-105">When you undo a posted assembly order, a set of corrective item ledger entries is created to reverse the original entries.</span><span class="sxs-lookup"><span data-stu-id="b671b-105">When you undo a posted assembly order, a set of corrective item ledger entries is created to reverse the original entries.</span></span> <span data-ttu-id="b671b-106">Each positive output entry for the assembly item is reversed by a negative output entry.</span><span class="sxs-lookup"><span data-stu-id="b671b-106">Each positive output entry for the assembly item is reversed by a negative output entry.</span></span> <span data-ttu-id="b671b-107">Each negative consumption entry for an assembly component is reversed by a positive consumption entry.</span><span class="sxs-lookup"><span data-stu-id="b671b-107">Each negative consumption entry for an assembly component is reversed by a positive consumption entry.</span></span> <span data-ttu-id="b671b-108">Fixed cost application is automatically created between the corrective and original entries to ensure exact cost reversal.</span><span class="sxs-lookup"><span data-stu-id="b671b-108">Fixed cost application is automatically created between the corrective and original entries to ensure exact cost reversal.</span></span>  

<span data-ttu-id="b671b-109">When you undo a fully posted assembly order, then you can choose to recreate the assembly order to its original state, for example to make corrections before reposting it.</span><span class="sxs-lookup"><span data-stu-id="b671b-109">When you undo a fully posted assembly order, then you can choose to recreate the assembly order to its original state, for example to make corrections before reposting it.</span></span> <span data-ttu-id="b671b-110">Alternatively, you can choose to not recreate the assembly order.</span><span class="sxs-lookup"><span data-stu-id="b671b-110">Alternatively, you can choose to not recreate the assembly order.</span></span>  

<span data-ttu-id="b671b-111">When you undo a partially posted assembly order, then all affected quantity fields, such as the **Assembled Quantity**, **Consumed Quantity**, and **Remaining Quantity** fields are restored to the values they had before the posting in question.</span><span class="sxs-lookup"><span data-stu-id="b671b-111">When you undo a partially posted assembly order, then all affected quantity fields, such as the **Assembled Quantity**, **Consumed Quantity**, and **Remaining Quantity** fields are restored to the values they had before the posting in question.</span></span>  

<span data-ttu-id="b671b-112">To recreate or restore assembly orders, the following conditions must apply to the assembly item that was output in the original posting:</span><span class="sxs-lookup"><span data-stu-id="b671b-112">To recreate or restore assembly orders, the following conditions must apply to the assembly item that was output in the original posting:</span></span>  

-   <span data-ttu-id="b671b-113">It must still be in inventory, that is, it is not sold or otherwise consumed by outbound transactions.</span><span class="sxs-lookup"><span data-stu-id="b671b-113">It must still be in inventory, that is, it is not sold or otherwise consumed by outbound transactions.</span></span>  
-   <span data-ttu-id="b671b-114">It must not be reserved.</span><span class="sxs-lookup"><span data-stu-id="b671b-114">It must not be reserved.</span></span>  
-   <span data-ttu-id="b671b-115">It must exist in the bin that it was output to.</span><span class="sxs-lookup"><span data-stu-id="b671b-115">It must exist in the bin that it was output to.</span></span>  

<span data-ttu-id="b671b-116">In addition, existing assembly orders can only be restored if the number of lines and the sequence of lines on the original assembly order are not changed.</span><span class="sxs-lookup"><span data-stu-id="b671b-116">In addition, existing assembly orders can only be restored if the number of lines and the sequence of lines on the original assembly order are not changed.</span></span>  

> [!TIP]  
>  <span data-ttu-id="b671b-117">To solve conflicts due to line changes, you can manually revert the changes on the lines in question before undoing the related posted assembly order.</span><span class="sxs-lookup"><span data-stu-id="b671b-117">To solve conflicts due to line changes, you can manually revert the changes on the lines in question before undoing the related posted assembly order.</span></span> <span data-ttu-id="b671b-118">Alternatively, you can post the assembly order fully and then select to recreate it when undoing the posting.</span><span class="sxs-lookup"><span data-stu-id="b671b-118">Alternatively, you can post the assembly order fully and then select to recreate it when undoing the posting.</span></span>  

<span data-ttu-id="b671b-119">The following procedure describes how to undo posted assembly orders where the items were assembled to stock.</span><span class="sxs-lookup"><span data-stu-id="b671b-119">The following procedure describes how to undo posted assembly orders where the items were assembled to stock.</span></span> <span data-ttu-id="b671b-120">If you want to undo posted assembly orders where the items were assembled to a sales order, then you must use the **Undo Shipment** function on the posted shipment that relates to the posted assembly order.</span><span class="sxs-lookup"><span data-stu-id="b671b-120">If you want to undo posted assembly orders where the items were assembled to a sales order, then you must use the **Undo Shipment** function on the posted shipment that relates to the posted assembly order.</span></span> <span data-ttu-id="b671b-121">For more information, see [How to: Reverse Postings](finance-how-reverse-journal-posting.md).</span><span class="sxs-lookup"><span data-stu-id="b671b-121">For more information, see [How to: Reverse Postings](finance-how-reverse-journal-posting.md).</span></span> <span data-ttu-id="b671b-122">The undoing of the posted assembly order then happens automatically in the same way as described in this topic.</span><span class="sxs-lookup"><span data-stu-id="b671b-122">The undoing of the posted assembly order then happens automatically in the same way as described in this topic.</span></span>  

## <a name="to-undo-posting-of-an-assembly-order"></a><span data-ttu-id="b671b-123">To undo posting of an assembly order</span><span class="sxs-lookup"><span data-stu-id="b671b-123">To undo posting of an assembly order</span></span>  
1.  <span data-ttu-id="b671b-124">To undo a fully or partially posted assembly order, Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Assembly Orders**, and choose the related link.</span><span class="sxs-lookup"><span data-stu-id="b671b-124">To undo a fully or partially posted assembly order, Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Assembly Orders**, and choose the related link.</span></span>  

    <span data-ttu-id="b671b-125">The **Posted Assembly Orders** window opens showing one or more posted assembly orders that are posted from the assembly order in question.</span><span class="sxs-lookup"><span data-stu-id="b671b-125">The **Posted Assembly Orders** window opens showing one or more posted assembly orders that are posted from the assembly order in question.</span></span> <span data-ttu-id="b671b-126">Each partial posting creates a separate posted assembly order.</span><span class="sxs-lookup"><span data-stu-id="b671b-126">Each partial posting creates a separate posted assembly order.</span></span>  
2.  <span data-ttu-id="b671b-127">Open the posted assembly order that you want to undo, and then choose the **Undo Assembly** action.</span><span class="sxs-lookup"><span data-stu-id="b671b-127">Open the posted assembly order that you want to undo, and then choose the **Undo Assembly** action.</span></span>  

    <span data-ttu-id="b671b-128">If the posted assembly order that you want to undo relates to a fully posted assembly order that is now deleted, then you have the option to recreate it, typically because you want to reprocess it.</span><span class="sxs-lookup"><span data-stu-id="b671b-128">If the posted assembly order that you want to undo relates to a fully posted assembly order that is now deleted, then you have the option to recreate it, typically because you want to reprocess it.</span></span>  
3.  <span data-ttu-id="b671b-129">If you want to recreate the assembly order, choose the **Yes** button.</span><span class="sxs-lookup"><span data-stu-id="b671b-129">If you want to recreate the assembly order, choose the **Yes** button.</span></span> <span data-ttu-id="b671b-130">To undo the posting without recreating the related assembly order, choose the **No** button.</span><span class="sxs-lookup"><span data-stu-id="b671b-130">To undo the posting without recreating the related assembly order, choose the **No** button.</span></span>  

<span data-ttu-id="b671b-131">The **Reversed** field on the assembly order header changes to **Yes**.</span><span class="sxs-lookup"><span data-stu-id="b671b-131">The **Reversed** field on the assembly order header changes to **Yes**.</span></span> <span data-ttu-id="b671b-132">The assembly order posting is now reversed, and you can proceed to process the entire assembly order if you chose to recreate it or the open assembly order that you have restored to its original state.</span><span class="sxs-lookup"><span data-stu-id="b671b-132">The assembly order posting is now reversed, and you can proceed to process the entire assembly order if you chose to recreate it or the open assembly order that you have restored to its original state.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="b671b-133">To restore quantities from multiple partial postings in an assembly order, you must undo all the posted assembly orders in question by following steps 1 through 3 above for each posted assembly order.</span><span class="sxs-lookup"><span data-stu-id="b671b-133">To restore quantities from multiple partial postings in an assembly order, you must undo all the posted assembly orders in question by following steps 1 through 3 above for each posted assembly order.</span></span>  

## <a name="see-also"></a><span data-ttu-id="b671b-134">See Also</span><span class="sxs-lookup"><span data-stu-id="b671b-134">See Also</span></span>  
[<span data-ttu-id="b671b-135">Assembly Management</span><span class="sxs-lookup"><span data-stu-id="b671b-135">Assembly Management</span></span>](assembly-assemble-items.md)  
[<span data-ttu-id="b671b-136">How to: Reverse Postings</span><span class="sxs-lookup"><span data-stu-id="b671b-136">How to: Reverse Postings</span></span>](finance-how-reverse-journal-posting.md)  
<span data-ttu-id="b671b-137">[How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md)  </span><span class="sxs-lookup"><span data-stu-id="b671b-137">[How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md)  </span></span>  
[<span data-ttu-id="b671b-138">How to: Work with Bills of Material</span><span class="sxs-lookup"><span data-stu-id="b671b-138">How to: Work with Bills of Material</span></span>](inventory-how-work-BOMs.md)  
[<span data-ttu-id="b671b-139">Inventory</span><span class="sxs-lookup"><span data-stu-id="b671b-139">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="b671b-140">Design Details: Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="b671b-140">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="b671b-141">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b671b-141">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
