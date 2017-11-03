---
title: Withholding Tax
description: Withholding Tax (WHT) is tax withheld by a company when making a payment to a vendor, in which the full amount owed to that vendor is reduced by the tax withheld. The withheld tax is then remitted to the Australian Taxation Office (ATO) during the next Business Activity Statement (BAS) submission.
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: ae69518039ad39e74e48bb6c846ac4184ecedab1
ms.contentlocale: en-au
ms.lasthandoff: 10/23/2017

---
# <a name="withholding-tax"></a><span data-ttu-id="3de3c-104">Withholding Tax</span><span class="sxs-lookup"><span data-stu-id="3de3c-104">Withholding Tax</span></span>
<span data-ttu-id="3de3c-105">Withholding Tax (WHT) is tax withheld by a company when making a payment to a vendor, in which the full amount owed to that vendor is reduced by the tax withheld.</span><span class="sxs-lookup"><span data-stu-id="3de3c-105">Withholding Tax (WHT) is tax withheld by a company when making a payment to a vendor, in which the full amount owed to that vendor is reduced by the tax withheld.</span></span> <span data-ttu-id="3de3c-106">The withheld tax is then remitted to the Australian Taxation Office (ATO) during the next Business Activity Statement (BAS) submission.</span><span class="sxs-lookup"><span data-stu-id="3de3c-106">The withheld tax is then remitted to the Australian Taxation Office (ATO) during the next Business Activity Statement (BAS) submission.</span></span>  

<span data-ttu-id="3de3c-107">The Australian government requires taxes to be withheld from payment to vendors under the following circumstances:</span><span class="sxs-lookup"><span data-stu-id="3de3c-107">The Australian government requires taxes to be withheld from payment to vendors under the following circumstances:</span></span>  

-   <span data-ttu-id="3de3c-108">The vendor is a local supplier who has not supplied an Australian Business Number (ABN) before the payment is processed, and the individual transaction amount is greater than the specified threshold amount.</span><span class="sxs-lookup"><span data-stu-id="3de3c-108">The vendor is a local supplier who has not supplied an Australian Business Number (ABN) before the payment is processed, and the individual transaction amount is greater than the specified threshold amount.</span></span>  

-   <span data-ttu-id="3de3c-109">The vendor is a non-resident supplier and the payment is to be made to this non-resident entity in the form of interest, royalty, or dividend payments.</span><span class="sxs-lookup"><span data-stu-id="3de3c-109">The vendor is a non-resident supplier and the payment is to be made to this non-resident entity in the form of interest, royalty, or dividend payments.</span></span> <span data-ttu-id="3de3c-110">Currently, there is no minimum threshold amount.</span><span class="sxs-lookup"><span data-stu-id="3de3c-110">Currently, there is no minimum threshold amount.</span></span> <span data-ttu-id="3de3c-111">Withholding rates may vary due to payment, or international tax treaties existing between Australia and the vendor's country.</span><span class="sxs-lookup"><span data-stu-id="3de3c-111">Withholding rates may vary due to payment, or international tax treaties existing between Australia and the vendor's country.</span></span>  

<span data-ttu-id="3de3c-112">Fields within **WHT Business Posting Groups** and **WHT Product Posting Groups** must be set up in the **WHT Posting Setup** window so that the correct WHT calculations are made for each vendor.</span><span class="sxs-lookup"><span data-stu-id="3de3c-112">Fields within **WHT Business Posting Groups** and **WHT Product Posting Groups** must be set up in the **WHT Posting Setup** window so that the correct WHT calculations are made for each vendor.</span></span>  

