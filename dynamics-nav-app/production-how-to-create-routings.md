---
title: How to Create Routings
description: A routing holds master data that captures the process requirements of a given produced item. Once a production order is created for that item, its routing will govern the scheduling of operations as represented in the **Prod. Order Routing** window under the production order.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 49cce1f32f1d66dc17c0d9758937541ef1baaae7
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-routings"></a><span data-ttu-id="cc095-104">How to: Create Routings</span><span class="sxs-lookup"><span data-stu-id="cc095-104">How to: Create Routings</span></span>
<span data-ttu-id="cc095-105">Manufacturing companies use routings to visualize and direct the manufacturing process.</span><span class="sxs-lookup"><span data-stu-id="cc095-105">Manufacturing companies use routings to visualize and direct the manufacturing process.</span></span>

<span data-ttu-id="cc095-106">The routing is the basis of process scheduling, capacity scheduling, scheduled assignment of material needs, and manufacturing documents.</span><span class="sxs-lookup"><span data-stu-id="cc095-106">The routing is the basis of process scheduling, capacity scheduling, scheduled assignment of material needs, and manufacturing documents.</span></span>  

<span data-ttu-id="cc095-107">As for production BOMs, the routings are assigned to the manufacturing end item.</span><span class="sxs-lookup"><span data-stu-id="cc095-107">As for production BOMs, the routings are assigned to the manufacturing end item.</span></span> <span data-ttu-id="cc095-108">A routing holds master data that captures the process requirements of a given produced item.</span><span class="sxs-lookup"><span data-stu-id="cc095-108">A routing holds master data that captures the process requirements of a given produced item.</span></span> <span data-ttu-id="cc095-109">Once a production order is created for that item, its routing will govern the scheduling of operations as represented in the **Prod. Order Routing** window under the production order.</span><span class="sxs-lookup"><span data-stu-id="cc095-109">Once a production order is created for that item, its routing will govern the scheduling of operations as represented in the **Prod. Order Routing** window under the production order.</span></span>  

<span data-ttu-id="cc095-110">Before you can set up a routing, the following must be in place:</span><span class="sxs-lookup"><span data-stu-id="cc095-110">Before you can set up a routing, the following must be in place:</span></span>  

- <span data-ttu-id="cc095-111">Item cards are created for parent items that take part in manufacturing.</span><span class="sxs-lookup"><span data-stu-id="cc095-111">Item cards are created for parent items that take part in manufacturing.</span></span> <span data-ttu-id="cc095-112">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="cc095-112">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>
- <span data-ttu-id="cc095-113">Production resources are set up.</span><span class="sxs-lookup"><span data-stu-id="cc095-113">Production resources are set up.</span></span> <span data-ttu-id="cc095-114">For more information, see [How to: Set Up Work Centres and Machine Centres](production-how-to-set-up-work-and-machine-centers.md).</span><span class="sxs-lookup"><span data-stu-id="cc095-114">For more information, see [How to: Set Up Work Centers and Machine Centers](production-how-to-set-up-work-and-machine-centers.md).</span></span>

## <a name="to-create-a-routing"></a><span data-ttu-id="cc095-115">To create a routing</span><span class="sxs-lookup"><span data-stu-id="cc095-115">To create a routing</span></span>  
1.  <span data-ttu-id="cc095-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="cc095-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="cc095-117">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="cc095-117">Choose the **New** action.</span></span>  
3. <span data-ttu-id="cc095-118">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="cc095-118">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  <span data-ttu-id="cc095-119">In the **Type** field, select **Serial** to calculate the production routing according to the value in the **Operation No.**</span><span class="sxs-lookup"><span data-stu-id="cc095-119">In the **Type** field, select **Serial** to calculate the production routing according to the value in the **Operation No.**</span></span> <span data-ttu-id="cc095-120">field.</span><span class="sxs-lookup"><span data-stu-id="cc095-120">field.</span></span>   
    <span data-ttu-id="cc095-121">Select **Parallel** to calculate the operations according to the value in the **Next Operation No.**</span><span class="sxs-lookup"><span data-stu-id="cc095-121">Select **Parallel** to calculate the operations according to the value in the **Next Operation No.**</span></span> <span data-ttu-id="cc095-122">field.</span><span class="sxs-lookup"><span data-stu-id="cc095-122">field.</span></span>  
