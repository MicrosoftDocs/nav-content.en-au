---
title: Design Details - Rounding
description: Rounding residuals can occur when you value the cost of an inventory decrease that is measured in a different quantity than the corresponding inventory increase. Rounding residuals are calculated for all costing methods when you run the **Adjust Cost - Item Entries** batch job.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2a5187811051ee2bd32ec44b22876f0a468225e2
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-rounding"></a><span data-ttu-id="c683e-104">Design Details: Rounding</span><span class="sxs-lookup"><span data-stu-id="c683e-104">Design Details: Rounding</span></span>
<span data-ttu-id="c683e-105">Rounding residuals can occur when you value the cost of an inventory decrease that is measured in a different quantity than the corresponding inventory increase.</span><span class="sxs-lookup"><span data-stu-id="c683e-105">Rounding residuals can occur when you value the cost of an inventory decrease that is measured in a different quantity than the corresponding inventory increase.</span></span> <span data-ttu-id="c683e-106">Rounding residuals are calculated for all costing methods when you run the **Adjust Cost - Item Entries** batch job.</span><span class="sxs-lookup"><span data-stu-id="c683e-106">Rounding residuals are calculated for all costing methods when you run the **Adjust Cost - Item Entries** batch job.</span></span>  

 <span data-ttu-id="c683e-107">When you use the average costing method, the rounding residual is calculated and recorded on a cumulative, entry-by-entry basis.</span><span class="sxs-lookup"><span data-stu-id="c683e-107">When you use the average costing method, the rounding residual is calculated and recorded on a cumulative, entry-by-entry basis.</span></span>  

 <span data-ttu-id="c683e-108">When you use a costing method other than Average, the rounding residual is calculated when the inventory increase has been fully applied, that is when the remaining quantity for the inventory increase is equal to zero.</span><span class="sxs-lookup"><span data-stu-id="c683e-108">When you use a costing method other than Average, the rounding residual is calculated when the inventory increase has been fully applied, that is when the remaining quantity for the inventory increase is equal to zero.</span></span> <span data-ttu-id="c683e-109">A separate entry is then created for the rounding residual, and the posting date on this rounding entry is the posting date of the last invoiced value entry of the inventory increase.</span><span class="sxs-lookup"><span data-stu-id="c683e-109">A separate entry is then created for the rounding residual, and the posting date on this rounding entry is the posting date of the last invoiced value entry of the inventory increase.</span></span>  

## <a name="example"></a><span data-ttu-id="c683e-110">Example</span><span class="sxs-lookup"><span data-stu-id="c683e-110">Example</span></span>  
 <span data-ttu-id="c683e-111">The following example illustrates how different rounding residuals are handled for the average costing method and non-Average costing method, respectively.</span><span class="sxs-lookup"><span data-stu-id="c683e-111">The following example illustrates how different rounding residuals are handled for the average costing method and non-Average costing method, respectively.</span></span> <span data-ttu-id="c683e-112">In both cases, the **Adjust Cost - Item Entries** batch job has been run.</span><span class="sxs-lookup"><span data-stu-id="c683e-112">In both cases, the **Adjust Cost - Item Entries** batch job has been run.</span></span>  

 <span data-ttu-id="c683e-113">The following table shows the item ledger entries that the example is based on.</span><span class="sxs-lookup"><span data-stu-id="c683e-113">The following table shows the item ledger entries that the example is based on.</span></span>  

|<span data-ttu-id="c683e-114">Posting Date</span><span class="sxs-lookup"><span data-stu-id="c683e-114">Posting Date</span></span>|<span data-ttu-id="c683e-115">Quantity</span><span class="sxs-lookup"><span data-stu-id="c683e-115">Quantity</span></span>|<span data-ttu-id="c683e-116">Entry No.</span><span class="sxs-lookup"><span data-stu-id="c683e-116">Entry No.</span></span>|  
|------------------|--------------|---------------|  
|<span data-ttu-id="c683e-117">01-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-117">01-01-20</span></span>|<span data-ttu-id="c683e-118">3</span><span class="sxs-lookup"><span data-stu-id="c683e-118">3</span></span>|<span data-ttu-id="c683e-119">1</span><span class="sxs-lookup"><span data-stu-id="c683e-119">1</span></span>|  
|<span data-ttu-id="c683e-120">02-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-120">02-01-20</span></span>|<span data-ttu-id="c683e-121">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-121">-1</span></span>|<span data-ttu-id="c683e-122">2</span><span class="sxs-lookup"><span data-stu-id="c683e-122">2</span></span>|  
|<span data-ttu-id="c683e-123">03-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-123">03-01-20</span></span>|<span data-ttu-id="c683e-124">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-124">-1</span></span>|<span data-ttu-id="c683e-125">3</span><span class="sxs-lookup"><span data-stu-id="c683e-125">3</span></span>|  
|<span data-ttu-id="c683e-126">04-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-126">04-01-20</span></span>|<span data-ttu-id="c683e-127">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-127">-1</span></span>|<span data-ttu-id="c683e-128">4</span><span class="sxs-lookup"><span data-stu-id="c683e-128">4</span></span>|  

 <span data-ttu-id="c683e-129">For an item using the Average costing method, the rounding residual (1/300) is calculated with the first decrease (entry number 2) and is carried forward to entry number 3.</span><span class="sxs-lookup"><span data-stu-id="c683e-129">For an item using the Average costing method, the rounding residual (1/300) is calculated with the first decrease (entry number 2) and is carried forward to entry number 3.</span></span> <span data-ttu-id="c683e-130">Therefore, entry number 3 is valued at –3.34.</span><span class="sxs-lookup"><span data-stu-id="c683e-130">Therefore, entry number 3 is valued at –3.34.</span></span>  

 <span data-ttu-id="c683e-131">The following table shows the resulting value entries.</span><span class="sxs-lookup"><span data-stu-id="c683e-131">The following table shows the resulting value entries.</span></span>  

