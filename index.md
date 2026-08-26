<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Computação Visual — Henrique Jean</title>
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
    --accent-dim: #8a742a;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:'Inter',sans-serif;
    line-height:1.5;
  }
  a{color:inherit;text-decoration:none;}
  header{
    display:flex;justify-content:space-between;align-items:center;
    padding:28px 6vw;border-bottom:1px solid var(--panel-border);
  }
  .brand{display:flex;align-items:center;gap:10px;font-weight:600;letter-spacing:0.02em;}
  .brand .mark{
    width:14px;height:14px;background:var(--accent);
    transform:rotate(45deg);
  }
  nav a{font-size:14px;color:var(--text-dim);margin-left:28px;transition:color .2s;}
  nav a:hover, nav a:focus-visible{color:var(--accent);}

  .hero{padding:100px 6vw 60px;max-width:900px;}
  .eyebrow{
    color:var(--accent);font-size:12px;letter-spacing:0.16em;
    text-transform:uppercase;font-weight:600;margin-bottom:18px;
  }
  h1{
    font-family:'Fraunces',serif;font-weight:500;
    font-size:clamp(2.6rem, 6vw, 4.6rem);
    line-height:1.02;letter-spacing:-0.01em;
  }
  h1 span{color:var(--accent);font-style:italic;}
  .meta{
    margin-top:28px;color:var(--text-dim);font-size:14px;
    display:flex;gap:22px;flex-wrap:wrap;
  }
  .meta b{color:var(--text);font-weight:500;}

  .divider{
    height:1px;background:var(--panel-border);margin:0 6vw;
  }

  main{padding:60px 6vw 100px;}
  .grid{
    display:grid;grid-template-columns:repeat(auto-fill, minmax(260px, 1fr));
    gap:1px;background:var(--panel-border);
    border:1px solid var(--panel-border);
  }
  .card{
    background:var(--panel);padding:32px 28px;min-height:220px;
    display:flex;flex-direction:column;justify-content:space-between;
    transition:background .2s;
  }
  .card.active{cursor:pointer;}
  .card.active:hover, .card.active:focus-visible{background:#1d1a12;}
  .card-num{font-size:12px;color:var(--text-dim);letter-spacing:0.1em;}
  .card-title{
    font-family:'Fraunces',serif;font-size:1.3rem;font-weight:500;
    margin-top:14px;color:var(--text);
  }
  .card.locked .card-title{color:var(--text-dim);}
  .card-foot{
    margin-top:24px;font-size:12px;color:var(--text-dim);
    display:flex;justify-content:space-between;align-items:center;
  }
  .tag{
    font-size:11px;padding:4px 10px;border:1px solid var(--panel-border);
    color:var(--text-dim);letter-spacing:0.05em;
  }
  .tag.active{border-color:var(--accent);color:var(--accent);}

  footer{
    padding:40px 6vw;color:var(--text-dim);font-size:13px;
    border-top:1px solid var(--panel-border);
  }
</style>
</head>
<body>

<header>
  <div class="brand"><span class="mark"></span> COMPVIS</div>
  <nav>
    <a href="index.html">Início</a>
    <a href="https://github.com/jeam122323/ComputacaoVisual-10277156" target="_blank">Repositório</a>
  </nav>
</header>

<section class="hero">
  <div class="eyebrow">Blog · Computação Visual</div>
  <h1>Computação <span>Visual</span></h1>
  <div class="meta">
    <span><b>Henrique Jean</b></span>
    <span>2026.2</span>
    <span>1 post publicado</span>
  </div>
</section>

<div class="divider"></div>

<main>
  <div class="grid">
    <a href="01-o-que-eu-esperava.html" class="card active">
      <div>
        <div class="card-num">01</div>
        <div class="card-title">O que eu esperava da disciplina?</div>
      </div>
      <div class="card-foot">
        <span>18/08/2026</span>
        <span class="tag active">Ler post</span>
      </div>
    </a>

    <div class="card locked">
      <div>
        <div class="card-num">02</div>
        <div class="card-title">Em construção</div>
      </div>
      <div class="card-foot">
        <span>Em breve</span>
        <span class="tag">Aguardando</span>
      </div>
    </div>

    <div class="card locked">
      <div>
        <div class="card-num">03</div>
        <div class="card-title">Em construção</div>
      </div>
      <div class="card-foot">
        <span>Em breve</span>
        <span class="tag">Aguardando</span>
      </div>
    </div>
  </div>
</main>

<footer>
  Blog pessoal da disciplina de Computação Visual — construído com GitHub Pages.
</footer>

</body>
</html>