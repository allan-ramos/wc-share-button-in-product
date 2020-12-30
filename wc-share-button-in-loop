<?php

add_action( 'woocommerce_after_shop_loop_item', 'woocommerce_after_shop_loop_item_title', 10 );
function woocommerce_after_shop_loop_item_title(){
	$phone = '50499999999';
	$message = 'Quiero información del producto: '.get_the_title().' ';
	$text = 'Preguntar por Whatsapp';
	$ico = '<img src="https://i.pinimg.com/originals/79/dc/31/79dc31280371b8ffbe56ec656418e122.png" style="width:30px;height:30px;"/>';

	$url = 'https://api.whatsapp.com/send?phone='.$phone.'&amp;text='.str_replace(' ', '%20', $message);
	$link = '<a class="dc-link" href="'.$url.'" target="_blank" >'.$ico. '</a>';

	echo '<div class="dc-whatsapp-container" style="text-align: -webkit-center;margin-top:30px;">'. $link. '</div>';
};
?>
