# ch03_HTMl
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!--css적용방법 1파일로 적용-->
    <link rel="stylesheet" href="style.css">
    <!--css적용방법 2 style 태그로 적용-->
    <style>
        body{ background-color:rgb(57, 99, 99);}
    </style>
</head>
<body>
    <h3>미래융합교육원</h3>
    <hr>
    <p>2023.12.29 open</p>
    <!--css 적용방법 3 태그에 style 속성에 정의-->
    <P style="color: yellow; font-size: 20px">위치:202호</P>
    <p>전화번호:042-488-9222</p>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h3,li{color:brown;} /*xorm tpffprxj*/
        div>div>strong{background-color:yellow;}/* ><-- 자식 셀렉터*/
        ul strong{color:dodgerblue;}/* 띄워쓰기 자손 셀렉터*/
        .warning{color:red;}/*class 셀렉터*/
        body.main{background-color:aliceblue ;}/*태그+class명 셀렉터*/
        #list{background-color: mistyrose;}/*id 셀렉터*/
        /*hover 마우스 올렸을때(가장 클래스 셀렉터)*/
        li:hover{background-color: yellowgreen;}
    </style>
</head>
<body>
    <h3>Web prigramming</h3>
    <hr>
    <div>
        2일차<strong>학습내용 </strong>입니다
        <ul id="list">
            <li><span>HTML5</span></li>
            <LI><strong>CSS3</strong></LI>
            <li>Javascript</li>
        </ul>
        <div class="warning">60점 이하는 F</div>
    </div>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>블록,인라인,인라인블록</title>
    <style>
        div{border: 2px solid yellowgreen;color:blue;background-color: aliceblue;}
        span{border:3px dotted red; background-color: yellow;}
    </style>
</head>
<body>
    <h3>인라인은 height가 안됨</h3>
    <hr>
    이 엘리먼트는<div style="display:none;">div(none)</div>입니다<br>
    이 엘리먼트는<div style="display:inline;height:200px;">div(inline)</div>입니다<br>
    이 엘리먼트는<div style="display:inline-block;height:200px ;">div(inline-block)</div>입니다<br>
    이 엘리먼트는<div> div<span style="display:block">(block)</span></div>입니다

    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width>, initial-scale=1.0">
    <title>상대배치,relative</title>
    <style>div{display:inline-block;height:50px;width:50px;
            border:1px solid lightgrey;text-align:center;
            color: white;background-color: red;}
            #down:hover{position: relative;left:20px;top:20px;background-color: green;}
            #down:active{background-color: black;}
            #up:hover{position: relative;right:20px;bottom:20px;background-color: green;}

    </style>
</head>
<body>
    <h3>relative</h3>
    <hr>
    <div>T</div>
    <div id="down"><h></div>   
    <div>a></div>    
    <div>n</div>   
    <div id="up">k</div>    
    <div>s</div>    

    
</body>
</html>
