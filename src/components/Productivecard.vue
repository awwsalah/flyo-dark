<template>
    <div class="container">
        <div class="flex-card">
            <div class="card">
                <img src="../assets/images/illustration-stay-productive.png" alt="">
            </div>
            <div class="card2">
                <h2>
                    Stay productive, wherever you are
                </h2>
                <p>
                    Never let location be an issue when accessing your files. Fylo has you covered for all of your file storage needs. 
                </p>
                <i>See how Flyo works</i>
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
    max-width: 1230px;
    margin: 50px;
}
.flex-card {
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-align: start;
    gap: 50px;
    margin: 50px;
}

.card2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: start;
    text-align: start;
    gap: 10px;
    color: white;
    max-width: 615px;
    padding: 20px;
}
img{
    width: 614.76px;
}

@media (max-width: 1030px){
    
    .flex-card{
        width: 800px;
    }
    img{
        width: 400px;
    }
    
}
@media (max-width: 800px){
    .flex-card{
        flex-direction: column;
        gap: 50px;
    }
    img{
        width: 300px;
    }
}
</style>