<template>
    <div class="container">
        <div class="intro-card">
        <div class="intro-img">
            <img src="../assets/images/illustration-intro.png" alt="illustration-intro" />
        </div>
        <h1>All your files in one secure location accessible anywhere.</h1>
        <p>Fylo stores all your most important files in one secure location. Access them wherever you need, share and collaborate with friends family, and co-workers.</p>
        <button>Get Started</button>
    </div>
    </div>
</template>

<style scoped>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 50px;
}
.intro-img img {
    width: 604px;
}
.intro-card {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    max-width: 734px;
    height: 900px;
    margin: 20px;
    gap: 10px;
}
button{
    background-image: linear-gradient(90deg, #63E1D9, #34A0CD);
    width: 280px;
    height: 56px;
    border-radius: 50px;
    border: none;
    color: white;
    font-size: 16px;
    font-weight: 700;
}
button:hover{
    background-color: #8ADAE3;
    background-image: none;
    cursor: pointer;
}

h1{
    font-size: 40px;
    font-weight: 700;
    color: white;
    text-align: center;
}
p{
    font-size: 20px;
    font-weight: 400;
    color: white;
    text-align: center;
    line-height: 2;
}
</style>