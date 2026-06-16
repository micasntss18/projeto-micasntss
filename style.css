/* ===== RESET & VARIÁVEIS ===== */
* { margin: 0; padding: 0; box-sizing: border-box; }

:root {
    /* Paleta de cores — altere aqui para mudar todo o site */
    --cor-primaria: #00e5ff;
    --cor-secundaria: #7b2fff;
    --cor-fundo: #0f172a;
    --cor-card: #1e293b;
    --cor-texto: #e2e8f0;
    --cor-texto-suave: #64748b;
}

body {
    font-family: 'Poppins', sans-serif;
    background: var(--cor-fundo);
    color: var(--cor-texto);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 24px;
}

/* ===== NAVBAR ===== */
.navbar {
    position: fixed;
    top: 0; left: 0; right: 0;
    background: rgba(15,23,42,0.9);
    backdrop-filter: blur(10px);
    padding: 16px 0;
    z-index: 100;
}
.navbar .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.logo { color: var(--cor-primaria); font-weight: 700; font-size: 20px; }
.nav-links { display: flex; list-style: none; gap: 32px; }
.nav-links a { color: var(--cor-texto-suave); text-decoration: none; transition: 0.2s; }
.nav-links a:hover { color: var(--cor-primaria); }

/* ===== BANNER ===== */
.banner {
    min-height: 100vh;
    display: flex;
    align-items: center;
    background: linear-gradient(135deg, #0f172a, #1e293b);
    text-align: center;
    padding-top: 80px;
}
.banner h1 { font-size: 52px; font-weight: 800; line-height: 1.2; margin-bottom: 20px; }
.banner p  { font-size: 18px; color: var(--cor-texto-suave); margin-bottom: 40px; }
.banner-btns { display: flex; gap: 16px; justify-content: center; }

/* ===== BOTÕES ===== */
.btn-primary, .btn-secondary, .btn-cta {
    padding: 14px 32px; border-radius: 8px;
    font-weight: 700; cursor: pointer;
    transition: 0.3s; border: none; font-size: 15px;
}
.btn-primary { background: var(--cor-primaria); color: #000; }
.btn-primary:hover { transform: translateY(-3px); box-shadow: 0 12px 32px rgba(0,229,255,0.3); }
.btn-secondary { background: transparent; border: 2px solid var(--cor-primaria); color: var(--cor-primaria); }

/* ===== CARDS ===== */
.cards-grid { display: flex; gap: 24px; flex-wrap: wrap; justify-content: center; }
.card {
    background: var(--cor-card); border-radius: 16px;
    padding: 32px; text-align: center;
    flex: 1; min-width: 240px; max-width: 300px;
    transition: 0.3s;
}
.card:hover { transform: translateY(-8px); box-shadow: 0 20px 40px rgba(0,0,0,0.4); }

/* ===== VÍDEO RESPONSIVO ===== */
.video-wrapper { position: relative; padding-bottom: 56.25%; height: 0; }
.video-wrapper iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px; }

/* ===== RESPONSIVIDADE ===== */
@media (max-width: 768px) {
    .banner h1 { font-size: 32px; }
    .nav-links { display: none; }
    .nav-links.aberto { display: flex; flex-direction: column; }
    .banner-btns { flex-direction: column; align-items: center; }
}
