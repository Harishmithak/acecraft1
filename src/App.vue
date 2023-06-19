
<template>

  <div class='navbarfull col-lg-12 col-md-12 col-sm-12 col-xl-12 fixed-top' >
    <router-link class='titlename' to="#">acecraft</router-link>
    <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
            <a class="navbar-brand" to="#"></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <router-link class='nav-link' id="school" aria-current="page" to="/">SCHOOL</router-link>
                    <router-link class='nav-link' id="college" to="/">COLLEGE</router-link>
                    <router-link class='nav-link' id="enterprise" to="/">ENTERPRISE</router-link>
                    <router-link class='nav-link notes' id="notes" to="/">NOTES</router-link>
                    <router-link class='nav-link' id='areamask' to="/">ARIEN MASK</router-link>
                    <!-- <div class="nav-item dropdown setting">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                <i class="fas fa-cog"></i> 
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#"><i class="fas fa-sign-in-alt"></i> Sign In</a></li>
                <li><a class="dropdown-item" href="#"><i class="fas fa-user-plus"></i> Register</a></li>
                <li><a class="dropdown-item" href="#"><i class="fas fa-box"></i> Order Status</a></li>
                <li><a class="dropdown-item" href="#"><i class="fas fa-envelope"></i> Contact</a></li>
              </ul> -->
        
  
              <!-- <li class="companymenuli"><FontAwesomeIcon icon="cog" /><b class="caret"></b></li> -->
                        <!-- <li class="companymenuli"><img src='../src/assets/setting.png.crdownload' width='20px' /><b class="caret"></b> -->
                            <!-- <ul class="ul">
                                <li>Sign In &nbsp; |</li>
                                <li>Register  &nbsp; |</li>
                                <li>Order Status &nbsp; |</li>
                                <li>Contact  &nbsp; |</li>
  
                            </ul> -->
                    
  
<!--   
                    </div> -->
  
                    <!-- <div>
                      <button class="btn" type="button">
              <i class="fas fa-shopping-cart"></i> 
              <span class="badge"></span>
            </button>
                    </div> -->
                </div>
            </div>
        </div>
    </nav >
  
  </div>


  <div class="background-image-container">
    <div class="overlay">
<pre>Choose Class
over the common.</pre>

    </div>
    <router-link to="#" class="acecraftforcolleges"> ACECRAFT FOR COLLEGES</router-link>
                <i  class="fas fa-chevron-right arrow-right "></i>

  </div>

  <div class="image-container">
    
    <img src="https://cdn.storehippo.com/s/5997cc7c4d6e8ffa20e50aae/ms.files/home3.jpg" alt="Left Image" class="left-image">
    <img src="https://cdn.storehippo.com/s/5997cc7c4d6e8ffa20e50aae/ms.files/home4.jpg" alt="Right Image" class="right-image">
  </div>

  </template>






