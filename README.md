﻿# CSS-Aquatech
@import url('https://fonts.googleapis.com/css2?family=Barlow:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');


body {
    margin: 0;
    padding: 0;
    font-family: 'Barlow', sans-serif;
    background-color: black;

}

:root {
    --tamanho-header: 80px;
    --tamanho-footer: 90px;
    --tamanho-banner: calc(100vh - var(--tamanho-header) - var(--tamanho-footer) - 2px );
}

/*header*/

.header {
    height: var(--tamanho-header);
    border-bottom: 2px solid #32b9cd;
}

.titulo {
    color: #32b9cd;
    width: fit-content;
    font-weight: 500;
}

.container {
    display: flex;
    width: 80%;
    margin: auto;
}

.header .container {
    justify-content: space-between;
    align-items: center;
    height: 100%;
}

.navbar {
    width: 300px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    list-style: none;
    color: #e3b062;
}

.header a {
    text-decoration: none;
    color: #e3b062;
}

.agora {
    font-weight: 800;
}

/*banner*/

.banner {
    height: var(--tamanho-banner);
    color: white;
    background-image: url('../assets/imgs/bg-jelly-fish-para-home.png');
    background-size: cover;
}

.banner .container {
    justify-content: center;
    align-items: center;
    height: 100%;
}

.banner .container p {
    width: 50%;
    margin: 0;
    padding: 0;
    font-size: 36px;
}

.banner .container .span {
    font-weight: 800;
    position: relative; left: 440px;
}

.social {
    background-color: #e5e5e5 ;
    display: flex;
    justify-content: center;
    text-align: center;
}

.social .container .boxes {
    display: flex;
    justify-content: space-between;
    width: 100%;
    padding: 30px 0;
}

.box {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.box img {
    width: 170px;
}

/*FOOTER*/

.footer {
    background-color: #32b9cd;
    height: var(--tamanho-footer);
    color: #fff;
    display: flex;
    font-size: 15px;
}

.footer .container {
    justify-content: center;
    text-align: center;
}

.version {
    font-size: 12px;
}

/*login*/

.login {
    height: var(--tamanho-banner);
    display: flex;
}

.login .container {
    justify-content: center;
    text-align: center;
}

.card-login {
    width: 60%;
    padding: 30px 0;
    border-radius: 10px;
    font-weight: 600;
    background-color:rgb(220, 220, 220);
    color:rgb(233, 175, 185);
}

input[type=text] {
    width: 50%;
    padding: 10px;
    margin: 5px 0;
    border: 2px solid #32b9cd;
    border-radius: 5px;
}

input[type=password] {
    width: 50%;
    padding: 10px;
    margin: 5px 0;
    border: 2px solid #32b9cd;
    border-radius: 5px;
}

button {
    background-color: rgb(233, 175, 185);
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
}

/*cadastro*/

.container .card-cadastro {
    width: 60%;
    padding: 30px 0;
    border-radius: 10px;
    font-weight: 600;
    background-color:rgb(220, 220, 220);
    color:rgb(233, 175, 185);
}   

/*simulador*/

.simulador .container {
    color: #fff;
}
