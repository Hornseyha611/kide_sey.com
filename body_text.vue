<template>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
   <div class="box-text">
        <div class="text">
             <div class="txt_1">
            <h1>Secure a</h1>
            <h1>Better Future</h1>
            <h1>For Your  <sup> <font style="color: blue;">Kids</font></sup></h1>
            <p> <Marquee behavior="alternate" >Spark a love of learning in your child’s world.</Marquee></p>
             </div>
            <div class="txt_2 ">
                <p>Welcome to Kiddy Star, a playful and engaging website templat
                    e designed to showcase your kindergarten,
                     prep school, tutoring or any other services 
                     that come to your mind. Explore our classrooms,
                      meet our educators, and discover the enriching
                       experiences that await your little learners.</p>
                <button type="button" class="btn btn-danger">LERN MORE</button>
            </div>
        </div>
        <div class="picture">
            <div class="image_head">
                <div class="rigth">
                    <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-hero-img-001.jpg" alt="">
                </div>
                <div class="left">
                    <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-hero-img-002.jpg" alt="">
                </div>
            </div>
            <div class="image_foot">
                <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-hero-img-003.jpg" alt="">

            </div>

        </div>
   </div>

</template>
<script setup>


</script>
<style scoped>
.box-text{
    width: 100%;
    height: 500px;
    padding: 10px;
    background-color: rgb(146, 185, 242);
    display: flex;
    & .text{
        width: 50%;
        height: 100%;
        
        /* background-color: dodgerblue; */

        & .txt_1{
            width: 100%;
            height: 50%;
            /* background-color: gray; */
            display: flex;
            justify-content: center;
            flex-direction: column;
            padding: 90px;
            & h1{
                font-size: 50px;
                text-shadow: 3px 0px 3px;
                text-transform: uppercase;
                
            }
            & p{
                /* font-size: 20px; */
                margin-top: 10px;
                font-weight: bold;
                /* text-transform: uppercase; */
            }
            
        }
        & .txt_2{
            width: 100%;
            height: 50%;
            /* background-color: rgb(234, 31, 31); */
            padding: 90px;
            display: flex;
            justify-content: center;
            /* align-items: center; */
            flex-direction: column;
            & p{
                font-style: inherit;
                /* font-weight: bold; */
                font-style: oblique;
                
            }
            & button{
                width: 20%;
                margin-top: 20px;
            }
        }
    }
    & .picture{
        width: 50%;
        height: 100%;
        /* background-color: rgb(255, 70, 3); */

        & .image_head{
            width: 100%;
            height: 50%;
            /* background-color: rgb(0, 0, 0); */
            display: flex;

            & .rigth{
                width: 50%;
                height: 100%;
                display: flex;
                justify-content: end;
                margin-right: 40px;
                /* background-color: blue; */
                & img{
                /* width: 100%; */
                height:100%;
                border-radius: 300px;
                cursor: pointer;
                box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
            }

                
            }
            & .left{
                width: 50%;
                height: 100%;
                /* background-color: yellow; */
                & img{
                /* width: 100%; */
                height: 100%;
                border-radius: 300px;
                cursor: pointer;
                box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
            }



            }
        }
        & .image_foot{
            width: 100%;
            height: 50%;
            display: flex;
            justify-content: center;
            padding: 20px;
            & img{
                /* width: 100%; */
                height: 100%;
                border-radius: 300px;
                cursor: pointer;
                box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
            }

        }
        & img:hover{
            transform: translatey(10px);
            padding: 18px;
            transition: 0.4s ease-in-out;
            transform: scale(1.09);
            
            
        }
    }


}

 


</style>