5.  <span data-ttu-id="cc095-123">To edit the routing, set the **Status** field to **New** or **Under Development**.</span><span class="sxs-lookup"><span data-stu-id="cc095-123">To edit the routing, set the **Status** field to **New** or **Under Development**.</span></span> <span data-ttu-id="cc095-124">To activate it, set the **Status** field to **Certified**.</span><span class="sxs-lookup"><span data-stu-id="cc095-124">To activate it, set the **Status** field to **Certified**.</span></span>  

    <span data-ttu-id="cc095-125">Proceed to fill in the routing lines.</span><span class="sxs-lookup"><span data-stu-id="cc095-125">Proceed to fill in the routing lines.</span></span>
6.  <span data-ttu-id="cc095-126">In the **Operation No.**</span><span class="sxs-lookup"><span data-stu-id="cc095-126">In the **Operation No.**</span></span> <span data-ttu-id="cc095-127">field, enter the number of the first operation, for example,  **10**.</span><span class="sxs-lookup"><span data-stu-id="cc095-127">field, enter the number of the first operation, for example,  **10**.</span></span>  
7.  <span data-ttu-id="cc095-128">In the **Type** field, specify which kind of resource is used, for example, **Work Centre**.</span><span class="sxs-lookup"><span data-stu-id="cc095-128">In the **Type** field, specify which kind of resource is used, for example, **Work Center**.</span></span>  
8.  <span data-ttu-id="cc095-129">In the **No.**</span><span class="sxs-lookup"><span data-stu-id="cc095-129">In the **No.**</span></span> <span data-ttu-id="cc095-130">field, select the resource to be used, or type it in the field.</span><span class="sxs-lookup"><span data-stu-id="cc095-130">field, select the resource to be used, or type it in the field.</span></span>  
9.  <span data-ttu-id="cc095-131">In the **Routing Link Code** field, enter a code to connect the component to a specific operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-131">In the **Routing Link Code** field, enter a code to connect the component to a specific operation.</span></span> <span data-ttu-id="cc095-132">For more information, see the "To create routing links" section.</span><span class="sxs-lookup"><span data-stu-id="cc095-132">For more information, see the "To create routing links" section.</span></span>
10.  <span data-ttu-id="cc095-133">In the **Run Time** and **Setup Time** fields, enter the process times needed to perform the operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-133">In the **Run Time** and **Setup Time** fields, enter the process times needed to perform the operation.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="cc095-134">Setup time is calculated per production order, whereas run time is calculated per produced item.</span><span class="sxs-lookup"><span data-stu-id="cc095-134">Setup time is calculated per production order, whereas run time is calculated per produced item.</span></span>  

11.  <span data-ttu-id="cc095-135">In the **Concurrent Capacities** field, specify how many units of the selected resource are used to perform the operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-135">In the **Concurrent Capacities** field, specify how many units of the selected resource are used to perform the operation.</span></span> <span data-ttu-id="cc095-136">For example, two people allocated to one packing operation will halve the run time.</span><span class="sxs-lookup"><span data-stu-id="cc095-136">For example, two people allocated to one packing operation will halve the run time.</span></span>  
12.  <span data-ttu-id="cc095-137">Continue to fill in lines for all operations involved in producing the item in question.</span><span class="sxs-lookup"><span data-stu-id="cc095-137">Continue to fill in lines for all operations involved in producing the item in question.</span></span>  
13.  <span data-ttu-id="cc095-138">To copy lines from an existing routing, choose the **Copy Routing** action to select existing lines.</span><span class="sxs-lookup"><span data-stu-id="cc095-138">To copy lines from an existing routing, choose the **Copy Routing** action to select existing lines.</span></span>  
14. <span data-ttu-id="cc095-139">Certify the routing.</span><span class="sxs-lookup"><span data-stu-id="cc095-139">Certify the routing.</span></span>  
15. <span data-ttu-id="cc095-140">You can now attach the new routing to the card of the production item in question, by filling in the **Routing No.** field.</span><span class="sxs-lookup"><span data-stu-id="cc095-140">You can now attach the new routing to the card of the production item in question, by filling in the **Routing No.** field.</span></span> <span data-ttu-id="cc095-141">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="cc095-141">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="cc095-142">Remember also to recalculate the item’s standard cost from the **Item** card: Choose the **Manufacturing** action, select the **Calc. Standard Cost** action, and then select the **All Levels** action.</span><span class="sxs-lookup"><span data-stu-id="cc095-142">Remember also to recalculate the item’s standard cost from the **Item** card: Choose the **Manufacturing** action, select the **Calc. Standard Cost** action, and then select the **All Levels** action.</span></span>  

