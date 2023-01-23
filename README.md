# myEcommerce
My store based on bigCommerce

Clone cornerstone theme from:
 https://github.com/bigcommerce/cornerstone

Update the fonts in config.json, from "Google_Karla_400" to:
"body-font": "Google_Nunito_400"

Create a custom subdirectory in the templates/pages directory

Create the following four subdirectories under the templates/pages/custom directory:
brand
category
product
page

Create a custom-product.html file in the subdirectory custom/product

Add a product-view-custom.html file in the subdirectory templates/components/products

Update config.stencil.json , add the mapping in "product"
"customLayouts": {
    "brand": {},
    "category": {},
    "page": {},
    "product": {
      "custom-product.html": "/nag-product-2/"
    }
  }