<template>
    <div class="contant" id="teacher">
        <h1>Our Teachers</h1>
        
        <div class="box-card">
            <div class="card">
                <img src="https://img.freepik.com/premium-vector/friendly-approachable-cartoon-male-teacher-standing-confidently-front-blackboard_851674-43573.jpg" alt="">
                <p>Seyha</p>
            </div>
            <div class="card">
                <img src="https://i.pinimg.com/736x/11/f9/b5/11f9b55a05f2820b6359fbe9b638b081.jpg" alt="">
                <p>Thida</p>
            </div>
            <div class="card">
                <img src="https://img.favpng.com/11/13/11/teacher-cartoon-drawing-royalty-free-png-favpng-zE6bRpGk7fK7Jm8JNsRgPQSTB.jpg" alt="">
            <p>Sin</p>
            </div>
            <div class="card">
                <img src="https://clipart-library.com/2023/57a3a68b78c4ae192f4f3ea0654b48ed.jpg" alt="">
            <p>Mey</p>
            </div>
        </div>
    </div>
</template>]
<script setup>


</script>


<style scoped>
    .contant{
    width: 100%;
    height: 600px;
    background-color: rgb(43, 43, 126);
    padding: 10px;
    h1{
        text-align: center;
        color: whitesmoke;
        font-family: 'Times New Roman', Times, serif;
        font-size:60px;
        /* margin-top: 30px; */
    }
    .box-card{
        width: 70%;
        margin: auto;
        height: 70%;
        /* background-color: yellow; */
        display: grid;
        padding: 40px;
        grid-template-columns: repeat(4,1fr);
        gap: 10px;
        .card{
            width: 80%;
            height: 100%;
            /* background-color: red; */
            border-radius: 10px;
            overflow: hidden;
            position: relative;
            & img{
                width: 100%;
                height: 100%;
            }
            & p{
                position: absolute;
                top: 0;
                font-size: 20px;
                padding: 10px;
                font-weight: bold;
                display: none;
            }
            
        }
        & .card:hover{
            transform: translate(0px);
            transition: 0.1 ease-in-out;
            width: 99%;
            padding: 40px;
            transition-duration: 0.5s;
            /* padding: 5px; */
            & p{
                display: block;
                color: rgb(55, 82, 133);
            }
        }
    }
}


</style>