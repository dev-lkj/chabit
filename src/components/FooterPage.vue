<template>
    <footer class="footer">
     <h2>Our Service</h2>
     <ul class="family-site">
        <li>
            <h3>차빗 스토어</h3>
            <p>
                <a href="https://smartstore.naver.com/dotorijambo" title="차빗스토어">구경하기</a>
            </p>
        </li>
        <li>
            <h3>차빗 블로그</h3>
            <p>
                <a href="https://blog.naver.com/PostList.naver?blogId=dotorifamily_com" title="차빗 블로그">구경하기</a>
            </p>
        </li>
        <li>
            <h3>차빗 APP</h3>
            <p>
                <a href="#" title="차빗 APP">구경하기</a>
            </p>
        </li>
     </ul>

     <div class="line"></div>
     <div class="contact">
        <p class="contactus">Contact us.</p>
        <p class="email"><span>E-mail</span> dotorifamily2023@gmail.com</p>
     </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'FooterPage',
    props: {
    //   msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
    .footer{
        width: calc(100% - 84px- 84px);
        padding:88px 84px 69px;
        /* height:748px; */
        background-color: #01504E;
    }

    h2{
        color:#fff;
        font-weight: 700;
        font-size:26px;
    }
    .family-site {
        margin-top:55px;
        display:flex;
        overflow: scroll;
        
    }
    .family-site li{
        width:350px;
        height:132px;
        background-color: #fff;
        border-radius: 8px;
        padding:59px 0;
        margin-right:37px;
    }
   

    .family-site li h3{
        text-align: center;
        font-weight: 600;
        font-size:20px;
    }

    .family-site li p{
        margin-top:55px;
        text-align: center;
    }

    .family-site li p a{
        display:inline-block;
        width:142px;
        height:42px;
        line-height:42px;
        text-decoration: none;
        color:#000;
        background-color: #fff;
        border:1px solid #000;
        border-radius: 30px;
        font-weight: 600;
        font-size:14px;
    }
    .family-site li p a:hover {
        background-color: #01504E;
        color: #fff;
    }
    .line{
        margin-top:121px;
        width:100%;
        height:2px;
        background-color: #fff;
    }

    .contact {
        margin-top:59px;
    }
    .contactus{
        color:#fff;
        font-size:20px;
        font-weight:600;
    }
    .email{
        margin-top:35px;
        color:#fff;
    }
    .email span{
        font-size: 20px;
        font-weight: 600;
    }
     /* 노트북 & 테블릿 가로 (해상도 1024px ~ 1279px)*/ 
     @media all and (min-width:1024px) and (max-width:1279px) { 
       
      } 

      /* 테블릿 가로 (해상도 768px ~ 1023px)*/ 
      @media all and (min-width:768px) and (max-width:1023px) { 
      
      } 

      /* 모바일 가로 & 테블릿 세로 (해상도 480px ~ 767px)*/ 
      @media all and (min-width:480px) and (max-width:767px) {
      
      } 

      /* 모바일 세로 (해상도 ~ 479px)*/ 
      @media all and (max-width:479px) {
       footer {
        padding: 100px;
       }
      }

  </style>
  