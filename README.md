Changed the name of the product from “Black Leather Bag” to “Handbag”
Added 3 variants to the product: “Black” - “Red” - “Tan” - 
Added the price of each variant respectively 20$ black - 9.99$ red - 1115.01$ tan to the products
Modified the code to ensure when a site visitor clicks on Black variant - only images of the black handbag show. If the user selects red- only red handbags show and so on. 
In regards to step 4, swatches were used (with the bag images inside the pills). The code can be found on **product-variant-options.liquid** from line 63 to 68
Created a **custom-product template** to add the variant options “Unselected” ,“Small”, “Medium”, “Large” - as a DROPDOWN option. the code can be found on **product-variant-options.liquid** from line 97 to 113
When the page is refreshed while the size selected is either small, medium or large - the size variant will be unselected after the page is refreshed. the disable button code can be foung on **buy-buttons.liquid** from line 107 to 124
Commented out the search on **predictive-search.liquid** from line 134 to 171 in order to stop the “Soft Winter Jacket” from being searched because this product will only be offered in a bundle format 
Modified the **buy-buttons.liquid** file from line 91 to 93 and it contains the custom code to disable the add to cart button for the soft winter jacket because it can only be added as a bundle
Created a **free-gift.liquid** section to create the medium size bag and soft winter jacket bundle
In the **product-form.js** file, the code to add the free gift to the cart was implemented from line 95 to 129
In the **cart.js** file, the code to remove the free gift automatically once the bag is removed was implemented from line 110 to 142
