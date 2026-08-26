<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>O que eu esperava da disciplina? — Computação Visual</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,300;9..144,500;9..144,600&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #0d0c0a;
    --panel: #17150f;
    --panel-border: #2a2620;
    --text: #ece7dc;
    --text-dim: #9a9385;
    --accent: #c9a227;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  body{background:var(--bg);color:var(--text);font-family:'Inter',sans-serif;line-height:1.7;}
  a{color:var(--accent);text-decoration:none;border-bottom:1px solid var(--accent);}

  header{
    display:flex;justify-content:space-between;align-items:center;
    padding:28px 6vw;border-bottom:1px solid var(--panel-border);
  }
  .brand{display:flex;align-items:center;gap:10px;font-weight:600;letter-spacing:0.02em;text-decoration:none;border:none;color:var(--text);}
  .brand .mark{width:14px;height:14px;background:var(--accent);transform:rotate(45deg);}
  .back{font-size:14px;color:var(--text-dim);border:none;}
  .back:hover{color:var(--accent);}

  article{max-width:720px;margin:0 auto;padding:80px 6vw 120px;}
  .eyebrow{color:var(--accent);font-size:12px;letter-spacing:0.16em;text-transform:uppercase;font-weight:600;margin-bottom:18px;}
  h1{font-family:'Fraunces',serif;font-weight:500;font-size:clamp(2rem, 4.5vw, 3rem);line-height:1.1;margin-bottom:20px;}
  .date{color:var(--text-dim);font-size:14px;margin-bottom:48px;}

  h2{font-family:'Fraunces',serif;font-weight:500;font-size:1.5rem;margin:44px 0 16px;color:var(--accent);}
  p{color:var(--text);font-size:16px;margin-bottom:18px;}
  ul{margin:0 0 18px 22px;}
  li{margin-bottom:12px;}
  li b{color:var(--accent);font-weight:600;}

  hr{border:none;border-top:1px solid var(--panel-border);margin:56px 0 32px;}
</style>
</head>
<body>

<header>
  <a href="index.html" class="brand"><span class="mark"></span> COMPVIS</a>
  <a href="index.html" class="back">← Voltar</a>
</header>

<article>
  <div class="eyebrow">Post 01 · 18/08/2026</div>
  <h1>O que eu esperava da disciplina?</h1>
  <div class="date">Henrique Jean · Computação Visual (2026.2)</div>

  <h2>O que eu achava que veria</h2>
  <p>Antes da primeira aula eu não fazia muita ideia do que essa disciplina realmente ia abordar. Pelo nome, imaginei que fosse algo mais ligado a interfaces gráficas e front-end, meio parecido com IHC. Também pensei que pudesse envolver bastante ferramenta tipo Photoshop e Blender, ou até reconhecimento de padrões em imagem usando IA.</p>
  <p>Fiquei meio em dúvida também se era uma continuação de Computação Gráfica (modelagem 3D, renderização e esse tipo de coisa) ou se ia puxar mais pro lado de Visão Computacional, com câmera, detecção de objeto, esse tipo de aplicação. Como não tinha muita clareza sobre o conteúdo, fiquei curioso pra ver como o professor ia amarrar tudo isso numa matéria só.</p>

  <h2>O que eu entendi que vamos estudar</h2>
  <p>Depois de ver o material da primeira aula, entendi que Computação Visual é tipo um "guarda-chuva" que junta três áreas que normalmente são tratadas separadas: Computação Gráfica, Visão Computacional e Processamento de Imagens.</p>
  <p>O conteúdo da primeira aula começou pelos fundamentos da imagem digital, e curiosamente não começou falando de código ou algoritmo, e sim de como o próprio olho humano funciona. Alguns pontos que vimos:</p>
  <ul>
    <li><b>Olho humano:</b> as estruturas principais (córnea, íris, pupila, cristalino, retina) e como a imagem é formada e focalizada na fóvea.</li>
    <li><b>Fotorreceptores:</b> a diferença entre cones (sensíveis à cor, concentrados na fóvea, usados na visão de luz clara/fotópica) e bastonetes (sensíveis à luminosidade, espalhados pela retina, usados na visão noturna/escotópica).</li>
    <li><b>Adaptação ao brilho:</b> como o olho ajusta a sensibilidade dependendo da luz do ambiente, mesmo sem conseguir operar em toda a escala de intensidade luminosa ao mesmo tempo.</li>
    <li><b>Ilusões de ótica:</b> coisas como as bandas de Mach e o contraste simultâneo, que mostram que o brilho percebido não depende só da intensidade real da luz, mas também do que tem ao redor.</li>
    <li><b>Espectro eletromagnético e luz:</b> a luz visível é só uma fatia bem pequena do espectro eletromagnético todo, com a relação entre comprimento de onda, frequência e energia, além dos fenômenos de reflexão, transmissão, absorção e refração.</li>
    <li><b>Cor:</b> a diferença entre luz acromática (escala de cinza) e cromática, e as teorias que explicam como a gente percebe cor (Teoria Tricromática e Teoria de Maxwell), baseadas nos três tipos de cones sensíveis a vermelho, verde e azul.</li>
  </ul>
  <p>Achei interessante que antes de entrar em processamento de imagem em si, a disciplina começa explicando como a gente enxerga naturalmente. Faz sentido, já que pra processar ou criar imagem digital é bom entender primeiro como funciona a visão humana.</p>

  <hr>
</article>

</body>
</html>