---
title: Design Details - Variance
description: Variance is defined as the difference between the actual cost and the standard cost, as described in the following formula.
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
ms.openlocfilehash: 63032d592b5fe9e58c52e64ed0a30ceeda2532fe
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-variance"></a><span data-ttu-id="a177b-103">Design Details: Variance</span><span class="sxs-lookup"><span data-stu-id="a177b-103">Design Details: Variance</span></span>
<span data-ttu-id="a177b-104">Variance is defined as the difference between the actual cost and the standard cost, as described in the following formula.</span><span class="sxs-lookup"><span data-stu-id="a177b-104">Variance is defined as the difference between the actual cost and the standard cost, as described in the following formula.</span></span>  

 <span data-ttu-id="a177b-105">actual cost – standard cost = variance</span><span class="sxs-lookup"><span data-stu-id="a177b-105">actual cost – standard cost = variance</span></span>  

 <span data-ttu-id="a177b-106">If the actual cost changes, for example, because you post an item charge on a later date, then the variance is updated accordingly.</span><span class="sxs-lookup"><span data-stu-id="a177b-106">If the actual cost changes, for example, because you post an item charge on a later date, then the variance is updated accordingly.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="a177b-107">Revaluation does not affect the variance calculation, because revaluation only changes the inventory value.</span><span class="sxs-lookup"><span data-stu-id="a177b-107">Revaluation does not affect the variance calculation, because revaluation only changes the inventory value.</span></span>  

## <a name="example"></a><span data-ttu-id="a177b-108">Example</span><span class="sxs-lookup"><span data-stu-id="a177b-108">Example</span></span>  
 <span data-ttu-id="a177b-109">The following example illustrates how variance is calculated for purchased items.</span><span class="sxs-lookup"><span data-stu-id="a177b-109">The following example illustrates how variance is calculated for purchased items.</span></span> <span data-ttu-id="a177b-110">It is based on the following scenario:</span><span class="sxs-lookup"><span data-stu-id="a177b-110">It is based on the following scenario:</span></span>  

1.  <span data-ttu-id="a177b-111">The user purchases an item at LCY 90.00, but the standard cost is LCY 100.00.</span><span class="sxs-lookup"><span data-stu-id="a177b-111">The user purchases an item at LCY 90.00, but the standard cost is LCY 100.00.</span></span> <span data-ttu-id="a177b-112">Accordingly, the purchase variance is LCY –10.00.</span><span class="sxs-lookup"><span data-stu-id="a177b-112">Accordingly, the purchase variance is LCY –10.00.</span></span>  
2.  <span data-ttu-id="a177b-113">LCY 10.00 is credited to the purchase variance account.</span><span class="sxs-lookup"><span data-stu-id="a177b-113">LCY 10.00 is credited to the purchase variance account.</span></span>  
3.  <span data-ttu-id="a177b-114">The user posts an item charge of LCY 20.00.</span><span class="sxs-lookup"><span data-stu-id="a177b-114">The user posts an item charge of LCY 20.00.</span></span> <span data-ttu-id="a177b-115">Accordingly, the actual cost is increased to LCY 110.00, and the value of the purchase variance becomes LCY 10.00.</span><span class="sxs-lookup"><span data-stu-id="a177b-115">Accordingly, the actual cost is increased to LCY 110.00, and the value of the purchase variance becomes LCY 10.00.</span></span>  
4.  <span data-ttu-id="a177b-116">LCY 20.00 is debited to the purchase variance account.</span><span class="sxs-lookup"><span data-stu-id="a177b-116">LCY 20.00 is debited to the purchase variance account.</span></span> <span data-ttu-id="a177b-117">Accordingly, the net purchase variance becomes LCY 10.00.</span><span class="sxs-lookup"><span data-stu-id="a177b-117">Accordingly, the net purchase variance becomes LCY 10.00.</span></span>  
5.  <span data-ttu-id="a177b-118">The user revalues the item from LCY 100.00 to LCY 70.00.</span><span class="sxs-lookup"><span data-stu-id="a177b-118">The user revalues the item from LCY 100.00 to LCY 70.00.</span></span> <span data-ttu-id="a177b-119">This does not affect the variance calculation, only the inventory value.</span><span class="sxs-lookup"><span data-stu-id="a177b-119">This does not affect the variance calculation, only the inventory value.</span></span>  

 <span data-ttu-id="a177b-120">The following table shows the resulting value entries.</span><span class="sxs-lookup"><span data-stu-id="a177b-120">The following table shows the resulting value entries.</span></span>  

 <span data-ttu-id="a177b-121">![Purchase variance calculation](media/design_details_inventory_costing_11_purchase_variance.png "design_details_inventory_costing_11_purchase_variance")</span><span class="sxs-lookup"><span data-stu-id="a177b-121">![Purchase variance calculation](media/design_details_inventory_costing_11_purchase_variance.png "design_details_inventory_costing_11_purchase_variance")</span></span>  

