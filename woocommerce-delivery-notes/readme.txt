	=== WooCommerce Print Invoice & Delivery Note ===

Contributors: ashokrane, bhavik.kiri, tychesoftwares, rashmim
Donate link: https://www.paypal.me/TycheSoftwares
Tags: delivery note, packing slip, pdf invoice, delivery, shipping, print order, woocommerce, woothemes, shop
Requires at least: 4.0
Tested up to: 4.9.7
Author URI: https://www.tychesoftwares.com/
Stable tag: 4.4.6
License: GPLv3 or later
License URI: http://www.opensource.org/licenses/gpl-license.php

Print invoices and delivery notes for WooCommerce orders.  

== Description ==

You can print out invoices and delivery notes for the WooCommerce orders. You can also edit the Company/Shop name, Company/Shop postal address and also add personal notes, conditions/policies (like a refund policy) and a footer imprint.

The plugin adds a new side panel on the order page to allow shop administrators to print out the invoice or delivery note. Registered customers can also print their order with a button that is added to the order screen.


= Features =

* Print invoices and delivery notes via the side panel on the "Order Edit" page
* Quickly print invoices and delivery notes on the "Orders" page
* Bulk print invoices and delivery notes
* Allow customers to print the order in the "My Account" page
* Include a print link in customer E-Mails
* Add a company address, a logo and many other information to the invoice and delivery note
* Completely customize the invoice and delivery note template
* Simple invoice numbering
* Supports sequential order numbers
* Supports the WooCommerce refund system
* Intelligent invoice and delivery note template system with hooks and functions.php support  

= Support =

