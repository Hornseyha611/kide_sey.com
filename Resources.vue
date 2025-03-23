<template>
     <div class="containers" id="resource">
        <div class="t-head">
        <h4>Our Resources</h4>
        <p>This solution showcases your curriculum and facilities and connects with parents seeking the best education for their children.</p>
    </div>
        <div class="box-cards">
            <div class="cards">
                <img src="https://scontent.fpnh8-3.fna.fbcdn.net/v/t1.6435-9/103246909_109765764103862_8383295822733237019_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeGvqr929XpppXoKd9iiRTV75ubMF9yx4T7m5swX3LHhPqdfeZFR-w8I4l8g9dlO2QXRJ0M1XRNL58GEaGzepN5n&_nc_ohc=ZahZngPLPHUQ7kNvgG6SwEV&_nc_oc=Adj-ACHOcbtO_kcJzOESum9BnQ7zglA-rPYAubUltRYQ_cy4zA2FPDCOlWN-k6NnQxo&_nc_zt=23&_nc_ht=scontent.fpnh8-3.fna&_nc_gid=0k3cNgGn_-43RP_vgsTEUw&oh=00_AYHhtCoiAtbOaItlkFSwu45SogihQcYtkcNhi4Wu_AAGAg&oe=67FCF405" alt="">
                <p>READ STORY</p>
               
            </div>
            <div class="cards">
                <img src="https://centrepointschools.com/blogs/wp-content/uploads/2025/02/Essential-Study-Habits-for-Young-Learners.jpg" alt="">
                <p>READ STORY</p>
            </div>
            <div class="cards">
                <img src="https://res.cloudinary.com/grand-canyon-university/image/fetch/w_750,h_564,c_fill,g_faces,q_auto/https://www.gcu.edu/sites/default/files/media/images/Blog/Content%20Campaigns/gcu-studyhabits-graphic-v2_og.png" alt="">
                <p>READ STORY</p>

            </div>
        </div>
     </div>

</template>
<script setup>

</script>
<style scoped>
   .containers{
    width: 100%;
    background-color: antiquewhite;
    padding: 100px;
    .t-head{
        width: 100%;
        text-align: center;
        /* padding: 40px; */
        & h4{
            text-shadow: 2px 0px 3px;
        }
        & p{
            text-shadow: 1px 0px 1px;
        }
    }
    & .box-cards{
        width: 80%;
        margin: auto;
        display: grid;
        grid-template-columns: repeat(3,1fr);
        gap: 30px;
        margin-top: 40px;

        & .cards{
            width: 100%;
            height: 550px;
            background-color: rgb(237, 99, 29);
            border-radius: 20px;
            overflow: hidden;
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
          
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
            /* background-image: url(	https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-banner-img-002.jpg); */

            & img{
                width: 100%;
                height: 100%;
                overflow: hidden;
                cursor: pointer;
                
            }
            & P{
                position: absolute;
                top: 0;
                left: 0;
                padding: 10px;
                background-color: red;
                position: fixed;
            }
           
        }
        & .cards:hover{
            /* padding: 5px;
            transform: scaleY(-30px);
            transform: scale(1.03);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            transition: 0.1 ease-in-out; */
             transition-duration: 0.8s;
             transform: translatey(-20px);
            
            & img{
                 border-radius: 10px;

            }
            /* transform: scale(1.03); */
            
            & p{
                transform: scale(1.02);
                /* transition: cubic-bezier(0.23, 1, 0.320, 1); */
                color: white;
            }
            
         


           
            
        }
    }
   }

</style>