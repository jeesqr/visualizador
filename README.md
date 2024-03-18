<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="./css/estilo.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="./js/funciones.js"></script>
</head>

<body onload="iniciar()">

    <table id="Tablero">

        <tr>
            <td class="primera-celda"></td>
            <td>a</td>
            <td>b</td>
            <td>c</td>
            <td>d</td>
            <td>e</td>
            <td>f</td>
            <td>g</td>
            <td>h</td>
            <td></td>
        </tr>

        <tr>
            <td>8</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>8</td>
        </tr>

        <tr>
            <td>7</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>7</td>
        </tr>

        <tr>
            <td>6</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>6</td>
        </tr>

        <tr>
            <td>5</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>5</td>
        </tr>

        <tr>
            <td>4</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>4</td>
        </tr>

        <tr>
            <td>3</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>3</td>
        </tr>

        <tr>
            <td>2</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>2</td>
        </tr>

        <tr>
            <td>1</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td>1</td>
        </tr>

        <tr>
            <td></td>
            <td>a</td>
            <td>b</td>
            <td>c</td>
            <td>d</td>
            <td>e</td>
            <td>f</td>
            <td>g</td>
            <td>h</td>
            <td></td>
        </tr>

    </table>

    <div>
        <select name="" id="Combo" onchange="partidas()">
            <option value="0">---------</option>
            <option value="1">Partida 1</option>
            <option value="2">Partida 2</option>
            <option value="3">Partida 3</option>
        </select>


        <select id="selectColor" onchange="cambiarColorTablero()">
            <option value="#E7DAD8">Blanco</option>
            <option value="	#808080">Negro</option>
            <option value="#549548">Verde</option>
            <option value="#8FAECD">Azul</option>
            <option value="#D33B1C">Rojo</option>
        </select>



        <select id="velocidadMovimiento">
            <option value="1000">Lento</option>
            <option value="500">Medio</option>
            <option value="50">Rápido</option>
        </select>
        <button class="button2" onclick="ejecutarCompletoConVelocidad()">Completo</button>
        
       
        
        
    </div>

    

    <textarea name="" id="texto" cols="30" rows="10" disabled></textarea>
    <button class="button1" onclick="pasoApaso()">Paso a paso</button>
    <button class="button2" onclick="ejecutarCompleto()">Completo</button>

    
    <input class="button3" type="file" name="Cargar partida" id="cargarBoton" onchange="cargarPartida()">
    <input type="button" value="Test" onclick="test()">
    <h1><p id="turno">blanco</p>
    
    <p id="out"></p></h1>
</body>

</html>
