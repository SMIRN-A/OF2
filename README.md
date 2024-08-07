* {
	padding: 0px;
	margin: 0px;
	border: none;   
}


/* НЕ ТРОГАТЬ начало */


.razmitie {
  position: absolute;
  width: 30%;
  height: 24%;
  filter:blur(40px);
  border-radius: 40px;
  background-color:#000000be;
  z-index: 15;
  margin-top: 17%;
  margin-left: 35%;
}


.stroka {position: absolute;
background-color: #000000a0;
z-index: 1;
width: 8vw;
filter: blur(30px);
height: 8vw;
margin-left: 1%;
margin-top: 1%;
border-radius: 50%;}



.fon > .video_fon1 {

    position: fixed ;
    padding-left:50%;
    margin-top: -30%;
    width: 50%;
    filter:brightness(30%);
    z-index: 1;
    
    
}

.fon > .video_fon2 {

    position: fixed ;
    width: 47%;
    filter:brightness(30%);
    z-index: 1;
    
}

.fon > .video_fon3 {

  position: fixed ;
  margin-left: 30%;
  margin-top: 0%;
  width: 38%;
  filter:brightness(30%);
  z-index: 3;
  
}






body {
    background-color: rgb(32, 32, 32);
   
}



.logo {max-width: 7vw;
    margin-left: 1%;
    margin-top: 1%;
width: 7vw;
max-height: 7vw;
height: 7vw;
display: grid;
justify-items: center;
align-items: center;
border-radius: 50%;
position: absolute;
z-index: 5;}



.kart1 {width: 7vw;
left: 3% ;
top: 2%;
grid-column: 1 / -1;
grid-row: 1 / -1;
cursor: pointer;


animation: rotation infinite 10s linear ;
}

@keyframes rotation {
    0%{rotate:0deg}
    10%{filter: brightness(100%)}
    20%{filter: brightness(100%)}
    30%{filter: brightness(80%)}
    40%{filter: brightness(60%)}
    50%{filter: brightness(40%)}
    60%{filter: brightness(20%)}
    70%{filter: brightness(40%)}
    80%{filter: brightness(60%)}
    90%{filter: brightness(100%)}
    100%{rotate:360deg}
   
}





