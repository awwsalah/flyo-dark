<template>
    <nav>
        <div class="nav-wrapper">
            <div class="logo">
                <a href="#" ><img src="@/assets/images/logo.svg" alt="Logo"></a>
            </div>
            <div class="headerlist">
                <ul id="nav-mobile" class="right hide-on-med-and-down">
                <li><a href="#">Features</a></li>
                <li><a href="#">Team</a></li>
                <li><a href="#">Sign In</a></li>
            </ul>
            </div>
        </div>
    </nav>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap');
    .nav-wrapper {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 40px;
        font-family: "Raleway", sans-serif;
    }

    .logo img {
        width: 178px;
    }

    .headerlist ul {
        display: flex;
        list-style: none;
    }

    .headerlist ul li {
        margin: 0 20px;
    }

    .headerlist ul li a {
        color: hsl(0, 0%, 100%);
        text-decoration: none;
        font-weight: 400;
        font-size: 16px;
    }

    .headerlist ul li a:hover {
        color: white;
        cursor: pointer;
        font-weight: 700;
        text-decoration: underline;
    }
    

    @media (max-width: 600px) {
        .nav-wrapper {
            flex-direction: column;
        }

        .headerlist ul {
            margin-top: 20px;
        }
    }
</style>