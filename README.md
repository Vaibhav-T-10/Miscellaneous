# HTML_Game.
🕹️ Free HTML Arcade
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Free Fun HTML Games</title>
<style>
  :root{
    --accent:#ff6a00;
    --muted:#bdbdbd;
    --bg:#0f1724;
    --card:#0b1220;
  }
  body{
    margin:0;
    font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    background: linear-gradient(180deg,#071027 0%, #0f1724 100%);
    color:#e6eef8;
    display:flex;
    align-items:center;
    justify-content:center;
    min-height:100vh;
  }
  .hero{
    background:linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.01));
    padding:2rem 2.5rem;
    border-radius:16px;
    box-shadow: 0 8px 30px rgba(2,6,23,0.6);
    max-width:900px;
    width:100%;
  }
  h1{
    margin:0 0 .4rem 0;
    font-size:2rem;
    letter-spacing:0.5px;
    display:flex;
    gap:.6rem;
    align-items:center;
  }
  p.lead{
    margin:0;
    color:var(--muted);
  }
  .badge{
    font-size:.8rem;
    background:rgba(255,255,255,0.06);
    padding:.25rem .6rem;
    border-radius:999px;
    color:var(--accent);
    margin-left:.3rem;
  }
</style>
</head>
<body>
  <section class="hero" role="banner">
    <h1>🎉 Free HTML Games <span class="badge">Beta</span></h1>
    <p class="lead">All games are under testing & improvement — try one and send feedback! 😊</p>
  </section>
</body>
</html>
