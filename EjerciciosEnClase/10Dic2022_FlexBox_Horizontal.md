*****HTML*****

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
    <h1>Cajas Flexibles</h1>
    <h2>Space between</h2>
    <div class="caja">

        <div class="cajita">between</div>
        <div class="cajita">between</div>
        <div class="cajita">between</div>

    </div>



    <h2>Space around</h2>
    <div class="caja2">

        <div class="cajita2">around</div>
        <div class="cajita2">around</div>
        <div class="cajita2">around</div>

    </div>



    <h2>space evenly</h2>
    <div class="caja3">

        <div class="cajita3">evenly</div>
        <div class="cajita3">evenly</div>
        <div class="cajita3">evenly</div>

    </div>


</body>
</html>


*****CSS******

*{
padding: 0;
margin: 0;
}

.caja{
    display: flex;
    justify-content: space-between;
}

.cajita{
    background-color: cornflowerblue;
    width: 10%;
    height: 10vh;
}

.caja2{
    display: flex;
    justify-content: space-around;
}
.cajita2{
    background-color:aquamarine;
    width: 10%;
    height: 10vh;
}

.caja3{
    display: flex;
    justify-content: space-evenly;
}
.cajita3{
    background-color: brown;
    width: 10%;
    height: 10vh;
}


![image](https://user-images.githubusercontent.com/61428623/206877384-ce829b0f-88b8-49ef-a9ce-b59e0a42ec7a.png)

[FlexBox_Horizontal.zip](https://github.com/Armando573/Diseno_Web/files/10201043/FlexBox_Horizontal.zip)

