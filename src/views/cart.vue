<template>
  <div class="catalog_in_header">
        <div class="container">
          <section class="new-arrivals "> 
        <div class="container">
          
        </div>
    </section>
    </div>
    </div>
    <div class="shoping_content container_boot">
        <div class="container">
        <div class="card_box">
            <div class="shoping_card_li shoping_li">
                <a href="catalog.html" class="shoping_card_a shoping">
                    <img class="shoping_content_img" src="img/product-3.jpg" alt="card_product">
                </a>
                <div class="shoping_card_txt">
                    <p class="shoping_card_title shoping_txt">MANGO PEOPLE
                        <span class="shoping_cross">&#10006;</span><br>
                        T-SHIRT
                    </p>
                    <p class="shoping_card_text">Price: <span class="card_price">$300</span></p>
                    <p class="shoping_card_text">Color: Red</p>
                    <p class="shoping_card_text">Size: Xl </p>
                    <p class="shoping_card_text quanty">Quantity:</p>
                    <input class="shoping_bdr" required autocomplete="off" value="1" type="number" min="1" max="100">
                </div>
            </div>
            <div class="shoping_card_li shoping_li">
                <a href="catalog.html" class="shoping_card_a shoping">
                    <img class="shoping_content_img" src="img/product-7.jpg" alt="card_product">
                </a>
                <div class="shoping_card_txt">
                    <p class="shoping_card_title shoping_txt">MANGO PEOPLE <span
                            class="shoping_cross">&#10006;</span><br>
                        T-SHIRT</p>
                    <p class="shoping_card_text">Price: <span class="card_price">$300</span></p>
                    <p class="shoping_card_text">Color: Red</p>
                    <p class="shoping_card_text">Size: Xl </p>
                    <p class="shoping_card_text">Quantity:</p>
                    <input name="quantity" class="shoping_bdr" required autocomplete="off" value="1" type="number"
                        min="1" max="100">
                </div>
            </div>
            <div class="shoping_card_button_wrap">
                <a href="#" class="shoping_card_button">CLEAR SHOPPING CART</a>
                <a href="#" class="shoping_card_button">CONTINUE SHOPPING</a>
            </div>
        </div>
        <div class="form_box">
            <form class="shoping_form" action="#" method="POST">
                <p class="shoping_form_txt">SHIPPING ADRESS</p>
                <input class="shoping_input" type="text" name="country" value="" placeholder="Bangladesh" required
                    pattern="\S+[А-ЯA-Z]"><br>
                <input class=" shoping_input" type="text" name="state" value="" placeholder="State" required
                    pattern="\S+[А-ЯA-Z]"><br>
                <input class=" shoping_input" type="text" name="postcode" value="" placeholder="Postcode / Zip"
                    required><br>
                <input class="shoping_button" type="submit" value="GET A QUOTE">
            </form>
            <div class="shoping_total">
                <div class="shoping_total_txt">
                    <p class="total_txt_sml">SUB TOTAL &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $900</p>
                    <p class="total_txt_big">GRAND TOTAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <span>$900</span></p>
                </div>
                <div class="total_line"></div>
                <div class="shoping_total_button">
                    <a class="shoping_total_lnk" href="registracion.html">
                        <p class="shoping_total_lnk_txt">PROCEED TO CHECKOUT</p>
                    </a>
                </div>
            </div>
        </div>
    
    </div>
    </div>
</template>

<script>
export default {
name:'cart'
}
</script>

<style>

</style>