## <a name="determining-the-standard-cost"></a><span data-ttu-id="a177b-122">Determining the Standard Cost</span><span class="sxs-lookup"><span data-stu-id="a177b-122">Determining the Standard Cost</span></span>  
 <span data-ttu-id="a177b-123">The standard cost is used when calculating variance and the amount to capitalise.</span><span class="sxs-lookup"><span data-stu-id="a177b-123">The standard cost is used when calculating variance and the amount to capitalize.</span></span> <span data-ttu-id="a177b-124">Since the standard cost can be changed over time because of manual update calculation, you need a point in time when the standard cost is fixed for variance calculation.</span><span class="sxs-lookup"><span data-stu-id="a177b-124">Since the standard cost can be changed over time because of manual update calculation, you need a point in time when the standard cost is fixed for variance calculation.</span></span> <span data-ttu-id="a177b-125">This point is when the inventory increase is invoiced.</span><span class="sxs-lookup"><span data-stu-id="a177b-125">This point is when the inventory increase is invoiced.</span></span> <span data-ttu-id="a177b-126">For produced or assembled items, the point when standard cost is determined is when the cost is adjusted.</span><span class="sxs-lookup"><span data-stu-id="a177b-126">For produced or assembled items, the point when standard cost is determined is when the cost is adjusted.</span></span>  

 <span data-ttu-id="a177b-127">The following table shows how different cost shares are calculated for produced and assembled items when you use the Calculate Standard Cost function.</span><span class="sxs-lookup"><span data-stu-id="a177b-127">The following table shows how different cost shares are calculated for produced and assembled items when you use the Calculate Standard Cost function.</span></span>  

