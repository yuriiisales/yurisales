<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yuri Vitor | Dev</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background: linear-gradient(270deg, #0f172a, #1e293b, #020617);
  background-size: 600% 600%;
  animation: bgAnimation 10s ease infinite;
  color: #fff;
}

@keyframes bgAnimation {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 40px 20px;
}

header {
  text-align: center;
  margin-bottom: 50px;
  animation: fadeDown 1s ease;
}

header h1 {
  font-size: 2.8rem;
  color: #38bdf8;
}

header p {
  color: #cbd5f5;
  margin-top: 10px;
}

.section {
  margin-bottom: 30px;
  padding: 25px;
  border-radius: 15px;
  background: rgba(255,255,255,0.05);
  backdrop-filter: blur(12px);
  box-shadow: 0 10px 30px rgba(0,0,0,0.4);
  animation: fadeUp 1s ease;
}

.section:hover {
  transform: translateY(-5px);
  transition: 0.3s;
}

h2 {
  color: #38bdf8;
  margin-bottom: 15px;
}

ul {
  margin-left: 20px;
}

li {
  margin-bottom: 6px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
}

.card {
  padding: 15px;
  border-radius: 10px;
  background: rgba(0,0,0,0.3);
  text-align: center;
  transition: 0.3s;
}

.card:hover {
  background: #38bdf8;
  color: #000;
  transform: scale(1.05);
}

.stats img {
  width: 100%;
  margin-top: 10px;
  border-radius: 10px;
}

.highlight {
  font-size: 1.2rem;
  color: #38bdf8;
  text-align: center;
  margin-top: 10px;
}

/* animações */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes fadeDown {
  from { opacity: 0; transform: translateY(-30px); }
  to { opacity: 1; transform: translateY(0); }
}

footer {
  text-align: center;
  margin-top: 40px;
  color: #94a3b8;
}
</style>
</head>

<body>

<div class="container">

<header>
  <h1>👋 Yuri Vitor</h1>
  <p>💻 Desenvolvedor | 🚀 Evolução constante | 🔥 Treinar e aprender sempre</p>
</header>

<div class="section">
  <h2>🧠 Sobre mim</h2>
  <ul>
    <li>🔭 Projetos pessoais e evolução constante</li>
    <li>🌱 Desenvolvimento web</li>
    <li>⚡ Backend, Frontend e automações</li>
    <li>🎯 Foco em prática e crescimento</li>
  </ul>
</div>

<div class="section">
  <h2>🛠️ Tecnologias</h2>
  <div class="grid">
    <div class="card">JavaScript</div>
    <div class="card">PHP</div>
    <div class="card">C / C++</div>
    <div class="card">Node.js</div>
    <div class="card">HTML</div>
    <div class="card">CSS</div>
    <div class="card">MySQL</div>
    <div class="card">Docker</div>
  </div>
</div>

<div class="section stats">
  <h2>📊 GitHub Stats</h2>
  <img src="https://github-readme-stats.vercel.app/api?username=yuriiisales&show_icons=true&theme=tokyonight">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yuriiisales&layout=compact&theme=tokyonight">
</div>

<div class="section stats">
  <h2>🔥 Streak</h2>
  <img src="https://streak-stats.demolab.com?user=yuriiisales&theme=tokyonight">
</div>

<div class="section">
  <h2>📌 Projetos</h2>
  <p>🚧 Em construção...</p>
</div>

<div class="section">
  <h2>📫 Contato</h2>
  <p>Email: seuemail@email.com</p>
</div>

<div class="section">
  <h2>⚡ Mentalidade</h2>
  <p class="highlight">Treinar e aprender sempre, até o conhecimento nunca faltar.</p>
</div>

<footer>
  ⭐ Se curtir, deixa uma estrela nos repositórios
</footer>

</div>

</body>
</html>
