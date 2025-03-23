<template>

    <div class="contant" id="about">
         <div class="box-text">
            <div class="box">
            <div class="image">
                <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kindergarten.png" alt="">
            </div>
            <div class="text">
                    <h3>Nurture</h3>
                    <p>Launch your kindergarten's website with ease using the Kiddy Star template by OceanWP.</p>
            </div>
            
        </div>
        <div class="box">
             <div class="image">
                <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/bear-toy.png" alt="">
            </div>
            <div class="text">
                <h3>Playtime</h3>
                <p>Launch your kindergarten's website with ease using the Kiddy Star template by OceanWP.</p>
                
            </div>

        </div>
        <div class="box">
             <div class="image">
                <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/pencil-2.png" alt="">
            </div>
            <div class="text">
                <h3>Activities</h3>
                <p>Launch your kindergarten's website with ease using the Kiddy Star template by OceanWP.</p>
                
            </div>

        </div>
         </div>

    </div>

</template>

<script setup>

</script>

<style scoped>

   .contant{
    width: 100%;
    height: 100%;
    & .box-text{
        width: 80%;
        height: 400px;
        margin: auto;
        /* background-color: yellow; */
        display: flex;
        /* gap: 10px; */
        & .box{
            width: 33.33%;
            height: 100%;
            /* background-color: darkorange; */
            display: flex;
            & .image{
                width: 40%;
                height: 100%;
                /* background-color: darkviolet; */
                display: flex;
                justify-content: center;
                align-items: center;
                & img{
                    width: 90px;
                    height: 20%;
                    cursor: pointer;
                }

            }
            & .text{
                width: 60%;
                height: 100%;
                /* background-color: blue; */
                display: flex;
                justify-content: center;
                align-items: center;
                flex-direction: column;
                & h3{
                    margin-right: 140px;
                    text-shadow: 2px 0px 2px;

                }
                & p{
                    font-style: oblique;
                }
            }
        }
    }

   }


</style>