Support can take place in the [public support forums](http://wordpress.org/support/plugin/woocommerce-delivery-notes), where the community can help each other out.

= Contributing =

If you have a patch, or stumbled upon an issue with the source code that isn't a [WooCommerce issue](https://github.com/woothemes/woocommerce/issues?labels=Bug&milestone=22&state=open), you can contribute this back [on GitHub](https://github.com/TycheSoftwares/woocommerce-delivery-notes).

= Translating =

When your language is missing you can contribute a translation to the [GitHub repository](https://github.com/TycheSoftwares/woocommerce-delivery-notes#translating).

**Some of our Pro plugins:**

1. **[Abandoned Cart Pro for WooCommerce](https://www.tychesoftwares.com/store/premium-plugins/woocommerce-abandoned-cart-pro/?utm_source=wprepo&utm_medium=otherprolink&utm_campaign=WCDeliveryNotes "Abandoned Cart Pro for WooCommerce")**

2. **[Booking & Appointment Plugin for WooCommerce](https://www.tychesoftwares.com/store/premium-plugins/woocommerce-booking-plugin/?utm_source=wprepo&utm_medium=link&utm_campaign=WCDeliveryNotes "Booking & Appointment Plugin for WooCommerce")**

3. **[Order Delivery Date Pro for WooCommerce](https://www.tychesoftwares.com/store/premium-plugins/order-delivery-date-for-woocommerce-pro-21/?utm_source=wprepo&utm_medium=link&utm_campaign=WCDeliveryNotes "Order Delivery Date Pro for WooCommerce")**

4. **[Product Delivery Date Pro for WooCommerce](https://www.tychesoftwares.com/store/premium-plugins/product-delivery-date-pro-for-woocommerce/?utm_source=wprepo&utm_medium=link&utm_campaign=WCDeliveryNotes "Product Delivery Date Pro for WooCommerce")**

5. **[Deposits For WooCommerce](https://www.tychesoftwares.com/store/premium-plugins/deposits-for-woocommerce/?utm_source=wprepo&utm_medium=link&utm_campaign=WCDeliveryNotes "Deposits For WooCommerce")**

**Some of our other free plugins:**

1. **[Order Delivery Date for WooCommerce - Lite](https://wordpress.org/plugins/order-delivery-date-for-woocommerce/ "Order Delivery Date for WooCommerce - Lite")**

2. **[Abandoned Cart for WooCommerce](https://wordpress.org/plugins/woocommerce-abandoned-cart/ "Abandoned Cart for WooCommerce")**

3. **[Product Delivery Date for WooCommerce – Lite](https://wordpress.org/plugins/product-delivery-date-for-woocommerce-lite/ "Product Delivery Date for WooCommerce – Lite")**

4. **[Order Delivery Date for WP e-Commerce](https://wordpress.org/plugins/order-delivery-date/ "Order Delivery Date for WP e-Commerce")**

5. **[Prevent Customers To Cancel WooCommerce Orders](https://wordpress.org/plugins/woo-prevent-cancel-order/ "Prevent Customers To Cancel WooCommerce Orders")**

6. **[WooCommerce Coupons by Categories and Tags](https://wordpress.org/plugins/woo-coupons-by-categories-and-tags/ "WooCommerce Coupons by Categories and Tags")**

7. **[Arconix FAQ](https://wordpress.org/plugins/arconix-faq/ "Arconix FAQ")**

8. **[Arconix Shortcodes](https://wordpress.org/plugins/arconix-shortcodes/ "Arconix Shortcodes")**

9. **[Arconix Flexslider](https://wordpress.org/plugins/arconix-flexslider/ "Arconix Flexslider")**

10. **[Arconix Portfolio](https://wordpress.org/plugins/arconix-portfolio/ "Arconix Portfolio")**

11. **[Arconix Testimonials](https://wordpress.org/plugins/arconix-testimonials/ "Arconix Testimonials")**

12. **[Export WordPress Menus](https://wordpress.org/plugins/wp-export-menus/ "Export WordPress Menus")**

**[Developer Documentation](https://www.tychesoftwares.com/docs/print-invoice-apidocs/index.html "Developer Documentation")**

== Installation ==

= Minimum Requirements =

* WooCommerce 2.2 or later
* WordPress 4.0 or later

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don’t need to leave your web browser. To do an automatic install of WooCommerce, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type “WooCommerce Print Invoice” and click Search Plugins. Once you’ve found the plugin you can view details about it such as the the point release, rating and description. Most importantly of course, you can install it by simply clicking “Install Now”.

= Manual installation =

The manual installation method involves downloading the plugin and uploading it to your webserver via your favourite FTP application. The WordPress codex contains [instructions on how to do this here](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

== Frequently Asked Questions ==

= How to prevent that the Website URL and page numbers are printed? =

You can find an option in the print window of your browser to hide those. This is a browser specific option that can't be controlled by the plugin. Please read the browser help for more information.

= Why are my bulk printed orders not splited to separate pages? =

Your browser is to old to create the page breaks correctly. Try to update it to the latest version or use another browser.

= Even though the shipping and billing address is the same, both are still shown, why? =

It depends on your WooCommerce settings. Addresses are displayed the same way as on the WooCommerce account page. Only one address is printed in case you disabled alternative shipping addresses or the whole shipping. In all other cases both addresses are shown.

= It prints the 404 page instead of the order, how to correct that? =

This is most probably due to the permalink settings. Go either to the WordPress Permalink or the WooCommerce Print Settings and save them again.

If that didn't help, go to the WooCommerce 'Accounts' settings tab and make sure that for 'My Account Page' a page is selected.  

= How do I quickly change the font of the invoice and delivery note? =

You can change the font with CSS. Use the `wcdn_head` hook and then write your own CSS code. It's best to place the code in the `functions.php` file of your theme. 

An example that changes the font and makes the addresses very large. Paste the code in the `functions.php` file of your theme:

`
function example_serif_font_and_large_address() {
	?>
		<style>	
			`#page {
				font-size: 1em;
				font-family: Georgia, serif;
			}
			
			.order-addresses address {
				font-size: 2.5em;
				line-height: 125%;
			}
		</style>
	<?php
`}
add_action( 'wcdn_head', 'example_serif_font_and_large_address', 20 );
`

= Can I hide the prices on the delivery note? =

Sure, the easiest way is to hide them with some CSS that is hooked in with `wcdn_head`.

An example that hides the whole price column and the totals. Paste the code in the `functions.php` file of your theme:

`
function example_price_free_delivery_note() {
	?>
		<style>
			.delivery-note .head-item-price,
			.delivery-note .head-price, 
			.delivery-note .product-item-price,
			.delivery-note .product-price,
			.delivery-note .order-items tfoot {
				display: none;
			}
			.delivery-note .head-name,
			.delivery-note .product-name {
				width: 50%;
			}
			.delivery-note .head-quantity,
			.delivery-note .product-quantity {
				width: 50%;
			}
			.delivery-note .order-items tbody tr:last-child {
				border-bottom: 0.24em solid black;
			}
		</style>
	<?php
}
add_action( 'wcdn_head', 'example_price_free_delivery_note', 20 );
`

= I use the receipt in my POS, can I style it? =

Sure, you can style with CSS, very much the same way as the delivery note or invoice. 

An example that hides the addresses. Paste the code in the `functions.php` file of your theme:

`
function example_address_free_receipt() {
	?>
		<style>
			.content {
				padding: 4% 6%;
			}
			.company-address,
			.order-addresses {
				display: none;
			}
			.order-info li span {
				display: inline-block;
				float: right;
			}
			.order-thanks {
				margin-left: inherit;
			}
		</style>
	<?php
}
add_action( 'wcdn_head', 'example_address_free_receipt', 20 );
`

= Is it possible to remove a field from the order info section? =

Yes, use the `wcdn_order_info_fields` filter hook. It returns all the fields as array. Unset or rearrange the values as you like.

An example that removes the 'Payment Method' field. Paste the code in the `functions.php` file of your theme:

`
function example_removed_payment_method( $fields ) {
	unset( $fields['payment_method'] );
	return $fields;
}
add_filter( 'wcdn_order_info_fields', 'example_removed_payment_method' );
`

=  How can I add some more fields to the order info section? =

Use the `wcdn_order_info_fields` filter hook. It returns all the fields as array. Read the WooCommerce documentation to learn how you get custom checkout and order fields. Tip: To get custom meta field values you will most probably need the `get_post_meta( $order->id, 'your_meta_field_name', true);` function and of course the `your_meta_field_name`. 

An example that adds a 'VAT' and 'Customer Number' field to the end of the list. Paste the code in the `functions.php` file of your theme:

`
function example_custom_order_fields( $fields, $order ) {
	$new_fields = array();
		
	if( get_post_meta( $order->id, 'your_meta_field_name', true ) ) {
		$new_fields['your_meta_field_name'] = array( 
			'label' => 'VAT',
			'value' => get_post_meta( $order->id, 'your_meta_field_name', true )
		);
	}
	
	if( get_post_meta( $order->id, 'your_meta_field_name', true ) ) {
		$new_fields['your_meta_field_name'] = array( 
			'label' => 'Customer Number',
			'value' => get_post_meta( $order->id, 'your_meta_field_name', true )
		);
	}
	
	return array_merge( $fields, $new_fields );
}
add_filter( 'wcdn_order_info_fields', 'example_custom_order_fields', 10, 2 );
`

=  What about the product image, can I add it to the invoice and delivery note? =

Yes, use the `wcdn_order_item_before` action hook. It allows you to add html content before the item name.

An example that adds a 40px large product image. Paste the code in the `functions.php` file of your theme:

`
function example_product_image( $product ) {	
	if( isset( $product->id ) && has_post_thumbnail( $product->id ) ) {
		echo get_the_post_thumbnail( $product->id, array( 40, 40 ) );
	}
}
add_action( 'wcdn_order_item_before', 'example_product_image' );
`

= How can I differentiate between invoice and delivery note through CSS? =

The `body` tag contains a class that specifies the template type. The class can be `invoice` or `delivery-note`. You can prefix your style rules to only target one template. For example you could rise the font size for the addresses on the right side:

`
.invoice .billing-address {
	font-size: 2em;
}

.delivery-note .shipping-address {
	font-size: 2em;
}
`

= How do I customize the look of the invoice and delivery note? =

You can use the techniques from the questions above. Or you consider the `wcdn_head` hook to enqueue your own stylesheet. Or for full control, copy the file `style.css` from `woocommerce-delivery-notes/templates/print-order` to `yourtheme/woocommerce/print-order` and start editing it. 

Note: Create the `woocommerce` and `print-order` folders if they do not exist. This way your changes won't be overridden on plugin updates.

= I would like to move the logo to the bottom, put the products between the shipping and billing address and rotate it by 90 degrees, how can I do that? =

Well, first try it with CSS and some filter/action hooks, maybe the questions above can help you. If this isn't enough, you are free to edit the HTML and CSS of the template. Consider this solution only, if you really know some HTML, CSS and PHP! Most probably you want to edit the `print-content.php` and `style.css`. Copy the files from `woocommerce-delivery-notes/templates/print-order` to `yourtheme/woocommerce/print-order` and start editing them. 

Note: Create the `woocommerce` and `print-order` folders if they do not exists. This way your changes won't be overridden on plugin updates.

= Is there a list of all action and filter hooks? =

Unfortunately there isn't yet. But you can look directly at the template files to see what is available. 

= Which template functions are available? =

You can use the functions from WordPress, WooCommerce and every installed plugin or activated theme. You can find all plugin specific functions in the `wcdn-template-functions.php` file. In addition the `$order`variable in the template is just a normal `WC_Order` instance. 

= Can I download the order as PDF instead of printing it out? =

No, this isn't possible. Look for another plugin that can do this.

= I need some more content on the order, how can I add it? =

The plugin uses the exact same content as WooCommerce. If the content isn't available in WooCommerce, then it will neither be in the delivery note and invoice. In case you have some special needs, you first have to enhance WooCommerce to solve your issue. Afterwards you can integrate the solution into the invoice and delivery note template via hooks.

= How can I translate the plugin? =

Upload your language file to `/wp-content/languages/plugins/` (create this folder if it doesn't exist). WordPress will then load the language. Make sure you use the same locale as in your configuration and the correct plugin locale i.e. `woocommerce-delivery-notes-it_IT.mo/.po`. 

Please [contribute your translation](https://github.com/TycheSoftwares/woocommerce-delivery-notes#translating) to include it in the distribution.

== Screenshots ==

1. The clean invoice print view. 
2. Print panel.
3. Quick print actions.
4. Bulk print orders.
5. Enter company and contact information.
6. Customers can also print the order.

== Changelog ==

= Minimum Requirements: WooCommerce 2.2 =

= 4.4.7 (24.11.2018) =

* Fix – Fixed compatibility related issue with WooCommerce Product Add-ons v3.0.x. Options were not being printed.
* Fix – Fixed compatibility related issue with Woocommerce Partial Orders Pro Plugin.

= 4.4.6 (22.10.2018) =

* .po, .mo is updated for all the other languages.

= 4.4.5 (22.10.2018) =

* .pot file updated.

= 4.4.4 (13.10.2018) =

* Removed the Welcome page of the plugin and also removed the promotional notices which were being displayed on admin end of the WordPress website.

= 4.4.3 (23.07.2018) =

* Usage Tracking has been added in the plugin. It provides an option to allow  tracking of the non-sensitive data of our plugin from the website. You can read more about it [here](https://www.tychesoftwares.com/docs/docs/woocommerce-print-invoice-delivery-note/usage-tracking/).

= 4.4.2 (22.02.2018) =

* Fix - With the latest WooCommerce version 3.3, the icons for Print were missing. This is fixed.

= 4.4.1 (29.12.2017) =

* This version has 1 bug fix.

* Fix - PHP short tag was inadvertently added in the plugin in v4.4, which was causing an error. This has been fixed.

= 4.4 (29.12.2017) =

* This version has 1 bug fix.

* Fix - Earlier with WooCommerce Local Pickup Plus v2.x.x, pickup locations were not displayed on the invoices, delivery notes & receipts. Now, the plugin is compatible with it and it will display the pickup locations. 

* Code Enhancement - Now, the plugin has the uninstall file for deleting the plugin options.

= 4.3.6 (19.12.2017) =

* Added translation for the word 'Price' for dutch language
* Removed Pro version link that was not going anywhere

= 4.3.5 (14.11.2017) =

* Fix issue of invoice date label not appearing translated

= 4.3.4.1 (07.11.2017) =

* Updating missing .mo files for Japanese and Norwegian.

= 4.3.4 (26.09.2017) =

* .po and .mo files for Japanese and Norwegian language is added in the plugin. The plugin strings can now be translated to this languages using these files.

= 4.3.3 (13.09.2017) =

* Fix - The unwanted attributes from products were getting displayed in the invoice.

* Fix - Notice of deprecated function get_item_downloads() in the invoice for downloadable products.

= 4.3.2 (05.09.2017) =

* In this version deprecated functions and classes have been removed. Because of that attributes were missing and attribute slug was getting printed on Invoice page. This has been fixed.

* Fix - There was no line break before SKU element for variable products on Invoice page. This has been fixed.

* Fix - The deprecated function WC_Order::get_order_currency has been removed and replaced with get_currency().

= 4.3.1 (23.08.2017) =

* This version has 1 bug fix.

* Fix - The attributes of variable product were not displayed with the variation name in the Print screen. This has been fixed.

= 4.3 (19.08.2017) =

* This version has 1 bug fix.

* Fix - Warnings were displayed on My Account, Checkout, Orders page with WooCommerce version 3.0.x. This has been fixed.

= 4.2.0 =

* Tweak - Refactored settings screen
* Fix - Compatibility with latest WooCommerce
* Fix - Print preview loading indicators
* Fix - Icon font embed
* Dev - Load only one instance of the plugin (singleton class)
* Dev - New settings hooks that work better with WooCommerce

= 4.1.6 =

* Fix - More flexible protocol checks of email permalinks

= 4.1.5 =

* Fix - Check protocol of email permalinks
* Fix - Show preview links on the settings page
* Fix - Consistent privileges for users with admin access

= 4.1.4 =

* Fix - Double check the bulk action type to improve bulk order deletion
* Fix - Default arguments for the E-Mail hook

= 4.1.3 =

* Feature - Better support for WooCommerce 2.3 refunds

= 4.1.2 =

* Fix - For a fatal error caused by an unknown property in the plugin update system
* Fix - Where the 'Types' options didn't stick in some cases

= 4.1.1 =

* Fix - For a fatal error caused by an unknown property in the plugin update system

= 4.1 =

* Feature - Support for WooCommerce 2.2 refunds 
* Feature - Option to add a print link to customer emails
* Tweak - Code improvements and some new hooks

= 4.0.2 =

* Tweak - Second attempt for better spacing between price columns

= 4.0.1 =

* Tweak - Better spacing between price columns

= 4.0 =

* The print page now also includes the item price
* Customize titles with your own translation file (woocommerce-delivery-notes-xx_XX.mo). Place it in /wp-content/languages/plugins to override the plugin language. 

= 3.4.2 =

* Remove some left over developer comments from the print page

= 3.4.1 =

* Fix an issue where a blank page was printed in WooCommerce 2.1

= 3.4 =

**Note: The template was modified. Please check your print-content.php if you copied it to your theme directory.**

* Improved WooCommerce 2.2 compatibility
* Fix an issue were shipping and billing addresses did not respect the WooCommerce settings
* Better way to reset the invoice number counter

= 3.3.1 =

* Small code improvements

= 3.3 =

* WordPress 4.0 and WooCommerce 2.2 compatibility
* Fix an issue where the print buttons were hidden after the update

= 3.2.3 =

* WordPress 4.0 and WooCommerce 2.2 compatibility
* Template: Improved the CSS to generate less blank pages
* Fixed the settings link on the Plugins page

= 3.2.2 =

* Some language upadates. Old outdated languages were removed. Please [contribute your language](https://github.com/piffpaffpuff/woocommerce-delivery-notes#translating)!
* Fix a print issue with not completed orders.
* Tweaked JavaScript for the theme print button to gracefully handle non-modern browsers.

= 3.2.1 =

* New template function for the invoice date 
* Fix invoice number display logic 
* Fix slashes in the options fields

= 3.2 =

* Improved theme print button: Print the invoice only for completed orders and a receipt for all other order states. This can be changed via 'wcdn_theme_print_button_template_type' filter hook.
* Fix the print button on the "Thank You" page for guest checkouts
* Added CSS classes to the admin side panel

= 3.1.1 =

* Fix the hidden loading indicator on order edit screen
* Other small visual optimizations
* Later plugin load hook for better compatibility

= 3.1 =

**Note: Template changes had to be made. Please control your template after the update in case you applied some custom styling.**

* By popular demand the 'Quantity' column is back in the template
* Basic invoice numbering

= 3.0.6 =

* Fixed the known issue where the print button stopped working becuse of SSL
* Fixed an issue where the print page was redirected to the account page 

= 3.0.5 =

**Known issue: Printing won't work when your account uses SSL and the rest of the page doesn't. The issue will be fixed in a future version.**

* Added SKU to the template
* Modified the alignment of product attributes in the template
* Print buttons in the theme will print the invoice (can be changed with hook) 

= 3.0.4 =

* Save the endpoint at activation to not print a 404 page. (Note: Try to resave the print settings if the issue persists after the update.)

= 3.0.3 =

**Attention: This update works only with WooCommerce 2.1 (or later) and Wordpress 3.8 (or later). Install it only if your system meets the requirements.**

* Supports only WooCommerce 2.1 (or later)
* Bulk print actions
* Print buttons in the front-end
* Redesigned template look
* New template structure and action hooks

== Upgrade Notice ==

= 4.2.0 =

4.2.0 requires at least WooCommerce 2.2.

= 4.1.5 =

4.1.5 requires at least WooCommerce 2.2.
