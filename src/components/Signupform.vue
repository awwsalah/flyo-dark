<script setup>
import { ref } from 'vue'
const email = ref('')
const emailError = ref(false)
if (email.value === null) {
    emailError.value = true
}
</script>

<template>
    <div class="container">
        <h2>Get early access today</h2>
        <p>It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you.</p>
        <form class="form-flex">
            <div class="form-control">
                <input type="email" id="email" v-model="email"  placeholder="email@example.com"/>
                <p v-if="emailError">Please enter a valid email address</p>
                <button>Get Started For Free</button>
            </div>
            
        </form>
    </div>
</template>

<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.container {
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
    gap: 10px;
    max-width: 800px;
    margin: 50px;
    background-color: #1B2330;
    border-radius: 10px;
    box-shadow: 5px 5px 8px rgba(0, 0, 0, 0.5);
    color: white;
    padding: 20px;
    text-align: center;
    position:absolute;
    top: 402%;
}
.form-control{
    display: flex;
    justify-content: center;
    gap: 20px;
    max-width: 800px;
    padding: 20px;
}
input{
    width: 480px;
    height: 50px;
    border-radius: 50px;
    border: none;
    padding: 10px;
}
input::placeholder{
    padding-left: 20px;
    font-size: 15px;
    font-weight: 400;
}
button{
    background-image: linear-gradient(90deg, #63E1D9, #34A0CD);
    width: 200px;
    border-radius: 50px;
    border: none;
}
button:hover{
    background-color: #8ADAE3;
    background-image: none;
    cursor: pointer;
}
h2{
    font-size: 32px;
    font-weight: 700;
}
p{
    font-size: 14px;
    font-weight: 400;
    line-height: 1.8;
}
@media (max-width: 800px){
    .container{
        margin: 0;
        max-width: 375px;
        justify-content: center;
        align-items: center;
        gap: 0;
        padding: 20px;
        margin-bottom: 20px;
    }
    .form-flex{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    
    .form-control{
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        gap: 20px;
    }
    input{
        height: 50px;
        max-width: 300px;
    }
    button{
        height: 50px;
        width: 300px;
    }
    h2{
        font-size: 18px;
    }
    p{
        font-size: 14px;
    }
}
</style>