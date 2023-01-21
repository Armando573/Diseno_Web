**********HTML**********
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animaciones</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
    <header>
        <nav>
            <p>Logo</p>
            <ul>
                <li>inicio</li>
               <a href="#section1"> <li>animacion_1</li> </a>
               <a href="#section2"> <li>animacion_2</li> </a>
               <a href="#section3"> <li>animacion_3</li> </a>
               <a href="#section4"> <li>animacion_4</li> </a>
               <a href="#section5"> <li>animacion_5</li> </a>
            </ul>
        </nav>
        <h1>EFECTOS Y ANIMACIONES</h1>
    </header>
    <main>
        <section class="animacion_1" id="section1">
            <h2>ANIMACION1 ROTAR</h2> 
            <img class="img1" src="C:\Users\PILARES2\Desktop\Animaciones\img\planeta.jfif" alt = "astro">;
        </section>

        <section class="animacion_2" id="section2">
            <h2>ANIMACION2</h2> 
           <p class="animacion"> ARMANDO RIVERA</p>
        </section>

        <section class="animacion_3" id="section3">
            <h2>ANIMACION3</h2> 
        </section>

        <section class="animacion_4" id="section4">
            <h2 class="olivetti">ANIMACION_4 OLIVETTI</h2> 
        </section>

        <section class="animacion_5" id="section5">
            <h2>ANIMACION5</h2> 
            <img class="img2" src="C:\Users\PILARES2\Desktop\Animaciones\img\planeta_2.jfif" alt = "astro">;
        </section>

    </main>
</body>
</html>



**********CSS**********
*{
    margin: 0;
    padding: 0;
}


section{
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

::-webkit-scrollbar-thumb{
    background-color: beige;
    border-radius: 10px;
}

::-webkit-scrollbar-track{
    border-radius: 10px;
    background-color: rgb(247, 136, 0);
    width: 10px;
}

::-webkit-scrollbar{
    width: 10px;
}

header{
    height: 100vh;
    background: url(https://www.xtrafondos.com/wallpapers/planetas-en-el-espacio-3897.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

nav{
    display: flex;
    justify-content: space-around;
}

ul{
    display: flex;
}

li{
    list-style: none;
    margin-right: 20px;
    background-color: rgb(99, 243, 195);
    border-radius: 10px;
    padding: 20px;
    color: black;
}

li:hover{
    background-color: aquamarine;
    color: blueviolet;
}


.animacion_1{
    background-color: rgb(169, 137, 243);
}
.animacion_1 img{
    width: 30%;

}
.img1:hover{
    border-radius: 50%;
    box-shadow: 0 0 15px 15px yellow;
    transform: rotate(360deg);
    transition: all .5s ease-in-out;
}


.animacion_2{
    background-color: brown;
  

}

@keyframes MOVIMIENTO_LATERAL {from{left:-500px} to{left:500px}}

.animacion {
    animation-name: MOVIMIENTO_LATERAL;
    animation-duration: 5s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
    width: 200px;
    background-color: rgb(45, 212, 142);
    padding: 2px;
    position: relative;
    color: rgb(17, 1, 4);
    
}


.animacion_3{
    background-color: chocolate;
} 

@keyframes fadeIn{
    to
    {transform: translateX(0px);
     opacity: 1;
    }            }

.animacion_3{
    opacity: 0;
    transform: translateX(1500px);
    animation: fadeIn 2s linear forwards;
}


.animacion_4{
    background-color: darkcyan;
}
@keyframes olivetti{
    from{
        width: 0;
        }          }

        @keyframes pampaguya{
             50% {
                border-color: transparent;
            }
        }
.olivetti{
    font-size: 2rem;
    font-family: monospace;
    color: white;
    width: 30%;
    animation: olivetti 5s steps(30), pampaguya 0.5s step-end infinite alternate;
    white-space: nowrap;
    overflow: hidden;
    border-right: 2px solid white;

}

.animacion_5{
    background-color: lightpink;
   
}

.img2{
    width: 30%;
    max-height: 40vh;
    -webkit-box-reflect:
     below -1px
     linear-gradient(to bottom, transparent,
     rgba(0, 0, 0, 0.8));
}





**********IMAGENES**********
![image](https://user-images.githubusercontent.com/61428623/212503572-2748b592-6c55-4ff4-b3a7-d2fd1a291600.png)
![image](https://user-images.githubusercontent.com/61428623/212503577-3ee9f369-c606-4c6c-91eb-c15fb2bf1001.png)
![image](https://user-images.githubusercontent.com/61428623/212503580-e69aa66c-5a75-49eb-81bb-fe13147d943e.png)
![image](https://user-images.githubusercontent.com/61428623/212503584-5fe99e68-31c6-427b-b668-fd61b4c79433.png)
![image](https://user-images.githubusercontent.com/61428623/212503586-fca39878-2d3b-40d3-9214-9ceb64468400.png)
![image](https://user-images.githubusercontent.com/61428623/212503592-7511ce23-5ea5-4426-a839-db7366604280.png)





**********ZIP**********


[Animaciones.zip](https://github.com/Armando573/Diseno_Web/files/10473137/Animaciones.zip)

