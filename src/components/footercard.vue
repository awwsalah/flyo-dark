<template>
    <div class="footer">
        <div class="footer-logo">
                <img src="../assets/images/logo.svg" alt="logo" />
            </div>
        <div class="footer-content">
            <div class="text">
                <i class="fa-solid fa-location-dot"></i>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</p>
            </div>
            <div class="contact text-space">
                <div class="contact-flex">
                    <i class="fa-solid fa-phone"></i>
                    <p>+1-543-123-4567</p>
                </div>
                <div class="contact-flex">
                    <i class="fa-solid fa-envelope"></i>
                    <p>example@flyo.com</p>
                </div>
            </div>
            <div class="footer-links text-space">
                <a href="#">About Us</a>
                <a href="#">Jobs</a>
                <a href="#">Press</a>
                <a href="#">Blog</a>
            </div>
            <div class="footer-links text-space">
                <a href="#">Contact Us</a>
                <a href="#">Terms</a>
                <a href="#">Privacy</a>
            </div>
            <div class="footer-socials">
                <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
                
            </div>
        </div>
    </div>
</template>

<style scoped>
.footer{
    background-color: #1B2330;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: start;
    gap: 50px;
    padding: 50px;
    max-height: 440px;
    width: 100%;
}
footer-logo{
    width: 100px;
}
.footer-content{
    display: flex;
    justify-content: space-between;
    align-items: start;
    gap: 20px;
    width: 100%;
}
.footer-links{
    display: flex;
    flex-direction: column;
    gap: 10px;
    color: white;
    font-size: 16px;
    font-weight: 400;
}
.text{
    display: flex;
    gap: 20px;
    max-width: 380px;
}
.text-space{
    display: flex;
    flex-direction: column;
    gap: 20px;
}
.contact{
    display: flex;
    flex-direction: column;
}
.contact-flex{
    display: flex;
    gap: 20px;
}
.footer-socials{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}
.footer-socials a{
    width: 20px;
    height: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    border: 1px solid white;
    border-radius: 50px;
    padding: 20px;
    
}
.footer-links a{
    color: white;
    text-decoration: none;
}
.footer-links a:hover{
    cursor: pointer;
    font-weight: 700;
}
@media (max-width: 800px){
    .footer{
        padding: 20px;
        gap: 20px;
    }
    .footer-content{
        flex-direction: column;
        justify-content: start;
        align-items: flex-start;
        gap: 20px;
    }
    .footer-content:last-child{
        gap: 30px;
        justify-self: center;
        align-self: center;
    }
    .text{
        flex-direction: column;
        gap: 20px;
    }
    .footer-links{
        gap: 10px;
    }
    .footer-socials{
        gap: 10px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
}
</style>