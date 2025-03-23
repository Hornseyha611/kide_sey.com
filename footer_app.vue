<template>

    <div class="footer_text">
         <div class="contant">
            <div class="text_1">
            <h4>ABOUT US</h4>
            <p>We are a leading company in web development and design, committed to delivering quality solutions for our clients.</p>
        </div>
        <div class="text_1">
            <h4>Quick Links</h4>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Service</a></li>
                <li><a href="#">Contact</a></li>
            </ul>

        </div>
        <div class="text_1">
            <h4>Follow us</h4>
            <ul>
                <li><a href="#" ><i class="fa-brands me-2 text-primary fa-telegram"></i>Telegram</a></li>
                <li><a href="#"><i class="fa-brands  me-2 text-secondary fa-twitter"></i>Twinter</a></li>
                <li><a href="#"><i class="fa-brands  me-2 text-bg-primary fa-facebook"></i>Facebook</a></li>
                <li><a href="#"><i class="fa-brands  me-2 text-bg-dark fa-tiktok"></i>Tiktok</a></li>
            </ul>


        </div>
         </div>

    </div>
</template>

<script setup>




</script>

<style scoped>
.footer_text{
    width: 100%;
    height: 200px;
    background-color: rgb(215, 212, 212);
   
     
    


    & .contant{
        width: 80%;
        height: 100%;
        display: flex;
        gap: 10px;
        margin: auto;
        padding: 10px;
        & .text_1{
        width: 33.33%;
        height: 100%;
        
        /* background-color: rgb(241, 18, 18);? */
        
        padding-left: 60px;
        & p{
            text-shadow: 0px 1px 0px;
            font-family: 'Times New Roman', Times, serif
        }

        & h4{
            text-shadow: 1px 1px 3px;
            font-weight: bold;
        }

        & ul{
            list-style: none;
            display: flex;
            flex-direction: column;
            & li a{
                text-decoration: none;
                font-size: 17px;
                /* font-weight: bold; */
                font-family: 'Times New Roman', Times, serif;

                color: black;
                
            }
            & li a:hover{
                text-decoration: underline;
                color: rebeccapurple;

            }
            
        }

    }

    }
}
</style>