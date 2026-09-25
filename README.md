<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ficha - Preston Goldstein</title>
    <!-- Fuentes elegantes de estilo manuscrito y moderno -->
    <link href="https://googleapis.com|Caveat:700&display=swap" rel="stylesheet">
    
    <style>
        /* Configuración de fondo de la pantalla local */
        body {
            margin: 0;
            padding: 20px;
            background-color: #1a1a1a;
            font-family: 'Calibri', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* Contenedor principal estilo "Tríptico/Ficha Extendida" */
        .ficha-contenedor {
            width: 1000px;
            background-color: #d1dfec; /* Color azul grisáceo idéntico al tuyo */
            border: 4px double #335272;
            padding: 15px;
            box-sizing: border-box;
            display: grid;
            grid-template-columns: 240px 220px 240px 240px; /* Estructura exacta de 4 columnas */
            gap: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.6);
            color: #2c3e50;
        }

        /* Estilo de los carteles de títulos oscuros con cintas blancas debajo */
        .bloque-titulo {
            background-color: #335272;
            color: #ffffff;
            font-family: 'Caveat', cursive;
            font-size: 26px;
            text-align: center;
            padding: 8px 5px;
            margin-bottom: 12px;
            border-radius: 4px;
            position: relative;
            box-shadow: 0 3px 6px rgba(0,0,0,0.15);
        }

        .cinta-blanca {
            background-color: #ffffff;
            color: #335272;
            font-family: 'Quicksand', sans-serif;
            font-size: 13px;
            font-weight: bold;
            display: inline-block;
            padding: 2px 12px;
            margin-top: 4px;
            border-radius: 3px;
            text-transform: uppercase;
        }

        /* Caja de textos de datos */
        .caja-datos {
            background-color: rgba(255, 255, 255, 0.85);
            border: 1px dashed #335272;
            padding: 12px;
            border-radius: 4px;
            font-size: 12px;
            line-height: 1.4;
            height: calc(100% - 70px);
            box-sizing: border-box;
            overflow-y: auto;
        }

        .caja-datos p {
            margin: 0 0 8px 0;
            border-bottom: 1px solid rgba(51, 82, 114, 0.15);
            padding-bottom: 4px;
        }

        .caja-datos strong {
            color: #335272;
            display: block;
            font-size: 11px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        /* Configuración general para las 3 columnas de imágenes */
        .columna-imagen {
            height: 100%;
            border: 2px solid #335272;
            border-radius: 4px;
            position: relative;
            background-size: cover;
            background-position: center;
            box-sizing: border-box;
            min-height: 480px;
        }

        /* Caja oscura inclinada para los datos de Habbo (Columna Central) */
        .habbo-banner {
            position: absolute;
            bottom: 15px;
            left: 5%;
            width: 90%;
            background-color: rgba(51, 82, 114, 0.95);
            color: white;
            padding: 8px;
            box-sizing: border-box;
            text-align: center;
            font-size: 11px;
            transform: rotate(-3deg); /* Simula la inclinación de tu imagen original */
            border-radius: 3px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        .habbo-banner div {
            border-bottom: 1px dashed rgba(255,255,255,0.3);
            padding: 3px 0;
        }
        .habbo-banner div:last-child {
            border-none: none;
        }

        /* Estilo para las listas de calificaciones (TIMO's y EXTASIS) */
        .lista-notas {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .lista-notas li {
            display: flex;
            justify-content: space-between;
            padding: 4px 0;
            border-bottom: 1px dotted #335272;
            font-size: 11px;
        }

        .nota-numero {
            font-weight: bold;
            color: #335272;
            background: rgba(255,255,255,0.9);
            padding: 0 6px;
            border-radius: 3px;
        }

        /* Recuadro decorativo de la cruz "Image Not Found" */
        .caja-not-found {
            border: 2px dashed #335272;
            background-color: rgba(255, 255, 255, 0.6);
            border-radius: 4px;
            padding: 10px;
            text-align: center;
            margin: 12px 0;
            color: #335272;
            font-family: 'Quicksand', sans-serif;
            font-size: 11px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="ficha-contenedor">
        
        <!-- COLUMNA 1: DATOS DEL PERSONAJE -->
        <div>
            <div class="bloque-titulo">
                Datos del
                <div class="cinta-blanca">Personaje</div>
            </div>
            
            <div class="caja-datos">
                <p><strong>Nombre del Personaje:</strong> Preston Chase Goldstein</p>
                <p><strong>Fecha de Nacimiento:</strong> 28 de Diciembre de 1930</p>
                <p><strong>Edad:</strong> 20 años</p>
                <p><strong>Raza:</strong> Mago</p>
                <p><strong>Tipo de Sangre:</strong> Mestiza</p>
                <p><strong>Rango:</strong> VIII</p>
                <p><strong>Varita Asignada:</strong> Tilo Plateado y Pluma de Fénix</p>
                <p><strong>Casa de Hogwarts:</strong> Ravenclaw</p>
                <p><strong>Rasgos:</strong> Empollón(gratis), Atleta, Precoz, Adinerado, Carismático, Valeroso, Ojo de Halcón, Trabajador, Fría Lógica, Don de Idiomas (Hebreo y Latín), Escrupuloso.</p>
                <p><strong>Fobia:</strong> Arpías</p>
                <p><strong>Derrochador:</strong> Mala suerte, Intrépido</p>
                <p><strong style="color: #c0392b;">Puntos de Rasgos [PR]:</strong> 17/17/0</p>
                <p><strong style="color: #d35400;">Puntos de Esfuerzo [PDE]:</strong> 994/972/22</p>
                <p><strong>Boggart:</strong> Arpía</p>
                <p><strong>Patronus:</strong> —</p>
            </div>
        </div>

        <!-- COLUMNA 2: PRIMERA IMAGEN (Traje Oscuro) -->
        <!-- Puedes cambiar el link entre comillas simples por tu imagen preferida -->
        <div class="columna-imagen" style="background-image: url('https://unsplash.com');">
        </div>

        <!-- COLUMNA 3: SEGUNDA IMAGEN + NOMBRE Y DATOS DE HABBO -->
        <div class="columna-imagen" style="background-image: url('https://unsplash.com');">
            <!-- Título del Nombre del personaje flotando arriba -->
            <div style="text-align:center; font-family:'Caveat', cursive; font-size:32px; color:#335272; background:rgba(255,255,255,0.8); padding:5px 0; font-weight:bold;">
                Preston Goldstein
            </div>

            <!-- Banner Inclinado de Habbo abajo -->
            <div class="habbo-banner">
                <strong style="font-size:9px; letter-spacing:1px; display:block; margin-bottom:2px;">DATOS EN HABBO</strong>
                <div>Complicated-</div>
                <strong style="font-size:9px; margin-top:4px;">FECHA DE INICIO</strong>
                <div>17/10/2019</div>
            </div>
        </div>

        <!-- COLUMNA 4: TERCERA IMAGEN + NOTAS ACADÉMICAS -->
        <div>
            <!-- Título de TIMO'S -->
            <div class="bloque-titulo">
                Notas de
                <div class="cinta-blanca">TIMO's</div>
            </div>
            
            <div class="caja-datos" style="height: auto; margin-bottom: 10px; background-color: rgba(255,255,255,0.9);">
                <ul class="lista-notes lista-notas">
                    <li><span>Astronomía</span> <span class="nota-numero">9</span></li>
                    <li><span>CCM</span> <span class="nota-numero">9</span></li>
                    <li><span>DCAO</span> <span class="nota-numero">9</span></li>
                    <li><span>Encantamientos</span> <span class="nota-numero">10</span></li>
                    <li><span>Estudios Muggles</span> <span class="nota-numero">10</span></li>
                    <li><span>Herbología</span> <span class="nota-numero">10</span></li>
                    <li><span>HDM</span> <span class="nota-numero">10</span></li>
                    <li><span>Pociones</span> <span class="nota-numero">10</span></li>
                    <li><span>Runas Antiguas</span> <span class="nota-numero">10</span></li>
                    <li><span>Transformaciones</span> <span class="nota-numero">9</span></li>
                </ul>
            </div>

            <!-- Caja decorativa de la "Imagen No Encontrada" idéntica a tu captura -->
            <div class="caja-not-found">
                <div style="font-size: 20px; margin-bottom: 2px;">✕</div>
                Image Not Found
            </div>

            <!-- Título de EXTASIS -->
            <div class="bloque-titulo" style="margin-top: 5px;">
                Notas de
                <div class="cinta-blanca">EXTASIS</div>
            </div>

            <div class="caja-datos" style="height: auto; background-color: rgba(255,255,255,0.9);">
                <ul class="lista-notas">
                    <li><span>Astronomía</span> <span class="nota-numero">10</span></li>
