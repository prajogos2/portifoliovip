# portifoliovip<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prajogos Studio | Video Editing</title>
<style>
  /* Reset básico */
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
  body { background-color: #0a0a0a; color: #fff; overflow-x: hidden; }

  /* Glow neon azul */
  .neon { color: #00f0ff; text-shadow: 0 0 5px #00f0ff, 0 0 10px #00f0ff, 0 0 20px #00f0ff; }

  /* Links / botões */
  a, button { color: #00f0ff; text-decoration: none; border: 2px solid #00f0ff; padding: 10px 20px; border-radius: 5px; transition: all 0.3s ease; background: transparent; }
  a:hover, button:hover { background-color: #00f0ff; color: #0a0a0a; box-shadow: 0 0 10px #00f0ff, 0 0 20px #00f0ff; }

  header { display: flex; justify-content: space-between; align-items: center; padding: 20px 50px; }
  nav a { margin-left: 20px; }

  /* Hero */
  .hero { height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; }
  .hero h1 { font-size: 3rem; margin-bottom: 20px; }
  .hero p { font-size: 1.2rem; margin-bottom: 30px; }

  /* Portfolio */
  .portfolio { padding: 50px; display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
  .portfolio iframe { width: 100%; height: 200px; border: 0; border-radius: 10px; box-shadow: 0 0 10px #00f0ff; transition: transform 0.3s ease, box-shadow 0.3s ease; }
  .portfolio iframe:hover { transform: scale(1.05); box-shadow: 0 0 20px #00f0ff, 0 0 40px #00f0ff; }

  /* About */
  .about { padding: 50px; text-align: center; }
  .about img { width: 150px; height: 150px; border-radius: 50%; margin-bottom: 20px; border: 2px solid #00f0ff; box-shadow: 0 0 10px #00f0ff; }

  /* Services */
  .services { padding: 50px; display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }
  .card { border: 2px solid #00f0ff; padding: 20px; border-radius: 10px; min-width: 200px; text-align: center; backdrop-filter: blur(5px); transition: all 0.3s ease; }
  .card:hover { box-shadow: 0 0 20px #00f0ff, 0 0 40px #00f0ff; transform: translateY(-5px); }

  /* Contact */
  .contact { padding: 50px; text-align: center; }
  .contact button { font-size: 1.2rem; }

  /* Footer */
  footer { text-align: center; padding: 20px; border-top: 1px solid #00f0ff; margin-top: 50px; font-size: 0.9rem; }

  /* Responsivo */
  @media(max-width:768px){ header { flex-direction: column; } nav a { margin: 10px 0; } .hero h1 { font-size: 2rem; } }
</style>
</head>
<body>

<header>
  <div class="neon">Prajogos Studio</div>
  <nav>
    <a href="#portfolio">Projetos</a>
    <a href="#services">Serviços</a>
    <a href="#about">Sobre</a>
    <a href="#contact">Contato</a>
  </nav>
</header>

<section class="hero">
  <h1 class="neon">Edição de Vídeos Profissional</h1>
  <p>High-performance edits for YouTube, reels, gaming & cinematic projects.</p>
  <a href="#portfolio">Ver Projetos</a>
</section>

<section class="portfolio" id="portfolio">
  <iframe src="https://www.youtube.com/embed/VIDEO1" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/VIDEO2" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/VIDEO3" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/VIDEO4" allowfullscreen></iframe>
</section>

<section class="services" id="services">
  <div class="card neon">Edição de YouTube</div>
  <div class="card neon">Shorts / Reels</div>
  <div class="card neon">Gaming & Gameplay</div>
  <div class="card neon">Edição Cinemática</div>
</section>

<section class="about" id="about">
  <img src="https://via.placeholder.com/150" alt="Foto do Editor">
  <h2 class="neon">Sobre Prajogos</h2>
  <p>Sou um editor apaixonado por transformar imagens em histórias impactantes. Trabalho com conteúdos para YouTube, redes sociais e projetos cinematográficos.</p>
</section>

<section class="contact" id="contact">
  <h2 class="neon">Entre em Contato</h2>
  <p>Vamos levar seu projeto para outro nível.</p>
  <button onclick="window.location.href='mailto:contato@prajogosstudio.com'">Enviar Email</button>
  <button onclick="window.location.href='https://wa.me/559999999999'">WhatsApp</button>
</section>

<footer>
  &copy; 2026 Prajogos Studio. Todos os direitos reservados.
</footer>

</body>
</html>
