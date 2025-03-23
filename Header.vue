

<template>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <div class="containers">
        <div class="logo">
            <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-logo.jpg" alt="">
        </div>
        <div class="list">
            <ul>
            <!-- <li> <a href="#"><i class="fa-solid fa-house"></i></a></li> -->
            <li><a href="#about">About Us</a></li>
            <li><a href="#resource">Resource</a></li>
            <li><a href="#contactus">Creativity</a></li>
            <li><a href="#teacher">Teachers</a></li>
            <li><a href="../App.vue">Contact Us</a></li>
        </ul>
        </div>
    </div>
    


</template>

<script setup>
 
 

</script>


<style scoped>
 
    .containers{
       width: 100%;
       height: 90px;
       display: flex;
       box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
       background-color: rgb(255, 255, 255);
       position: sticky;
       top: 0;
       z-index: 11;
       & .logo{
        width: 45%;
        height: 100%;
       
        display: flex;
        justify-content: center;
        & img{
            width:40%;
            height: 100%;
        }
       }
       & .list{
        width: 55%;
        height: 100%;
        /* background-color: dodgerblue; */
        & ul{
        width: 100%;
        height: 100%;
        list-style: none;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 40px;
        & li{
            height: 100%;
            & a{
                height: 100%;
                display: flex;
                justify-content: center;
                align-items: center;
                
                font-size: 19px;
                text-decoration: none;
                color: rgb(0, 0, 0);
                text-transform: uppercase;
                font-weight: bold;
                 

            }


        }
        & li:hover{
            background-color: rgb(238, 237, 237);
            /* padding: 2px; */
            
            border-radius: 2px;
            & a{
                color: blue;
            }
            
        }
        
       }
     }
       
       

    }

</style>