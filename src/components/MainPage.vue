<template>
    <main class="main">
      <section class="bg-area">
        <h2>Chabit</h2>
        <h3>체중 관리를 위한 습관의 변화</h3>

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
    .bg-area{
      position:relative;
      width:100vw;
      height:748px;
      background-image: url("/src/assets/main/main_bg.jpg");
      background-size: 100%;
      background-repeat: no-repeat;
      background-position: center;
    }
    .bg-area h2{
      position:absolute;
      left:45px;
      bottom: 145px;
      color:#fff;
      font-size: 48px;
      font-weight: 700;
    }
    .bg-area h3{
      position:absolute;
      bottom: 85px;
      left:45px;
      color:#fff;
      font-size: 26px;
      font-weight: 600;
    }
    .intro{
      padding:178px 80px 168px;
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

  </style>
  