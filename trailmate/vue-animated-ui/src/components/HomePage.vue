<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>TrailMate</title>
    <style>
        body{
            background-color: #212530;
            color: white;
            text-align: center;
        
        }
        .buton1{
            background-color:   #219653;;
            width: 500px;
            height: 150px;
            position: relative;
            margin: auto;
            margin-top: 100px;
            border-radius: 25px;
        }
        .buton2{
            background-color:   #219653;;
            width: 240px;
            height: 120px;
            position: relative;
            margin: auto;
            right: 130px;
            margin-top: 50px;
            border-radius: 25px;
        }
        .buton3{
            background-color:   #219653;;
            width: 240px;
            height: 120px;
            position: relative;
            margin: auto;
            left: 130px;
            margin-top: -140px;
            border-radius: 25px;
        }
        .buton4{
            background-color:   #219653;;
            width: 500px;
            height: 150px;
            position: relative;
            margin: auto;
            margin-top: 60px;
            border-radius: 25px;
        }
    </style>
</head>
<body>

<div class="screen">
    
   <div class="header">
        <h5>TrailMate</h5>
   </div>

    <div class="buton1" onclick="myF()">
        <h5>Buton 1</h5>
    </div>

    <div class="buton2" onclick="myF()">
        <h5>Buton 2</h5>
    </div>

    <div class="buton3" onclick="myF()">
        <h5>Buton 3</h5>
    </div>

    <div class="buton4" onclick="myF()">
        <h5>Buton 4</h5>
    </div>

</div>
<script type="application/javascript">
    function myF(item) {
    alert(item);
}
</script>
</body>
</html>