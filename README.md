<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Ejemplo de div y css</title>
    <link rel="stylesheet" href="estilo.css">
    <style>
        .pollito-rico {
            width: 150px;
            height: 210px;
        }

        .mostrito-rico {
            width: 150px;
            height: 210px;
            float: right;
        }

        .caldo-rico {
            width: 150px;
            height: 210px;
            float: right;
            margin-right: 83px;
        }

        .clase-broaster {
            float: left;
            margin-left: 100px;
            margin-right: 111px;
        }

        .clase-mostrito {
            float: right;
            margin-left: 110px;
            margin-right: 100px;
        }

        .clase-caldo {
            float: left;
            margin-right: 110px;
            margin-left: 100px;
        }

        .hamburguesa-rico {
            width: 150px;
            height: 210px;
            float: left;
            margin-left: 150px;
            margin-right: 83px;
        }

        .hamburguesa-carne {
            width: 150px;
            height: 210px;
            float: right;
            margin-left: 150px;
            margin-right: 83px;
        }

        .clase-pollo {
            float: left;
            margin-left: 150px;
            margin-right: 83px;

        }

        .clase-carne {
            float: right;
            margin-left: 110px;
            margin-right: 100px;
        }
        .h3-menor{
            float: right;
            margin-right: 83px;
            color: black;
        }
    </style>

</head>

<body>
    <div class="contenedor">
        <div class="cabecera">
            <h1> El SABOR DE ESTELITA POLLOS BROSATER TU DELICIA</h1>
        </div>
        <div class="contenedor-productos clearfix">
            <P>Productos en ventas:</P>
            <img src="pollo.jpg" alt="imagen de pollo BROSATER" class="pollito-rico">
            <img src="mostrito.jpg" alt="imagen del mostrito" class="mostrito-rico">
            <img src="caldo.jpg" alt="Imagen de caldo de Gallina" class="caldo-rico">
            <p class="clase-broaster">POLLO BROASTER</p>
            <P class="clase-caldo">CALDO DE GALLINA</P>
            <P class="clase-mostrito">MOSTRITO</P>
            <br>
            <img src="hamburguesa.jpg" alt="iamgen de hamburguesa" class="hamburguesa-rico">
            <img src="hamburguesa_carne.jpg" alt="hamburguesa de carne" class="hamburguesa-carne">
            <p class="clase-pollo">HAMBURGUESA DE BROASTER</p>
            <p class="clase-carne">HAMBURGUESA DE CARNE</p>
        </div>
        <div class="contenido-principal">
            <h3 class="h3-menor">HORA DE ATENCION DE LAS 12:OO PM HASTA LAS 11:PM</h3>
        </div>
        <div class="pie-pagina">
            HOY 1/01/2024
        </div>
    </div>
</body>

</html>
