
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SaidLabs | Independent Engineering</title>
<style>
:root {
  --bg:#080d18;
  --panel:#111a2b;
  --blue:#38a5ff;
  --text:#edf4ff;
  --muted:#91a2bb;
}
* { box-sizing:border-box; }
body {
  margin:0;
  font-family:Segoe UI,Arial,sans-serif;
  color:var(--text);
  background:radial-gradient(circle at top right,#102b4d,var(--bg) 48%);
  min-height:100vh;
}
header {
  display:flex; justify-content:space-between;
  align-items:center; padding:24px 8%;
  border-bottom:1px solid #26344b;
}
.logo {font-size:25px;font-weight:800;letter-spacing:1px}
.logo span {color:var(--blue)}
nav a {
  color:var(--muted);text-decoration:none;
  margin-left:22px;font-size:14px;
}
nav a:hover {color:var(--blue)}
main {max-width:1050px;margin:auto;padding:90px 24px}
.tag {
  color:var(--blue);font-size:13px;
  letter-spacing:3px;text-transform:uppercase;
}
h1 {font-size:clamp(42px,8vw,76px);margin:18px 0}
h1 span {color:var(--blue)}
.intro {
  color:var(--muted);font-size:19px;
  line-height:1.7;max-width:650px;
}
.actions {display:flex;gap:14px;flex-wrap:wrap;margin:32px 0 65px}
.btn {
  padding:13px 21px;border-radius:8px;
  text-decoration:none;font-weight:700;
  border:1px solid var(--blue);color:var(--blue);
}
.btn.primary {background:var(--blue);color:#06101d}
.section-title {font-size:25px;margin-bottom:22px}
.projects {
  display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:18px;
}
.project {
  background:linear-gradient(145deg,#17243a,#101827);
  border:1px solid #263b59;border-radius:14px;
  padding:25px;transition:.25s;
}
.project:hover {transform:translateY(-5px);border-color:var(--blue)}
.project h3 {margin-top:0}
.project p {color:var(--muted);line-height:1.6}
.project a {color:var(--blue);text-decoration:none}
footer {
  text-align:center;color:var(--muted);
  padding:35px;border-top:1px solid #26344b;
  font-size:13px;
}
@media(max-width:600px) {
  header {padding:20px;align-items:flex-start;gap:15px;flex-direction:column}
  nav a {margin:0 14px 0 0}
  main {padding-top:60px}
}
</style>
</head>
<body>

<header>
  <div class="logo">Said<span>Labs</span></div>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="about">
    <div class="tag">Independent Software Development</div>
    <h1>Build.<br><span>Develop.</span><br>Innovate.</h1>
    <p class="intro">
      Exploring software engineering, AI research and practical
      technology. Building independent projects with a focus on
      responsible engineering and useful solutions.
    </p>
    <div class="actions">
      <a class="btn primary" href="#projects">Explore Projects</a>
      <a class="btn" href="https://github.com/grfzx0-star">GitHub Profile</a>
    </div>
  </section>

  <section id="projects">
    <h2 class="section-title">Featured Projects</h2>
    <div class="projects">
      <article class="project">
        <h3>DriverMasterPro</h3>
        <p>Windows desktop project for local Plug-and-Play device
        inventory and scan history.</p>
        <a href="https://github.com/grfzx0-star/DriverMasterPro">
          View Repository →
        </a>
      </article>

      <article class="project">
        <h3>COLORText AI</h3>
        <p>Research direction covering OCR, text processing,
        Arabic typography, RTL and color analysis.</p>
        <a href="https://github.com/grfzx0-star/COLORText">
          Project Link →
        </a>
      </article>
    </div>
  </section>

  <section id="contact" style="margin-top:65px">
    <h2 class="section-title">Let's Collaborate</h2>
    <p class="intro">
      Interested in AI, open-source engineering or creative
      technology? Explore my work and connect through GitHub.
    </p>
    <a class="btn" href="https://github.com/grfzx0-star">
      Connect on GitHub
    </a>
  </section>
</main>

<footer>
  © 2026 SaidLabs · Independent Engineering · Responsible AI
</footer>

</body>
</html>