|<span data-ttu-id="c683e-132">Posting Date</span><span class="sxs-lookup"><span data-stu-id="c683e-132">Posting Date</span></span>|<span data-ttu-id="c683e-133">Quantity</span><span class="sxs-lookup"><span data-stu-id="c683e-133">Quantity</span></span>|<span data-ttu-id="c683e-134">Cost Amount (Actual)</span><span class="sxs-lookup"><span data-stu-id="c683e-134">Cost Amount (Actual)</span></span>|<span data-ttu-id="c683e-135">Item Ledger Entry No.</span><span class="sxs-lookup"><span data-stu-id="c683e-135">Item Ledger Entry No.</span></span>|<span data-ttu-id="c683e-136">Entry No.</span><span class="sxs-lookup"><span data-stu-id="c683e-136">Entry No.</span></span>|  
|------------------|--------------|----------------------------|---------------------------|---------------|  
|<span data-ttu-id="c683e-137">01-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-137">01-01-20</span></span>|<span data-ttu-id="c683e-138">3</span><span class="sxs-lookup"><span data-stu-id="c683e-138">3</span></span>|<span data-ttu-id="c683e-139">10</span><span class="sxs-lookup"><span data-stu-id="c683e-139">10</span></span>|<span data-ttu-id="c683e-140">1</span><span class="sxs-lookup"><span data-stu-id="c683e-140">1</span></span>|<span data-ttu-id="c683e-141">1</span><span class="sxs-lookup"><span data-stu-id="c683e-141">1</span></span>|  
|<span data-ttu-id="c683e-142">02-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-142">02-01-20</span></span>|<span data-ttu-id="c683e-143">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-143">-1</span></span>|<span data-ttu-id="c683e-144">-3.33</span><span class="sxs-lookup"><span data-stu-id="c683e-144">-3.33</span></span>|<span data-ttu-id="c683e-145">2</span><span class="sxs-lookup"><span data-stu-id="c683e-145">2</span></span>|<span data-ttu-id="c683e-146">2</span><span class="sxs-lookup"><span data-stu-id="c683e-146">2</span></span>|  
|<span data-ttu-id="c683e-147">03-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-147">03-01-20</span></span>|<span data-ttu-id="c683e-148">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-148">-1</span></span>|<span data-ttu-id="c683e-149">-3.34</span><span class="sxs-lookup"><span data-stu-id="c683e-149">-3.34</span></span>|<span data-ttu-id="c683e-150">3</span><span class="sxs-lookup"><span data-stu-id="c683e-150">3</span></span>|<span data-ttu-id="c683e-151">3</span><span class="sxs-lookup"><span data-stu-id="c683e-151">3</span></span>|  
|<span data-ttu-id="c683e-152">04-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-152">04-01-20</span></span>|<span data-ttu-id="c683e-153">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-153">-1</span></span>|<span data-ttu-id="c683e-154">-3.33</span><span class="sxs-lookup"><span data-stu-id="c683e-154">-3.33</span></span>|<span data-ttu-id="c683e-155">4</span><span class="sxs-lookup"><span data-stu-id="c683e-155">4</span></span>|<span data-ttu-id="c683e-156">4</span><span class="sxs-lookup"><span data-stu-id="c683e-156">4</span></span>|  

 <span data-ttu-id="c683e-157">For an item using a costing method other than Average, the rounding residual (0.01) is calculated when the remaining quantity for the inventory increase is zero.</span><span class="sxs-lookup"><span data-stu-id="c683e-157">For an item using a costing method other than Average, the rounding residual (0.01) is calculated when the remaining quantity for the inventory increase is zero.</span></span> <span data-ttu-id="c683e-158">The rounding residual has a separate entry (number 5).</span><span class="sxs-lookup"><span data-stu-id="c683e-158">The rounding residual has a separate entry (number 5).</span></span>  

 <span data-ttu-id="c683e-159">The following table shows the resulting value entries.</span><span class="sxs-lookup"><span data-stu-id="c683e-159">The following table shows the resulting value entries.</span></span>  

