<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>제주도 여행 일정표</title>
    <style>
        body{
            /*margin: 0; */
            /*padding: 0; */
        }
        ul, ol{
            /*list-style: none; */
            list-style-position: inside;
        }
        a img{
            width: 300px;
            height: 200px;
            border-radius: 10px;
            /*margin: 20px; */
            margin-bottom: 20px;
            /*padding: 10px; */
            /*padding-left: 30px; */
            transition: 0.5s;
            opacity: 0.9;
        }
        a img:hover{
            transform: scale(1.01);
            opacity: 1;
        }
        .map_img{
            margin-left: 50px;
            
        }
        h3{
            margin-left: 60px;
        }

    </style>
</head>
<body>
    <h3>선재의 2박3일 가족여행코스</h3>
    <div class="map_img"><img src="./img/map.jpg" alt="제주도 지도" width="300" height="300"></div>
    <!-- ul>li>ol>(li+a>[href="#"]img[src"./imges/img0$"][alt="img0$"])*3 -->

    <ul>
        <li>1일차 여행
            <ol type="A">
                <li>산방식당</li>
                <a href="#"><img src="./img/img01.jpg" alt="산방식당" width="300px" height="200px"></a>
                <li>성산일출봉</li>
                <a href="#"><img src="./img/img02.jpg" alt="성산일출봉" width="300px" height="200px"></a>
                <li>광치기 해변</li>
                <a href="#"><img src="./img/img03.jpg" alt="광치기해변" width="300px" height="200px"></a>
            </ol>
        </li>
        <li>2일차 여행
            <ol type="a" start="4">
                <li>흑돈가</li>
                <a href="#"><img src="./img/img04.jpg" alt="흑돈가" width="300px" height="200px"></a>
                <li>제주오름승마랜드</li>
                <a href="#"><img src="./img/img05.jpg" alt="제주오름승마랜드" width="300px" height="200px"></a>
                <li>춘심이네</li>
                <a href="#"><img src="./img/img06.jpg" alt="춘심이네" width="300px" height="200px"></a>
            </ol>
        </li><li>3일차 여행
            <ol type="i" start="7">
                <li>협재 해녀의 집</li>
                <a href="#"><img src="./img/img07.jpg" alt="협재 해녀의 집" width="300px" height="200px"></a>
                <li>한성오메기떡</li>
                <a href="#"><img src="./img/img08.jpg" alt="한성오메기떡" width="300px" height="200px"></a>
                <li>제주돌문화공원</li>
                <a href="#"><img src="./img/img09.jpg" alt="제주돌문화공원" width="300px" height="200px"></a>
            </ol>
        </li>
    </ul>
    <a href="#">시간표</a>
</body>
</html>
