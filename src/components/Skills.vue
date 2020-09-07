<template>
    <div class="skills">  
        <div class="section-header">
            <h1>Skills.</h1>
        </div>
        <div class="container">
            <div class="content d-flex flex-row">
                <div class="svg">
                    <img src="../assets/svg/html5.svg">
                    <img src="../assets/svg/css3.svg">
                    <img src="../assets/svg/javascript.svg">
                    <img src="../assets/svg/git.svg">
                    <img src="../assets/svg/php.svg">
                    <img src="../assets/svg/mysql.svg">   
                    <img src="../assets/svg/wordpress.svg">   
                    <img src="../assets/svg/vue-dot-js.svg">   

                    <img src="../assets/svg/laravel.svg">   
                    <img src="../assets/svg/adobexd.svg">   
                    <img src="../assets/svg/adobeillustrator.svg">   
                    <img src="../assets/svg/adobephotoshop.svg">   
                    <img src="../assets/svg/figma.svg">   
                    <img src="../assets/svg/sass.svg">   
                </div>
            </div>  
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

    $main: #F6F5F5;
    $primary: #101010;

    $font1: "Made Tommy", Arial, Helvetica, sans-serif;
    $font2: 'Source Sans Pro', sans-serif, Arial, Helvetica, sans-serif;

.skills 
{   
    margin-top: 100px;
    .section-header {
        font-size: 160px;
        font-weight: 800;
        letter-spacing: -0.02em;
        text-align: left;
        z-index: 10;
        position: relative;
        top: 45px;
        padding-left: 85px;

        @media screen and (max-width: 600px) {
            padding-left: 20px;
            
        }

        h1 {
            color: $primary;  
            font-family: $font1;
            font-size: 120px; 

            @media screen and (max-width: 600px) {
                font-size: 60px;
                position: relative;
                top: -17px;             
            }
        }
    }
    .container {
            background-color: #EE6F57;
            padding: 60px 0;
            max-width: 90%;

        @media screen and (max-width: 600px){
            padding: 30px;         
        }

    .content {
            margin: auto;
            width: 46%;
            padding: 10px;        

        img {
            width: 70px;
            margin: 10px; 
            transition: transform .2s;  
        }
        img:hover {
             transform:translateY(-10px) 
        }

         @media screen and (max-width: 600px){   
            width: 100%;
             
              img {
                  width: 40px;
              }
        }
    }
    

    }
}
</style>