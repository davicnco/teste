<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Frilancei — serviços freelance, portfólio e contato." />
  <title>Frilancei — Seu freelancer de confiança</title>

  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#06b6d4;--muted:#94a3b8;--txt:#e6eef6}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter, system-ui, Arial, sans-serif;background:linear-gradient(180deg,#071023 0%, #071836 100%);color:var(--txt);-webkit-font-smoothing:antialiased}

    header{display:flex;align-items:center;justify-content:space-between;padding:18px 24px;max-width:1100px;margin:0 auto}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:44px;height:44px;border-radius:8px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:700}
    nav a{color:var(--txt);text-decoration:none;margin-left:18px;font-weight:600}

    .hero{max-width:1100px;margin:36px auto;padding:28px;display:grid;grid-template-columns:1fr 360px;gap:28px;align-items:center}
    .card{background:rgba(255,255,255,0.03);padding:24px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    h1{font-size:28px;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0 0 16px}

    .cta{display:inline-block;padding:10px 16px;border-radius:10px;background:var(--accent);color:#042028;text-decoration:none;font-weight:700}

    .services{display:flex;flex-direction:column;gap:12px}
    .service{display:flex;gap:12px;align-items:flex-start}
    .dot{width:44px;height:44px;border-radius:8px;background:rgba(255,255,255,0.04);display:flex;align-items:center;justify-content:center;font-weight:700}

    .aside{display:flex;flex-direction:column;gap:12px}
    .profile{display:flex;gap:12px;align-items:center}
    .avatar{width:72px;height:72px;border-radius:12px;background:linear-gradient(135deg,#7c3aed,#06b6d4);display:flex;align-items:center;justify-content:center;font-weight:800}

    main{max-width:1100px;margin:18px auto;padding:0 24px}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .portfolio-item{background:var(--card);padding:14px;border-radius:10px}

    footer{max-width:1100px;margin:36px auto;padding:18px 24px;color:var(--muted);text-align:center}

    form{display:flex;flex-direction:column;gap:10px}
    input,textarea{padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.06);background:transparent;color:var(--txt);min-width:0}
    button{padding:10px;border-radius:8px;border:0;background:var(--accent);font-weight:700}

    @media(max-width:880px){
      .hero{grid-template-columns:1fr}
      .grid{grid-template-columns:repeat(2,1fr)}
    }
    @media(max-width:520px){
      .grid{grid-template-columns:1fr}
      nav{display:none}
    }
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo">F</div>
      <div>
        <div style="font-weight:800">Frilancei</div>
        <div style="font-size:12px;color:var(--muted)">Freelance — qualidade e comprometimento</div>
      </div>
    </div>

    <nav>
      <a href="#servicos">Serviços</a>
      <a href="#portfolio">Portfólio</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <div class="card">
      <h1>Precisa de um freelancer confiável?</h1>
      <p class="lead">Design, desenvolvimento web e consultoria digital. Entregas pontuais, comunicação clara e qualidade no resultado.</p>
      <div class="services">
        <div class="service"><div class="dot">D</div><div><strong>Desenvolvimento Web</strong><div style="color:var(--muted);font-size:13px">Sites rápidos e responsivos (HTML/CSS/JS)</div></div></div>
        <div class="service"><div class="dot">U</div><div><strong>UI / UX</strong><div style="color:var(--muted);font-size:13px">Interfaces modernas e usáveis</div></div></div>
        <div class="service"><div class="dot">C</div><div><strong>Consultoria</strong><div style="color:var(--muted);font-size:13px">Orientação para seu projeto digital</div></div></div>
      </div>
      <div style="margin-top:16px">
        <a class="cta" href="#contato">Peça um orçamento</a>
      </div>
    </div>

    <aside class="aside card">
      <div class="profile">
        <div class="avatar">FC</div>
        <div>
          <div style="font-weight:700">Frilancei</div>
          <div style="color:var(--muted);font-size:13px">Desenvolvedor & Designer</div>
        </div>
      </div>

      <div style="margin-top:8px;color:var(--muted);font-size:14px">Especialidades:</div>
      <ul style="color:var(--muted);margin:8px 0 0 18px;font-size:14px">
        <li>HTML / CSS / JavaScript</li>
        <li>Sites estáticos & GitHub Pages</li>
        <li>Performance & SEO básico</li>
      </ul>

      <div style="margin-top:12px">
        <a class="cta" href="#portfolio">Ver portfólio</a>
      </div>
    </aside>
  </section>

  <main>
    <section id="servicos" class="card" style="margin-bottom:18px">
      <h2>Serviços</h2>
      <p style="color:var(--muted)">Projetos por hora ou por escopo. Entrega com revisão e suporte inicial.</p>
      <div style="display:flex;gap:12px;margin-top:12px;flex-wrap:wrap">
        <div style="padding:12px;background:rgba(255,255,255,0.02);border-radius:8px">Landing pages</div>
        <div style="padding:12px;background:rgba(255,255,255,0.02);border-radius:8px">Sites institucionais</div>
        <div style="padding:12px;background:rgba(255,255,255,0.02);border-radius:8px">Portfólios</div>
        <div style="padding:12px;background:rgba(255,255,255,0.02);border-radius:8px">SEO básico</div>
      </div>
    </section>

    <section id="portfolio">
      <h2 style="margin-bottom:12px">Portfólio</h2>
      <div class="grid">
        <div class="portfolio-item">Projeto A — Landing</div>
        <div class="portfolio-item">Projeto B — Site</div>
        <div class="portfolio-item">Projeto C — Redesign</div>
        <div class="portfolio-item">Projeto D — E-commerce (mock)</div>
        <div class="portfolio-item">Projeto E — App Web</div>
        <div class="portfolio-item">Projeto F — Blog</div>
      </div>
    </section>

    <section id="contato" class="card" style="margin-top:18px">
      <h2>Contato</h2>
      <form id="formContato">
        <input type="text" id="nome" placeholder="Seu nome" required />
        <input type="email" id="email" placeholder="Seu e‑mail" required />
        <textarea id="mensagem" rows="4" placeholder="Mensagem" required></textarea>
        <button type="submit">Enviar mensagem</button>
      </form>
    </section>
  </main>

  <footer>
    © 2025 Frilancei — Feito com atenção. — <span style="color:var(--muted)">github: seu-usuario</span>
  </footer>

  <script>
    document.getElementById('formContato').addEventListener('submit', function(e){
      e.preventDefault();
      const nome = document.getElementById('nome').value.trim();
      alert('Obrigado, '+(nome||'amigo')+'! Mensagem recebida.');
      this.reset();
    });

    // Navegação suave para anchors
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', function(ev){
        ev.preventDefault();
        const id = this.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if(el) el.scrollIntoView({behavior:'smooth',block:'start'});
      });
    });
  </script>
</body>
</html>
