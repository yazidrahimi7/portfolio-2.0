<template>
<div class="projects">  
        <div class="section-header">
            <h1>Projects.</h1>
        </div>
        <div class="container container-first"> 
            <div class="pokemon row">
                <div class="pokemon-text col-sm-6 col-xs-12">
                        <h3>Pokemon</h3>
                        <p>A Pokemon battle between Charizard and Pikachu! <br> My first Vue JS project.</p> 
                </div>
                <div class="col-sm-6 col-xs-12">
                        <img src="../assets/2.png" class="pokemon-img">
                </div>    
            </div>
        </div>
        <div class="container-second container"> 
            <div class="row">
               <div class="content-left col-sm-6 col-xs-12">
                   <h3>iSMS 1.0</h3>
                   <img src="../assets/3.jpg" class="consec-img">
                   <p>Send SMS to remind customers directly to their <br> phones easily with API integration.</p> 
               </div>
               <div class="content-right col-sm-6 col-xs-12">
                   <h3>DB System</h3>
                   <img src="../assets/4.png" class="consec-img">
                   <p>Stored procedure and function methods to enhanced the database. <br> A great way to enhanced my MySQL skills.</p> 
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

    $p-1: #00C5A5;
    $p-2: #ADD8E6;
    $p-3: #FCFCC1;

    $font1: "Made Tommy", Arial, Helvetica, sans-serif;
    $font2: 'Source Sans Pro', sans-serif, Arial, Helvetica, sans-serif;

.projects 
{
    margin-top: 100px;

      @media screen and (max-width: 600px) {
                h3 {
                    font-size: 35px;
                }
               
                p {
                    font-size: 17px;
                    text-align: left;                    
                }           
            }

                p {
                    font-family: $font2;
                    font-size: 20px;
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

    .container-first {
        background-color: $p-1;
        padding: 20px;
        max-width: 90%;

        h3 {
            font-family: $font1;
            font-size: 50px;           
        }

        h3, p {
            color: $primary;
            text-align: center;
            padding: 10px; 
            transition: transform .2s;       
        }
        
       

        .pokemon-img {
            width: 100%;
            height: 100%;
            filter: drop-shadow(0px 6px 6px rgba(16,27,30,0.5));
        }

        .pokemon-text {
            text-align: center;
            margin: auto;
        }
    }

    .container-first:hover {
        h3, p {
        transform:translateY(-10px) 
            }
    }

    .container-second {
         max-width: 90%;
         font-family: $font1;
         color: $primary;
         
        h3 {
            color: $primary;
            padding: 10px;
            font-family: $font1;
            font-size: 50px;
        }

    .consec-img {
                filter: drop-shadow(0px 6px 6px rgba(16,27,30,0.5)); 
                max-width: 90%;   
                height: auto;
            }
        
            .content-left {
            text-align: center;
            background-color: $p-2;
            padding: 50px 0 0;

              p {
                    // margin-top: 20px !important;
                    // margin: 50px;
                    margin: 30px 50px 80px 50px;
                }
                
                h3, p {
                    transition: transform .2s; 
                }
          
            }
            .content-left:hover {
                h3 {
                    transform:translateY(-10px)
                }
                p {
                    transform:translateY(10px)
                }
            }
        
    .content-right {
                text-align: center;
                background-color: $p-3;
                padding: 50px 0 0;

                p {
                    margin: 10%;
                }
                h3, p {
                    transition: transform .2s; 
                }
        }    
     .content-right:hover {
                h3 {
                    transform:translateY(-10px)
                }
                p {
                    transform:translateY(10px)
                }
            }
    }    
}

</style>