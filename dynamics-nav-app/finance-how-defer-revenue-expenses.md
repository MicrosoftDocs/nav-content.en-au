---
title: 'How to: Defer Revenues and Expenses'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 865bc307e8635b5a5aba11b5bc2e2e448c05e769
ms.contentlocale: en-au
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-defer-revenues-and-expenses"></a>How to: Defer Revenues and Expenses
To recognise a revenue or an expense in a period other than the period in which the transaction was posted, you can use functionality to automatically defer revenues and expenses over a specified schedule.

To distribute revenues or expenses on the involved accounting periods, you set up a deferral template for the resource, item, or G/L account that the revenue or expense will be posted for. When you post the related sales or purchase document, the revenue or expense are deferred to the involved accounting periods, according to a deferral schedule that is governed by settings in the deferral template and the posting date.

## <a name="to-set-up-a-gl-account-for-deferral"></a>To set up a G/L account for deferral
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.
2. Choose the **New** action.
3. Fill in the fields as necessary to create a G/L account for deferred revenues. For more information, see [The General Ledger and the Chart of Accounts](finance-setup-general-ledger.md).
3. Repeat steps 2 and 3 to create a new G/L account for deferred expenses.

For both types of deferral, select **Balance Sheet** in the **Type** field, and name the accounts appropriately, such as "Unearned Income" for deferred revenues and "Unpaid Expenses" for deferred expenses.

## <a name="to-set-up-a-deferral-template"></a>To set up a deferral template
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Deferral Templates**, and then choose the related link.
2. Choose the **New** action.
3. Fill in the fields as necessary.
4. In the **Calc. Method** field, specify how the **Amount** field for each period in the **Deferral Schedule** window is calculated. You can choose between the following options:
    - **Straight-Line**: The periodic deferral amounts are calculated according to the number of periods, distributed according to period length.
    - **Equal Per Period**: The periodic deferral amounts are calculated according to the number of periods, distributed evenly on periods.
    - **Days Per Period**: The periodic deferral amounts are calculated according to the number of days in the period.
    - **User-Defined**: The periodic deferral amounts are not calculated. You must manually fill the Amount field for each period in the Deferral Schedule window. For more information, see the “To change a deferral schedule from a sales invoice” section.

5. In the **Period Desc.** field, specify a description that will be shown on entries for the deferral posting. You can enter the following placeholder codes for typical values, which will be inserted automatically when the period description is displayed.
    - %1 = The day number of the period posting date
    - %2 = The week number of the period posting date
    - %3 = The month number of the period posting date
    - %4 = The month name of the period posting date
    - %5 = The accounting period name of the period posting date
    - %6 = The fiscal year of the period posting date

Example: The posting date is 02/06/2016. If you enter “Expenses deferred for %4 %6”, then the description displayed will be "Expenses deferred for February 2016".

## <a name="to-assign-a-deferral-template-to-an-item"></a>To assign a deferral template to an item
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Deferral Templates**, and then choose the related link.
2. Open the card for the item for which revenues or expenses must be deferred to the accounting periods when the item was sold or purchased.
3. In the **Default Deferral Template** field, select the relevant deferral template.

## <a name="to-change-a-deferral-schedule-from-a-sales-invoice"></a>To change a deferral schedule from a sales invoice
**Note**: The steps in this procedure are the same as when you change a deferral schedule, for expenses, from a purchase invoice.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Invoices**, and then choose the related link.
2. Create a sales invoice for an item that has a deferral template assigned. For more information, see [How to: Invoice Sales](sales-how-invoice-sales.md).

    Notice that as soon as you enter the item (or resource or G/L account) on the invoice line, the **Deferral Code** field is filled with the code of the assigned deferral template.
3. Choose the **Deferral Schedule** action.
4. In the **Deferral Schedule** window, change settings on the header or values on the lines, for example to defer the amount to an additional accounting period.
5. Choose the **Calculate Schedule** action.
6. Choose the **OK** button. The deferral schedule is updated for the sales invoice. The related deferral template is unchanged.

## <a name="to-preview-how-deferred-revenues-or-expenses-will-be-posted-to-the-general-ledger"></a>To preview how deferred revenues or expenses will be posted to the general ledger
**Note**: The steps in this procedure are the same as when you preview how expense deferrals are posted.

1. In the **Sales Invoice** window, choose the **Preview Posting** action.
2. In the **Posting Preview** window, choose the **G/L Entry** action, and then choose the **Show Related Entries** action.

G/L entries to be posted to the specified deferral account, for example, Unearned Income, are denoted by the description that you entered in the **Period Desc.** field in the deferral template, for example, "Expenses deferred for February 2016".

## <a name="to-review-posted-deferrals-in-the-sales-deferral-summary-report"></a>To review posted deferrals in the Sales Deferral Summary report
**Note**: The steps in this procedure are the same as when you review the Purchasing Deferral Summary report.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Deferral Summary**, and then choose the related link.
2. In the **Sales Deferral Summary** window, in the **Balance as of** field, enter the date up to which you want to see deferred revenues.
3. Choose the **Preview** button.

## <a name="see-also"></a>See Also
[Finance](finance-setup.md)  
[Set Up Core Financial Processes](finance-setup-setup-finance-setup.md)  
[How to: Work With General Journals](ui-work-general-journals.md)
