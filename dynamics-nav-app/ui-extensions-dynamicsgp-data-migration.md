---
title: Migrate Data from Dynamics GP with the Data Migration Extension
description: Use the Dynamics GP Data Migration extension to migrate customers, vendors, inventory items, and accounts from Dynamics GP to Dynamics NAV.
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0156ec040b96f007674161361e4368b81f7c42d9
ms.contentlocale: en-au
ms.lasthandoff: 10/16/2017

---
# <a name="the-dynamics-gp-data-migration-extension-for-dynamics-nav"></a><span data-ttu-id="d4855-103">The Dynamics GP Data Migration Extension for Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="d4855-103">The Dynamics GP Data Migration Extension for Dynamics NAV</span></span>
<span data-ttu-id="d4855-104">This extension makes it easy to migrate customers, vendors, inventory items, and accounts from Dynamics GP to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="d4855-104">This extension makes it easy to migrate customers, vendors, inventory items, and accounts from Dynamics GP to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="d4855-105">If your business uses Dynamics GP today, you can export the relevant master records and then open an assisted setup guide to add the data to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="d4855-105">If your business uses Dynamics GP today, you can export the relevant master records and then open an assisted setup guide to add the data to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="d4855-106">For more information, see [Migrate Business Data from Other Finance Systems](upload-data.md).</span><span class="sxs-lookup"><span data-stu-id="d4855-106">For more information, see [Migrate Business Data from Other Finance Systems](upload-data.md).</span></span>

## <a name="exporting-data-from-dynamics-gp"></a><span data-ttu-id="d4855-107">Exporting Data from Dynamics GP</span><span class="sxs-lookup"><span data-stu-id="d4855-107">Exporting Data from Dynamics GP</span></span>
<span data-ttu-id="d4855-108">You must have exported some or all of your existing customers, vendors, inventory items, and accounts to a file, using the Dynamics GP functionality for data export.</span><span class="sxs-lookup"><span data-stu-id="d4855-108">You must have exported some or all of your existing customers, vendors, inventory items, and accounts to a file, using the Dynamics GP functionality for data export.</span></span> <span data-ttu-id="d4855-109">For the purposes of [!INCLUDE[d365fin](includes/d365fin_md.md)], you can export the following types of data:</span><span class="sxs-lookup"><span data-stu-id="d4855-109">For the purposes of [!INCLUDE[d365fin](includes/d365fin_md.md)], you can export the following types of data:</span></span>

* <span data-ttu-id="d4855-110">Account</span><span class="sxs-lookup"><span data-stu-id="d4855-110">Account</span></span>  
* <span data-ttu-id="d4855-111">Customer</span><span class="sxs-lookup"><span data-stu-id="d4855-111">Customer</span></span>  
* <span data-ttu-id="d4855-112">Item</span><span class="sxs-lookup"><span data-stu-id="d4855-112">Item</span></span>  
* <span data-ttu-id="d4855-113">Vendor</span><span class="sxs-lookup"><span data-stu-id="d4855-113">Vendor</span></span>  

<span data-ttu-id="d4855-114">The Dynamics GP Data Migration extension automatically maps the exported data so that your data is quickly available to you in your new [!INCLUDE[d365fin](includes/d365fin_md.md)] company.</span><span class="sxs-lookup"><span data-stu-id="d4855-114">The Dynamics GP Data Migration extension automatically maps the exported data so that your data is quickly available to you in your new [!INCLUDE[d365fin](includes/d365fin_md.md)] company.</span></span> <span data-ttu-id="d4855-115">During the process, supporting setup information is created, such as posting groups.</span><span class="sxs-lookup"><span data-stu-id="d4855-115">During the process, supporting setup information is created, such as posting groups.</span></span> <span data-ttu-id="d4855-116">Inventory items will be brought into the system with FIFO as the cost valuation method.</span><span class="sxs-lookup"><span data-stu-id="d4855-116">Inventory items will be brought into the system with FIFO as the cost valuation method.</span></span> <span data-ttu-id="d4855-117">Accounts will be set up as the main account segment from Dynamics GP with dimensions, because [!INCLUDE[d365fin](includes/d365fin_long_md.md)] does not have account segments.</span><span class="sxs-lookup"><span data-stu-id="d4855-117">Accounts will be set up as the main account segment from Dynamics GP with dimensions, because [!INCLUDE[d365fin](includes/d365fin_long_md.md)] does not have account segments.</span></span>

## <a name="see-also"></a><span data-ttu-id="d4855-118">See Also</span><span class="sxs-lookup"><span data-stu-id="d4855-118">See Also</span></span>
[<span data-ttu-id="d4855-119">Importing Business Data from Other Finance Systems</span><span class="sxs-lookup"><span data-stu-id="d4855-119">Importing Business Data from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="d4855-120">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions ](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="d4855-120">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions ](ui-extensions.md)</span></span>  
