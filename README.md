# Amor
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feliz 1º mês de namoro</title>
  <style>
    @keyframes surgirSuave {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, pink, orange);
    }

    .container {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      padding: 20px 10px;
    }

    .titulo {
      color: white;
      font-size: 2em;
      font-weight: bold;
      text-align: center;
      margin-bottom: 20px;
      animation: surgirSuave 2s ease-in-out;
    }

    .cora {
      font-size: 6em;
      color: #FF1493;
      margin-bottom: 20px;
      text-align: center;
    }

    .texto {
      background: rgba(255,255,255,0.95);
      border-radius: 15px;
      padding: 20px;
      text-align: center;
      line-height: 1.8;
      max-width: 100%;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      font-size: 1em;
    }
  </style>
</head>
<body>

  <!-- MÚSICA -->
  <audio id="musica" src="musica.mp3" loop></audio>
  <script>
    document.addEventListener('click', function tocarMusica() {
      const audio = document.getElementById('musica');
      audio.play().catch(() => {});
      document.removeEventListener('click', tocarMusica);
    });
  </script>

  <div class="container">
    <div class="titulo">Feliz 1º mês de namoro, meu amor!</div>
    <h1 style="color: white; font-size: 1.8em; margin-bottom: 10px; text-align: center;">Você é tudo pra mim</h1>
    <h2 style="color: black; font-size: 1.2em; animation: surgirSuave 2s ease-in-out; margin-bottom: 20px; text-align: center;">Eu te amo Isabela</h2>
    <div class="cora">❤️</div>
    <div class="texto">
      Meu amorrr! ❤️‍🔥<br><br>
      Parece que foi ontem que nossos caminhos se cruzaram de uma forma tão inesperada e linda. Hoje, celebramos nosso primeiro mês de namoro, e meu coração transborda de uma alegria que eu jamais imaginei ser possível. Mesmo que a distância física ainda nos separe, sinto você tão perto, tão presente em cada pensamento, em cada batida do meu coração. <br><br>
      Nesse um mês, você se tornou meu porto seguro, a pessoa que ilumina meus dias e me faz acreditar ainda mais no amor. Cada conversa, cada risada, cada emoji trocado fortalece um sentimento que cresce a cada segundo. É incrível como a conexão da nossa alma é tão forte que a falta do toque físico se torna apenas um detalhe diante da imensidão do que sinto por você. <br><br>
      Eu te amo com uma intensidade que transcende qualquer barreira. Amo seu sorriso, sua voz, seu jeito único de me fazer sentir o homem mais sortudo do mundo. Amo sua inteligência, sua sensibilidade, sua capacidade de me surpreender a cada dia. E, mais do que tudo, amo a forma como você me faz sentir completo, mesmo que estejamos a quilômetros de distância. <br><br>
      Sei que o futuro nos reserva o tão esperado encontro, e mal posso esperar para te abraçar bem forte, te beijar muito e te dizer pessoalmente o quanto você é especial para mim. Enquanto esse dia não chega, vou continuar te amando, te mimando e te fazendo sorrir todos os dias, mesmo que seja por uma tela. Você é a mulher da minha vida, e meu amor por você é eterno. <br><br>
      <strong>Feliz 1º mês de namoro, minha vida!</strong> Que venham muitos e muitos meses, anos e uma eternidade ao seu lado. Eu te amo mais do que as palavras podem expressar. Te amo, te amo, te amo! ♥️
    </div>
  </div>
</body>
</html>