## <a name="to-create-routing-links"></a><span data-ttu-id="cc095-143">To create routing links</span><span class="sxs-lookup"><span data-stu-id="cc095-143">To create routing links</span></span>
<span data-ttu-id="cc095-144">You can create routing links to connect components to specific operations in order to retain their relationship even though the production BOM or routing is modified.</span><span class="sxs-lookup"><span data-stu-id="cc095-144">You can create routing links to connect components to specific operations in order to retain their relationship even though the production BOM or routing is modified.</span></span> <span data-ttu-id="cc095-145">It also facilitates just-in-time flushing of components, namely when the specific linked operation starts, not when the complete production order is released.</span><span class="sxs-lookup"><span data-stu-id="cc095-145">It also facilitates just-in-time flushing of components, namely when the specific linked operation starts, not when the complete production order is released.</span></span> <span data-ttu-id="cc095-146">For more information see [How to: Flush Components According to Operation Output](production-how-to-flush-components-according-to-operation-output.md).</span><span class="sxs-lookup"><span data-stu-id="cc095-146">For more information see [How to: Flush Components According to Operation Output](production-how-to-flush-components-according-to-operation-output.md).</span></span>  

<span data-ttu-id="cc095-147">Another important benefit is that linked components and operations are displayed in a logical process structure when you use the **Production Journal** window for output and consumption posting.</span><span class="sxs-lookup"><span data-stu-id="cc095-147">Another important benefit is that linked components and operations are displayed in a logical process structure when you use the **Production Journal** window for output and consumption posting.</span></span>  

1.  <span data-ttu-id="cc095-148">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="cc095-148">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="cc095-149">Open the routing that contains the operations that you want to link.</span><span class="sxs-lookup"><span data-stu-id="cc095-149">Open the routing that contains the operations that you want to link.</span></span>  

    <span data-ttu-id="cc095-150">Make sure the routing status is **Under Development**.</span><span class="sxs-lookup"><span data-stu-id="cc095-150">Make sure the routing status is **Under Development**.</span></span>  

3.  <span data-ttu-id="cc095-151">On the relevant routing line, in the **Routing Link Code** field, select a code.</span><span class="sxs-lookup"><span data-stu-id="cc095-151">On the relevant routing line, in the **Routing Link Code** field, select a code.</span></span>  
4.  <span data-ttu-id="cc095-152">Proceed to add different routing link codes to other operations in the routing, if relevant.</span><span class="sxs-lookup"><span data-stu-id="cc095-152">Proceed to add different routing link codes to other operations in the routing, if relevant.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="cc095-153">You should not use the same routing link code in different operations on a routing because you may incorrectly link a component to two different operations, so that it is consumed two times.</span><span class="sxs-lookup"><span data-stu-id="cc095-153">You should not use the same routing link code in different operations on a routing because you may incorrectly link a component to two different operations, so that it is consumed two times.</span></span>  
    >   
    >  <span data-ttu-id="cc095-154">It is a good idea to name the routing link code after the operation in order to ensure operation-specific routing links.</span><span class="sxs-lookup"><span data-stu-id="cc095-154">It is a good idea to name the routing link code after the operation in order to ensure operation-specific routing links.</span></span>

5.  <span data-ttu-id="cc095-155">Set the routing status to **Certified**.</span><span class="sxs-lookup"><span data-stu-id="cc095-155">Set the routing status to **Certified**.</span></span>  

    <span data-ttu-id="cc095-156">Routing link codes are now assigned to operations.</span><span class="sxs-lookup"><span data-stu-id="cc095-156">Routing link codes are now assigned to operations.</span></span> <span data-ttu-id="cc095-157">Next, you must create the actual link by assigning the same codes to specific components in the relevant production BOM.</span><span class="sxs-lookup"><span data-stu-id="cc095-157">Next, you must create the actual link by assigning the same codes to specific components in the relevant production BOM.</span></span>  

