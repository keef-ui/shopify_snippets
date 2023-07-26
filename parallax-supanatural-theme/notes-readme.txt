- create dwan theme
- copy headr.liquid
- copy custom.css
*** Edit templet.liquid to include custom.css -- paste follwoing around  line 222 - just after base.css ***
   {{ 'custom.css' | asset_url | stylesheet_tag }}

- copy over cart icon  

*********** Header should work now   *******

in page builder set sticky header to --> always reduce logo size

- Setup new product in product page
-