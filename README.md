# css Positions

## html-structure
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./css/index.css">
</head>
<body>
    <div class="parent">
        <div class="div1">item 1</div>
        <div class="div2">item 2</div>
        <div class="div3">ietm 3</div>
        <div class="div4">item 4</div>
    </div>
</body>
</html>

## css Structure

*{
    margin: 0;
    padding: 0;
}
.div1{
    width: 200px;
    height: 100px;
    background-color: rgb(207, 20, 27);
    position: static;
    top: 10px;
    bottom: 20px;

}
.div2{
    width: 200px;
    height: 100px;
    background-color: rgb(108, 138, 138);
    position: sticky;
    top: 0px;
    left: 230px;
    
}
.div4{
    width: 200px;
    height: 100px;
    background-color: rgb(22, 181, 33);
    position: relative;
    
    top: 10px;
    
}
.div3{
    width: 200px;
    height: 100px;
    background-color: aqua;
    position: absolute;
    top: 0px;
    
}
.parent{
    width: 100vw;
    height: 2000px;
    background-color: blueviolet;
}