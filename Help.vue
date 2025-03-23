<template>
    <div class="containers">
      <div class="content_text">
          <div class="left_text">
            <img src="https://kiddystar.oceanwp.org/wp-content/uploads/2024/02/kiddystar-img-001.jpg" alt="">
            </div>
          <div class="right_text">
                <h1>Help your kids discover and </h1>
                <h1>unleash  <font style="color: darkblue;">Creativity</font></h1>
                <p>Welcome to the Kiddy Star website template! Built with the 
                    
                    user-friendly Elementor drag-and-drop editor, this template o
                    ffers complete customization freedom. Easily personalize the 
                    content, images, and color scheme to perfectly reflect your 
                    kindergarten’s atmosphere and connect with parents and children alike.</p>
            </div>
        </div>


    </div>

    <div class="Input_information">
        <div class="text">
            <h1>Our Upcoming Programs</h1>
        <p>Subscribe to our newsletter and be the first to
            learn about our new programs</p>
            <input type="text" name="" id=""  placeholder="Enter Your Email.........." >
             <button type="button">Go</button>
        </div>
    </div>
</template>
<script setup>


</script>

<style scoped>

.Input_information{
    width: 100%;
    height: 410px;
    background-color: rgb(48, 100, 152);
    display: flex;
    justify-content: center;
    & .text{
        width: 30%;
        height: 100%;
        /* background-color: rgb(6, 108, 162); */
        display: flex;
        flex-direction: column;
        /* padding: 50px; */
        justify-content: center;
        /* align-items: center; */
        & p,h1{
            color: whitesmoke;
            /* text-shadow: 1px 0px 0px; */
            font-family: 'Times New Roman', Times, serif;
        }
        & input{
            width: 70%;
            height: 15%;
            border-radius: 10px;
            border: 2px solid whitesmoke;
             background: transparent;
             padding: 10px;
             outline: none;
             color: whitesmoke;
             position: relative;
             background: transparent;
             
            
        }
        & button{
            position: absolute;
            margin-top: 120px;
           right: 690px;
           padding: 6px;
           border-radius: 10px;
           outline: none;
           color: rgb(0, 0, 0);
           box-shadow: rgba(0, 0, 0, 0.14) 0px 5px 15px;
           background: transparent;
             
        }
        & button:hover{
            color: rgb(0, 0, 0);
            background-color: rgb(250, 250, 250);
        }

        
        
    }
}
.containers{
    width: 100%;
    & .content_text{
        width: 80%;
        margin: auto;
        height: 500px;
        
        /* background-color: red; */
        display: flex;
        gap: 90px;
        & .left_text{
            width: 50%;
            height: 100%;
            /* background-color: yellow; */
            display: flex;
            justify-content: center;
            align-items: center;
            & img{
                /* width: 100%; */
                height: 60%;
                border-radius: 40px;
                cursor: pointer;
            }
        }
        & .right_text{
            width: 50%;
            height: 100%;
            /* background-color: rgb(178, 175, 175); */
            display: flex;
            
            /* align-items: center; */
            flex-direction: column;
            margin-top:100px;
            & h1{
                text-shadow: 2px 0px 2px;
            }
            & p{
                font-style: oblique;
            }
        }
    }

}

</style>