-   <span data-ttu-id="3de3c-113">**WHT Calculation Rule** – This field controls how calculation applies to the **WHT Minimum Invoice Amount**, or the invoice threshold amount.</span><span class="sxs-lookup"><span data-stu-id="3de3c-113">**WHT Calculation Rule** – This field controls how calculation applies to the **WHT Minimum Invoice Amount**, or the invoice threshold amount.</span></span> <span data-ttu-id="3de3c-114">The following options exist:</span><span class="sxs-lookup"><span data-stu-id="3de3c-114">The following options exist:</span></span>  

    - <span data-ttu-id="3de3c-115">**Less than**</span><span class="sxs-lookup"><span data-stu-id="3de3c-115">**Less than**</span></span>  
    - <span data-ttu-id="3de3c-116">**Less than or equal to**</span><span class="sxs-lookup"><span data-stu-id="3de3c-116">**Less than or equal to**</span></span>  
    - <span data-ttu-id="3de3c-117">**Equal to**</span><span class="sxs-lookup"><span data-stu-id="3de3c-117">**Equal to**</span></span>  
    - <span data-ttu-id="3de3c-118">**Greater than**</span><span class="sxs-lookup"><span data-stu-id="3de3c-118">**Greater than**</span></span>  
    - <span data-ttu-id="3de3c-119">**Greater than or equal to**</span><span class="sxs-lookup"><span data-stu-id="3de3c-119">**Greater than or equal to**</span></span>  

<span data-ttu-id="3de3c-120">In Australia, WHT is not calculated if the individual invoice amount is less than or equal to the threshold amount.</span><span class="sxs-lookup"><span data-stu-id="3de3c-120">In Australia, WHT is not calculated if the individual invoice amount is less than or equal to the threshold amount.</span></span> <span data-ttu-id="3de3c-121">Australian companies should select **Less than or equal to**.</span><span class="sxs-lookup"><span data-stu-id="3de3c-121">Australian companies should select **Less than or equal to**.</span></span>  

- <span data-ttu-id="3de3c-122">**WHT Minimum Invoice Amount** – Enter the invoice threshold amount.</span><span class="sxs-lookup"><span data-stu-id="3de3c-122">**WHT Minimum Invoice Amount** – Enter the invoice threshold amount.</span></span>  

- <span data-ttu-id="3de3c-123">**WHT %** – Enter the relevant WHT rate for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span><span class="sxs-lookup"><span data-stu-id="3de3c-123">**WHT %** – Enter the relevant WHT rate for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span></span> <span data-ttu-id="3de3c-124">If you do not wish to calculate any withholding amount, enter 0.00.</span><span class="sxs-lookup"><span data-stu-id="3de3c-124">If you do not wish to calculate any withholding amount, enter 0.00.</span></span>  

- <span data-ttu-id="3de3c-125">**Realised WHT Type** – Select **Payment** to calculate only the withholding amount at the time of payment.</span><span class="sxs-lookup"><span data-stu-id="3de3c-125">**Realised WHT Type** – Select **Payment** to calculate only the withholding amount at the time of payment.</span></span> <span data-ttu-id="3de3c-126">The other options of **Invoice** and **Earliest** do not apply to Australia.</span><span class="sxs-lookup"><span data-stu-id="3de3c-126">The other options of **Invoice** and **Earliest** do not apply to Australia.</span></span>  

- <span data-ttu-id="3de3c-127">**Payable WHT Account Code** – Enter the number of the G/L account to which you want to post **Purchase WHT** for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span><span class="sxs-lookup"><span data-stu-id="3de3c-127">**Payable WHT Account Code** – Enter the number of the G/L account to which you want to post **Purchase WHT** for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.</span></span>  

- <span data-ttu-id="3de3c-128">**Purch. WHT Adjustment Account No.** – Select an account number for **Purchase CR/Adj Note** adjustments.</span><span class="sxs-lookup"><span data-stu-id="3de3c-128">**Purch. WHT Adjustment Account No.** – Select an account number for **Purchase CR/Adj Note** adjustments.</span></span>  

- <span data-ttu-id="3de3c-129">**Revenue Types** – Drill down to the **WHT Revenue Types** window.</span><span class="sxs-lookup"><span data-stu-id="3de3c-129">**Revenue Types** – Drill down to the **WHT Revenue Types** window.</span></span> <span data-ttu-id="3de3c-130">These values determine how the combination of **WHT Business Posting Group** and **WHT Product Posting Group** are displayed in reports.</span><span class="sxs-lookup"><span data-stu-id="3de3c-130">These values determine how the combination of **WHT Business Posting Group** and **WHT Product Posting Group** are displayed in reports.</span></span> <span data-ttu-id="3de3c-131">You must enter a value in order for this combination to appear in the WHT reports.</span><span class="sxs-lookup"><span data-stu-id="3de3c-131">You must enter a value in order for this combination to appear in the WHT reports.</span></span>  

