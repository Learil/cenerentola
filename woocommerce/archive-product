<?php
/**
 * The Template for displaying product archives, including the main shop page which is a post type archive.
 *
 * Override this template by copying it to yourtheme/woocommerce/archive-product.php
 *
 * @author 		WooThemes
 * @package 	WooCommerce/Templates
 * @version     2.0.0
 */

if ( ! defined( 'ABSPATH' ) ) exit; // Exit if accessed directly

get_header( 'shop' ); ?>

	<?php
		/**
		 * woocommerce_before_main_content hook
		 *
		 * @hooked woocommerce_output_content_wrapper - 10 (outputs opening divs for the content)
		 * @hooked woocommerce_breadcrumb - 20
		 */
		do_action( 'woocommerce_before_main_content' );
	?>


		<ul id="catimg">
			<li id="scarpe"> 
				<a href="http://www.cenerentolacuneo.it/scarpe/">
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/scarpe.png" />
				</a>
			</li>
			<li id="offerte"> 
				<a href="http://www.cenerentolacuneo.it/offerte/">
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/offerte.png" />
				</a>
			</li>
			<li id="accessori"> 
				<a href="http://www.cenerentolacuneo.it/accessori/">
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/accessori.png" />
				</a>
			</li>
			<li id="abbigliamento">
				 <a href="http://www.cenerentolacuneo.it/abbigliamento/">
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/abbigliamento.png" />
				</a>
			</li>
			<li id="handmade"> 
				<a href="http://www.cenerentolacuneo.it/handmade/">
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/handmade.png" />
				</a>
			</li>
			<li id="homeware">
				<a href="http://www.cenerentolacuneo.it/homeware/">
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/homeware.png" /> 
				</a>
			</li>
			<li id="stivali">
				<a href="http://www.cenerentolacuneo.it/borse/">
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/borse.png" /> 
				</a>
			</li>
			<li id="ideeregalo">
				<a href="http://www.cenerentolacuneo.it/idee-regalo/"> 
					<img src="http://www.cenerentolacuneo.it/wp-content/themes/cenerentola/img/ideeregalo.png" />
				</a>
			</li>
		</ul>
		<div class="clearfixmg"> </div>

		<?php get_sidebar('shop_online'); ?>

		<ul class="products pagshop">
			<?php
				$args = array(
					'post_type' => 'product',
					'posts_per_page' => 6
					);
				$loop = new WP_Query( $args );
				if ( $loop->have_posts() ) {
					while ( $loop->have_posts() ) : $loop->the_post();
						woocommerce_get_template_part( 'content', 'product' );
					endwhile;
				} else {
					echo __( 'No products found' );
				}
				wp_reset_postdata();
			?>
		</ul><!--/.products-->

		<div class="clearfixmg"> </div>

		<?php get_sidebar('tab_widget'); ?>
		<div class="clearfixmg"> </div>
		<?php get_sidebar('negozio'); ?>


<?php get_footer(); ?>
