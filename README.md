<link href="https://fonts.googleapis.com/css?family=Quicksand:300,400,500,700&display=swap" rel="stylesheet">

<div class="onenight-wrapper">
    <div class="onenight-00">
        <!-- Encabezado con imagen de fondo -->
        <div class="onenight-header-container">
            <div class="onenight-imagen"></div>
            <div class="onenight-01">
                <span class="onenight-titu">B<span class="brillante1">l</span>inding Lig<span class="brillante2">t</span>hs</span>
                <span class="onenight-subti">Lugar — Hora</span>
            </div>
        </div>

        <!-- Primer Personaje -->
        <div class="onenightrelativito">
            <div class="onenight-iconito" style="background-image:url(https://66.media.tumblr.com/e4b1aca8236ff406c8cfd6d5b2c4c840/tumblr_p2na7osPeP1v4hlcio5_250.jpg)"></div>
            <div class="onenight-textito">
                <a href="#" class="onenight-nombree">Personaje uno</a>
                Aquí va el texto del primer participante del rol. Puedes escribir todo lo que quieras en este espacio.
            </div>
            <div class="clear"></div>
        </div>

        <!-- Segundo Personaje -->
        <div class="onenightrelativito">
            <div class="onenight-iconito icon-derecha" style="background-image:url(https://66.media.tumblr.com/f4da3284f5df630e4812e3bd137f005c/tumblr_ojitut8AHo1u7j6e0o3_250.jpg)"></div>
            <div class="onenight-textito text-derecha">
                <a href="#" class="onenight-nombree" style="text-align: right">Personaje dos</a>
                Aquí va el texto del segundo participante del rol. Todo alineado correctamente a la derecha.
            </div>
            <div class="clear"></div>
        </div>
        
        <!-- Créditos del autor integrados -->
        <div class="credits-container">
            <a href="https://ablackroseablaze.tumblr.com/" id="kay-credits">K a y</a>
        </div>
    </div>
</div>

<!-- Estilos CSS Corregidos -->
<style>
.onenight-wrapper {
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: #1a1a1a;
    padding: 20px 0;
}
.onenight-00 {
    width: 550px;
    position: relative;
    background: #0d0d0d;
    padding-bottom: 20px;
    box-sizing: border-box;
} 
.onenight-header-container {
    position: relative;
    width: 550px;
    height: 200px;
    overflow: hidden;
}
.onenight-imagen {
    background-image: url(https://i.ibb.co/k6Mxs44/mohammed-elnabarawy-final2.jpg);
    width: 550px;
    height: 200px;
    background-size: cover;
    background-position: center;
    opacity: 0.6;
    position: absolute;
    top: 0;
    left: 0;
} 
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
} 
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
} 
.onenightrelativito {
    display: block;
    padding: 0 20px;
    margin-top: 30px;
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
.icon-derecha {
    float: right;
}
.onenight-textito {
    color: #787878;
    font: 13px Calibri, sans-serif;
    float: left;
    text-align: justify;
    width: 390px;
    margin-left: 15px;
    box-sizing: border-box;
} 
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
} 
.credits-container {
    text-align: center;
    margin-top: 30px;
    clear: both;
}
a#kay-credits {
    font: 10px Calibri, sans-serif;
    color: #555;
    text-decoration: none;
    text-transform: uppercase;
    letter-spacing: 2px;
}
.clear {
    clear: both;
}
</style>