6.  <span data-ttu-id="cc095-158">Open the **Production BOM** that contains the components that you want to link to the above operations.</span><span class="sxs-lookup"><span data-stu-id="cc095-158">Open the **Production BOM** that contains the components that you want to link to the above operations.</span></span> <span data-ttu-id="cc095-159">For more information, see [How to: Create Production BOMs](production-how-to-create-production-boms.md).</span><span class="sxs-lookup"><span data-stu-id="cc095-159">For more information, see [How to: Create Production BOMs](production-how-to-create-production-boms.md).</span></span>
7.  <span data-ttu-id="cc095-160">Make sure the BOM status is **Under Development**.</span><span class="sxs-lookup"><span data-stu-id="cc095-160">Make sure the BOM status is **Under Development**.</span></span>  
8.  <span data-ttu-id="cc095-161">On the relevant production BOM line, in the **Routing Link Code** field, select the code that you have just assigned to the relevant operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-161">On the relevant production BOM line, in the **Routing Link Code** field, select the code that you have just assigned to the relevant operation.</span></span>  
9. <span data-ttu-id="cc095-162">Proceed to add routing link codes to other components according to the unique operations where they are used.</span><span class="sxs-lookup"><span data-stu-id="cc095-162">Proceed to add routing link codes to other components according to the unique operations where they are used.</span></span>  
10. <span data-ttu-id="cc095-163">Set the production BOM status to **Certified**.</span><span class="sxs-lookup"><span data-stu-id="cc095-163">Set the production BOM status to **Certified**.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="cc095-164">To enable the routing links on an existing production order, you must refresh the productio1n order.</span><span class="sxs-lookup"><span data-stu-id="cc095-164">To enable the routing links on an existing production order, you must refresh the productio1n order.</span></span> <span data-ttu-id="cc095-165">For more information, see [How to: Create Production Orders](production-how-to-create-production-orders.md).</span><span class="sxs-lookup"><span data-stu-id="cc095-165">For more information, see [How to: Create Production Orders](production-how-to-create-production-orders.md).</span></span>  

<span data-ttu-id="cc095-166">The selected components will now be linked to the selected operations when you create or refresh a production order using the production BOM and routing in question.</span><span class="sxs-lookup"><span data-stu-id="cc095-166">The selected components will now be linked to the selected operations when you create or refresh a production order using the production BOM and routing in question.</span></span> <span data-ttu-id="cc095-167">This is visible in the **Prod. Order Components** window under the production order, and here you can also remove and add the defined routing link codes at any time.</span><span class="sxs-lookup"><span data-stu-id="cc095-167">This is visible in the **Prod. Order Components** window under the production order, and here you can also remove and add the defined routing link codes at any time.</span></span>

## <a name="to-assign-personnel-tools-and-quality-measures-to-routing-operations"></a><span data-ttu-id="cc095-168">To assign personnel, tools, and quality measures to routing operations.</span><span class="sxs-lookup"><span data-stu-id="cc095-168">To assign personnel, tools, and quality measures to routing operations.</span></span>
<span data-ttu-id="cc095-169">If you require personnel with qualifications, special knowledge, or special authorisation for an operation, you can assign these personnel to the operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-169">If you require personnel with qualifications, special knowledge, or special authorization for an operation, you can assign these personnel to the operation.</span></span> <span data-ttu-id="cc095-170">In addition, you can assign tools and quality requirements to the operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-170">In addition, you can assign tools and quality requirements to the operation.</span></span> <span data-ttu-id="cc095-171">This procedure describes how to assign personnel.</span><span class="sxs-lookup"><span data-stu-id="cc095-171">This procedure describes how to assign personnel.</span></span> <span data-ttu-id="cc095-172">The steps are similar for other types of operation information.</span><span class="sxs-lookup"><span data-stu-id="cc095-172">The steps are similar for other types of operation information.</span></span>

1.  <span data-ttu-id="cc095-173">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="cc095-173">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="cc095-174">Open the relevant routing.</span><span class="sxs-lookup"><span data-stu-id="cc095-174">Open the relevant routing.</span></span>  
3.  <span data-ttu-id="cc095-175">On the **Lines** FastTab, select the line that you want to process, and then choose the **Personnel** action.</span><span class="sxs-lookup"><span data-stu-id="cc095-175">On the **Lines** FastTab, select the line that you want to process, and then choose the **Personnel** action.</span></span>  
4.  <span data-ttu-id="cc095-176">Fill in the fields in the **Routing Personnel** window.</span><span class="sxs-lookup"><span data-stu-id="cc095-176">Fill in the fields in the **Routing Personnel** window.</span></span>  
5.  <span data-ttu-id="cc095-177">Choose the **OK** button to exit the window.</span><span class="sxs-lookup"><span data-stu-id="cc095-177">Choose the **OK** button to exit the window.</span></span> <span data-ttu-id="cc095-178">The entered values are copied and assigned to the operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-178">The entered values are copied and assigned to the operation.</span></span>    

## <a name="to-create-a-new-versions-of-a-routing"></a><span data-ttu-id="cc095-179">To create a new versions of a routing</span><span class="sxs-lookup"><span data-stu-id="cc095-179">To create a new versions of a routing</span></span>  
<span data-ttu-id="cc095-180">The version principle enables you to manage several versions of a routing.</span><span class="sxs-lookup"><span data-stu-id="cc095-180">The version principle enables you to manage several versions of a routing.</span></span> <span data-ttu-id="cc095-181">The structure of the routing version corresponds to the structure of the routing consisting of the routing version header and the routing version lines.</span><span class="sxs-lookup"><span data-stu-id="cc095-181">The structure of the routing version corresponds to the structure of the routing consisting of the routing version header and the routing version lines.</span></span> <span data-ttu-id="cc095-182">The basic difference is defined by the starting date.</span><span class="sxs-lookup"><span data-stu-id="cc095-182">The basic difference is defined by the starting date.</span></span>  

