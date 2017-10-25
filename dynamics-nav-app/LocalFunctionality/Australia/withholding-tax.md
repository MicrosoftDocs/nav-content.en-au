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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 04df47377b8788313f04581eafaa5f31de4d748d
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="withholding-tax"></a>Withholding Tax
Withholding Tax (WHT) is tax withheld by a company when making a payment to a vendor, in which the full amount owed to that vendor is reduced by the tax withheld. The withheld tax is then remitted to the Australian Taxation Office (ATO) during the next Business Activity Statement (BAS) submission.  
  
 The Australian government requires taxes to be withheld from payment to vendors under the following circumstances:  
  
-   The vendor is a local supplier who has not supplied an Australian Business Number (ABN) before the payment is processed, and the individual transaction amount is greater than the specified threshold amount.  
  
-   The vendor is a non-resident supplier and the payment is to be made to this non-resident entity in the form of interest, royalty, or dividend payments. Currently, there is no minimum threshold amount. Withholding rates may vary due to payment, or international tax treaties existing between Australia and the vendor's country.  
  
 **WHT Business Posting Groups** and **WHT Product Posting Groups** must be set up in the **WHT Posting Setup** window so that the correct WHT calculations are made for each vendor.  
  
-   **WHT Calculation Rule** – This field controls how calculation applies to the **WHT Minimum Invoice Amount**, or the invoice threshold amount. The options are:  
  
    -   **Less than**  
  
    -   **Less than or equal to**  
  
    -   **Equal to**  
  
    -   **Greater than**  
  
    -   **Greater than or equal to**  
  
 In Australia, WHT is not calculated if the individual invoice amount is less than or equal to the threshold amount. Australian companies should select **Less than or equal to**.  
  
-   **WHT Minimum Invoice Amount** – Enter the invoice threshold amount.  
  
-   **WHT %** – Enter the relevant WHT rate for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**. If you do not wish to calculate any withholding amount, enter 0.00.  
  
-   **Realised WHT Type** – Select **Payment** to calculate only the withholding amount at the time of payment. The other options of **Invoice** and **Earliest** do not apply to Australia.  
  
-   **Payable WHT Account Code** – Enter the number of the G/L account to which you want to post **Purchase WHT** for the particular combination of **WHT Business Posting Group** and **WHT Product Posting Group**.  
  
-   **Purch. WHT Adjustment Account No.** – Select an account number for **Purchase CR/Adj Note** adjustments.  
  
-   **Revenue Types** – Drill down to the **WHT Revenue Types** window. These values determine how the combination of **WHT Business Posting Group** and **WHT Product Posting Group** are displayed in reports. You must enter a value in order for this combination to appear in the WHT reports.  
  
## <a name="wht-for-suppliers-without-an-abn"></a>WHT for Suppliers Without an ABN  
 Ensure that there is a valid combination of **General Business** and **General Product Posting Groups** with the correct threshold. For example, in Australia today the minimum threshold is $75 with a rate of 46.50%.  
  
 The percentage withheld is specified in **WHT Posting Setup**. The amount to be withheld is calculated automatically at the time of payment. The WHT certificate is printed automatically, and then sent to the vendor with payment. The WHT certificate explains the reasons for not sending the full invoiced amount.  
  
## <a name="wht-for-foreign-suppliers"></a>WHT for Foreign Suppliers  
 Ensure that a valid combination of **General Business** and **General Product PostingGroups** has been established for vendors for whom you need to withhold tax, other than for non-ABN.  
  
## <a name="see-also"></a>See Also  
 [How to: Set Up Withholding Tax](how-to-set-up-withholding-tax.md)   
 [How to: Set Up Vendors Without ABN for Calculating the Withholding Tax](how-to-set-up-vendors-without-abn-for-calculating-the-withholding-tax.md)   
 [How to: Set Up Revenue Types for Withholding Tax](how-to-set-up-revenue-types-for-withholding-tax.md)   
 [How to: Calculate and Post Withholding Tax Settlements](how-to-calculate-and-post-withholding-tax-settlements.md)   
 [How to: View Withholding Tax Entries](how-to-view-withholding-tax-entries.md)   
 [Australia Local Functionality](australia-local-functionality.md)