|<span data-ttu-id="c683e-160">Posting Date</span><span class="sxs-lookup"><span data-stu-id="c683e-160">Posting Date</span></span>|<span data-ttu-id="c683e-161">Quantity</span><span class="sxs-lookup"><span data-stu-id="c683e-161">Quantity</span></span>|<span data-ttu-id="c683e-162">Cost Amount (Actual)</span><span class="sxs-lookup"><span data-stu-id="c683e-162">Cost Amount (Actual)</span></span>|<span data-ttu-id="c683e-163">Item Ledger Entry No.</span><span class="sxs-lookup"><span data-stu-id="c683e-163">Item Ledger Entry No.</span></span>|<span data-ttu-id="c683e-164">Entry No.</span><span class="sxs-lookup"><span data-stu-id="c683e-164">Entry No.</span></span>|  
|------------------|--------------|----------------------------|---------------------------|---------------|  
|<span data-ttu-id="c683e-165">01-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-165">01-01-20</span></span>|<span data-ttu-id="c683e-166">3</span><span class="sxs-lookup"><span data-stu-id="c683e-166">3</span></span>|<span data-ttu-id="c683e-167">10</span><span class="sxs-lookup"><span data-stu-id="c683e-167">10</span></span>|<span data-ttu-id="c683e-168">1</span><span class="sxs-lookup"><span data-stu-id="c683e-168">1</span></span>|<span data-ttu-id="c683e-169">1</span><span class="sxs-lookup"><span data-stu-id="c683e-169">1</span></span>|  
|<span data-ttu-id="c683e-170">02-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-170">02-01-20</span></span>|<span data-ttu-id="c683e-171">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-171">-1</span></span>|<span data-ttu-id="c683e-172">-3.33</span><span class="sxs-lookup"><span data-stu-id="c683e-172">-3.33</span></span>|<span data-ttu-id="c683e-173">2</span><span class="sxs-lookup"><span data-stu-id="c683e-173">2</span></span>|<span data-ttu-id="c683e-174">2</span><span class="sxs-lookup"><span data-stu-id="c683e-174">2</span></span>|  
|<span data-ttu-id="c683e-175">03-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-175">03-01-20</span></span>|<span data-ttu-id="c683e-176">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-176">-1</span></span>|<span data-ttu-id="c683e-177">-3.33</span><span class="sxs-lookup"><span data-stu-id="c683e-177">-3.33</span></span>|<span data-ttu-id="c683e-178">2A-2B GST Net Amt. (3)</span><span class="sxs-lookup"><span data-stu-id="c683e-178">3</span></span>|<span data-ttu-id="c683e-179">2A-2B GST Net Amt. (3)</span><span class="sxs-lookup"><span data-stu-id="c683e-179">3</span></span>|  
|<span data-ttu-id="c683e-180">04-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-180">04-01-20</span></span>|<span data-ttu-id="c683e-181">-1</span><span class="sxs-lookup"><span data-stu-id="c683e-181">-1</span></span>|<span data-ttu-id="c683e-182">-3.33</span><span class="sxs-lookup"><span data-stu-id="c683e-182">-3.33</span></span>|<span data-ttu-id="c683e-183">Total Amounts Withheld From All Payments (4)</span><span class="sxs-lookup"><span data-stu-id="c683e-183">4</span></span>|<span data-ttu-id="c683e-184">Total Amounts Withheld From All Payments (4)</span><span class="sxs-lookup"><span data-stu-id="c683e-184">4</span></span>|  
|<span data-ttu-id="c683e-185">01-01-20</span><span class="sxs-lookup"><span data-stu-id="c683e-185">01-01-20</span></span>|<span data-ttu-id="c683e-186">0</span><span class="sxs-lookup"><span data-stu-id="c683e-186">0</span></span>|<span data-ttu-id="c683e-187">-0.01</span><span class="sxs-lookup"><span data-stu-id="c683e-187">-0.01</span></span>|<span data-ttu-id="c683e-188">1</span><span class="sxs-lookup"><span data-stu-id="c683e-188">1</span></span>|<span data-ttu-id="c683e-189">5</span><span class="sxs-lookup"><span data-stu-id="c683e-189">5</span></span>|  

## <a name="see-also"></a><span data-ttu-id="c683e-190">See Also</span><span class="sxs-lookup"><span data-stu-id="c683e-190">See Also</span></span>  
 <span data-ttu-id="c683e-191">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span><span class="sxs-lookup"><span data-stu-id="c683e-191">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span></span>  
 <span data-ttu-id="c683e-192">[Design Details: Cost Adjustment](design-details-cost-adjustment.md) </span><span class="sxs-lookup"><span data-stu-id="c683e-192">[Design Details: Cost Adjustment](design-details-cost-adjustment.md) </span></span>  
 <span data-ttu-id="c683e-193">[Design Details: Costing Methods](design-details-costing-methods.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)</span><span class="sxs-lookup"><span data-stu-id="c683e-193">[Design Details: Costing Methods](design-details-costing-methods.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)</span></span>  
 [<span data-ttu-id="c683e-194">Finance</span><span class="sxs-lookup"><span data-stu-id="c683e-194">Finance</span></span>](finance.md)  
 <span data-ttu-id="c683e-195">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c683e-195">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
