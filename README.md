
<!-- saved from url=(0174)file:///C:/Users/%E5%8D%8E%E7%A1%95/Documents/WeChat%20Files/wxid_53yqlv72nhri22/FileStorage/File/2021-08/%E6%96%B0%E5%BB%BA%E6%96%87%E6%9C%AC%E6%96%87%E6%A1%A3%20(2)(1).html -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"></head><body>


    <div class="box-a">


        <span id="in-front">

              <img src="./img/微信图片_20210811170039.jpg" class="in-img">  

            </span>

        <span id="in-back">

               <img src="./img/微信图片_20210811170048.jpg" class="in-img">

            </span>

        <span id="in-left">

                <img src="./img/微信图片_20210811170056.jpg" class="in-img">

            </span>

        <span id="in-right">

                <img src="./img/微信图片_20210811170104.jpg" class="in-img">

            </span>

        <span id="in-top">

                <img src="./img/微信图片_20210811154313.jpg" class="in-img">

            </span>

        <span id="in-bottom">

                 <img src="./img/微信图片_20210811170024.jpg" class="in-img">

            </span>


        <div class="out-front">

            <img src="./img/微信图片_20210811170024.jpg" class="out-img">

        </div>

        <div class="out-back">

            <img src="./img/微信图片_20210811170039.jpg" class="out-img">

        </div>

        <div class="out-left">

            <img src="./img/微信图片_20210811170048.jpg" class="out-img">

        </div>

        <div class="out-right">

            <img src="./img/微信图片_20210811170056.jpg" class="out-img">

        </div>

        <div class="out-top">

            <img src="./img/微信图片_20210811170104.jpg" class="out-img">

        </div>

        <div class="out-bottom">

            <img src="./img/微信图片_20210811154313.jpg" class="out-img">

        </div>

    </div>






<style type="text/css">

    * {


        padding: 0;

        margin: 0;

    }

    

    body {


        width: 100%;

        height: 100%;

        background-image: url(./image/bg2.gif);

    }

    

    .box-a span {

        display: block;


        position: absolute;


        width: 100px;

        height: 100px;

        top: 50px;

        left: 50px;

    }

    

    .box-a div {

        position: absolute;

        transition: all .4s;


    }

    

    .box-a {

        width: 200px;

        height: 200px;

        margin: 200px auto;

        animation: rotate 20s infinite;


        transform-style: preserve-3d;


        animation-timing-function: linear;

    }

    

    div .in-img {

        width: 100px;

        height: 100px;

    }

    

    div .out-img {

        width: 200px;

        height: 200px;

    }

    

    @keyframes rotate {

        from {

            transform: rotateX(0deg) rotateY(0deg);

        }

        to {

            transform: rotateX(360deg) rotateY(360deg);

        }

    }


    

    #in-front {

        transform: translateZ(50px);

    }

    

    #in-back {

        transform: translateZ(-50px);

    }

    

    #in-left {

        transform: rotateY(90deg) translateZ(50px);

    }

    

    #in-right {

        transform: rotateY(-90deg) translateZ(50px);

    }

    

    #in-top {

        transform: rotateX(90deg) translateZ(50px);

    }

    

    #in-bottom {

        transform: rotateX(-90deg) translateZ(50px);

    }


    

    .out-front {

        transform: translateZ(100px);

    }

    

    .out-back {

        transform: translateZ(-100px);

    }

    

    .out-left {

        transform: rotateY(90deg) translateZ(100px);

    }

    

    .out-right {

        transform: rotateY(-90deg) translateZ(100px);

    }

    

    .out-top {

        transform: rotateX(90deg) translateZ(100px);

    }

    

    .out-bottom {

        transform: rotateX(-90deg) translateZ(100px);

    }


    

    .box-a:hover .out-front {

        transform: translateZ(200px);

    }

    

    .box-a:hover .out-back {

        transform: translateZ(-200px);

    }

    

    .box-a:hover .out-left {

        transform: rotateY(90deg) translateZ(200px);

    }

    

    .box-a:hover .out-right {

        transform: rotateY(-90deg) translateZ(200px);

    }

    

    .box-a:hover .out-top {

        transform: rotateX(90deg) translateZ(200px);

    }

    

    .box-a:hover .out-bottom {

        transform: rotateX(-90deg) translateZ(200px);

    }

</style></body></html>
