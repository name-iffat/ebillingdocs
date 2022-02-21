# Home

## On Boarding Screen (UI)
> First screen when user open app for first time
 Open `lib/screens/home/onboard_screen.dart` file in project

  ![On Board screen](/img/onboard-screen.png)
  
-----
 ## Home Tab
 Open `lib/menu/maintab.dart` file in project

 ![Product list screen](/img/maintab.png)


-----
## Tabbar

 ![Tabbar](/img/tabbar.png)

> 🔲This consist of home, category, search, cart and profile button. Click below to go to site.
>>🏠[Home button](#home-tab)

>>🗄[Category button](category.md)

>>🔍[Search button](#search)

>>👜[Cart button](#cart-screen)

>>👤[Profile button](#profile-screen)

For the tabbar main function and to apply existed style of fluxstore tabbar can be access by:
> Tabbar Styles that provided by Fluxstore shown by [👉CLICK HERE](https://support.inspireui.com/help-center/articles/42/44/11/customize-ui-layout#7-dynamic-tabbar)
+ Open `lib/menu/maintab.dart` file in project.

While the tabbar UI layout can be access by:
+ Open `lib/modules/dynamic_layout/tabbar/tabbar_custom.dart` file in project.

For tabbar icon can be access by:
+ Open `lib/modules/dynamic_layout/tabbar/tabbar_custom.dart` file in project.

-----
## Logo 
 ![Logo Home](/img/logo-home.png)

> 🔲This consist of search button, sidebar and the logo. For chart and notification function can be enable by fluxbuilder or manually at config_en.json . 

+ Open `lib/modules/dynamic_layout/logo/logo.dart` file in project

For Sidebar function:

+ Open `lib/menu/sidebar.dart` file in project

![Sidebar](/img/sidebar.png)


<span id="search">For Search function:<span>

 > ❗On home page search file is not the same as search at the tab bar

+ Open `lib/modules/dynamic_layout/search/home_search_page.dart
` file in project

 ![Homepage Search](/img/search-home.png)

-----

## Category screen
Open ``lib/screens/categories/categories_screen.dart`` file in project

![Category screen](/img/category-screen.png)

-----

## Search Screen
This search screen is from the bottom tabbar.
>💠 To differentiate between search screen from home tab and tabbar is the **tabbar has title "Search"**

Open `lib/screens/search/search_screen.dart` file in project.

 ![Search Tabbar Screen](/img/search-tabbar.png)

-----
## Cart Screen
Open `lib/screens/cart/my_cart_screen.dart` file in project.

 ![Cart Screen](/img/my-cart-screen.png)

-----
## Profile Screen

Open `lib/screens/settings/settings_screen.dart` file in project.
> 🔲This consist of profile details, ibilling wallet and setting.

 ![Profile Screen](/img/profile-screen.png)

👉For more about profile screen widget, **[CLICK HERE!](profile.md)** .