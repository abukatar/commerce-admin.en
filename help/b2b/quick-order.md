---
title: Quick Orders
description: Learn about quick order functionality and enabling it for your customers.
exl-id: 7007e1b4-a64f-46fe-a235-3ca9f64e77e4
---
# Quick Orders

The Quick Order feature reduces the order process to several clicks for customers who know the product name or SKU of the products they want to order. Orders with multiple SKUs can be entered manually, or imported into the Quick Order form. Quick Order can be used by customers who are logged in to their accounts, and by guests. When enabled, the Quick Order link appears at the top of the page, next to the customer name.

![Quick Order Link](./assets/quick-order-link.png)<!-- zoom -->

## Step 1: Enable Quick Orders

1. On the _Admin_ sidebar, go to **[!UICONTROL Stores]** > _[!UICONTROL Settings]_ > **[!UICONTROL Configuration]**.

1. In the _[!UICONTROL General]_ section on the left panel, choose **[!UICONTROL B2B Features]**.

1. Set **[!UICONTROL Enable Quick Order]** to `Yes`.

    ![Enable Quick Order](./assets/quick-orders-config.png)<!-- zoom -->

1. Click **[!UICONTROL Save Config]**.

1. When prompted, click [Cache Management](https://docs.magento.com/user-guide/system/cache-management.html) and refresh any invalid caches.

## Step 2: Specify products for Quick Order

Customers can specify products for Quick Order using either of the following methods.

### Method 1: Enter individual products

1. The customer clicks the **[!UICONTROL Quick Order]** link.

1. Selects the product by SKU or product name:

   - To place a quick order by SKU, does the following:

      - Enters the **[!UICONTROL SKU]**.

      - Clicks **[!UICONTROL Add to List]**.

         The SKU appears in the input line, with the product detail below.

         ![Quick Order Detail](./assets/quick-order-product-detail.png)<!-- zoom -->

   - To place a quick order by Product Name, does the following:

      - Enters the first few characters of the **[!UICONTROL Product Name]**.

         >[!NOTE]
         >
         >Do not use the _Enter_ key to choose the name of the product.

      - When the list of possible matches appears, clicks the product that you want to order.

          ![Click to Choose Product Name](./assets/quick-order-product-name.png)<!-- zoom -->

1. Enters the **[!UICONTROL Qty]**.

1. Using the next input line, repeats this process as many times as necessary.

1. Clicks **[!UICONTROL Add to Cart]**.

### Method 2: Enter multiple products

1. In the **[!UICONTROL Enter Multiple SKUs]** box, the customer does one of the following:

   - Enters one SKU per line

   - Enters all SKUs on the same line, separated by commas, and without spaces.

      ![Enter Multiple SKUs](./assets/quick-order-skus.png)<!-- zoom -->

1. To add the products to the list, clicks **[!UICONTROL Add to List]**.

1. Enters the **[!UICONTROL Qty]** to be ordered for each item in the list.

   ![Quick Order List](./assets/quick-order-skus-detail.png)<!-- zoom -->

   >[!NOTE]
   >
   >If the product has required options, you are prompted to choose the options. Wait until you reach the shopping cart to add product options.

   ![Choose Options](./assets/quick-order-skus-product-options.png)<!-- zoom -->

### Method 3: Upload a list of products

1. In the _[!UICONTROL Add from File]_ section, click **[!UICONTROL Download Sample]** to download an order template.

    ![Add from File](./assets/quick-order-skus-add-from-file.png)<!-- zoom -->

1. Opens the downloaded file.

1. Uses the template to add the product SKUs to upload for the Quick Order list.

1. When complete, clicks **[!UICONTROL Save]**.

    ![SKUs to Upload](./assets/quick-order-skus-add-from-file-sample.png)<!-- zoom -->

1. To upload the file, clicks **[!UICONTROL Choose]** and selects the file from their system.

   The items are added to the Quick Order list.

1. When ready, clicks **[!UICONTROL Add to Cart]**.

After the customer creates the quick order, they can proceed through checkout as usual.

![Quick Order](./assets/quick-order-add-to-cart.png)<!-- zoom -->
