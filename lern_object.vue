<template>
    <div class="containers">
        <div class="box">
            <div class="left">
                <h4>Learning objective &</h4>
                <h4>outcome</h4>
                 <div class="input-box">
                    <input type="checkbox" name="" id="in">   Values Formation <br>
                    <input type="checkbox" name="" id="in">   Values Formation <br>
                    <input type="checkbox" name="" id="in">   Values Formation
                 </div>
            </div>
            <div class="rigth">
                <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-img-002.jpg" alt="">
            </div>
        </div>
    </div>

</template>


<script setup>


</script>


<style scoped>
    .containers{
        width: 100%;
        height: 400px;
        background-color: rgb(218, 218, 218);


        & .box{
            width: 80%;
            height: 100%;
            margin: auto;
            /* background-color: red; */
            display: flex;
            & .left{
                padding: 40px;
                width: 50%;
                height: 100%;
                /* background-color: dodgerblue; */
                & .input-box{
                    width: 100%;
                    height: 80%;
                    /* background-color: red; */
                    /* display: flex; */
                    flex-direction: column;
                    font-size: 25px;
                    color: rgb(20, 15, 6);
                    text-shadow: 1px 0px 2px;
                    font-family: 'Times New Roman', Times, serif;
                   
                    
                }
                & h4{
                    font-size: 45px;
                    text-shadow: 2px 0px 3px;
                }
            }
            & .rigth{
                width: 50%;
                height: 100%;
                /* background-color: rgb(0, 0, 0); */
                display: flex;
                justify-content: center;
                align-items: center;
                & img{
                    /* width: 80%; */
                    height: 80%;
                    border-radius: 10px;

                }
            }
        }
    }


</style>