1.  <span data-ttu-id="cc095-183">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="cc095-183">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="cc095-184">Select the routing to be copied, and then choose the **Versions** action.</span><span class="sxs-lookup"><span data-stu-id="cc095-184">Select the routing to be copied, and then choose the **Versions** action.</span></span>  
3. <span data-ttu-id="cc095-185">In the **Routing Versions** window, choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="cc095-185">In the **Routing Versions** window, choose the **New** action.</span></span>
4. <span data-ttu-id="cc095-186">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="cc095-186">Fill in the fields as necessary.</span></span>
5.  <span data-ttu-id="cc095-187">In the **Version Code** field, enter the unique identification of the version.</span><span class="sxs-lookup"><span data-stu-id="cc095-187">In the **Version Code** field, enter the unique identification of the version.</span></span> <span data-ttu-id="cc095-188">Any combination of numbers and letters is permitted.</span><span class="sxs-lookup"><span data-stu-id="cc095-188">Any combination of numbers and letters is permitted.</span></span>  

    <span data-ttu-id="cc095-189">The newly created version is automatically assigned the status **New**.</span><span class="sxs-lookup"><span data-stu-id="cc095-189">The newly created version is automatically assigned the status **New**.</span></span>  
6.  <span data-ttu-id="cc095-190">To create operation lines, select the first blank line, and then fill in the **Operation No.**</span><span class="sxs-lookup"><span data-stu-id="cc095-190">To create operation lines, select the first blank line, and then fill in the **Operation No.**</span></span> <span data-ttu-id="cc095-191">field according to the sequence of operations.</span><span class="sxs-lookup"><span data-stu-id="cc095-191">field according to the sequence of operations.</span></span>

    <span data-ttu-id="cc095-192">The operation lines are sorted in ascending order by operation numbers.</span><span class="sxs-lookup"><span data-stu-id="cc095-192">The operation lines are sorted in ascending order by operation numbers.</span></span> <span data-ttu-id="cc095-193">To be able to make changes later, we recommend you to select adequate step widths.</span><span class="sxs-lookup"><span data-stu-id="cc095-193">To be able to make changes later, we recommend you to select adequate step widths.</span></span> <span data-ttu-id="cc095-194">The **Next Operation No.**</span><span class="sxs-lookup"><span data-stu-id="cc095-194">The **Next Operation No.**</span></span> <span data-ttu-id="cc095-195">field refers to the following operation.</span><span class="sxs-lookup"><span data-stu-id="cc095-195">field refers to the following operation.</span></span> <span data-ttu-id="cc095-196">The number of the operation can be entered directly.</span><span class="sxs-lookup"><span data-stu-id="cc095-196">The number of the operation can be entered directly.</span></span>

7. <span data-ttu-id="cc095-197">When the routing version is completed, setting the **Status** field to **Certified**.</span><span class="sxs-lookup"><span data-stu-id="cc095-197">When the routing version is completed, setting the **Status** field to **Certified**.</span></span>

<span data-ttu-id="cc095-198">The time validity of the version is specified by the **Starting Date** field.</span><span class="sxs-lookup"><span data-stu-id="cc095-198">The time validity of the version is specified by the **Starting Date** field.</span></span>  

## <a name="see-also"></a><span data-ttu-id="cc095-199">See Also</span><span class="sxs-lookup"><span data-stu-id="cc095-199">See Also</span></span>  
[<span data-ttu-id="cc095-200">How to: Create Production BOMs</span><span class="sxs-lookup"><span data-stu-id="cc095-200">How to: Create Production BOMs</span></span>](production-how-to-create-production-boms.md)  
[<span data-ttu-id="cc095-201">Setting Up Manufacturing</span><span class="sxs-lookup"><span data-stu-id="cc095-201">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="cc095-202">[Manufacturing](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="cc095-202">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="cc095-203">[Planning](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="cc095-203">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="cc095-204">Inventory</span><span class="sxs-lookup"><span data-stu-id="cc095-204">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="cc095-205">Purchasing</span><span class="sxs-lookup"><span data-stu-id="cc095-205">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="cc095-206">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="cc095-206">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
