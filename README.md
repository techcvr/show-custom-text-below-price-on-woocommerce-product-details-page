# show-custom-text-below-price-on-woocommerce-product-details-page

Add the below code on function.php

```php

add_action( 'woocommerce_single_product_summary', function() {
	echo "SOMETHING HERE";
}, 10);
