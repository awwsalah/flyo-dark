<template>
    <div class="container">
        <div class="card-grid">
            <div class="card">
                <img src="../assets/images/icon-access-anywhere.svg" alt="icon-access-anywhere" />
                <h2>Access your files, anywhere</h2>
                <p>The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.</p>
            </div>
            <div class="card">
                <img src="../assets/images/icon-security.svg" alt="icon-security" />
                <h2>Security you can trust</h2>
                <p>2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.</p>
            </div>
            <div class="card">
                <img src="../assets/images/icon-collaboration.svg" alt="icon-collaboration" />
                <h2>Real-time collaboration</h2>
                <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
            </div>
            <div class="card">
                <img src="../assets/images/icon-any-file.svg" alt="">
                <h2>Store any type of file</h2>
                <p>Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.</p>
            </div>

        </div>
    </div>
</template>

<style scoped>
.container {
    display: grid;
    place-items: center;
    max-width: 880px;
}
.card-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    justify-content: center;
    align-content: center;
    gap: 80px;
    margin: 50px;
}
.card{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    gap: 10px;
    color: white;
}
img{
    width: 80px;
}
h1{
    font-size: 20px;
    font-weight: 700;
}
p{
    font-size: 14px;
    font-weight: 400;
    line-height: 1.5;
}
@media (max-width: 800px){
    .container{
        margin: 0;
        max-width: 320px;
    }
    .card-grid{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .flex-card{
        flex-direction: column;
        gap: 50px;
    }
    .card{
        max-width: 320px;
    }
    img{
        width: 80px;
    }
    h1{
        font-size: 18px;
    }
    p{
        font-size: 14px;
    }
}
</style>