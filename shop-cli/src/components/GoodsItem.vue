<template>
    <div>
        <div class="section1">
            <div class="nav">
                <ul class="menu1 clearfix">
                    <li class="menu-list"><a href="#" class="menu-link1 menu-active1">All</a></li>
                    <li class="menu-list"><a href="#" class="menu-link1">HOME</a></li>
                    <li class="menu-list"><a href="#" class="menu-link1">OFFICE</a></li>
                    <li class="menu-list"><a href="#" class="menu-link1">FURNITURE</a></li>
                    <li class="menu-list"><a href="#" class="menu-link1">MODERN</a></li>
                    <li class="menu-list"><a href="#" class="menu-link1">CLASSIC</a></li>
                </ul>
            </div>
        </div>
        <div class="section2">
            <div class="itemAll">
                <div class="itemImg">

                </div>
                <div class="itemInf">
                    <h2 class="itemImg-h2">Fishnet Chair</h2>
                    <p class="hotDeal">Hot Deal</p>
                    <p class="price"><span class="usd">$</span>36.7<span class="sq">/sq</span></p>
                    <a href="#" class="buttonOrange">Order Us</a>
                    <div class="itemInf-text">
                        <p class="inf-text">The majesty of Mountains - Ugmonk style. <br><br>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore <br><br>
                            et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br><br>
                        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
                    </div>
                </div>
            </div>
            <div class="otherImg">
                <a href="#"><div class="OI otherImg1"></div></a> 
                <a href="#"><div class="OI otherImg2"></div></a>
                <a href="#"><div class="OI otherImg3"></div></a>
            </div>
        </div>
        <div class="section3 padding-site1">
            <div class="nav2 clearfix">
                <h2 class="nav_h2">Trending Products</h2>
                <a href="#" class="exploreAll-1">explore all</a>
            </div>
            <div class="trending_products">
                <div class="trending_link prod-11">
                    <div class="product_content">
                        <a href="#" class="button_product">
                            <img src="../assets/img/arrow.svg" alt="Arrow" class="arrow">
                        </a>
                        <h3 class="product_h3">Fishnet Chair</h3>
                        <p class="product_p">
                            Seat and back with upholstery made of cold cure foam
                        </p>
                    </div>
                </div>
                <div class="trending_link prod-21">
                    <div class="product_content">
                        <a href="#" class="button_product">
                            <img src="../assets/img/arrow.svg" alt="Arrow" class="arrow">
                        </a>
                        <h3 class="product_h3">Fishnet Chair</h3>
                        <p class="product_p">
                            Seat and back with upholstery made of cold cure foam
                        </p>
                    </div>
                </div>
                <div class="trending_link prod-31">
                    <div class="product_content">
                        <a href="#" class="button_product">
                            <img src="../assets/img/arrow.svg" alt="Arrow" class="arrow">
                        </a>
                        <h3 class="product_h3">Fishnet Chair</h3>
                        <p class="product_p">
                            Seat and back with upholstery made of cold cure foam
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <footer>
            <div class="footer padding-site3">
                <div class="footer1">
                    <div class="topFootLeft">
                        <p class="contactUs">Contact Us</p>
                        <div class="footerBlockContentLeft">
                            <p class="footer-contentLeft">132A Bridge Road Richmond VIC Australia. <br> <br> Talk to us on 1300 132 info@interior.com</p>
                        </div>
                    </div>
                    <div class="topFootMid">
                        <p class="usefulInformation">Useful Information</p>
                        <div class="footerBlockContenMid">
                            <div class="footerBlockContentMidLeft">
                                    Sales terms
                                    Customer care
                                    Delivery
                            </div>
                            <div class="footerBlockContentMidRight">
                                    Architect accounts Careers <br> Exchanges & returns
                            </div>
                        </div>
                    </div>
                    <div class="topFootRight">
                        <p class="Let">Let’s Stay in Touch!</p>
                        <div class="footerBlockContenRight">
                            <p class="footer-contentRight">Suscribe to know about our latest news, products and special offers just for suscribers.</p>
                        </div>
                        <div class="block-mail">
                            <input type="email" class="mail" placeholder="your email address">
                            <button class="mail-submit" type="submit">
                                <img src="../assets/img/air.png" alt="send">
                            </button>
                        </div>
                    </div>
                </div>
                <div class="botFoot">
                    <p class="botFootLeft">© Copyright - INTERIOR 2016. All Rights Reserved.</p>
                    <div class="icons"></div>
                    <p class="botFootRight">Terms & Conditions  /  Privacy policy & Cookies</p>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'goodsitem',
    data() {
        return {}
    }
}
</script>

