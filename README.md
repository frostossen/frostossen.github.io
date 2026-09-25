<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Rol - Blinding Lights</title>
    <!-- Fuentes externas de Google Fonts -->
    <link href="https://googleapis.com" rel="stylesheet">
    
    <style>
        /* Configuración global de la página en GitHub */
        body {
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            font-family: Calibri, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* Contenedor principal de la tablilla */
        .onenight-00 {
            width: 550px;
            position: relative;
            background: #0d0d0d;
            padding-bottom: 25px;
            box-sizing: border-box;
            box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.5);
            border-radius: 4px;
            overflow: hidden;
        } 

        /* Encabezado con la imagen de fondo de la ciudad */
        .onenight-header-container {
            position: relative;
            width: 550px;
            height: 200px;
            overflow: hidden;
        }

        .onenight-imagen {
            background-image: url(https://ibb.co);
            width: 550px;
            height: 200px;
            background-size: cover;
            background-position: center;
            opacity: 0.6;
            position: absolute;
            top: 0;
            left: 0;
        } 

        /* Triángulo translúcido del título */
        .onenight-01 {
            width: 400px;
            height: 200px;
            clip-path: polygon(50% 100%, 0 0, 100% 0);
            background: rgba(0,0,0,0.7);
            margin: 0px auto;
            text-align: center;
            position: relative;
            z-index: 2;
        } 

        .onenight-titu {
            color: #787878;
            font: 20px 'Quicksand', sans-serif;
            text-transform: uppercase;
            margin-top: 30px;
            display: inline-block;
            letter-spacing: 1px;
        } 

        /* Efecto de parpadeo de las letras (Animación) */
        .brillante1, .brillante2 {
            text-shadow: 2px 2px 4px #fff, -2px -2px 4px #fff;
            color: #fff;
        } 
        .brillante1 { animation: brillantina 3s infinite; } 
        .brillante2 { animation: brillantina 4s infinite; } 

        @keyframes brillantina {
            0% { opacity: 1; } 
            50% { opacity: 0; } 
            90% { opacity: 1.0; } 
            92% { opacity: 0.2; } 
            94% { opacity: 1.0; } 
            96% { opacity: 0.2; } 
            100% { opacity: 1.0; }
        } 

        .onenight-subti {
            color: #dedede;
            display: block;
            font: 10px 'Quicksand', sans-serif;
            text-transform: uppercase;
            margin-top: 5px;
            letter-spacing: 2px;
        } 

        /* Bloques de los personajes */
        .onenightrelativito {
            display: block;
            padding: 0 25px;
            margin-top: 35px;
            box-sizing: border-box;
        }

        .onenight-iconito {
            width: 100px;
            height: 120px;
            background-size: cover;
            background-position: center;
            float: left;
            outline: 10px solid #0d0d0d;
            outline-offset: -4px;
        } 

        /* Variación para enviar el avatar a la derecha */
        .icon-derecha {
            float: right;
        }

        .onenight-textito {
            color: #787878;
            font: 13px Calibri, sans-serif;
            float: left;
            text-align: justify;
            width: 380px;
            margin-left: 15px;
            box-sizing: border-box;
            line-height: 1.4;
        } 

        /* Variación para enviar el texto a la derecha */
        .text-derecha {
            float: right;
            margin-left: 0;
            margin-right: 15px;
        }

        a.onenight-nombree {
            text-decoration: none;
            color: #aeaeae;
            font: 15px 'Quicksand', sans-serif;
            display: block;
            text-transform: uppercase;
            border-bottom: 1px solid #222;
            padding-bottom: 5px;
            margin-bottom: 8px;
            letter-spacing: 1px;
        } 

        /* Limpiador de flujos flotantes */
        .clear {
            clear: both;
        }

        /* Contenedor inferior de créditos */
        .credits-container {
            text-align: center;
            margin-top: 40px;
            clear: both;
        }

        a#kay-credits {
            font: 10px Calibri, sans-serif;
            color: #444;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 3px;
            transition: color 0.3s;
        }

        a#kay-credits:hover {
            color: #787878;
        }
    </style>
</head>
<body>

    <div class="onenight-00">
        <!-- Encabezado con imagen urbana -->
        <div class="onenight-header-container">
            <div class="onenight-imagen"></div>
            <div class="onenight-01">
                <span class="onenight-titu">B<span class="brillante1">l</span>inding Lig<span class="brillante2">t</span>hs</span>
                <span class="onenight-subti">Lugar — Hora</span>
            </div>
        </div>

        <!-- Bloque del Primer Personaje -->
        <div class="onenightrelativito">
            <div class="onenight-iconito" style="background-image:url(https://tumblr.com)"></div>
            <div class="onenight-textito">
                <a href="#" class="onenight-nombree">Personaje uno</a>
                No tengo ni idea.
            </div>
            <div class="clear"></div>
        </div>

        <!-- Bloque del Segundo Personaje -->
        <div class="onenightrelativito">
            <div class="onenight-iconito icon-derecha" style="background-image:url(https://tumblr.com)"></div>
            <div class="onenight-textito text-derecha">
                <a href="#" class="onenight-nombree" style="text-align: right">Personaje dos</a>
                Aquí va el texto del segundo participante del rol. Las alineaciones de texto e imágenes se mantendrán perfectamente estructuradas simétricamente a la derecha.
            </div>
            <div class="clear"></div>
        </div>
        
        <!-- Zona de créditos -->
        <div class="credits-container">
            <a href="https://tumblr.com" id="kay-credits" target="_blank">K a y</a>
        </div>
    </div>

</body>
</html>
