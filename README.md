# github.io
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DisasterAlert+</title>
    <style>
        
        body {  
            background-color: #fdfaea;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0; /* 웹 페이지 전체 크기를 모바일 화면에 맞게 변경 */
        }

        h1 {
            color: #4CAF50;
            
        }

        p {
            color: #333;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px; /* 전체 컨텐츠의 패딩을 추가 */
        }

        .header {
            background-color: #fdfaea;
            padding: 10px;
            text-align: center;
        }

        .navigation {
            display: flex;
            justify-content: center;
            background-color: #4CAF50;
            padding: 10px;
        }

        .navigation a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }

        .content {
            padding: 20px;
        }

        .footer {
            text-align: center;
            padding: 10px;
            background-color: #fdfaea;
        }

        #map {
            width: 100%;
            height: 300px; /* 지도의 높이를 300px로 지정 */
        }
        @media (max-width: 768px) {
            /* 768px 이하의 화면 크기에 대한 스타일 지정 */
            .container {
                padding: 10px; /* 작은 화면에서 패딩을 줄여 화면을 꽉 차게 표시 */
            }
        }

        /* 랜덤 배너 */
        * {
            box-sizing: border-box;
        }

        .mySlides {
            display: none;
        }

        img {
            vertical-align: middle;
        }

        /* Slideshow container */
        .slideshow-container {
            max-width: 600px;
            position: relative;
            margin: auto;
        }

        /* Number text (1/3 etc) */
        .numbertext {
            color: #f2f2f2;
            font-size: 10px;
            padding: 6px 10px;
            position: absolute;
            top: 0;
        }

        /* Fading animation */
        .fade {
            -webkit-animation-name: fade;
            -webkit-animation-duration: 1.5s;
            animation-name: fade;
            animation-duration: 1.5s;
        }


    /* The dots/bullets/indicators */
    .dot {
      height: 10px;
      width: 10px;
      margin: 0 2px;
      background-color: #bbb;
      border-radius: 50%;
      display: inline-block;
      transition: background-color 0.6s ease;
    }

    .active {
      background-color: #717171;
    }

        @-webkit-keyframes fade {
            from {
              opacity: .4
            }
      
            to {
              opacity: 1
            }
        }
      
        @keyframes fade {
            from {
              opacity: .4
            }
      
            to {
              opacity: 1
            }
        }
      
        /* On smaller screens, decrease text size */
        @media only screen and (max-width: 300px) {
            .text {
              font-size: 10px
            }
        }

        
    </style>
</head>
<body topmargin="0" bottommargin="0" leftmargin="0" rightmargin="0">
    <div class="container">
        <div class="header">
            <h1>DisasterAlert+</h1>
        </div>
        <div class="navigation">
            <a href="file:///C:/Users/AIONE/Desktop/%EB%AF%B8%EB%9E%98%EC%A7%80%EA%B8%B0.html">홈</a>
            <a href="https://ysw1mst.github.io/Smartcity/">지진</a>
            <a href="#">태풍</a>
             <a href="floodweb.html">홍수</a>
            <a href="#">재난현황</a>
            <a href="https://www.safekorea.go.kr/idsiSFK/neo/sfk/cs/ppn/emg/SDIJKM5602.html?menuSeq=596">비상연락망</a>

         
        </div>
        <section>
            <section>
                <h3 id="chapter1">현재 재난상황</h3>
                <p>서울에서 !@!#@!# 발생</p>
                <p>대전에서 !@!#@!# 발생</p>
                <p>대구에서 !@!#@!# 발생</p>
                <p>부산에서 !@!#@!# 발생</p>
            </section>
           
   <aside style="display: flex;">
            <div style="flex: 1;">
                <h3 id="chapter1">대한민국 지도</h3>
                <div class="map-section">
                    <a href="https://floodmap.go.kr/fldara/fldaraList.do"target="_blank">
                     <img src="./korea.jpg" alt="대한민국" style="width:100%"/>
                    </a>
                </div>
            </div>

<!-- 랜덤 배너 -->
            <div style="flex: 1;">
                <div class="slideshow-container">
                    <div class="mySlides fade">
                        <div class="numbertext">1 / 4</div>
                        <img src="./사진1.png" alt="사진 1" style="width:100%"/>
                    </div>
                    <div class="mySlides fade">
                        <div class="numbertext">2 / 4</div>
                        <img src="./사진2.png" alt="사진 2" style="width:100%"/>
                    </div>
                    <div class="mySlides fade">
                        <div class="numbertext">3 / 4</div>
                        <img src="./사진3.png" alt="사진 3" style="width:100%"/>
                    </div>
                    <div class="mySlides fade">
                        <div class="numbertext">4 / 4</div>
                        <img src="./사진4.png" alt="사진 4" style="width:100%"/>
                    </div>
                </div>
                  <div style="text-align:center">
                    <span class="dot"></span>
                    <span class="dot"></span>
                    <span class="dot"></span>
                    <span class="dot"></span>
                  </div>
            </div>
        </aside>
        </section>
 
        <div class="content">
            <h2>환영합니다!</h2>
            <p>이곳은 간단한 홈페이지의 예시입니다. 원하는 내용으로 커스터마이즈하여 사용하시면 됩니다.</p>
            <p>추가적인 내용이 필요하다면 이곳에 작성해주세요.</p>
        </div>
        <div class="footer">
            <p>&copy; 2023. MIRAEJIGI. All rights reserved.</p>
        </div>
    </div>

  <script>
        /* 랜덤 배너 */
        var slideIndex = 0;
        showSlides();

        function showSlides() {
            var i;
            var slides = document.getElementsByClassName("mySlides");
            var dots = document.getElementsByClassName("dot");
            for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
            }
            slideIndex++;
            if (slideIndex > slides.length) { slideIndex = 1 }
            for (i = 0; i < dots.length; i++) {
                   dots[i].className = dots[i].className.replace(" active", "");
                 }
            slides[slideIndex - 1].style.display = "block";
            dots[slideIndex - 1].className += " active";
            setTimeout(showSlides, 2000); // Change image every 2 seconds
        }
    </script>
</body>
</html>
