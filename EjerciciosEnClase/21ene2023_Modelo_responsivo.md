*****HTML*****
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diseño Responsivo</title>
    <link rel="stylesheet" href="css/estilos.css">
    
</head>
<header>
    <h1>Diseño Responsive</h1>
</header>
<main>
    <div> <img src="C:\Users\PILARES2\Desktop\Diseño Responsivo\img\computadora.jpg" alt="">
    <h2>MAS DE 1024px</h2>
    </div>
    <div> 
        <img src="C:\Users\PILARES2\Desktop\Diseño Responsivo\img\tableta.jpg" alt="">
        <h2>1023px A 768px </h2>
    </div>
    <div> 
        <img src="C:\Users\PILARES2\Desktop\Diseño Responsivo\img\celular.jfif" alt="">
        <h2>767px A 320px</h2>
    </div>

</main>
<footer>
    <img src="C:\Users\PILARES2\Desktop\Diseño Responsivo\img\computadora.jpg" class="img1" alt="">
    <img src="C:\Users\PILARES2\Desktop\Diseño Responsivo\img\celular_color.jfif" class="img2" alt="">

</footer>
<body>
    
</body>
</html>

*****CSS*****
*{
    margin: 0;
    padding: 0;
}

header{
    width: 90%;
    margin: auto;
    height: 30vh;
    background-color: gray;
    display: flex;
    justify-content: center;
    align-items: center;
}

h1{
    color: gray;
    -webkit-text-stroke: 2px black;
    font-size: 3em;
    letter-spacing: 3px;
    text-shadow: 0px 0px 5px yellow;
}

main{
    height: 60vh;
    justify-content: space-around;
    display: flex;
    align-items: center;
}

div{
    background-color: gray;
    border-radius: 20px;
    width: 30%;
    height: 25vh;
    text-align: center;
    transition: height 1s;
}

div:hover{
    height: 20em;
}

img{
    width: 100%;
    margin-top: -80px;
    height: 400px;
}

footer .img1{
    width: 10%;
    display: block;
}

footer .img2{
    width: 10%;
    display: none;
}

/* DISEÑO PARA CELULAR - DISEÑO RESPONSIVO */

@media(max-width: 767px){
    body{
        background: url(https://images.pexels.com/photos/1519088/pexels-photo-1519088.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1);
    }
    header{
        width: 100%;
        height: 20vh;
        background-color: rgba(255, 192, 203, 0.568);
    }

    h1{
        font-size: 2em;
        letter-spacing: 10px;
    }

    main{
        flex-direction: column;
        height: 150vh;
    }

    footer .img1{
        width: 10%;
        display: none;
    }
    
    footer .img2{
        width: 10%;
        height: 30%;
        display: block;
    }





}

*****Imagenes*****
![image](https://user-images.githubusercontent.com/61428623/213890499-73c6018c-7136-4e43-8d44-6b3dafb256a7.png)
![image](https://user-images.githubusercontent.com/61428623/213890500-2c7a84f4-0649-4ef8-9496-a3ed9513daa8.png)


![image](https://user-images.githubusercontent.com/61428623/213890482-2e17bb55-59b4-4be2-b79a-f7b559b356f6.png)
![image](https://user-images.githubusercontent.com/61428623/213890485-213d4465-5cf8-4232-bd69-56274248d29f.png)



*****ZIP*****

[Diseño Responsivo.zip](https://github.com/Armando573/Diseno_Web/files/10473284/Diseno.Responsivo.zip)



