---
title: How to Set Up Business Activity Statements
description: You must set up a Business Activity Statement (BAS) to generate a BAS report.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 076cd71b223e2cf68b6e42a5c616cef817750694
ms.contentlocale: en-au
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-business-activity-statements"></a><span data-ttu-id="2a69a-103">How to: Set Up Business Activity Statements</span><span class="sxs-lookup"><span data-stu-id="2a69a-103">How to: Set Up Business Activity Statements</span></span>
<span data-ttu-id="2a69a-104">You must set up a Business Activity Statement (BAS) to generate a BAS report.</span><span class="sxs-lookup"><span data-stu-id="2a69a-104">You must set up a Business Activity Statement (BAS) to generate a BAS report.</span></span> <span data-ttu-id="2a69a-105">BAS setup includes the following:</span><span class="sxs-lookup"><span data-stu-id="2a69a-105">BAS setup includes the following:</span></span>  

-   <span data-ttu-id="2a69a-106">Goods and Services Tax (GST) posting setup.</span><span class="sxs-lookup"><span data-stu-id="2a69a-106">Goods and Services Tax (GST) posting setup.</span></span>  
-   <span data-ttu-id="2a69a-107">BAS – XML field IDs.</span><span class="sxs-lookup"><span data-stu-id="2a69a-107">BAS – XML field IDs.</span></span>  
-   <span data-ttu-id="2a69a-108">BAS setup names.</span><span class="sxs-lookup"><span data-stu-id="2a69a-108">BAS setup names.</span></span>  

## <a name="to-set-up-gst-posting"></a><span data-ttu-id="2a69a-109">To set up GST posting</span><span class="sxs-lookup"><span data-stu-id="2a69a-109">To set up GST posting</span></span>  

1.  <span data-ttu-id="2a69a-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Posting Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="2a69a-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **VAT Posting Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="2a69a-111">To set up GST posting rules, create a new line and enter information into the relevant fields.</span><span class="sxs-lookup"><span data-stu-id="2a69a-111">To set up GST posting rules, create a new line and enter information into the relevant fields.</span></span>  
3.  <span data-ttu-id="2a69a-112">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="2a69a-112">Choose the **OK** button.</span></span>  

## <a name="to-set-up-bas--xml-field-ids"></a><span data-ttu-id="2a69a-113">To set up BAS – XML field IDs</span><span class="sxs-lookup"><span data-stu-id="2a69a-113">To set up BAS – XML field IDs</span></span>  

1.  <span data-ttu-id="2a69a-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS – XML Field IDs**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="2a69a-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS – XML Field IDs**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="2a69a-115">Choose the **New** action to create a new line.</span><span class="sxs-lookup"><span data-stu-id="2a69a-115">Choose the **New** action to create a new line.</span></span>  
3.  <span data-ttu-id="2a69a-116">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="2a69a-116">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="2a69a-117">Field</span><span class="sxs-lookup"><span data-stu-id="2a69a-117">Field</span></span>|<span data-ttu-id="2a69a-118">Description</span><span class="sxs-lookup"><span data-stu-id="2a69a-118">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="2a69a-119">**XML Field ID**</span><span class="sxs-lookup"><span data-stu-id="2a69a-119">**XML Field ID**</span></span>|<span data-ttu-id="2a69a-120">The name for the BAS field, as it appears in the XML file.</span><span class="sxs-lookup"><span data-stu-id="2a69a-120">The name for the BAS field, as it appears in the XML file.</span></span>|  
    |<span data-ttu-id="2a69a-121">**Field No.**</span><span class="sxs-lookup"><span data-stu-id="2a69a-121">**Field No.**</span></span>|<span data-ttu-id="2a69a-122">The internal [!INCLUDE[navnow](../../includes/navnow_md.md)] number that corresponds to the field label number in the XML file.</span><span class="sxs-lookup"><span data-stu-id="2a69a-122">The internal [!INCLUDE[navnow](../../includes/navnow_md.md)] number that corresponds to the field label number in the XML file.</span></span>|  
    |<span data-ttu-id="2a69a-123">**Field Label No.**</span><span class="sxs-lookup"><span data-stu-id="2a69a-123">**Field Label No.**</span></span>|<span data-ttu-id="2a69a-124">This value is replicated from the XML file received from the Australian Tax Office (ATO).</span><span class="sxs-lookup"><span data-stu-id="2a69a-124">This value is replicated from the XML file received from the Australian Tax Office (ATO).</span></span> <span data-ttu-id="2a69a-125">It refers to the relevant section of the BAS, as described in the BAS instructions from the ATO.</span><span class="sxs-lookup"><span data-stu-id="2a69a-125">It refers to the relevant section of the BAS, as described in the BAS instructions from the ATO.</span></span> <span data-ttu-id="2a69a-126">**Note:**  The value in this field is updated when you select a value in the **Field No.** field.</span><span class="sxs-lookup"><span data-stu-id="2a69a-126">**Note:**  The value in this field is updated when you select a value in the **Field No.** field.</span></span>|  
    |<span data-ttu-id="2a69a-127">**Field Description**</span><span class="sxs-lookup"><span data-stu-id="2a69a-127">**Field Description**</span></span>|<span data-ttu-id="2a69a-128">This is the description for the value in the **Field Label No.**</span><span class="sxs-lookup"><span data-stu-id="2a69a-128">This is the description for the value in the **Field Label No.**</span></span> <span data-ttu-id="2a69a-129">field.</span><span class="sxs-lookup"><span data-stu-id="2a69a-129">field.</span></span> <span data-ttu-id="2a69a-130">**Note:**  The value in this field is updated when you select a value in the **Field No.** field.</span><span class="sxs-lookup"><span data-stu-id="2a69a-130">**Note:**  The value in this field is updated when you select a value in the **Field No.** field.</span></span>|  