.logo >p {font-size: 4vw;
    
    grid-column: 1 / -1;
    grid-row: 1 / -1;
    color: rgba(255, 255, 255, 0.737);
    background: linear-gradient(to right, #4d4d4d 0, #fff 10%, #4d4d4d 20%);
    background-position: 0;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        animation: shine 10s infinite linear;
        animation-fill-mode: forwards;
        -webkit-text-size-adjust: none;
    animation: spinn 10s infinite linear Alternate;
    transform: left;
    cursor: pointer
    }

    @keyframes spinn {
        0%{transform: rotateY(0deg);
            background-position: 180px
            
        }
        100%{transform: rotateY(360deg)}
      
       
    }
    
  






     
      


      .btn-shine {
        position: absolute;
        font-family: Georgia;
        margin-top: 20%;
        margin-left: 38%;
 -webkit-text-fill-color: transparent;
       
        color: w ;
        background: linear-gradient(45deg,  #ffd04289 30%,#ffffff ,#392b00,  #ffd043 );
        background-position: 0;
        -webkit-background-clip: text;
        -webkit-text-size-adjust: none;
        text-decoration: none;
        animation: shine 25s infinite linear;
        animation-fill-mode: forwards;
        font-weight: 500;
        font-size: 4vw;
        z-index: 30;
        
     
      }
      @keyframes shine {
        0% {
          background-position: 0vw;
          
        }
          
        
        100% {
          background-position: 100vw;
        }
      }



      .btn-shine2 {
        position: absolute;
        font-family: Georgia;
        margin-top: 23.5%;
        margin-left: 45%;
        z-index: 150;
        
        color: rgba(255, 255, 255, 0) ;
        background: linear-gradient(45deg,  #bfbfbf89 30%,#ffffff ,#404040,  #ffffff );
        background-position: 0;
     -webkit-background-clip: text;       
        -webkit-text-size-adjust: none;
        text-decoration: none;
        animation: btn-shine2 45s infinite linear;
        animation-fill-mode: forwards;
        font-weight: 400;
        font-size: 3vw;
       
        
     
      }
      @keyframes btn-shine2 {
        0% {
          background-position: 0vw;
          
        }
          
        
        100% {
          background-position: 100vw;
        }
      }

      
      
      
      .ramka1 {
        position: absolute;
        z-index: 18;
        margin-left: 45.5%;
        margin-top: 14%;
        width: 10%;
        opacity: 100%;
        animation: shine3 reverse 7s infinite ;
      }
      
      @keyframes shine3 {
        50%{opacity: 10%;
          filter: brightness(-50%);}
          
        }
        
        
        
        .ramka2 {
          position: absolute;
          z-index: 17;
          margin-left: 45.5%;
          margin-top: 14%;
          width: 10%;
          opacity: 100%;
        }
        
        .ramka3 {
          position: absolute;
          z-index: 17;
          margin-left: 45.5%;
          margin-top: 14%;
          width: 10%;
          opacity: 100%;
        }
        
        
        
        
        .container {
          margin-left: 23%;
          position: absolute;
          z-index: 30;
          display: flex;
          justify-content: center;
          align-items: center;
          height: 10vh;
          width: 50vw;
        }
        .container:hover > .section {
          filter: brightness(22%);
        }
        .container:hover > .section:hover {
          filter: brightness(100%);
        }
        .container .section {
          flex-grow: 1;
          position: relative;
          height: 100%;
          transition: all 0.4s;
          align-items: center;
          justify-content: center;
          box-sizing: border-box;
          text-align: center;
          flex: 1;
          cursor: pointer
        }
        .container .section .cont_title {
          position: relative;
          margin: auto;
          width: 100%;
          height: auto;
          text-align: center;
          margin-top: 3vh;
          cursor: pointer
          /*.letter-container{
            position: relative;
            width: 2vw;
            height: 100px;
            position: relative;
            margin: auto;
            .lettering{
              transition: all 0.3s;
              color: white;
              
              span{
                height: 10vw;
                font-family: 'Economica', sans-serif;
                font-size: 1.6vw;
                text-shadow: 1px 2px 5px rgba(0,0,0,0.5);
                position: absolute;
                width: 15px;
                left: 0;
                top: 0;
                transform-origin: bottom center;
              }
              @include rotated-text(11);
            }
          }*/
        }
        .container .section .cont_title h1 {
          text-transform: uppercase;
          color: rgb(255, 225, 1);
          font-family: "Economica", sans-serif;
          text-shadow: 1px 2px 5px rgba(0, 0, 0, 0.5);
          font-size: 0vw;
          margin: 0;
          transition: font-size 0.3s;
          vertical-align: middle;
          cursor: pointer
        }
        .container .section .cont_title h3 {
          text-transform: uppercase;
          font-family: "Economica", sans-serif;
          font-size: 1vw;
          transition: all 0.3s;
          color: rgba(255, 255, 255, 0.646);
          background: linear-gradient(to bottom, rgb(0, 0, 0),rgb(255, 255, 255), rgb(0, 0, 0));
          -webkit-background-clip: text;
          -webkit-text-size-adjust: none;
          text-decoration: none;
          letter-spacing: normal;
          text-shadow: 1px 2px 5px rgba(0, 0, 0, 0.5);
          cursor: pointer
        }
        .container .section .cont_desc {
          position: relative;
          display: block;
          text-align: center;
          width: 5vw;
          height: auto;
          margin: auto;
          opacity: 0;
          transition: opacity 0.8s, transform 0.7s, padding-top 0.9s;
          padding-top: 2vh;
          transform: scale(1.2);
        }
        .container .section .cont_desc p {
          margin: 0;
          font-family: "Economica", sans-serif;
          color: white;
          font-size: 0.5vw;
        }
        .container .section:hover {
          flex-grow: 1.8;
  transition: flex 0.2s;
}
.container .section:hover > .cont_title h1 {
  font-size: 1.3vw;
  transition: font-size 0.4s;
}
.container .section:hover > .cont_title h3 {
  font-size: 1.3vw;
  transition: all 0.4s;
}
.container .section:hover > .cont_desc {
  opacity: 1;
  padding-top: 2vh;
  transform: scale(1.5);
  transition: opacity 0.7s, padding-top 0.5s, transform 0.1s;
  transition-delay: 0s, 0.1s, 0s;
}
.container .section:nth-child(1) {
  background: url("https://artsandculture.withgoogle.com/gcs/national-parks-service/en-us/Asset-Kenai-desktop.jpg") center;
}
.container .section:nth-child(2) {
  background: url }

.smirnov {position: absolute;
  color: #ffffff;
z-index: 30;
font-size: 1vw;
margin-left: 45%;
margin-top: 11%;
border: ridge 2px white;
padding: 3px;
cursor: pointer}

  
.obramlenie {position: absolute;
    width: 35%;
  z-index: 35;
  
  margin-left: 33.5%;
  margin-top: 18%;
  cursor: pointer}

.chern {
margin-left: 25%;
margin-top: 0.7%;
  width: 48%;
  height: 6%;
  background-color: #000000ad;
  position: absolute;
  z-index: 3;
  filter: blur(14px);
}

 


.text_opisanie {
  position: absolute;
  z-index: 1500;
  margin-top: 31%;
  margin-left: 24%;
  margin-right: 21%;
  color: #fff;
  font-size: 0.9vw;
  background-color: #00000068;
  padding: 1%;
  
}

.shpon {
  
  color: #fff;
  z-index: 2800;
  font-family: Georgia;
  -webkit-text-fill-color: transparent;
  
  color: w ;
  background: linear-gradient(20deg,  #ffcd3863,#ffffff,  #ffd75e57,#ffffff,  #ffd75ea1,  #ffd75e57,#ffffff );
  background-position: 0;
  -webkit-background-clip: text;
  -webkit-text-size-adjust: none;
  text-decoration: none;
  animation: shine2 8s infinite linear;
  animation-fill-mode: forwards;
  font-weight: 500;
  font-size: 3vw;
  background-color: #000000;
  
  
}

@keyframes shine2 {
  0% {
    background-position: 0vw;
    
  } 
  100% {
    background-position: 36vw;
    
  }
}

.sosos {
  position: absolute;
  z-index: 15000;
  margin-top: 60%;
  margin-left: 34%;
  
}

.sosos_img1 {width: 5vw;
  margin-top: 58%;
  margin-left: 28%;
  position: absolute;
  z-index: 35000}
  
  .sosos_img2 {width: 5vw;
    margin-top: 58%;
    margin-left: 71%;
    position: absolute;
    z-index: 35000}
    
    .zatemnenie {
      position: absolute;
      
      z-index: 2000;
      width: 99vw;
      height: 8vw;
      background-color: #00000082;
      margin-top: 56vw;
    }
    
    
    /* КАБИНЕТ ШПОН КАРТИНКИ НАЧАЛО */
    .kabinet_shpon_img1 {
      min-width: 46vw;
      min-height: auto  ;
      max-width: 46vw;
      max-height: auto ;
      border-radius: 8%;
      filter: brightness(80%);
      &.kabinet_shpon_img1:hover {scale: 1.1;
        transition: 0.4s;
        cursor: pointer;}
    }
    
    
    
    .kabinet_shpon_img2 {
      min-width: 15vw;
      min-height: auto  ;
      max-width: 15vw;
      max-height: auto ;
      border-radius: 8%;
      &.kabinet_shpon_img2:hover {scale: 1.2;
        transition: 0.4s;
        cursor: pointer;}
      }
      
      .kabinet_shpon_img3 {
        min-width: 15vw;
        min-height: auto  ;
        max-width: 15vw;
        max-height: auto ;
        border-radius: 8%;
        &.kabinet_shpon_img3:hover {scale: 1.2;
          transition: 0.4s;
          cursor: pointer;}
        }
        
        .kabinet_shpon_img4 {
          min-width: 15vw;
          min-height: auto  ;
          max-width: 15vw;
          max-height: auto ;
          border-radius: 8%;
          &.kabinet_shpon_img4:hover {scale: 1.2;
            transition: 0.4s;
            cursor: pointer;}
          }
          
          .box_kabinet_shpon_img1 {position: absolute;
            z-index: 12500;
            min-width: 20vw;
            min-height: auto  ;
            margin-top: 0%;
            margin-left: 0;
            padding: 1vw;
            margin-top: 70%;
            margin-left: 2%;
            display: flex;
            justify-items: center;
            align-items: center;
            
            
            border-style: #ffd043 ridge 20px;
            
          }
          
          .box_kabinet_shpon_img2 {position: absolute;
            z-index: 12501;
            min-width: 20vw;
            min-height: auto  ;
            margin-top: 0%;
            margin-left: 0;
            padding: 1vw;
            margin-top: 102%;
            margin-left: 2%;
            display: flex;
            justify-items: center;
            align-items: center;
            border-style: #ffd043 ridge 20px;
          }
          
          
          .box_kabinet_shpon_img3 {position: absolute;
            z-index: 12502;
            min-width: 20vw;
            min-height: auto  ;
            margin-top: 0%;
            margin-left: 16;
            padding: 1vw;
            margin-top: 102%;
            margin-left: 18%;
            display: flex;
            justify-items: center;
            align-items: center;
            
            
            border-style: #ffd043 ridge 20px;
            
          }
          
          
          .box_kabinet_shpon_img4 {position: absolute;
            z-index: 22503;
            min-width: 20vw;
            min-height: auto  ;
            margin-top: 0%;
            margin-left: 0;
            padding: 1vw;
            margin-top: 102%;
      margin-left: 34%;
      display: flex;
      justify-items: center;
      align-items: center;
      
      
      border-style: #ffd043 ridge 20px;
      
    }
    
    /* КАБИНЕТ ШПОН КАРТИНКИ КОНЕЦ */
    
     /* КАБИНЕТ ШПОН ОПИСАНИЕ НАЧАЛО */
    .nazvanie_shpon {
      position: absolute;
      z-index: 22504;
      font-size: 1.5vw;
      min-height: auto  ;
      margin-top: 0%;
      margin-left: 0;
      padding: 1vw;
      margin-top: 73%;
      margin-left: 54%;
      display: flex;
      color: white;
      background-color: #0000004d;
      
    }
      
      .box_kabinet_shpon_opisanie_1 {position: absolute;
        z-index: 22504;
        font-size: 0.6vw;
        min-height: auto  ;
        margin-top: 0%;
        margin-left: 0;
        margin-right: 1%;
        margin-top: 77%;
        margin-left: 54%;
        display: flex;
        & li {
          padding: 0.3vw;
          color: white;
          background-color: #00000063;
        }
      }
      ul {list-style-type: none;
      }
      
      .box_kabinet_shpon_opisanie_2 {position: absolute;
        z-index: 22504;
        font-size: 0.8vw;
        min-height: auto  ;
        margin-top: 0%;
        margin-left: 0;
        padding: 1vw;
        margin-top: 80%;
        margin-left: 54%;
        margin-right: 1%;
        display: flex;
        color: white;
        background-color: #0000004d;
      }
      
      
      .box_kabinet_shpon_opisanie_3 {position: absolute;
        z-index: 22504;
        font-size: 0.8vw;
        min-height: auto  ;
        margin-top: 0%;
        margin-left: 0;
        padding: 1vw;
        margin-top: 89%;
        margin-left: 54%;
        margin-right: 1%;
        display: flex;
        color: white;
        background-color: #0000004d;
      }
      
      .box_kabinet_shpon_opisanie_4 {position: absolute;
        z-index: 22504;
        font-size: 0.8vw;
        min-height: auto  ;
        margin-top: 0%;
        margin-left: 0;
        padding: 1vw;
        margin-top: 96%;
        margin-left: 54%;
        margin-right: 1%;
        display: flex;
        color: white;
        background-color: #0000004d;
      }
      /* КАБИНЕТ ШПОН ОПИСАНИЕ КОНЕЦ */


      
      
      /* КАБИНЕТ_2 ШПОН КАРТИНКИ НАЧАЛО */


      .kabinet_2_shpon_img1 {
        min-width: 46vw;
        min-height: auto  ;
        max-width: 46vw;
        max-height: auto ;
        border-radius: 8%;
        filter: brightness(80%);
        &.kabinet_2_shpon_img1:hover {scale: 1.1;
          transition: 0.4s;
          cursor: pointer;}
      }
      
      
      
      .kabinet_2_shpon_img2 {
        min-width: 15vw;
        min-height: auto  ;
        max-width: 15vw;
        max-height: auto ;
        border-radius: 8%;
        &.kabinet_2_shpon_img2:hover {scale: 1.2;
          transition: 0.4s;
          cursor: pointer;}
        }
        
        .kabinet_2_shpon_img3 {
          min-width: 15vw;
          min-height: auto  ;
          max-width: 15vw;
          max-height: auto ;
          border-radius: 8%;
          &.kabinet_2_shpon_img3:hover {scale: 1.2;
            transition: 0.4s;
            cursor: pointer;}
          }
          
          .kabinet_2_shpon_img4 {
            min-width: 15vw;
            min-height: auto  ;
            max-width: 15vw;
            max-height: auto ;
            border-radius: 8%;
            &.kabinet_2_shpon_img4:hover {scale: 1.2;
              transition: 0.4s;
              cursor: pointer;}
            }
            
            .box_kabinet_2_shpon_img1 {position: absolute;
              z-index: 12500;
              min-width: 20vw;
              min-height: auto  ;
              margin-top: 0%;
              margin-left: 0;
              padding: 1vw;
              margin-top: 130%;
              margin-left: 2%;
              display: flex;
              justify-items: center;
              align-items: center;
              border-style: #ffd043 ridge 20px;
              
              
              
            }
            
            .box_kabinet_2_shpon_img2 {position: absolute;
              z-index: 12501;
              min-width: 20vw;
              min-height: auto  ;
              margin-top: 0%;
              margin-left: 0;
              padding: 1vw;
              margin-top: 162%;
              margin-left: 2%;
              display: flex;
              justify-items: center;
              align-items: center;
              border-style: #ffd043 ridge 20px;
            }
            
            
            .box_kabinet_2_shpon_img3 {position: absolute;
              z-index: 12502;
              min-width: 20vw;
              min-height: auto  ;
              margin-top: 0%;
              margin-left: 16;
              padding: 1vw;
              margin-top: 162%;
              margin-left: 18%;
              display: flex;
              justify-items: center;
              align-items: center;
              
              
              border-style: #ffd043 ridge 20px;
              
            }
            
            
            .box_kabinet_2_shpon_img4 {position: absolute;
              z-index: 22505;
              min-width: 20vw;
              min-height: auto  ;
              
              
              padding: 1vw;
              margin-top: 162%;
        margin-left: 34%;
        display: flex;
        justify-items: center;
        align-items: center;
        
        
        border-style: #ffd043 ridge 20px;
        
      }
 /* КАБИНЕТ_2 ШПОН КАРТИНКИ КОНЕЦ */



 /* КАБИНЕТ_2 ШПОН ОПИСАНИЕ НАЧАЛО */
 .nazvanie_2_shpon {
  position: absolute;
  z-index: 22504;
  font-size: 1.5vw;
  min-height: auto  ;
  margin-top: 0%;
  margin-left: 0;
  padding: 1vw;
  margin-top: 133%;
  margin-left: 54%;
  margin-right: 1%;
  display: flex;
  color: white;
  background-color: #0000004d;
  
}
  
  .box_kabinet_2_shpon_opisanie_1 {position: absolute;
    z-index: 22504;
    font-size: 0.6vw;
    min-height: auto  ;
    margin-top: 137%;
    margin-left: 54%;
    margin-right: 1%;
    display: flex;
    & li {
      padding: 0.3vw;
      color: white;
      background-color: #00000063;
    }
  }
  ul {list-style-type: none;
  }
  
  .box_kabinet_2_shpon_opisanie_2 {position: absolute;
    z-index: 22504;
    font-size: 0.8vw;
    min-height: auto  ;
    
    padding: 1vw;
    margin-top: 140%;
    margin-left: 54%;
    margin-right: 1%;
    display: flex;
    color: white;
    background-color: #0000004d;
  }
  
  
  .box_kabinet_2_shpon_opisanie_3 {position: absolute;
    z-index: 22504;
    font-size: 0.8vw;
    min-height: auto  ; 
    padding: 1vw;
    margin-top: 149%;
    margin-left: 54%;
    margin-right: 1%;
    display: flex;
    color: white;
    background-color: #0000004d;
  }
  
  .box_kabinet_2_shpon_opisanie_4 {position: absolute;
    z-index: 22504;
    font-size: 0.8vw;
    min-height: auto  ;
    padding: 1vw;
    margin-top: 156%;
    margin-left: 54%;
    margin-right: 1%;
    display: flex;
    color: white;
    background-color: #0000004d}
/* КАБИНЕТ_2 ШПОН ОПИСАНИЕ Конец */

    
.shpon-2 {
  
  color: #fff;
  z-index: 3800;
  font-family: Georgia;
  -webkit-text-fill-color: transparent;
  
  color: w ;
  background: linear-gradient(20deg,  #ffcd3863,#ffffff,  #ffd75e57,#ffffff,  #ffd75ea1,  #ffd75e57,#ffffff );
  background-position: 0;
  -webkit-background-clip: text;
  -webkit-text-size-adjust: none;
  text-decoration: none;
  animation: shine2 8s infinite linear;
  animation-fill-mode: forwards;
  font-weight: 500;
  font-size: 3vw;
  background-color: #000000;
  
  
}

@keyframes shine2 {
  0% {
    background-position: 0vw;
    
  } 
  100% {
    background-position: 36vw;
    
  }
}

.sosos-2 {
  position: absolute;
  z-index: 15000;
  margin-top: 190%;
  margin-left: 31%;
  
}

.sosos-2_img1 {width: 5vw;
  margin-top: 188%;
  margin-left: 25%;
  position: absolute;
  z-index: 24000}
  
  .sosos-2_img2 {width: 5vw;
    margin-top: 188%;
    margin-left: 71%;
    position: absolute;
    z-index: 24000}
    
    .zatemnenie-2 {
      position: absolute;
      
      z-index: 3000;
      width: 98vw;
      height: 8vw;
      background-color: #00000082;
      margin-top: 185vw;
    }


    
    
    
    
    /* КАБИНЕТ_3 ШПОН КАРТИНКИ НАЧАЛО */
    
    
    .kabinet_3_shpon_img1 {
      
      min-width: 46vw;
      min-height: auto  ;
      max-width: 46vw;
      max-height: auto ;
      border-radius: 8%;
      filter: brightness(80%);
      
      &.kabinet_3_shpon_img1:hover {scale: 1.1;
        transition: 0.4s;
        cursor: pointer;}
    }
    
    
    
    .kabinet_3_shpon_img2 {
      min-width: 15vw;
      min-height: auto  ;
      max-width: 15vw;
      max-height: auto ;
      border-radius: 8%;
      &.kabinet_3_shpon_img2:hover {scale: 1.2;
        transition: 0.4s;
        cursor: pointer;}
      }
      
      .kabinet_3_shpon_img3 {
        min-width: 15vw;
        min-height: auto  ;
        max-width: 15vw;
        max-height: auto ;
        border-radius: 8%;
        &.kabinet_3_shpon_img3:hover {scale: 1.2;
          transition: 0.4s;
          cursor: pointer;}
        }
        
        .kabinet_3_shpon_img4 {
          min-width: 15vw;
          min-height: auto  ;
          max-width: 15vw;
          max-height: auto ;
          border-radius: 8%;
          &.kabinet_3_shpon_img4:hover {scale: 1.2;
            transition: 0.4s;
            cursor: pointer;}
          }
      
          .box_kabinet_3_shpon_img1 {position: absolute;
            z-index: 24500;
            min-width: 20vw;
            min-height: auto  ;
            
            padding: 1vw;
            margin-top: 200%;
            margin-left: 2%;
            display: flex;
            justify-items: center;
            align-items: center;
            border-style: #ffd043 ridge 20px;
            
            
          }
          
          .box_kabinet_3_shpon_img2 {position: absolute;
            z-index: 12501;
            min-width: 20vw;
            min-height: auto  ;
            padding: 1vw;
            margin-top: 232%;
            margin-left: 2%;
            display: flex;
            justify-items: center;
            align-items: center;
            border-style: #ffd043 ridge 20px;
          }
          
          
          .box_kabinet_3_shpon_img3 {position: absolute;
            z-index: 12502;
            min-width: 20vw;
            min-height: auto  ;
            margin-top: 0%;
            margin-left: 16;
            padding: 1vw;
            margin-top: 232%;
            margin-left: 18%;
            display: flex;
            justify-items: center;
            align-items: center;
            
            
            border-style: #ffd043 ridge 20px;
            
          }
          
          
          .box_kabinet_3_shpon_img4 {position: absolute;
            z-index: 22505;
            min-width: 20vw;
            min-height: auto;
            padding: 1vw;
            margin-top: 232%;
            margin-left: 34%;
            display: flex;
            justify-items: center;
            align-items: center;
            
            
            border-style: #ffd043 ridge 20px;
            
          }
          /* КАБИНЕТ_3 ШПОН КАРТИНКИ КОНЕЦ */
          
          
          
          /* КАБИНЕТ_3 ШПОН ОПИСАНИЕ НАЧАЛО */
          .nazvanie_3_shpon {
            position: absolute;
            z-index: 22504;
            font-size: 1.5vw;
            min-height: auto  ;
            padding: 1vw;
            margin-top: 203%;
            margin-left: 54%;
            display: flex;
            color: white;
            background-color: #0000004d;
            
          }
          
          .box_kabinet_3_shpon_opisanie_1 {position: absolute;
            z-index: 22504;
            font-size: 0.6vw;
            min-height: auto  ;                    
            margin-top: 207%;
            margin-left: 54%;
            margin-right: 1%;
            display: flex;
            & li {
              padding: 0.3vw;
              color: white;
              background-color: #00000063;
            }
          }
          ul {list-style-type: none;
          }
          
          .box_kabinet_3_shpon_opisanie_2 {position: absolute;
            z-index: 22504;
            font-size: 0.8vw;
            min-height: auto  ;
            
            padding: 1vw;
            margin-top: 212%;
            margin-left: 54%;
            margin-right: 1%;
            display: flex;
            color: white;
            background-color: #0000004d;
          }
          
          
          .box_kabinet_3_shpon_opisanie_3 {position: absolute;
            z-index: 22504;
            font-size: 0.8vw;
            min-height: auto  ;
            padding: 1vw;
            margin-top: 210%;
            margin-left: 54%;
            margin-right: 1%;
display: flex;
color: white;
background-color: #0000004d;
}

.box_kabinet_3_shpon_opisanie_4 {position: absolute;
  z-index: 22504;
  font-size: 0.8vw;
  min-height: auto  ;
  margin-top: 0%;
  margin-left: 0;
  padding: 1vw;
  margin-top: 220%;
  margin-left: 54%;
  margin-right: 1%;
  display: flex;
  color: white;
  background-color: #0000004d}
  
  .box_kabinet_3_shpon_opisanie_5 {position: absolute;
    z-index: 32504;
    font-size: 0.8vw;
    min-height: auto  ;
    padding: 1vw;
    margin-top: 227%;
    margin-left: 54%;
    margin-right: 1%;
    display: flex;
    color: white;
    background-color: #0000004d}
    /* КАБИНЕТ_3 ШПОН ОПИСАНИЕ Конец */
    
    
    .prodolzhenie {
      position: absolute;
      z-index: 20000;
      margin-top: 270%;
      padding-bottom: 40%;
      font-size: 2vw;
      color: #ffffff;
      left: 35%;
    }
    
    
    
    
    
    
    
    .centered {    
      position: absolute;
      z-index: 80000;
      margin-left: 82vw;
    }
    
    .group {
      width: 15vw;
      min-height: 5vw;
      overflow: hidden;
      position: absolute;
    }
    
    label {
      position: absolute;
      top: 0vw;
      color: rgb(255, 255, 255);
      font: 400 1vw  Roboto;
      cursor: text;
      transition: 0.25s ease;
    }
    
    input {
      display: block;
      width: 25vw;
      padding-top: 1vw;
      border: none;
      border-radius: 0;
      color: rgb(255, 255, 255);
      background: #ffffff46;
      font-size: 1vw;
      transition: 0.3s ease;
      
      
      
    }
    input:valid ~ label {
      top: 0;
      font: 700 0.5vw Roboto;
      color: rgb(255, 255, 255);
    }
    input:focus {
      outline: none;
    }
    input:focus ~ label {
      top: 0;
      font: 700 0.5vw Roboto;
      color: #ffffff;
    }
    input:focus ~ .bar:before {
      transform: translateX(0);
    }
    input:-webkit-autofill {
      -webkit-box-shadow: 0 0 0px 1000px #333 inset;
      -webkit-text-fill-color: white !important;
    }
    
    .bar {
      background:linear-gradient(to right,  #ffee6dab,#f90707 ,#fed40000);
      content: "";
      width: 550px;
      height: 0.3vw;
      transition: 0.3s ease;
      position: relative;
    }
    .bar:before {
      content: "";
      position: absolute;
      width: 100%;
      height: 150%;
      background: #fcd64db2;
      li
      transform: translateX(-100%);
    }
    
    ::selection {
      background: rgba(33, 150, 243, 0.3);
    }


    /* НЕ ТРОГАТЬ конец */
