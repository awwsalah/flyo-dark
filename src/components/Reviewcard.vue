<template>
    <div class="container">
        <div class="flex">
            <div class="card">
                <h3>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.</h3>
                <div class="user-flex">
                    <img src="../assets/images/profile-1.jpg" alt="profile-1">
                    <div class="user">
                        <h4>Satish Patel</h4>
                        <p>Founder & CEO, Huddle</p>
                    </div>
                </div>
            </div>
            <div class="card">
                <h3>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.</h3>
                <div class="user-flex">
                    <img src="../assets/images/profile-2.jpg" alt="profile-2">
                    <div class="user">
                        <h4>Bruce McKenzie</h4>
                        <p>Founder & CEO, Huddle</p>
                    </div>
                </div>
            </div>
            <div class="card">
                <h3>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.</h3>
                <div class="user-flex">
                    <img src="../assets/images/profile-3.jpg" alt="profile-3">
                    <div class="user">
                        <h4>Iva Boyd</h4>
                        <p>Founder & CEO, Huddle</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    max-width: 1240px;
    margin: 50px;
    background-image: url('../assets/images/bg-quotes.png');
    background-repeat: no-repeat;
    background-position: top 270px left 0px;
    position: relative;
}
.flex {
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    gap: 50px;
}
.card{
    max-width: 360px;
    padding: 30px 20px;
    font-size: 14px;
    color: white;
    font-weight: 400;
    display: flex;
    flex-direction: column;
    background-color: #202A3C;
    border-radius: 7px;
    gap: 20px;
}
.user-flex{
    display: flex;
    gap: 10px;
    align-items: center;
}
img{
    width: 24px;
    border-radius: 50px;
}
h3{
    font-size: 14px;
    font-weight: 400;
    line-height: 1.5;
}
h4{
    font-size: 10px;
    font-weight: 700;
}
p{
    font-size: 9px;
    font-weight: 400;
    line-height: 1.5;
}
@media (max-width: 1200px){
    .container{
        background-position: top 250px left 0px;
     position: relative;
    }
    .flex{
        gap: 50px;
    }
    .card{
        max-width: 920px;
    }
}
@media (max-width: 800px){
    .container{
        margin: 0;
        max-width: 320px;
        background-position: top 30px left 0px;
    position: relative;
    }
    .flex{
        flex-direction: column;
        gap: 50px;
    }
    .card{
        max-width: 320px;
    }
}

</style>