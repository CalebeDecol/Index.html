<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Agro Forte - Agricultura Sustentável</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background:#f4fff2;
      color:#1f1f1f;
      overflow-x:hidden;
    }

    /* MENU */
    header{
      width:100%;
      background:linear-gradient(90deg,#1b5e20,#43a047);
      padding:20px 8%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:fixed;
      top:0;
      z-index:1000;
      box-shadow:0 2px 10px rgba(0,0,0,0.2);
    }

    header h1{
      color:white;
      font-size:2rem;
    }

    nav a{
      color:white;
      text-decoration:none;
      margin-left:25px;
      font-weight:bold;
      transition:0.3s;
    }

    nav a:hover{
      color:#c8ffb0;
    }

    /* HERO */
    .hero{
      height:100vh;
      background:
      linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)),
      url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6?q=80&w=1400&auto=format&fit=crop');
      background-size:cover;
      background-position:center;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
    }

    .hero-content{
      color:white;
      max-width:800px;
      animation:fadeIn 2s ease;
    }

    .hero-content h2{
      font-size:4rem;
      margin-bottom:20px;
    }

    .hero-content p{
      font-size:1.3rem;
      margin-bottom:30px;
      line-height:1.6;
    }

    .btn{
      background:#8bc34a;
      color:#1b1b1b;
      padding:15px 35px;
      border:none;
      border-radius:40px;
      font-size:1rem;
      font-weight:bold;
      cursor:pointer;
      transition:0.3s;
    }

    .btn:hover{
      transform:scale(1.05);
      background:#c5ff6b;
    }

    /* SEÇÕES */
    section{
      padding:100px 8%;
    }

    .titulo{
      text-align:center;
      margin-bottom:60px;
    }

    .titulo h2{
      font-size:2.8rem;
      color:#2e7d32;
      margin-bottom:10px;
    }

    .titulo p{
      color:#555;
      font-size:1.1rem;
    }

    /* CARDS */
    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
      gap:30px;
    }

    .card{
      background:white;
      padding:35px;
      border-radius:20px;
      box-shadow:0 5px 20px rgba(0,0,0,0.1);
      transition:0.4s;
      text-align:center;
    }

    .card:hover{
      transform:translateY(-10px);
    }

    .card img{
      width:90px;
      margin-bottom:20px;
    }

    .card h3{
      margin-bottom:15px;
      color:#2e7d32;
    }

    .card p{
      color:#555;
      line-height:1.6;
    }

    /* TECNOLOGIA */
    .tecnologia{
      background:#e8f5e9;
    }

    .contador{
      text-align:center;
      margin-top:40px;
      font-size:2rem;
      color:#1b5e20;
      font-weight:bold;
    }

    /* GALERIA */
    .galeria{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
      gap:20px;
    }

    .galeria img{
      width:100%;
      height:250px;
      object-fit:cover;
      border-radius:15px;
      transition:0.4s;
    }

    .galeria img:hover{
      transform:scale(1.03);
    }

    /* FOOTER */
    footer{
      background:#1b5e20;
      color:white;
      text-align:center;
      padding:30px;
    }

    footer p{
      margin:10px 0;
    }

    /* ANIMAÇÃO */
    @keyframes fadeIn{
      from{
        opacity:0;
        transform:translateY(40px);
      }
      to{
        opacity:1;
        transform:translateY(0);
      }
    }

    /* RESPONSIVO */
    @media(max-width:768px){

      header{
        flex-direction:column;
      }

      nav{
        margin-top:15px;
      }

      .hero-content h2{
        font-size:2.5rem;
      }

      .hero-content p{
        font-size:1rem;
      }
    }
  </style>
</head>

<body>

  <!-- MENU -->
  <header>
    <h1>🌱 Agro Forte</h1>

    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#sustentabilidade">Sustentabilidade</a>
      <a href="#tecnologia">Tecnologia</a>
      <a href="#galeria">Galeria</a>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <h2>O Futuro da Agricultura é Sustentável</h2>

      <p>
        Tecnologia, inovação e sustentabilidade caminhando juntas para fortalecer
        o agro brasileiro e preservar o meio ambiente.
      </p>

      <button class="btn" onclick="mostrarMensagem()">
        Saiba Mais
      </button>
    </div>
  </section>

  <!-- SOBRE -->
  <section id="sobre">

    <div class="titulo">
      <h2>Agro Forte</h2>
      <p>
        A agricultura moderna utiliza tecnologia e práticas sustentáveis para
        produzir mais alimentos com menos impacto ambiental.
      </p>
    </div>

    <div class="cards">

      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/2909/2909763.png">

        <h3>Agricultura Sustentável</h3>

        <p>
          Uso consciente da água, preservação do solo e redução de desperdícios
          garantem uma produção responsável.
        </p>
      </div>

      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/1048/1048953.png">

        <h3>Energia Limpa</h3>

        <p>
          Fazendas inteligentes utilizam energia solar e soluções renováveis para
          diminuir impactos ambientais.
        </p>
      </div>

      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/1995/1995574.png">

        <h3>Tecnologia no Campo</h3>

        <p>
          Drones, sensores e inteligência artificial ajudam produtores a aumentar
          a produtividade.
        </p>
      </div>

    </div>
  </section>

  <!-- TECNOLOGIA -->
  <section class="tecnologia" id="tecnologia">

    <div class="titulo">
      <h2>Inovação Tecnológica</h2>

      <p>
        O uso da tecnologia fortalece o agronegócio e torna a produção mais eficiente.
      </p>
    </div>

    <div class="cards">

      <div class="card">
        <h3>🚜 Máquinas Inteligentes</h3>

        <p>
          Tratores automatizados e sistemas inteligentes aumentam a precisão no plantio.
        </p>
      </div>

      <div class="card">
        <h3>📡 Monitoramento por Satélite</h3>

        <p>
          Sensores monitoram plantações em tempo real para evitar desperdícios.
        </p>
      </div>

      <div class="card">
        <h3>🌾 Produção Sustentável</h3>

        <p>
          Tecnologias modernas ajudam a produzir alimentos preservando a natureza.
        </p>
      </div>

    </div>

    <div class="contador">
      <span id="numero">0</span> hectares monitorados com tecnologia
    </div>

  </section>

  <!-- GALERIA -->
  <section id="galeria">

    <div class="titulo">
      <h2>Galeria do Agro</h2>

      <p>
        Imagens que representam a força da agricultura sustentável.
      </p>
    </div>

    <div class="galeria">

      <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854?q=80&w=1200&auto=format&fit=crop">

      <img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399?q=80&w=1200&auto=format&fit=crop">

      <img src="https://images.unsplash.com/photo-1471193945509-9ad0617afabf?q=80&w=1200&auto=format&fit=crop">

    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <h2>🌱 Projeto Agrinho</h2>

    <p>
      Agro Forte - Agricultura Sustentável e Tecnologia no Campo
    </p>

    <p>
      Desenvolvido para o Projeto Agrinho 2026
    </p>
  </footer>

  <!-- JAVASCRIPT -->
  <script>

    function mostrarMensagem(){
      alert("A tecnologia e a sustentabilidade são essenciais para o futuro da agricultura!");
    }

    // CONTADOR ANIMADO
    let numero = 0;

    const contador = document.getElementById("numero");

    const intervalo = setInterval(() => {

      numero += 50;

      contador.innerHTML = numero;

      if(numero >= 5000){
        clearInterval(intervalo);
      }

    }, 30);

  </script>

</body>
</html>
