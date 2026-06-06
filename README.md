<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dyma | Tech Founder</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#0a0a0a;
    color:#fff;
    min-height:100vh;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:60px 0;
}

.hero{
    text-align:center;
    margin-bottom:60px;
}

.hero h1{
    font-size:4rem;
    background:linear-gradient(90deg,#00e5ff,#4f46e5);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.hero p{
    color:#aaa;
    max-width:800px;
    margin:20px auto;
    line-height:1.8;
}

.card{
    background:rgba(255,255,255,0.04);
    border:1px solid rgba(255,255,255,0.08);
    border-radius:24px;
    padding:35px;
    backdrop-filter:blur(20px);
    transition:0.4s;
}

.card:hover{
    transform:translateY(-5px);
    border-color:#00e5ff;
}

.section-title{
    font-size:2rem;
    margin-bottom:25px;
    color:#00e5ff;
}

.companies{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.company{
    background:#111;
    border-radius:16px;
    padding:20px;
    border:1px solid #222;
}

.company h3{
    margin-bottom:10px;
}

.company p{
    color:#999;
    font-size:.9rem;
}

.tech-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:15px;
    margin-top:20px;
}

.tech{
    background:#111;
    padding:15px;
    text-align:center;
    border-radius:12px;
    border:1px solid #222;
    transition:.3s;
}

.tech:hover{
    background:#161616;
    border-color:#00e5ff;
}

.stats{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
    margin-top:30px;
}

.stat{
    text-align:center;
}

.stat h2{
    color:#00e5ff;
    font-size:2rem;
}

.stat p{
    color:#aaa;
}

.footer{
    text-align:center;
    margin-top:60px;
    color:#666;
}

.glow{
    position:fixed;
    width:500px;
    height:500px;
    background:#00e5ff20;
    filter:blur(150px);
    border-radius:50%;
    top:-100px;
    right:-100px;
    z-index:-1;
}
</style>
</head>
<body>

<div class="glow"></div>

<div class="container">

    <section class="hero">
        <h1>DYMA</h1>
        <p>
            Cambodian Tech Founder & Entrepreneur building AI systems,
            SaaS platforms, software solutions, and digital business tools.
        </p>

        <div class="stats">
            <div class="stat">
                <h2>6</h2>
                <p>Companies Founded</p>
            </div>

            <div class="stat">
                <h2>20+</h2>
                <p>Technologies</p>
            </div>

            <div class="stat">
                <h2>∞</h2>
                <p>Innovation</p>
            </div>
        </div>
    </section>

    <div class="card">
        <h2 class="section-title">🚀 Founder Of</h2>

        <div class="companies">

            <div class="company">
                <h3>Angkor Apsara Tech</h3>
                <p>Software, SaaS, AI and digital solutions company.</p>
            </div>

            <div class="company">
                <h3>Angkor Apsara Tech Equipment</h3>
                <p>Technology and power equipment solutions.</p>
            </div>

            <div class="company">
                <h3>Soriya Shop</h3>
                <p>Commerce and retail technology platform.</p>
            </div>

            <div class="company">
                <h3>Apex Kinetic</h3>
                <p>Advanced technologies, drones and innovation.</p>
            </div>

            <div class="company">
                <h3>Krou AI Studio</h3>
                <p>AI-powered creative and technology studio.</p>
            </div>

            <div class="company">
                <h3>Vattana Meta</h3>
                <p>Business automation and social engagement tools.</p>
            </div>

        </div>
    </div>

    <br><br>

    <div class="card">
        <h2 class="section-title">💻 Tech Stack</h2>

        <div class="tech-grid">

            <div class="tech">Python</div>
            <div class="tech">PHP</div>
            <div class="tech">TypeScript</div>
            <div class="tech">JavaScript</div>
            <div class="tech">Java</div>
            <div class="tech">C++</div>
            <div class="tech">Rust</div>
            <div class="tech">Laravel</div>
            <div class="tech">FastAPI</div>
            <div class="tech">Node.js</div>
            <div class="tech">Vue.js</div>
            <div class="tech">MySQL</div>
            <div class="tech">MongoDB</div>
            <div class="tech">Firebase</div>
            <div class="tech">AWS</div>
            <div class="tech">Cloudflare</div>
            <div class="tech">Vercel</div>
            <div class="tech">Apache</div>
            <div class="tech">Nginx</div>
            <div class="tech">Figma</div>
            <div class="tech">Canva</div>
            <div class="tech">Framer</div>

        </div>
    </div>

    <div class="footer">
        © 2026 Dyma • Founder • Developer • Entrepreneur
    </div>

</div>

<script>
document.addEventListener("mousemove", (e) => {
    const glow = document.querySelector(".glow");

    glow.animate({
        left: `${e.clientX - 250}px`,
        top: `${e.clientY - 250}px`
    }, {
        duration: 1500,
        fill: "forwards"
    });
});
</script>

</body>
</html>
