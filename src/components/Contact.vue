<template>
    <div class="contact">
        <div class="section-header">
            <h1>Contact.</h1>
        </div>
        <div class="container-second container"> 
            <div class="row">
               <div class="content-left col-sm-6 col-xs-12">
                  <h3> <a href="mailto:yazidrahimi7@gmail.com?subject=Hello Yazid!">yazidrahimi7@gmail.com</a></h3>
                    <hr >
                   <p>I never stopped learning to upscale my skills, <br> Learning is a process of success. Master one thing to conquer everything. <br> Let's get in touch! 
                   <br><br><br> Muhammad Yazid bin Noor Rahimi <br> Kuala Lumpur, Malaysia. </p> 

                    <div class="svg">
                       <a href="https://github.com/yazidrahimi7">
                           <img src="../assets/svg/github.png">
                       </a>
                       <a href="https://www.linkedin.com/in/muhdyazid/">
                           <img src="../assets/svg/linkedin3.png">
                        </a>    
                    </div>
                  
               </div>
               <div class="content-right col-sm-6 col-xs-12">  
                   <img src="../assets/IMG_1.jpg" class="consec-img" >     
               </div>
            </div>
        </div>
    </div>
</template>

<script>

  
</script>

<style lang="scss" scoped>
    $main: #F6F5F5;
    $primary: #101010;
    $tertiary: #145374;

    $p-1: #00C5A5;
    $p-2: #ADD8E6;
    $p-3: #FCFCC1;

    $font1: "Made Tommy", Arial, Helvetica, sans-serif;
    $font2: 'Source Sans Pro', sans-serif, Arial, Helvetica, sans-serif;
      
.contact 
{
    margin-top: 100px;

   hr {
        border-top: 3px solid $main;
        margin: 60px 0 40px;
        width: 100px;  
    }

    p {
        color: $main;
        font-family: $font2;
        font-size: 20px;
        text-align: left;
            

@media screen and (max-width: 600px) {             
                     
                font-size: 17px;
                text-align: left;                                            
            }
        }

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

    .container-second {
         max-width: 90%;
         height: 600px;
         margin-bottom: 100px;
     
         h3 {
            padding: 10px;
            font-family: $font1;
            font-size: 50px;
           
            a {
                color: $main;
            }
                a:hover { 
                    text-decoration-color: $main;
                    text-decoration-thickness: 0.1em;
                    text-underline-offset: 5px;
                }

            @media screen and (max-width: 600px) {
              font-size: 20px;
              text-align: left;               
            }
        }

        .content-left {
            text-align: center;
            background-color: $tertiary;
            padding: 50px;
            height: 600px;
            
            img {
                width: 50px;
                margin: 35px 5px;
                float: left;
                transition: transform .2s;  
            }
            img:hover {
                 transform: scale(1.2) 
            }
        }
        
        .content-right {
                background-color: $tertiary;
                padding: 0;
                height: 600px;
                text-align: right;
          
        .consec-img {
                padding: 0;
                
                max-width: 100%;   
                max-height: 100%;    
            }
        }    
    }    
}


</style>