|<span data-ttu-id="a177b-128">Cost Share</span><span class="sxs-lookup"><span data-stu-id="a177b-128">Cost Share</span></span>|<span data-ttu-id="a177b-129">Purchased Item</span><span class="sxs-lookup"><span data-stu-id="a177b-129">Purchased Item</span></span>|<span data-ttu-id="a177b-130">Produced/Assembled Item</span><span class="sxs-lookup"><span data-stu-id="a177b-130">Produced/Assembled Item</span></span>|  
|----------------|--------------------|------------------------------|  
|<span data-ttu-id="a177b-131">**Standard Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-131">**Standard Cost**</span></span>||<span data-ttu-id="a177b-132">Single-Level Material Cost + Single-Level Capacity Cost + Single-Level Subcontrd. Cost + Single-Level Cap. Ovhd. Cost + Single-Level Mfg. Ovhd. Cost</span><span class="sxs-lookup"><span data-stu-id="a177b-132">Single-Level Material Cost + Single-Level Capacity Cost + Single-Level Subcontrd. Cost + Single-Level Cap. Ovhd. Cost + Single-Level Mfg. Ovhd. Cost</span></span>|  
|<span data-ttu-id="a177b-133">**Single-Level Material Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-133">**Single-Level Material Cost**</span></span>|<span data-ttu-id="a177b-134">Unit Cost</span><span class="sxs-lookup"><span data-stu-id="a177b-134">Unit Cost</span></span>|<span data-ttu-id="a177b-135">![Equation 1](media/design_details_inventory_costing_11_equation_1.png "design_details_inventory_costing_11_equation_1")</span><span class="sxs-lookup"><span data-stu-id="a177b-135">![Equation 1](media/design_details_inventory_costing_11_equation_1.png "design_details_inventory_costing_11_equation_1")</span></span>|  
|<span data-ttu-id="a177b-136">**Single-Level Capacity Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-136">**Single-Level Capacity Cost**</span></span>|<span data-ttu-id="a177b-137">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-137">Not applicable</span></span>|<span data-ttu-id="a177b-138">![Equation 2](media/design_details_inventory_costing_11_equation_2.png "design_details_inventory_costing_11_equation_2")</span><span class="sxs-lookup"><span data-stu-id="a177b-138">![Equation 2](media/design_details_inventory_costing_11_equation_2.png "design_details_inventory_costing_11_equation_2")</span></span>|  
|<span data-ttu-id="a177b-139">**Single-Level Subcontrd. Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-139">**Single-Level Subcontrd. Cost**</span></span>|<span data-ttu-id="a177b-140">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-140">Not applicable</span></span>|<span data-ttu-id="a177b-141">![Equation 3](media/design_details_inventory_costing_11_equation_3.png "design_details_inventory_costing_11_equation_3")</span><span class="sxs-lookup"><span data-stu-id="a177b-141">![Equation 3](media/design_details_inventory_costing_11_equation_3.png "design_details_inventory_costing_11_equation_3")</span></span>|  
|<span data-ttu-id="a177b-142">**Single-Level Cap. Ovhd Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-142">**Single-Level Cap. Ovhd Cost**</span></span>|<span data-ttu-id="a177b-143">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-143">Not applicable</span></span>|<span data-ttu-id="a177b-144">![Equation 4](media/design_details_inventory_costing_11_equation_4.png "design_details_inventory_costing_11_equation_4")</span><span class="sxs-lookup"><span data-stu-id="a177b-144">![Equation 4](media/design_details_inventory_costing_11_equation_4.png "design_details_inventory_costing_11_equation_4")</span></span>|  
|<span data-ttu-id="a177b-145">**Single-Level Mfg. Ovhd Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-145">**Single-Level Mfg. Ovhd Cost**</span></span>|<span data-ttu-id="a177b-146">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-146">Not applicable</span></span>|<span data-ttu-id="a177b-147">(Single-Level Material Cost + Single-Level Capacity Cost + Single-Level Subcontrd. Cost) * Indirect Cost % / 100 + Overhead Rate</span><span class="sxs-lookup"><span data-stu-id="a177b-147">(Single-Level Material Cost + Single-Level Capacity Cost + Single-Level Subcontrd. Cost) * Indirect Cost % / 100 + Overhead Rate</span></span>|  
|<span data-ttu-id="a177b-148">**Rolled-up Material Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-148">**Rolled-up Material Cost**</span></span>|<span data-ttu-id="a177b-149">Unit Cost</span><span class="sxs-lookup"><span data-stu-id="a177b-149">Unit Cost</span></span>|<span data-ttu-id="a177b-150">![Equation 5](media/design_details_inventory_costing_11_equation_5.png "design_details_inventory_costing_11_equation_5")</span><span class="sxs-lookup"><span data-stu-id="a177b-150">![Equation 5](media/design_details_inventory_costing_11_equation_5.png "design_details_inventory_costing_11_equation_5")</span></span>|  
|<span data-ttu-id="a177b-151">**Rolled-up Capacity Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-151">**Rolled-up Capacity Cost**</span></span>|<span data-ttu-id="a177b-152">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-152">Not applicable</span></span>|<span data-ttu-id="a177b-153">![Equation 6](media/design_details_inventory_costing_11_equation_6.png "design_details_inventory_costing_11_equation_6")</span><span class="sxs-lookup"><span data-stu-id="a177b-153">![Equation 6](media/design_details_inventory_costing_11_equation_6.png "design_details_inventory_costing_11_equation_6")</span></span>|  
|<span data-ttu-id="a177b-154">**Rolled-Up Subcontracted Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-154">**Rolled-Up Subcontracted Cost**</span></span>|<span data-ttu-id="a177b-155">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-155">Not applicable</span></span>|<span data-ttu-id="a177b-156">![Equation 7](media/design_details_inventory_costing_11_equation_7.png "design_details_inventory_costing_11_equation_7")</span><span class="sxs-lookup"><span data-stu-id="a177b-156">![Equation 7](media/design_details_inventory_costing_11_equation_7.png "design_details_inventory_costing_11_equation_7")</span></span>|  
|<span data-ttu-id="a177b-157">**Rolled-up Capacity Ovhd. Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-157">**Rolled-up Capacity Ovhd. Cost**</span></span>|<span data-ttu-id="a177b-158">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-158">Not applicable</span></span>|<span data-ttu-id="a177b-159">![Equation 8](media/design_details_inventory_costing_11_equation_8.png "design_details_inventory_costing_11_equation_8")</span><span class="sxs-lookup"><span data-stu-id="a177b-159">![Equation 8](media/design_details_inventory_costing_11_equation_8.png "design_details_inventory_costing_11_equation_8")</span></span>|  
|<span data-ttu-id="a177b-160">**Rolled-up Mfg. Ovhd. Cost**</span><span class="sxs-lookup"><span data-stu-id="a177b-160">**Rolled-up Mfg. Ovhd. Cost**</span></span>|<span data-ttu-id="a177b-161">Not applicable</span><span class="sxs-lookup"><span data-stu-id="a177b-161">Not applicable</span></span>|<span data-ttu-id="a177b-162">![Equation 9](media/design_details_inventory_costing_11_equation_9.png "design_details_inventory_costing_11_equation_9")</span><span class="sxs-lookup"><span data-stu-id="a177b-162">![Equation 9](media/design_details_inventory_costing_11_equation_9.png "design_details_inventory_costing_11_equation_9")</span></span>|  

## <a name="see-also"></a><span data-ttu-id="a177b-163">See Also</span><span class="sxs-lookup"><span data-stu-id="a177b-163">See Also</span></span>  
 <span data-ttu-id="a177b-164">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span><span class="sxs-lookup"><span data-stu-id="a177b-164">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span></span>  
 <span data-ttu-id="a177b-165">[Design Details: Costing Methods](design-details-costing-methods.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)</span><span class="sxs-lookup"><span data-stu-id="a177b-165">[Design Details: Costing Methods](design-details-costing-methods.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)</span></span>  
 [<span data-ttu-id="a177b-166">Finance</span><span class="sxs-lookup"><span data-stu-id="a177b-166">Finance</span></span>](finance.md)  
 <span data-ttu-id="a177b-167">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a177b-167">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