## <a name="wht-for-suppliers-without-an-abn"></a><span data-ttu-id="3de3c-132">WHT for Suppliers Without an ABN</span><span class="sxs-lookup"><span data-stu-id="3de3c-132">WHT for Suppliers Without an ABN</span></span>  
<span data-ttu-id="3de3c-133">Ensure that there is a valid combination of **General Business** and **General Product Posting Groups** with the correct threshold.</span><span class="sxs-lookup"><span data-stu-id="3de3c-133">Ensure that there is a valid combination of **General Business** and **General Product Posting Groups** with the correct threshold.</span></span> <span data-ttu-id="3de3c-134">For example, in Australia today the minimum threshold is $75 with a rate of 46.50%.</span><span class="sxs-lookup"><span data-stu-id="3de3c-134">For example, in Australia today the minimum threshold is $75 with a rate of 46.50%.</span></span>  

<span data-ttu-id="3de3c-135">The percentage withheld is specified in **WHT Posting Setup**.</span><span class="sxs-lookup"><span data-stu-id="3de3c-135">The percentage withheld is specified in **WHT Posting Setup**.</span></span> <span data-ttu-id="3de3c-136">The amount to be withheld is calculated automatically at the time of payment.</span><span class="sxs-lookup"><span data-stu-id="3de3c-136">The amount to be withheld is calculated automatically at the time of payment.</span></span> <span data-ttu-id="3de3c-137">The WHT certificate is printed automatically, and then sent to the vendor with payment.</span><span class="sxs-lookup"><span data-stu-id="3de3c-137">The WHT certificate is printed automatically, and then sent to the vendor with payment.</span></span> <span data-ttu-id="3de3c-138">The WHT certificate explains the reasons for not sending the full invoiced amount.</span><span class="sxs-lookup"><span data-stu-id="3de3c-138">The WHT certificate explains the reasons for not sending the full invoiced amount.</span></span>  

## <a name="wht-for-foreign-suppliers"></a><span data-ttu-id="3de3c-139">WHT for Foreign Suppliers</span><span class="sxs-lookup"><span data-stu-id="3de3c-139">WHT for Foreign Suppliers</span></span>  
<span data-ttu-id="3de3c-140">Ensure that a valid combination of **General Business** and **General Product PostingGroups** has been established for vendors for whom you need to withhold tax, other than for non-ABN.</span><span class="sxs-lookup"><span data-stu-id="3de3c-140">Ensure that a valid combination of **General Business** and **General Product PostingGroups** has been established for vendors for whom you need to withhold tax, other than for non-ABN.</span></span>  

## <a name="see-also"></a><span data-ttu-id="3de3c-141">See Also</span><span class="sxs-lookup"><span data-stu-id="3de3c-141">See Also</span></span>  
 <span data-ttu-id="3de3c-142">[How to: Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="3de3c-142">[How to: Set Up Withholding Tax](how-to-set-up-withholding-tax.md) </span></span>  
 <span data-ttu-id="3de3c-143">[How to: Set Up Vendors Without ABN for Calculating the Withholding Tax](how-to-set-up-vendors-without-abn-for-calculating-the-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="3de3c-143">[How to: Set Up Vendors Without ABN for Calculating the Withholding Tax](how-to-set-up-vendors-without-abn-for-calculating-the-withholding-tax.md) </span></span>  
 <span data-ttu-id="3de3c-144">[How to: Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span><span class="sxs-lookup"><span data-stu-id="3de3c-144">[How to: Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md) </span></span>  
 <span data-ttu-id="3de3c-145">[How to: Calculate and Post Withholding Tax Settlements](how-to-calculate-and-post-withholding-tax-settlements.md) </span><span class="sxs-lookup"><span data-stu-id="3de3c-145">[How to: Calculate and Post Withholding Tax Settlements](how-to-calculate-and-post-withholding-tax-settlements.md) </span></span>  
 <span data-ttu-id="3de3c-146">[How to: View Withholding Tax Entries](how-to-view-withholding-tax-entries.md) </span><span class="sxs-lookup"><span data-stu-id="3de3c-146">[How to: View Withholding Tax Entries](how-to-view-withholding-tax-entries.md) </span></span>  
 [<span data-ttu-id="3de3c-147">Australia Local Functionality</span><span class="sxs-lookup"><span data-stu-id="3de3c-147">Australia Local Functionality</span></span>](australia-local-functionality.md)