4.  <span data-ttu-id="2a69a-131">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="2a69a-131">Choose the **OK** button.</span></span>  

## <a name="to-set-up-bas"></a><span data-ttu-id="2a69a-132">To set up BAS</span><span class="sxs-lookup"><span data-stu-id="2a69a-132">To set up BAS</span></span>  

1.  <span data-ttu-id="2a69a-133">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS Setup Names**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="2a69a-133">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS Setup Names**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="2a69a-134">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="2a69a-134">Choose the **New** action.</span></span>  
3.  <span data-ttu-id="2a69a-135">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="2a69a-135">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="2a69a-136">Field</span><span class="sxs-lookup"><span data-stu-id="2a69a-136">Field</span></span>|<span data-ttu-id="2a69a-137">Description</span><span class="sxs-lookup"><span data-stu-id="2a69a-137">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="2a69a-138">**Name**</span><span class="sxs-lookup"><span data-stu-id="2a69a-138">**Name**</span></span>|<span data-ttu-id="2a69a-139">The BAS setup name.</span><span class="sxs-lookup"><span data-stu-id="2a69a-139">The BAS setup name.</span></span>|  
    |<span data-ttu-id="2a69a-140">**Description**</span><span class="sxs-lookup"><span data-stu-id="2a69a-140">**Description**</span></span>|<span data-ttu-id="2a69a-141">The description for the BAS setup name.</span><span class="sxs-lookup"><span data-stu-id="2a69a-141">The description for the BAS setup name.</span></span>|  

4.  <span data-ttu-id="2a69a-142">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="2a69a-142">Choose the **OK** button.</span></span>  
5.  <span data-ttu-id="2a69a-143">In the **BAS Setup Name** window, choose the **BAS Setup** action.</span><span class="sxs-lookup"><span data-stu-id="2a69a-143">In the **BAS Setup Name** window, choose the **BAS Setup** action.</span></span>  
6.  <span data-ttu-id="2a69a-144">In the **BAS Setup** window, enter the BAS setup information.</span><span class="sxs-lookup"><span data-stu-id="2a69a-144">In the **BAS Setup** window, enter the BAS setup information.</span></span>  
7.  <span data-ttu-id="2a69a-145">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="2a69a-145">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="2a69a-146">See Also</span><span class="sxs-lookup"><span data-stu-id="2a69a-146">See Also</span></span>  
 <span data-ttu-id="2a69a-147">[Business Activity Statements](business-activity-statements.md) </span><span class="sxs-lookup"><span data-stu-id="2a69a-147">[Business Activity Statements](business-activity-statements.md) </span></span>  
 <span data-ttu-id="2a69a-148">[How to: Export Business Activity Statements](how-to-export-business-activity-statements.md) </span><span class="sxs-lookup"><span data-stu-id="2a69a-148">[How to: Export Business Activity Statements](how-to-export-business-activity-statements.md) </span></span>  
 <span data-ttu-id="2a69a-149">[How to: Calculate Goods and Services Tax on Prepayments](how-to-calculate-goods-and-services-tax-on-prepayments.md) </span><span class="sxs-lookup"><span data-stu-id="2a69a-149">[How to: Calculate Goods and Services Tax on Prepayments](how-to-calculate-goods-and-services-tax-on-prepayments.md) </span></span>  
 [<span data-ttu-id="2a69a-150">How to: Print Goods and Services Tax Sales and Purchase Reports</span><span class="sxs-lookup"><span data-stu-id="2a69a-150">How to: Print Goods and Services Tax Sales and Purchase Reports</span></span>](how-to-print-goods-and-services-tax-sales-and-purchase-reports.md)

