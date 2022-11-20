<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
<h1> Venta de Tacos</h1>
<h2>Menú</h2>
<h3>Tacos</h3>
<ul>
    <li>Bisteck................$15</li>
    <li>Pastor..................$15</li>
    <li>Longaniza...........$15</li>
    <li>Cecina.................$15</li>
    <li>Tripa...................$15</li>
</ul>

<dl>
    <dt>Campechano.........$25</dt>
    <dd>Longaniza, bistek. Queso</dd>

    <dt>Especial.................$35</dt>
    <dd>Bisteck. Queso, Nopales, Papas</dd>

    <dt>Volcan...................$50</dt>
    <dd>Bisteck, Queso, Pastor, Cebolla, Tripa, Longaniza
    </dd>
</dl>

<h2> Realiza Tu Pedido</h2>

<form action="" method="">

    <!, Se crea el campo para ingresat eñ texto y con el "Place holder, se l muestra un ejemplo de como debe escribirlo" «––>
    <!, "required" indica que el campo es obligatorio «––>
    Nombre: <input type="text" placeholder="Ejemplo: Juan Perez" maxlength="30" minlength="3" required>  <br>
    Telefono: <input type="tel"  minlength = "10" maxlength  = "10" placeholder = "Ejemplo: 1234567890" value="52"> <br>
    E-mail: <input type="text" placeholder="Ejemplo: usuario@dominio.com" maxlength="30" minlength="3" required>  <br>

    <pre>
        ¿Es para recoger en el local o entrega a domicilio?
        <input type="radio" value = "Llevar" name="Llevar" id="" > Entrega a Domicilio
        <input type="radio" value = "Local" name="Llevar" id="" > Entrega en el local
    </pre>

    <pre>
        Ingresa tu direccion
        <textarea name="direccion" id="" cols="30" rows="10" placeholder="Calle, Numero, Colonia, Delegacion, C.P."></textarea> <br>
        Para cuando es tu orden?
        <input type="date" name="" id="" min="2022-11-19">

    </pre>

     Elije tus Tacos <br>
     <select name="orden1" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     Elije tus Tacos <br>
     <select name="orden2" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     Elije tus Tacos <br>
     <select name="orden3" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     Elije tus Tacos <br>
     <select name="orden4" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     Elije tus Tacos <br>
     <select name="orden5" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     Elije tus Tacos <br>
     <select name="orden6" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     Elije tus Tacos <br>
     <select name="orden7" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     Elije tus Tacos <br>
     <select name="orden8" id="">
        <option value="Selecciona">Selecciona tus tacos</option>
        <option value="Bisteck">Bisteck</option>
        <option value="Pastor">Pastor</option>
        <option value="Longaniza">Longaniza</option>
        <option value="Cecina">Cecina</option>
        <option value="Tripa">Tripa</option>
        <option value="Campechano">Campechano</option>
        <option value="Especial">Especial</option>
        <option value="Volcan">Volcan</option>
     </select> 
     ¿Cuantos quieres? 
     <input type="number" name="" id="" min="1" max="100"> <br> <br>

     *****Extras***** <br>
     <input type="checkbox" name="" id=""> Salsa Verde 
     <input type="checkbox" name="" id=""> Salsa Roja <br>
     <input type="checkbox" name="" id=""> Limones 
     <input type="checkbox" name="" id=""> Cebolla <br>
     <input type="checkbox" name="" id=""> Papas 
     <input type="checkbox" name="" id=""> Extra Queso <br> <br>

<input type="submit" value="Enviar Pedido"> <input type="reset" value="Limpiar Orden"> <br> <br>

Escoge un color <br>
<input type="color" name="" id="" > <br>
password <br>
<input type="password" name="" id=""> <br>
Archivo <br>
<input type="file" name="" id=""> <br>
</form>


    
</body>
</html>
