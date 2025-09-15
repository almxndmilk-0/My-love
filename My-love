<!DOCTYPE html>
<html>
<head>
<title>index.htlm</title>
</head>
<body>
<!-- Start your code here -->
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Carta para Erian</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff8f2;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
      color: #222;
      flex-direction: column;
    }
    .btn {
      padding: 12px 20px;
      background: #111;
      color: #fff;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      margin-top: 20px;
    }
    #carta {
      display: none;
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      margin-top: 20px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.06);
    }
    textarea, input {
      width: 100%;
      max-width: 300px;
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
      margin-top: 15px;
      resize: vertical;
    }
  </style>
</head>
<body>

<h1>💌 Carta para Erian</h1>

<p>Escribe tu recuerdo favorito con Kiri:</p>
<textarea id="recuerdo" placeholder="Tu recuerdo aquí..."></textarea>

<p>Mini reto: ¿Una frase que Kiri diga mucho? (pista: Ironman)</p>
<input id="reto" placeholder="Escribe la frase aquí...">

<button class="btn" id="revelar">Revelar carta</button>

<div id="carta">
  <p id="p_texto"></p>
  <p style="font-style: italic;">Con cariño, Kiri 💖</p>
</div>

<script>
const btn = document.getElementById('revelar');
const carta = document.getElementById('carta');
const p_texto = document.getElementById('p_texto');

const cartaBase = `Probablemente leas esto el día de tu cumpleaños, antes de iniciar quiero disculparme por darte algo tan simple como una carta. Sé que mereces muchísimo más, prometo esforzarme más. Primero que nada, ¡feliz cumpleaños! Estoy feliz y agradecida de estar un día más, un año más contigo. Estar contigo se siente como estar en casa, es algo que valoro y agradezco. Mi bonito, estoy muy orgullosa de ti, de lo que hasta el día de hoy has logrado. Eres alguien increíble y admirable.

¿Te confieso algo? Haría lo que fuera por seguir contigo. La verdad es que no importa el momento, siempre, siempre pienso en ti. No sé cómo demostrarlo o qué palabras usar, pero... me gustas mucho, muchísimo. Estoy completamente enamorada. Decírtelo no es suficiente, necesito hacer algo más, y ese es mi jodido problema, no sé qué hacer.

Y bueno... aunque algunas personas no comprendan mis sentimientos, aunque sus palabras intenten herirme, no puedo dejar de amarte. Nuestro amor es de esos que no se explican, que solo se sienten... y el mío por ti arde como fuego que no se apaga. A pesar de todo, aquí estamos otra vez: tú, yo... y un cielo entero que parece brillar solo para nosotros.

Ahora, tenerte cerca hace que mi corazón quiera romper mi pecho, que la alegría se derrame por cada rincón de mi alma. Te amo más allá de lo que las palabras puedan contener, más allá de lo que este mundo pueda medir.`;

btn.addEventListener('click', () => {
  const recuerdo = document.getElementById('recuerdo').value.trim();
  let reto = document.getElementById('reto').value.trim().toLowerCase();

  // Quitamos posibles espacios extra y el emoji 💖
  reto = reto.replace(/💖/g, '').trim();

  // Variantes válidas
  const respuestasValidas = [
    "te amo tres millones",
    "te amo 3 millones"
  ];

  if (!respuestasValidas.includes(reto)) {
    alert("Ups! Intenta de nuevo 😅");
    return;
  }

  p_texto.textContent = `✨ Tu recuerdo: "${recuerdo}" ✨\n\n${cartaBase}`;
  carta.style.display = 'block';
  btn.style.display = 'none';
});
</script>

</body>
</html>
<!-- End your code here -->
</body>
</html>
