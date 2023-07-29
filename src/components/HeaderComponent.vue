<template>
    
          <div class="hero">
            <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://cdn.icon-icons.com/icons2/582/PNG/512/gentleman_icon-icons.com_55044.png">
          Ikbal Miftahudin
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">Services</NavbarLink>
          <NavbarLink link="#">Pricing</NavbarLink>
          <NavbarLink link="#">Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
           <center><div class="content">
                <div class="flex flex-row">
                    <h1>Ikbal   <span>Miftahudin</span></h1>
                    <!-- <p>hallo aku ikbal Lorem ipsum dolor sit, amet consectetur adipisicing elit. Praesentium error modi non quis consequuntur ut similique iusto eligendi maxime cum?</p> -->
                      <img src="https://o.remove.bg/downloads/9359d5cc-b307-4dd5-ba5c-ce443e56f0c4/WhatsApp_Image_2023-07-29_at_09.31.06-removebg-preview.png" style="height: 450px; margin-left: 200px; margin-top:120px;">
                
                </div>
                
            </div>
    
        </center> 
        </div>

</template>

<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}
a {
    text-decoration: none;
}
.hero {
    width: 100%;
    height: 100vh;
     background: url(https://images.pexels.com/photos/768938/pexels-photo-768938.jpeg?cs=srgb&dl=pexels-brand-%26-palms-768938.jpg&fm=jpg);
    background-size: cover;
}
nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 30px 100px;
}
.logo {
    max-height: 60px;
}
nav ul li {
    list-style: none;
    display: inline-block;
    padding: 10px 20px;
    color: white;
}
nav ul li a {
    position: relative;
    padding: 10px 0;

}
nav ul li a:hover {
    color: white;
}
nav ul li a:after {
    content: "";
    position: absolute;
    left: 0;
    width: 0;
    height: 3px;
    background: white;
    transition: 0.3s;
    bottom: 0;
}
nav ul li a:hover:after {
    width: 100%;
}
.btn {
    background-color: linear-gradient(
        120deg,
        #1c99fe 20.69%,
        #7644ff 50.19%,
        #fd4766 79.69%
    );
    font-size: 16px;
    text-transform: uppercase;
    letter-spacing: 2px;
    padding: 16px 40px;
    border-radius: 500px;
    display: inline-block;
    font-weight: 500;
    transition: all 0.4s ease-in-out;
    background-size: 152% 100%;
    background: white;
    border: 2px solid white;
}
.btn:hover {
    background: transparent;
    border-color: white;
    color: white;
}
.content {
    position: absolute;
    top: 20%;
    right: 25%;
}
.content .title {
    color: white;
    font-size: 100px;
    text-transform: uppercase;
    letter-spacing: 10px;
    display: inline-block;
    margin-top: 10px;

}
.content h1 {
    color: 	black;
    font-size: 65px;
    font-weight: 1000;
    line-height: 80px;
    text-transform: inherit;
    width: 100%;
    margin-bottom: 100px;
    margin-top: 90px;
    margin-left: 450px;
    font-style:italic;

}
.content h1 span {
    color: black ;
}
.content p {
    width: 100%;
    color: black;
    margin-top: 300px;
    margin-bottom: 10px;
}</style>