<style scoped>
    .button {
        color: #212121;
        font-size: 18px;
        font-weight: 700;
        line-height: 45px;
        text-transform: uppercase;
        letter-spacing: 3.6px;
        text-decoration: none;
        box-shadow: 0 2px 5px 1px rgba(33, 33, 33, 0.35);
        border-radius: 23px;
        background-color: #ffffff;
        display: inline-block;
        width: 212px;
        height: 45px;
        text-align: center;
    }
    .button:hover:after {
        content: " >";
    }
    .button:active {
        color: #6c6c6c;
        box-shadow: -5px -6px 5px -5px rgba(33, 33, 33, 0.35);
    }
    .clearfix:after {
        content: "";
        display: table;
        clear: both;
    }
    .padding-site {
        padding-left: 98px;
        padding-right: 167px;
    }
    .header {
        padding-top: 63px;
    }
    .menu {
        float: right;
    }
    .menu-list {
        list-style-type: none;
        float: left;
    }
    .menu-link {
        color: #8c8c8c;
        font-size: 14px;
        font-weight: 300;
        text-transform: uppercase;
        text-decoration: none;
        padding: 10px 13px;
    }
    .menu-link:hover {
        color: #212121;
    }
    .menu-list:hover {
        transform: scale(1.1,1.1);
    }
    .menu-list:active {
        transform: scale(0.9,0.9);
    }
    .menu-active {
        color: #212121;
        font-weight: 700;
        letter-spacing: 1.4px;
        border-bottom: 3px solid #212121;
    }
    .section1 {
        height: 70px;
        background-color: #f4f4f4;
        margin-top: 29px;
    }
    .nav {
        padding-top: 27px;
        padding-left: 360px;
    }
    .menu-link1 {
        color: #6c6c6c;
        font-size: 18px;
        font-weight: 700;
        text-transform: uppercase;
        text-decoration: none;
        padding: 10px 13px;
        letter-spacing: 1.8px;
    }
    .menu-active1 {
        color: #212121;
        font-weight: 700;
        letter-spacing: 1.4px;
    }
    .menu-link1:hover {
        color: #212121;
    }
    .section2 {
        padding: 72px 98px 0 98px;
    }
    .itemAll {
        display: flex;
    }
    .itemImg {
        width: 570px;
        height: 570px;
        background-image: url(../assets/img/slider1.jpg);
    }
    .itemInf {
        width: 510px;
    }
    .itemImg-h2 {
        color: #212121;
        font-size: 36px;
        font-weight: 700;
        text-align: center;
    }
    .hotDeal {
        color: #e53935;
        font-size: 18px;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 1.8px;
        margin-top: 23px;
        text-align: center;
    }
    .price {
        margin-top: 36px;
        margin-left: 150px;
        color: #212121;
        font-weight: 300;
        line-height: 48.02px;
        font-size: 72px;
        text-transform: uppercase;
    }
    .usd {
        color: #212121;
        font-size: 48px;
        text-transform: uppercase;
        font-weight: 300;
    }
    .sq {
        font-size: 36px;
        color: #212121;
        font-weight: 300;
        text-transform: lowercase;
    }
    .buttonOrange {
        color: #ffffff;
        font-size: 22px;
        font-weight: 700;
        line-height: 71px;
        text-transform: uppercase;
        letter-spacing: 4.4px;
        text-decoration: none;
        box-shadow: 0 2px 5px 1px rgba(33, 33, 33, 0.35);
        border-radius: 35px;
        background-color: #f44336;
        display: inline-block;
        width: 510px;
        height: 71px;
        text-align: center;
        margin-top: 31px;
    }
    .buttonOrange:hover:after {
        content: " >";
    }
    .buttonOrange:active {
        transform: scale(0.9,0.9);
    }
    .itemInf-text {
        width: 499px;
        height: 244px;
        color: #212121;
        font-size: 16px;
        font-weight: 300;
        line-height: 24.01px;
        letter-spacing: 0.4px;
        margin-top: 49px;
    }
    .inf-text {
        text-align: start;
    }
    .OI {
        margin: 5px;
        width: 70px;
        height: 70px;
    }
    .otherImg1 {
        background-image: url(../assets/img/controll.jpg);
    }
    .otherImg2 {
        background-image: url(../assets/img/controll11.jpg);
    }
    .otherImg3 {
        background-image: url(../assets/img/controll2.jpg);
    }
    .otherImg {
        margin-left: 150px;
        display: flex;
    }
    .section3 {
        margin-top: 245px;
        padding-bottom: 120px;
    }
    .padding-site1 {
        padding-left: 98px;
        padding-right: 98px;
    }
    .nav_h2 {
        color: #212121;
        font-size: 36px;
        font-weight: 700;
    }
    .exploreAll-1 {
        text-decoration: none;
        color: #212121;
        font-size: 18px;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 3.6px;
        margin-top: -25px;
        float: right;
    }
    .exploreAll-1:hover:after {
        content: " >";
    }
    .exploreAll-1:hover {
        color: #6c6c6c;
    }
    .exploreAll-1:active{
        transform: scale(0.8,0.8);
    }
    .trending_products {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        margin-top: 34px;
    }
    .trending_link {
        width: 370px;
        height: 370px;
        margin-top: 30px;
    }
    .trending_link:hover .product_content {
        display: flex;
    }
    .prod-11 {
        background-image: url(../assets/img/product-11.jpg);
    }
    .prod-21 {
        background-image: url(../assets/img/product-21.jpg);
    }
    .prod-31 {
        background-image: url(../assets/img/product-31.jpg);
    }
    .prod-41 {
        background-image: url(../assets/img/product-41.jpg);
    }
    .prod-5 {
        background-image: url(../assets/img/product-5.jpg);
    }
    .prod-6 {
        background-image: url(../assets/img/product-6.jpg);
    }
    .product_content {
        border: 1px solid #9c9c9c;
        background-color: #fff;
        opacity: 0.9;
        height: 100%;
        display: none;
        flex-direction: column;
        align-items: center;
        padding: 32px;
        box-sizing: border-box;
        justify-content: center;
    }.button_product {
        width: 48px;
        height: 48px;
        box-shadow: 0 2px 5px 1px rgba(33, 33, 33, 0.35);
        border-radius: 50%;
        background-color: #ffffff;
        position: relative;
    }
    .arrow {
        position: absolute;
        top: 15px;
        left: 19px;
    }
    .product_h3 {
        margin-top: 19px;
        color: #212121;
        font-size: 22px;
        font-weight: 700;
    }
    .product_p {
        margin-top: 23px;
        width: 211px;
        color: #212121;
        font-size: 14px;
        font-weight: 300;
        line-height: 21.91px;
        text-align: center;
    }
    footer {
        height: 384px;
        background-color: #f7f7f7;
    }
    .footer1 {
        display: flex;
    }
    .footerBlockContentLeft {
        width: 221px;
        height: 102px;
    }
    .contactUs {
        color: #6c6c6c;
        font-size: 18px;
        font-weight: 900;
        text-transform: uppercase;
        letter-spacing: 1.8px;
        text-align: start;
    }
    .footer-contentLeft {
        margin-top: 24px;
        color: #212121;
        font-size: 14px;
        font-weight: 300;
        line-height: 22px;
        text-align: start;
    }
    .topFootMid {
        margin-left: 80px;
        text-align: start;
    }
    .usefulInformation {
        color: #6c6c6c;
        font-size: 18px;
        font-weight: 900;
        text-transform: uppercase;
        letter-spacing: 1.8px;
        text-align: start;
    }
    .footerBlockContenMid {
        display: flex;
    }
    .footerBlockContentMidLeft {
        width: 138px;
        height: 62px;
        margin-top: 25px;
        color: #212121;
        font-size: 14px;
        font-weight: 900;
        line-height: 26px;
        text-transform: uppercase;
        letter-spacing: 0.7px;
    }
    .footerBlockContentMidRight {
        margin-left: 103px;
        width: 194px;
        height: 63px;
        margin-top: 25px;
        color: #212121;
        font-size: 14px;
        font-weight: 900;
        line-height: 26px;
        text-transform: uppercase;
        letter-spacing: 0.7px;
    }
    .topFootRight {
        margin-left: 78px;
        text-align: start;
    }
    .Let {
        margin-bottom: 24px;
        color: #6c6c6c;
        font-size: 18px;
        font-weight: 900;
        text-transform: uppercase;
        letter-spacing: 1.8px;
    }
    .footer-contentRight {
        width: 372px;
        color: #212121;
        font-size: 14px;
        font-weight: 300;
        line-height: 22px;
    }
    .block-mail {
        width: 370px;
        height: 48px;
        border: 1px solid #d9dee1;
        background-color: #ffffff;
        margin-top: 26px;
        display: flex;
        justify-content: space-between
    }
    .mail {
        border: none;
        outline: none;
        color: #6c6c6c;
        margin-left: 19px;
        font-size: 14px;
        font-weight: 300;
        width: 326px;
    }
    .mail-submit {
        border: none;
        width: 44px;
        height: 48px;
        background-color: #ffffff
    }
    .botFoot {
        display: flex;
        margin-top: 65px;
    }
    .botFootLeft {
        display: inline-block;
        width: 422px;
        height: 10px;
        color: #6c6c6c;
        font-size: 12px;
        font-weight: 900;
        text-transform: uppercase;
        letter-spacing: 0.6px;
    }
    .icons {
        margin-right: 110px;
        margin-top: -9px;
        margin-left: 101px;
        width: 158px;
        height: 28px;
        background-image: url(../assets/img/social-links.png);
    }
    .botFootRight {
        width: 400px;
        color: #6c6c6c;
        font-size: 12px;
        font-weight: 900;
        text-transform: uppercase;
        letter-spacing: 0.6px;
    }
    .padding-site3 {
        padding: 120px 98px 0 99px;
    }
</style>