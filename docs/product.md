# Product

## Product model
Open `lib/models/category_model.dart` file in project

## Product List screen
The screen consist product list

Open `lib/screens/products/products_screen.dart` file in project

![Product screen-list](/img/product-screen-list.png)

-----
## Bottom Cart
The bottom cart  will navigate to "My Chart"

Open `lib/widgets/product/product_bottom_sheet.dart` file in project

![Bottom cart](/img/bottom-cart.png)


-----
## Product Card View
> This product card  have wishlist button & add to cart button .

Open `lib/widgets/product/product_card_view.dart` file in project

![Product card](/img/product-card.png)

## Wishlist button (❤Heart button)
+ Open `lib/widgets/product/widgets/heart_button.dart` file in project

## Cart button
+ Open `lib/widgets/product/widgets/cart_icon.dart` file in project

-----

## Product Detail Screen
Show a product detail.

+ Open `lib/screens/detail/product_detail_screen.dart` file in project

![Product detail screen](/img/product-screen.png)

For 3 top icon that are close , wishlish & show menu can be access by:
+ Open `lib/screens/detail/themes/simple_type.dart` file in project.

For quantity selection, buy now button & add to cart button can be access by:

+ Open `lib/frameworks/product_variant_mixin.dart` file in project.

>❗**BUY NOW** button & **ADD TO CART** style can access above, but **Quantity selection** style can be access at `lib/widgets/product/widgets/quantity_selection.dart` in file project.

- Description & Categories here are an expansion that can be access by open `lib/widgets/common/expansion_info.dart` file in project
    - For **Description Info** can be access at `lib/screens/detail/widgets/product_description.dart` in file project.
    - For **Categories Info** can be access at `lib/screens/detail/widgets/product_detail_categories.dart` in file project.

For Related product list can be access at `lib/screens/detail/widgets/related_product.dart` in file project.




