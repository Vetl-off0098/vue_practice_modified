<template>
    <div class="comp">
        <div class="section1">
            <div class="contacts">
                <div class="contact">
                    <img src="../assets/img/point.png" alt="Geo" class="lock">
                    <h3 class="contact-h3">California</h3>
                    <p class="contact-p">Phone: <br>
                        <span class="contact-span">1900 - 1234 -5678</span> <br><br>
                        Email: <br>
                        <span class="contact-span">info@interior.com</span> <br><br>
                        Address: <br>
                        <span class="contact-span">12 W 1st St, 90001 Los Angeles, California</span></p>
                </div>
                <div class="contact">
                    <img src="../assets/img/point.png" alt="Geo" class="lock">
                    <h3 class="contact-h3">California</h3>
                    <p class="contact-p">Phone: <br>
                        <span class="contact-span">1900 - 1234 -5678</span> <br><br>
                        Email: <br>
                        <span class="contact-span">info@interior.com</span> <br><br>
                        Address: <br>
                        <span class="contact-span">12 W 1st St, 90001 Los Angeles, California</span></p>
                </div>
                <div class="contact">
                    <img src="../assets/img/point.png" alt="Geo" class="lock">
                    <h3 class="contact-h3">California</h3>
                    <p class="contact-p">Phone: <br>
                        <span class="contact-span">1900 - 1234 -5678</span> <br><br>
                        Email: <br>
                        <span class="contact-span">info@interior.com</span> <br><br>
                        Address: <br>
                        <span class="contact-span">12 W 1st St, 90001 Los Angeles, California</span></p>
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
    name: 'contactcomp',
    data() {
        return {}
    }
}
</script>

<style scoped>
    /*section1 start*/
    .section1 {
        padding: 71px 98px 122px 98px;

    }
    .contacts {
        display: flex;
        justify-content: space-between;
    }
    .contact {
        width: 370px;
        height: 370px;
        border: 1px solid #9c9c9c;
        background-color: #ffffff;
        opacity: 0.9;
        text-align: center;
    }
    .contact:hover {
        background-color: #f7f7f7;
        border: 1px solid #212121;
    }
    .lock {
        margin-top: 48px;
        width: 38px;
        height: 48px;
    }
    .contact-h3 {
        color: #212121;
        font-size: 22px;
        font-weight: 700;
        text-transform: uppercase;
        margin-top: 12px;
    }
    .contact-p {
        color: #6c6c6c;
        font-size: 14px;
        font-weight: 700;
        line-height: 20px;
        margin-top: 12px;
    }
    .contact-span {
        color: #212121;
        font-weight: 700;
    }
    /*footer start*/
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
        font-family: Montserrat;
        font-size: 18px;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 1.8px;
    }
    .footer-contentLeft {
        margin-top: 24px;
        color: #212121;
        font-family: Montserrat;
        font-size: 14px;
        font-weight: 300;
        line-height: 22px;
    }
    .topFootMid {
        margin-left: 80px;
    }
    .usefulInformation {
        color: #6c6c6c;
        font-family: Montserrat;
        font-size: 18px;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 1.8px;
    }
    .footerBlockContenMid {
        display: flex;
    }
    .footerBlockContentMidLeft {
        width: 138px;
        height: 62px;
        margin-top: 25px;
        color: #212121;
        font-family: Montserrat;
        font-size: 14px;
        font-weight: 700;
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
        font-family: Montserrat;
        font-size: 14px;
        font-weight: 700;
        line-height: 26px;
        text-transform: uppercase;
        letter-spacing: 0.7px;
    }
    .topFootRight {
        margin-left: 78px;
    }
    .Let {
        margin-bottom: 24px;
        color: #6c6c6c;
        font-family: Montserrat;
        font-size: 18px;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 1.8px;
    }
    .footer-contentRight {
        width: 372px;
        color: #212121;
        font-family: Montserrat;
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
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 0.6px;
    }
    .icons {
        margin-right: 170px;
        margin-top: -9px;
        margin-left: 135px;
        width: 144px;
        height: 28px;
        background-image: url(../assets/img/social-links.png);
    }
    .botFootRight {
        width: 400px;
        color: #6c6c6c;
        font-size: 12px;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 0.6px;
    }
    .padding-site3 {
        padding: 120px 98px 0 99px;
    }
</style>