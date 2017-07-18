---
title: 'How to: Process Sales Returns or Cancellations'
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 92b65379f2ec633712a2b2c0f06615c6de61cc6e
ms.contentlocale: en-au
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-process-sales-returns-or-cancellations"></a>How to: Process Sales Returns or Cancellations
If your customer wants to return or get reimbursement for items or services that you have sold and received payment for, you must create and post a sales CR/Adj note that specifies the requested change. To include the correct sales invoice information, you can create the sales CR/Adj note from the posted sales invoice or use a copy function.

In addition to the original posted sales invoice, you can apply the sales CR/Adj note to other sales documents, for example another posted sales invoice, because the customer is also returning items delivered with that invoice.

A return or reimbursement may relate to only some of the items or services on the original sales invoice. In that case, you must edit information on the lines on the sales CR/Adj note. When you post the sales CR/Adj note, the sales documents that are affected by the change are reversed and a refund payment can be created for the customer.

You can send the posted sales CR/Adj note to the customer to confirm the return or cancellation and communicate that the related value will be reimbursed, for example when the items are returned.

## <a name="to-create-a-sales-credit-memo-from-a-posted-sales-invoice"></a>To create a sales CR/Adj note from a posted sales invoice
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Posted Sales Invoices**, and the choose the related link.  
2. In the **Posted Sales Invoices** window, select the posted sales invoice that you want to reverse, and then choose the **Create Corrective CR/Adj Note** action.

    Most fields on the sales CR/Adj note header are filled with the information from the posted sales invoice. You can edit all the fields, for example with new information that reflects the return agreement.
3. Edit information on the lines according to the agreement, such as the number of items returned or the amount to be reimbursed.
4. Choose the **Apply Entries** action.
5. In the **Apply Customer Entries** window, select the line with the posted sales document that you want to apply the sales CR/Adj note to, and then choose the **Applies-to ID** action.

    The number of the sales CR/Adj note is inserted in the **Applies-to ID** field.  
6. In the **Amount to Apply** field, enter the amount that you want to apply if smaller than the original amount.

    At the bottom of the **Apply Customer Entries** window, you can see the total amount to apply to reverse all involved entries, namely when the value in the **Balance** field is zero.  
7. Choose the **OK** button. When you post the sales CR/Adj note, it will be applied to the specified posted sales documents.

    When you have created or edited the needed sales CR/Adj note lines and the single or multiple applications are specified, you can proceed to post the sales CR/Adj note.
8. Choose the **Post and Send** action.

The **Post and Send Confirmation** dialogue box opens showing the preferred sending method for the customer. You can change the sending method by choosing the lookup button for the **Send Document** to field. For more information, see [How to: Set Up Document Sending Profiles](sales-how-setup-document-send-profiles.md).

The posted sales documents that you applied the CR/Adj note to are now reversed, and a refund payment can be created for the customer. The sales CR/Adj note is removed and replaced with a new document in the list of posted sales CR/Adj notes.

## <a name="to-create-a-sales-credit-memo-from-scratch"></a>To create a sales CR/Adj note from scratch
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Posted Sales Invoices**, and then choose the related link.
2. Choose the **New** action to open a new empty sales CR/Adj note.
3. In the **Customer** field, enter the name of an existing customer.
4. Choose the **Copy Document** action.
5. In the **Copy Sales Document** window, in the **Document Type** field, select **Posted Invoice**.
6. Choose the **Document No.** field to open the **Posted Sales Invoices** window, and then select the posted sales invoice that contains lines that you want to reverse.
7. Select the **Recalculate Lines** check box if you want the copied posted sales invoice lines to be updated with any changes in item price and unit cost since the invoice was posted.
8. Choose the **OK** button. The copied invoice lines are inserted in the sales CR/Adj note.
9. Complete the sales CR/Adj note as explained in the "To create a sales CR/Adj note from a posted sales invoice" section in this topic.

## <a name="see-also"></a>See Also  
[Manage Sales](sales-manage-sales.md)  
[Set Up Sales](sales-setup-sales.md)  
[How to: Send Documents by Email](ui-how-send-documents-email.md)  
[Work with Dynamics NAV](ui-work-product.md)

