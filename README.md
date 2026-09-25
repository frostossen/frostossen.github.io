<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ficha de Personaje</title>
    <!-- Fuente elegante y moderna similar a la imagen -->
    <link href="https://googleapis.com|Caveat:700&display=swap" rel="stylesheet">
    
    <style>
        /* Configuración de fondo de la web */
        body {
            margin: 0;
            padding: 40px 0;
            background-color: #1a1a1a;
            font-family: 'Calibri', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* Contenedor principal de la ficha (Tres Columnas) */
        .ficha-contenedor {
            width: 950px;
            background-color: #d1dfec; /* Color azul grisáceo claro de fondo */
            border: 4px double #335272; /* Bordes decorativos */
            padding: 20px;
            box-sizing: border-box;
            display: grid;
            grid-template-columns: 280px 1fr 240px; /* Tamaño de las 3 columnas */
            gap: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            color: #2c3e50;
        }

        /* Títulos estilizados en cintas oscuras */
        .seccion-titulo {
            background-color: #335272;
            color: #ffffff;
            font-family: 'Caveat', cursive;
            font-size: 26px;
            text-align: center;
            padding: 8px 10px;
            margin-bottom: 15px;
            border-radius: 4px;
            letter-spacing: 1px;
            box-shadow: inset 0 0 5px rgba(0,0,0,0.2);
        }

        /* Cajas de contenido internas */
        .caja-blanca {
            background-color: rgba(255, 255, 255, 0.85);
            border: 1px dashed #335272;
            padding: 15px;
            border-radius: 4px;
            margin-bottom: 15px;
            font-size: 13px;
            line-height: 1.5;
        }

        /* === COLUMNA 1: DATOS E IMAGEN === */
        .columna-izquierda {
            display: flex;
            flex-direction: column;
        }

        .avatar-personaje {
            width: 100%;
            height: 320px;
            /* Reemplaza este link por la foto de tu personaje preferido */
            background-image: url('https://unsplash.com');
            background-size: cover;
            background-position: center;
            border: 3px solid #335272;
            border-radius: 4px;
            margin-bottom: 15px;
        }

        .datos-lista {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .datos-lista li {
            margin-bottom: 6px;
            border-bottom: 1px solid rgba(51, 82, 114, 0.2);
            padding-bottom: 4px;
        }

        .datos-lista strong {
            color: #335272;
        }

        /* === COLUMNA 2: HABILIDADES Y EQUIPAMIENTO === */
        .subseccion-titulo {
            font-family: 'Quicksand', sans-serif;
            font-weight: 700;
            color: #335272;
            border-bottom: 2px solid #335272;
            margin: 10px 0 5px 0;
            font-size: 14px;
            text-transform: uppercase;
        }

        /* Contenedor central dividido para poner Habilidades y Equipamiento lado a lado */
        .centro-layout {
            display: grid;
            grid-template-columns: 1fr 120px;
            gap: 15px;
        }

        .equipamiento-vertical {
            background-color: #335272;
            color: white;
            padding: 10px;
            border-radius: 4px;
            font-size: 11px;
            text-align: center;
        }

        .equipamiento-vertical div {
            border-bottom: 1px solid rgba(255,255,255,0.2);
            padding: 6px 0;
        }

        /* Bloque de Stats con estilo de botones oscuros */
        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 8px;
            margin-top: 10px;
        }

        .stat-item {
            background-color: #335272;
            color: #fff;
            padding: 6px;
            text-align: center;
            border-radius: 4px;
            font-family: 'Quicksand', sans-serif;
            font-size: 12px;
        }

        /* === COLUMNA 3: NOTAS Y EXÁMENES === */
        .notas-lista {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .notas-lista li {
            display: flex;
            justify-content: space-between;
            padding: 4px 0;
            border-bottom: 1px dotted #335272;
        }

        .nota-valor {
            font-weight: bold;
            color: #335272;
        }
    </style>
</head>
<body>

    <div class="ficha-contenedor">
        
        <!-- COLUMNA 1 -->
        <div class="columna-izquierda">
            <div class="seccion-titulo">Datos del Personaje</div>
            <div class="avatar-personaje"></div>
            
            <div class="caja-blanca">
                <ul class="datos-lista">
                    <li><strong>Casa:</strong> Ravenclaw</li>
                    <li><strong>Rasgos:</strong> Empollón, Atleta, Precoz, Adinerado, Valeroso, Fría Lógica</li>
                    <li><strong>Puntos de Rasgos:</strong> 17 / 17</li>
                    <li><strong>Boggart:</strong> Arpí</li>
                    <li><strong>Patronus:</strong> Caballito de Mar Volador</li>
                    <li><strong>Dinero:</strong> 18 Galeones</li>
                    <li><strong>Empleo:</strong> Aprendiz de Sanador</li>
                </ul>
            </div>
        </div>

        <!-- COLUMNA 2 -->
        <div>
            <div class="seccion-titulo">Habilidades y Aprendizaje</div>
            
            <div class="caja-blanca">
                <div class="subseccion-titulo">Afinidades</div>
                <p style="margin: 5px 0 15px 0;">1. Encantamientos<br>2. Estudios Muggles<br><strong>Especial:</strong> Legeremancia Innata</p>
                
                <div class="subseccion-titulo">Habilidades Pasivas y Posturas</div>
                <div class="centro-layout">
                    <div>
                        <p><strong>[Pasiva]</strong> Yo lo escucho todo.<br><strong>[Pasiva]</strong> Oye, ten más cuidado.</p>
                        <p><strong>[Pasiva]</strong> Compañerismo (Constelación Orión).</p>
                        <p><strong>[Pasiva]</strong> Nuevo hogar, Ingenio.</p>
                        <p><strong>[Pasiva]</strong> Mi mejor amigo (Búho).</p>
                    </div>
                    <!-- Bloque vertical de equipamiento -->
                    <div class="equipamiento-vertical">
                        <strong style="font-size: 10px; display:block; margin-bottom:5px;">EQUIPO</strong>
                        <div>Varita</div>
                        <div>Torso: —</div>
                        <div>Cabeza: —</div>
                        <div>Pies: —</div>
                        <div>Bolso: —</div>
                    </div>
                </div>
            </div>

            <div class="seccion-titulo">* Stats</div>
            <div class="stats-grid">
                <div class="stat-item">Vitalidad: 6940</div>
                <div class="stat-item">Velocidad: 10</div>
                <div class="stat-item">Poder M: 500</div>
                <div class="stat-item">Inteligencia: 16</div>
            </div>
        </div>

        <!-- COLUMNA 3 -->
        <div>
            <div class="seccion-titulo">Notas de TIMO's</div>
            <div class="caja-blanca">
                <ul class="notas-lista">
                    <li><span>Astronomía</span> <span class="nota-valor">9</span></li>
                    <li><span>CCM</span> <span class="nota-valor">9</span></li>
                    <li><span>DCAO</span> <span class="nota-valor">9</span></li>
                    <li><span>Encantamientos</span> <span class="nota-valor">10</span></li>
                    <li><span>Estudios Muggles</span> <span class="nota-valor">10</span></li>
                    <li><span>Herbología</span> <span class="nota-valor">10</span></li>
                    <li><span>Pociones</span> <span class="nota-valor">10</span></li>
                </ul>
            </div>

            <div class="seccion-titulo">Notas de EXTASIS</div>
            <div class="caja-blanca">
                <ul class="notas-lista">
                    <li><span>Astronomía</span> <span class="nota-valor">10</span></li>
                    <li><span>CCM</span> <span class="nota-valor">10</span></li>
                    <li><span>DCAO</span> <span class="nota-valor">10</span></li>
                    <li><span>Encantamientos</span> <span class="nota-valor">10</span></li>
                    <li><span>Herbología</span> <span class="nota-valor">10</span></li>
                </ul>
            </div>
        </div>

    </div>

</body>
</html>
