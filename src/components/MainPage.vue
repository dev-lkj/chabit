<template>
    <main class="main">
      <section class="bg-area">
        <div class="main-titles">
          <h2>Chabit</h2>
          <h3>체중 관리를 위한 습관의 변화</h3>
        </div>
      </section>
      <section class="intro">
        <h2 class="title">누구나 바뀔 수 있습니다.</h2>
        <div class="desc-area">
          <p class="desc1">
            차빗은 ‘Change of Habit’의 약자로 건강한 생활 습관의 변화를 통해 체중 관리 및 건강 유지를 쉽고 즐겁게 할 수 있도록 사용자별 맞춤 서비스를 제공하기 위해 끊임없이 연구하고 있습니다.
          </p>
          <p class="desc2">
            차빗만의 기술력과 전문적인 컨텐츠를 통해 많은 사람들이 가장 효과적인 체중 관리를 통해 
            건강을 유지할 수 있도록 도움을 받을 수 있는 DTx(디지털 치료기기)를 만들어 나갈 수 있도록 노력하겠습니다.
          </p>
        </div>
      </section>
    </main>
  </template>
  
  <script>
  export default {
    name: 'MainPage',
    props: {
    //   msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
    .box {
      width: 100%;
      height: 200px;
      background-color: #E48942;
      display: none;
    }
    .bg-area{
      padding: 0;
      margin: 0;
      position:relative;
      width:100%;
      height: 70vh;
      background-image: url("/src/assets/main/main_bg.jpg");
      background-size: 100%;
      background-repeat: no-repeat;
      background-position: top;
    }
    .bg-area .main-titles {
      position: absolute;
      bottom: 45px;
      margin-left: 45px;
    }
    .bg-area h2{
      /* position:absolute; */
      /* left:45px; */
      /* bottom: 145px; */
      /* bottom: 10%; */
      color:#fff;
      font-size: 4vw;
      font-weight: 700;
    }
    .bg-area h3{
      margin-top: 24px;
      /* position:absolute; */
      /* bottom: 85px; */
      /* left:45px; */
      color:#fff;
      font-size: 2vw;
      font-weight: 600;
    }
    .intro{
      padding:178px 45px 168px;
    }
    .intro .title{
      font-size:30px;
    }
    
    .intro .desc1{
      margin-top: 79px;
      font-size:19px;
    }
    .intro .desc2{
      margin-top:30px;
      font-size:19px;
    }
    /* 노트북 & 테블릿 가로 (해상도 1024px ~ 1279px)*/ 
      @media all and (min-width:1024px) and (max-width:1279px) { 
        .bg-area{
          height: 50vh;
        }
      } 

      /* 테블릿 가로 (해상도 768px ~ 1023px)*/ 
      @media all and (min-width:768px) and (max-width:1023px) { 
        .bg-area{
          height: 30vh;
        }
      } 

      /* 모바일 가로 & 테블릿 세로 (해상도 480px ~ 767px)*/ 
      @media all and (min-width:480px) and (max-width:767px) {
        .bg-area{
          height: 20vh;
        }
      } 

      /* 모바일 세로 (해상도 ~ 479px)*/ 
      @media all and (max-width:479px) {
        .bg-area{
          height: 20vh;
        }
        .bg-area .main-titles h2 {
          color: #fff;
          font-size: 10vw;
        }
        .bg-area .main-titles h3 {
          color: #fff;
          font-size: 5vw;
        }
        .intro{
          padding:50px 45px 76px;
        }
        .intro .desc1 {
          margin-top: 36px;
        }
      }
  </style>
  