<template>
    <div class="contact">  
        <div class="section-header">
            <h1>Contact.</h1>
        </div>
        <div class="container">
            <div class="row"> 
                <div class="contact-text col-md-7 col-sm-12 col-xs-12">
                    <h3> <a href="mailto:yazidrahimi7@gmail.com?subject=Hello Yazid!">yazidrahimi7@gmail.com</a></h3>
                      <hr >
                   <p>I never stopped learning to upscale my skills, <br> Learning is a process of success. Master one thing to conquer everything. <br> Let's get in touch! 
                   <br><br><br> Muhammad Yazid bin Noor Rahimi <br> Kuala Lumpur, Malaysia. </p> 
                   <div class="svg">
                       <a href="https://github.com/yazidrahimi7">
                           <img src="../assets/svg/github.png" alt="github">
                       </a>
                       <a href="https://www.linkedin.com/in/muhdyazid/">
                           <img src="../assets/svg/linkedin3.png" alt="linkedin">
                        </a>    
                    </div>
                </div>
                <div class="contact-img col-md-5 col-sm-12 col-xs-12 d-none d-sm-block">
                    <img src="../assets/IMG_1.jpg" class="image" alt="yazidrahimi" loading="lazy">
                    
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
    $secondary: #484848;
    $tertiary: #145374;

    $font1:  'Source Sans Pro', sans-serif;
    $font2:  'Roboto', sans-serif;

.contact 
{   
    margin-top: 100px;
    // max-height: 500px;
  
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
        padding: 0;
        background-color: $tertiary;
        max-width: 90%;
        height: 100%;
        margin-bottom: 100px;
        padding: 0;
       
       .row {
           height: 100%;
       }
        .contact-text {
           width: 100%;
           height: 100%;
           padding: 50px;

            h3 {
                text-align: center;
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
                    font-size: 35px;
                    overflow-wrap: break-word;
                    text-align: left;               
                }
            }
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
                padding-top: 30px;
            }
            img {
                width: 50px;
                margin: 55px 5px;
                float: left;
                transition: transform .2s;  
            }
            img:hover {
                 transform: scale(1.2) 
            }
        }
    
        .contact-img {     
            .image {
                width: 100%;
                height: 100%;  
                object-fit: cover;      
            }
        }    
    } 
}
</style>