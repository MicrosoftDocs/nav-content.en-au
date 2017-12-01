---
title: Create a Sales Order Linked to a Purchase Order for a Direct Shipment
description: Describes how to create a sales order linked to a purchase order to enable shipment directly from the vendor to the customer.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: direct shipment
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 6be69a96ad6df401b3fedf5e0b81df870a1eedfc
ms.contentlocale: en-au
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="336de-103">How to: Make Drop Shipments</span><span class="sxs-lookup"><span data-stu-id="336de-103">How to: Make Drop Shipments</span></span>
<span data-ttu-id="336de-104">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span><span class="sxs-lookup"><span data-stu-id="336de-104">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="336de-105">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span><span class="sxs-lookup"><span data-stu-id="336de-105">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="336de-106">field, you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span><span class="sxs-lookup"><span data-stu-id="336de-106">field, you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="336de-107">To create a sales order for drop shipment</span><span class="sxs-lookup"><span data-stu-id="336de-107">To create a sales order for drop shipment</span></span>
<span data-ttu-id="336de-108">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span><span class="sxs-lookup"><span data-stu-id="336de-108">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="336de-109">Create a sales order for an item.</span><span class="sxs-lookup"><span data-stu-id="336de-109">Create a sales order for an item.</span></span> <span data-ttu-id="336de-110">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="336de-110">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="336de-111">On the sales order line for the drop shipment, select the **Drop Shipment** check box.</span><span class="sxs-lookup"><span data-stu-id="336de-111">On the sales order line for the drop shipment, select the **Drop Shipment** check box.</span></span> <span data-ttu-id="336de-112">Use the **Choose Columns** function if the field is not visible.</span><span class="sxs-lookup"><span data-stu-id="336de-112">Use the **Choose Columns** function if the field is not visible.</span></span> <span data-ttu-id="336de-113">For more information, see [User Personalization](ui-user-personalization.md).</span><span class="sxs-lookup"><span data-stu-id="336de-113">For more information, see [User Personalization](ui-user-personalization.md).</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="336de-114">To create the purchase order for drop shipment</span><span class="sxs-lookup"><span data-stu-id="336de-114">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="336de-115">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span><span class="sxs-lookup"><span data-stu-id="336de-115">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="336de-116">Create a purchase order.</span><span class="sxs-lookup"><span data-stu-id="336de-116">Create a purchase order.</span></span> <span data-ttu-id="336de-117">Do not fill any fields on the lines.</span><span class="sxs-lookup"><span data-stu-id="336de-117">Do not fill any fields on the lines.</span></span> <span data-ttu-id="336de-118">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="336de-118">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="336de-119">In the **Sell-to Customer No.**</span><span class="sxs-lookup"><span data-stu-id="336de-119">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="336de-120">field, select the customer that you are selling to.</span><span class="sxs-lookup"><span data-stu-id="336de-120">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="336de-121">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span><span class="sxs-lookup"><span data-stu-id="336de-121">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="336de-122">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span><span class="sxs-lookup"><span data-stu-id="336de-122">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="336de-123">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="336de-123">Choose the **OK** button.</span></span>

<span data-ttu-id="336de-124">The line information from the sales order is inserted on the purchase order line(s).</span><span class="sxs-lookup"><span data-stu-id="336de-124">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="336de-125">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span><span class="sxs-lookup"><span data-stu-id="336de-125">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="336de-126">To view the linked purchase order from the sales order</span><span class="sxs-lookup"><span data-stu-id="336de-126">To view the linked purchase order from the sales order</span></span>
* <span data-ttu-id="336de-127">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span><span class="sxs-lookup"><span data-stu-id="336de-127">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="336de-128">To post a drop shipment</span><span class="sxs-lookup"><span data-stu-id="336de-128">To post a drop shipment</span></span>
<span data-ttu-id="336de-129">After the vendor ships the items, you can post the sales order as shipped.</span><span class="sxs-lookup"><span data-stu-id="336de-129">After the vendor ships the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="336de-130">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span><span class="sxs-lookup"><span data-stu-id="336de-130">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>

1. <span data-ttu-id="336de-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales orders**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="336de-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="336de-132">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span><span class="sxs-lookup"><span data-stu-id="336de-132">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="336de-133">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span><span class="sxs-lookup"><span data-stu-id="336de-133">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
4. <span data-ttu-id="336de-134">Choose the **Post** or **Post and Send** action.</span><span class="sxs-lookup"><span data-stu-id="336de-134">Choose the **Post** or **Post and Send** action.</span></span>
5. <span data-ttu-id="336de-135">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span><span class="sxs-lookup"><span data-stu-id="336de-135">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="336de-136">See Also</span><span class="sxs-lookup"><span data-stu-id="336de-136">See Also</span></span>
<span data-ttu-id="336de-137">[How to: Create Special Orders](sales-how-to-create-special-orders.md)|</span><span class="sxs-lookup"><span data-stu-id="336de-137">[How to: Create Special Orders](sales-how-to-create-special-orders.md)|</span></span>  
[<span data-ttu-id="336de-138">How to: Sell Products</span><span class="sxs-lookup"><span data-stu-id="336de-138">How to: Sell Products</span></span>](sales-how-sell-products.md)  
[<span data-ttu-id="336de-139">How to: Record Purchases</span><span class="sxs-lookup"><span data-stu-id="336de-139">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="336de-140">Sales</span><span class="sxs-lookup"><span data-stu-id="336de-140">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="336de-141">Inventory</span><span class="sxs-lookup"><span data-stu-id="336de-141">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="336de-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="336de-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

