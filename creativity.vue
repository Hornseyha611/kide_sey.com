<template>
<div class="container-fluid" id="contactus">

    <div class="contant-box">
        <div class="left">
            <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-hero-img-002.jpg" alt="">
        </div>
        <div class="rigth">
            <div class="text_h">
                <h1>Check if we're the right</h1>
                <h1>Choice for your child.</h1>
                <h1>Take the online quiz now</h1>
            </div>
            <div class="text_p">
                <p> Share your educational philosophy, core values, and the 
                    passionate educators who nurture young minds. Highlight 
                    your unique offerings, such as extracurricular activities,
                     play-based learning, or specialized programs.</p>
                     <button type="button" class="btn btn-danger">CONTACT US</button>
            </div>

        </div>

        
    </div>
    <div class="foot_text d-flex justify-content-center p-2 mt-2">
            <div class="h1">
            <h1>Traditional in -person</h1>
            <h1>classroom encourages</h1>
            <h1>students to</h1>
            </div>
            <div class="p_text">
                <p>=> Grow patience and ability to focus over a longer period of times.</p>
                <p>=> Engage with their peers.</p>
                <p>=> Learn in a safe and inclusive environment</p>
            </div>
        </div>

</div>
</template>


<script setup>


</script>

<style scoped>

.container-fluid{
    width: 100%;
    /* height: */
    background-color: rgb(163, 163, 163);
    padding: 80px;
     .contant-box{
        width: 80%;
        margin: auto;
        background-color: rgb(72, 147, 194);
        height: 600px;
        display: flex;
        border-radius: 10px;
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;


        .left{
            width: 50%;
            height: 100%;
            /* background-color: red; */
            padding: 50px;
            & img{
                /* width: 100%; */
                height: 100%;
                border-radius: 60px;
                cursor: pointer;
                 
            }
            & img:hover{
                    transform: scale(1.02);
                    transition: 0.1 ease-in-out;
                }
            
        }
        .rigth{
            width: 50%;
            height: 100%;
            /* background-color: dodgerblue; */
            display: flex;
            flex-direction: column;
            justify-content: center;
            /* align-items: center; */
            padding: 60px;
            .text_p{
            /* padding: 70px; */
            text-shadow: 1px 0px 1px;
            & button{
                font-size:20px;
                font-family: 'Times New Roman', Times, serif;
            }
                
                 
                
            }
            .text_h{
                /* padding: 70px; */
                & h1{
                    text-shadow: 2px 0px 2px;
                    font-weight: bold;
                    font-family: 'Times New Roman', Times, serif;
                }
            }
        }

    }
}

.foot_text{
     & .h1{
        font-family: 'Times New Roman', Times, serif;
        color: rgb(0, 0, 0);
        text-shadow: 2px 0px 2px;
     }
     & .p_text{
        margin-left: 30px;
        & p{
            font-size: 17px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            /* text-shadow: 0px 0px 1px; */
        }

     }
}


</style>