<style>
#app {
font-family: Avenir, Helvetica, Arial, sans-serif; 
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color:white;
}
.titlename {
    color: #FFFFFF;
    margin-left: 80px;
    letter-spacing: 10px;
    padding: 25px 10px 20px;
    font-weight: 400;
    font-size: 30px;
    font-family: 'Courier New', Courier, monospace;
    text-decoration: none;
    margin-top: 10px;
    
  }
  .titlename:hover{
    color:white;
  }
  
  .navbarfull {
    background-color: black;
    height: 115px;
    position: sticky;
    top: 0;
  
  }

  
  .nav-link {
    color: #9e9e9e;
    margin-left: 340px;
    margin-right: -290px;
    font-weight: 500;
    font-size:14px;


  }
  
  .nav-link:hover {
    color: white;
    font-weight: bold;
  }
  
  .leftsidenav {
    margin-left: 200px;
  }
  
  
  .btn {
    margin-left: 10px;
    margin-top: -3px;
  }
  
  
  #areamask {
    width: 140px;
  }
  /* .nav-link:hover{

    color: white;
    font-weight: bold;
  } */
  
  
  #areamask:hover {
    color: white;
    font-weight: bold;
  }
  
  .badge:hover {
    background-color: #978f8f;
    border-radius: 25px;
  }
  
  
  .notes::after {
    content: "";
    display: inline-block;
    background: #8596ff;
    width: 6px;
    height: 6px;
    border-radius: 4px;
    position: relative;
    top: -2px;
    left: 20px;
  }
  
  
  
  .companymenuli {
    margin-top: 5px;
    margin-left: 260px;
  }
  
  
  .setting {
    margin-left: 200px;
    font-weight: 900;
    
  }
  
  
  
  .setting li ul {
    display: none;
    position: absolute;
    top: 100%;
    background-color: #fff;
    opacity: 0.5;
    width: 200px;
    height:1600px;
  }
  
  .setting li:hover ul {
    display: block;
  }
  
  .setting li ul li {
    display: block;
    color: rgb(49, 48, 48);
    font-size: 23px;
    font-weight: 400;
    margin-left: -50px;
    background-color: #000;
   
  
  }
  
  .setting li ul li a {
    display: flex;
    align-items: center;
    padding: 10px;
    color: #000;
    text-decoration: none;
    height:1600px;
  
    opacity: 1;
  }
  
  .setting li ul li a img {
    width: 20px;
    margin-right: 10px;
    opacity: 0.5;
    
  
  }
  
  .setting li ul li a:hover {
    background-color: #f2f2f2;
  
    opacity: 1;
  }
  
  .setting li ul li a:hover img {
    opacity: 1;
    background-color: #8596ff;
  }

.nav-brand{
  color:gray;
  font-family: 'Times New Roman', Times, serif;
}
 
#school:hover,
#college:hover,
#enterprise:hover,
#notes:hover {
  color: white;
  font-weight: bold;
}
.nav-link{
  color:white;
}
.navbar-nav{
  margin-left: -10px;
}
.fa-shopping-cart{
color: white;
}
.background-image-container {
  background-image: url(http://cdn.storehippo.com/s/5997cc7c4d6e8ffa20e50aae/ms.files/Home-1.jpg);
  background-size: cover;
  background-position: center;
  width: 100%;
  height: 650px; 
  margin-top: 113px;
}
.background-image-container{
  position: relative;
}
.overlay{
  position:absolute;
  color: #FFFFFF;
  margin-top: 450px;
  margin-left: 600px;
  border: solid;
  border-width: 0.01cqh;
  padding: 10px;
  padding-right: 35px;
  padding-left: 35px;
  font-family: cursive;
 
}
/* .fa-chevron-right {
    color: white;
    position: absolute;
    margin-top: 560px;
    font-size: 15px;
    margin-left: 60px;
    animation: mymove 1s linear infinite;
} */

.fa-chevron-right {
  color: white;
  position: absolute;
  top: 88%;
  left: 280px;
  transform: translateY(-50%);
  font-size: 15px;
  animation: mymove 1s linear infinite;
}
.fa-chevron-right:hover {
    color: black;
}


@keyframes mymove {
    0% {
        margin-left: 40%;
    }

    100% {
        margin-left: 46%;
        margin-right: 2%;
    }
}


.acecraftforcolleges {
    position: absolute;
    margin-top: 560px;
    margin-left: -100px;
    font-size: 17px;
    letter-spacing: 1px;
    color: white;
    font-weight: 500;
    text-decoration: none;
}

.acecraftforcolleges:hover {
    color: black;
}

.image-container {
  margin-top: 5px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #000;
}

.left-image, .right-image {
  width:50%; 
  height: 700px;

  transition: transform 1s ease; 
}
.image-container img + img {
  margin-left: 20px;
}
.left-image:hover,
.right-image:hover {
  transform: scale(1.05); 
}



</style>