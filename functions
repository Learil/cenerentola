<?php
// SIDEBAR NEGOZIO
if ( ! function_exists( 'negozio_sidebar' ) ) {
// Register Sidebar
function negozio_sidebar() {

	$args = array(
		'name'          => __( 'Sidebar pagina Negozio', 'text_domain' ),
		'id' 			=> 'negozio_sidebar',
		'description'   => __( 'La sidebar che va nella pagina del negozio', 'text_domain' ),
		'before_title'  => '<span class="h2"> <h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div></span>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'negozio_sidebar' );
}

// SIDEBAR HOME SX
if ( ! function_exists( 'home_sx' ) ) {
// Register Sidebar
function home_sx() {

	$args = array(
		'name'          => __( 'Home sinistra', 'text_domain' ),
		'id' 			=> 'home_sx',
		'description'   => __( 'La sidebar che va nella Home, lato sinistro', 'text_domain' ),
		'before_title'  => '<span class="h2"> <h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div></span>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'home_sx' );
}

// SIDEBAR HOME DX SOCIAL
if ( ! function_exists( 'home_dx' ) ) {
// Register Sidebar
function home_dx() {

	$args = array(
		'name'          => __( 'Home destra', 'text_domain' ),
		'id' 			=> 'home_dx',
		'description'   => __( 'La sidebar che va nella Home, lato destro', 'text_domain' ),
		'before_title'  => '<span class="h2"> <h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div></span>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'home_dx' );
}

// SIDEBAR CONTATTI sX 
if ( ! function_exists( 'contatti_sx' ) ) {
// Register Sidebar
function contatti_sx() {

	$args = array(
		'name'          => __( 'Contatti sinistra', 'text_domain' ),
		'id' 			=> 'contatti_sx',
		'description'   => __( 'La sidebar che va nei Contatti, lato sinistro', 'text_domain' ),
		'before_title'  => '<span class="h2"> <h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div></span>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'contatti_sx' );
}

// SIDEBAR CONTATTI DX 
if ( ! function_exists( 'contatti_dx' ) ) {
// Register Sidebar
function contatti_dx() {

	$args = array(
		'name'          => __( 'Contatti destra', 'text_domain' ),
		'id' 			=> 'contatti_dx',
		'description'   => __( 'La sidebar che va nei Contatti, lato destro', 'text_domain' ),
		'before_title'  => '<span class="h2"> <h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div></span>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'contatti_dx' );
}

// SIDEBAR SHOP ONLINE A SX
if ( ! function_exists( 'shop_online' ) ) {
// Register Sidebar
function shop_online() {

	$args = array(
		'name'          => __( 'shop_online', 'text_domain' ),
		'id' 			=> 'shop_online',
		'description'   => __( 'La sidebar che va nella pagina Shop online, con le categorie', 'text_domain' ),
		'before_title'  => '<span class="h2"> <h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div></span>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'shop_online' );
}

// SIDEBAR TAB WIDGET
if ( ! function_exists( 'tab_widget' ) ) {
// Register Sidebar
function tab_widget() {

	$args = array(
		'name'          => __( 'tab_widget', 'text_domain' ),
		'id' 			=> 'tab_widget',
		'description'   => __( 'La sidebar che va nella pagina Shop online e in home, con i tab e le slide prodotto', 'text_domain' ),
		'before_title'  => '<h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'tab_widget' );
}

// SIDEBAR BLOG
if ( ! function_exists( 'blog' ) ) {
// Register Sidebar
function blog() {

	$args = array(
		'name'          => __( 'blog', 'text_domain' ),
		'id' 			=> 'blog',
		'description'   => __( 'La sidebar che va nel blog', 'text_domain' ),
		'before_title'  => '<span class="h2"> <h2 class="widgettitle">',
		'after_title'   => '</h2><div class="clearh2"> </div></span>',
		'before_widget' => '<li id="%1$s" class="widget %2$s">',
		'after_widget'  => '</li>',
	);
	register_sidebar( $args );

}
// Hook into the 'widgets_init' action
add_action( 'widgets_init', 'blog' );
}




// SINGOLI PRODOTTI ___________________________________
remove_action( 'woocommerce_single_product_summary', 'woocommerce_template_single_meta', 40 );
add_action( 'woocommerce_single_product_summary', 'woocommerce_template_single_meta', 10 );

remove_action( 'woocommerce_single_product_summary', 'woocommerce_template_single_price', 10 );
add_action( 'woocommerce_single_product_summary', 'woocommerce_template_single_price', 25 );

remove_action( 'woocommerce_after_single_product_summary', 'woocommerce_output_product_data_tabs', 10 );
add_action( 'woocommerce_single_product_summary', 'woocommerce_output_product_data_tabs', 55 );



// SINGOLI PRODOTTI TAB ___________________________________
add_filter( 'woocommerce_product_tabs', 'woo_rename_tabs', 98 );
function woo_rename_tabs( $tabs ) {
 
$tabs['description']['title'] = __( 'More Information' ); // Rename the description tab
$tabs['reviews']['title'] = __( 'Commenti e domande' ); // Rename the reviews tab
$tabs['additional_information']['title'] = __( 'Product Data' ); // Rename the additional information tab
 
return $tabs; 
}

add_filter( 'woocommerce_product_tabs', 'woo_remove_product_tabs', 98 );
 
function woo_remove_product_tabs( $tabs ) {
 
unset( $tabs['description'] ); // Remove the description tab
unset( $tabs['additional_information'] ); // Remove the additional information tab
 
return $tabs;
}

// CANCELLA IL CONTENT EDITOR ___________________________________
function remove_product_editor() {
  remove_post_type_support( 'product', 'editor' );
}
add_action( 'init', 'remove_product_editor' );

// AGGIUNGI SHORTCODE ALLA DESCRIZ BREVE ___________________________________


// CARRELLO IN AJAX ___________________________________
add_filter('add_to_cart_fragments', 'woocommerce_header_add_to_cart_fragment');
 
function woocommerce_header_add_to_cart_fragment( $fragments ) {
global $woocommerce;
ob_start();
?>
<a class="cart-contents" href="<?php echo $woocommerce->cart->get_cart_url(); ?>" title="<?php _e('View your shopping cart', 'woothemes'); ?>"><?php echo sprintf(_n('%d item', '%d items', $woocommerce->cart->cart_contents_count, 'woothemes'), $woocommerce->cart->cart_contents_count);?> - <?php echo $woocommerce->cart->get_cart_total(); ?></a>
<?php
$fragments['a.cart-contents'] = ob_get_clean();
return $fragments;
}

// 3 PRODOTTI NELLE COLONNE SHOP ONLINE ___________________________________
add_filter( 'loop_shop_columns', 'wc_loop_shop_columns', 1, 10 );
function wc_loop_shop_columns( $number_columns ) {
return 3;
}

// COLONNE DEGLI UPSELLS ___________________________________
remove_action( 'woocommerce_after_single_product_summary', 'woocommerce_upsell_display', 15 );
add_action( 'woocommerce_after_single_product_summary', 'woocommerce_output_upsells', 15 );
 
if ( ! function_exists( 'woocommerce_output_upsells' ) ) {
function woocommerce_output_upsells() {
woocommerce_upsell_display( 4,4 ); // Display 3 products in rows of 3
}
}

// FAR COMPARIRE GLI SCONTI ___________________________________
add_filter( 'woocommerce_sale_price_html', 'woocommerce_custom_sales_price', 10, 2 );
function woocommerce_custom_sales_price( $price, $product ) {
$percentage = round( ( ( $product->regular_price - $product->sale_price ) / $product->regular_price ) * 100 );
return $price . sprintf( __(' Sconto %s', 'woocommerce' ), $percentage . '%' );
}

?>
