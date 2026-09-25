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
