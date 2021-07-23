# Custom theme with ACF Page Builder
1. Create an acf-json folder on your theme directory and keep changes to the acf field json under version control
https://www.advancedcustomfields.com/resources/local-json/
https://www.awesomeacf.com/how-to-avoid-conflicts-when-using-the-acf-local-json-feature/
2. Hide the custom fields option on the production site https://www.awesomeacf.com/snippets/hide-the-acf-admin-menu-item-on-selected-sites/
3. Always check a field value exists before trying to display the value. php error will occur if the value does not exist. https://www.advancedcustomfields.com/resources/get_field/
