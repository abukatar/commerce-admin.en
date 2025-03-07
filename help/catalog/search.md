---
title: Catalog search overview
description: Learn about the Quick Search and Advanced Search tools that customers can use to locate products on the storefront.
---
# Catalog search overview

>[!TIP]
>
>[Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html) delivers a fast, super-relevant, and intuitive search experience and is available for Adobe Commerce at no additional charge. This section describes the standard search functionality that might differ from Live Search.

Research shows that people who use search are more likely to make a purchase than those who rely on navigation alone. In fact, according to some studies, people who use search are nearly twice as likely to make a purchase.

The following sections describe how customers search for products in your catalog, and how you can configure catalog search.

## Quick Search

>[!NOTE]
>
>When [Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/live-search-storefront/quick-tour.html) is installed, the search box returns "search as you type" results in a pop over.

The Search box in the header of the store helps visitors find products in your catalog. The search text can be the full or partial product name or any other word or phrase that describes the product. The search terms that people use to find products can be managed from the Admin.

1. For **[!UICONTROL Search]**, the customer enters the first few letters of what they want to find.

   Any matches in the catalog appear below, with the number of results found.

1. The customer presses the Enter key or clicks a result in the list of matching products.

   ![Search](./assets/storefront-search-box.png)<!-- zoom -->

## Advanced Search

>[!NOTE]
>
>The advanced form search functionality described here does not apply to [Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html).

Advanced Search lets shoppers search the catalog based on values entered into a form. Because the form contains multiple fields, a single search can include several parameters. The result is a list of all products in the catalog that match the criteria. A link to Advanced Search is in the footer of your store.

![Advanced Search](./assets/storefront-search-advanced.png)<!-- zoom -->

Each field in the form corresponds to an attribute from your product catalog. To add a field, set the frontend properties of the attribute to `Include in Advanced Search`. As a best practice, include only the fields that customers are most likely to use to find a product, because having too many slows down the search.

1. In the footer of the store, the customer clicks **[!UICONTROL Advanced Search]**.

1. In the _Advanced Search_ form, adds full or partial values in as many fields as necessary.

1. Clicks **[!UICONTROL Search]** to display the results.

   ![Search Results](./assets/storefront-search-advanced-results-modify.png)<!-- zoom -->

1. If they do not see what they are looking for in the search results, the customer clicks **[!UICONTROL Modify your search]** and tries another combination of criteria.
