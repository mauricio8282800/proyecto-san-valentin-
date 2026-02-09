<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Pregunta importante 💘</title>
<style>
    body {
        font-family: Arial, sans-serif;
        text-align: center;
        background: #ffe6f0;
        padding-top: 60px;
    }
    h1 {
        color: #d63384;
    }
    button {
        font-size: 18px;
        padding: 10px 20px;
        margin: 10px;
        border: none;
        border-radius: 10px;
        cursor: pointer;
    }
    #si {
        background-color: #ff4d88;
        color: white;
    }
    #no {
        background-color: #999;
        color: white;
        position: absolute;
    }
</style>
</head>

<body>

<h1>Para mi atleta favorita 🏅💖</h1>
<h2>¿Quieres ser mi San Valentín? 💕</h2>

<button id="si" onclick="aceptar()">Sí 💘</button>
<button id="no">No 😢</button>

<script>
const botonNo = document.getElementById("no");

botonNo.addEventListener("mouseover", () => {
    const x = Math.random() * (window.innerWidth - 100);
    const y = Math.random() * (window.innerHeight - 50);
    botonNo.style.left = x + "px";
    botonNo.style.top = y + "px";
});

function aceptar() {
    document.body.innerHTML = `
        <h1 style="color:#d63384;">❤️ Sabía que dirías que sí ❤️</h1>
        <p style="font-size:18px; max-width:500px; margin:20px auto;">
        Este será nuestro último San Valentín distanciados amorcito mío, 
        ya pronto estaré cerca de ti y podré darte un montón de cosas 
        y sobretodo mi cariño. En fin amorcito, te amo demasiado ❤️  
        Y ya cuando vaya te daré tus regalos de San Valentín atrasados, 
        mi niña hermosa 💕
        </p>
    `;
}
</script>

</body>
</html>
