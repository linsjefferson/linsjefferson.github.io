<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Jefferson Lins | Fotografia</title>

<style>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #0a0a0a;
    color: #fff;
    font-family: Arial, Helvetica, sans-serif;
}

/* MENU */

nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 22px 6%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 1000;

    background: rgba(0,0,0,0.55);
    backdrop-filter: blur(12px);
}

.logo {
    font-size: 20px;
    font-weight: bold;
    letter-spacing: 3px;
}

nav ul {
    display: flex;
    gap: 30px;
    list-style: none;
}

nav a {
    color: white;
    text-decoration: none;
    font-size: 13px;
    letter-spacing: 1px;
    transition: 0.3s;
}

nav a:hover {
    color: #aaa;
}

/* HERO */

.hero {
    min-height: 100vh;

    display: flex;
    align-items: center;
    justify-content: center;

    text-align: center;

    padding: 30px;

    background:
    linear-gradient(
        rgba(0,0,0,0.45),
        rgba(0,0,0,0.85)
    ),
    url("https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=1800&q=90");

    background-size: cover;
    background-position: center;
}

.hero-content {
    max-width: 850px;
}

.hero small {
    letter-spacing: 5px;
    color: #bbb;
}

.hero h1 {
    font-size: clamp(55px, 9vw, 120px);
    line-height: 0.9;
    margin: 25px 0;
    letter-spacing: -4px;
}

.hero p {
    color: #ccc;
    font-size: 18px;
    margin-bottom: 35px;
}

.botao {
    display: inline-block;

    padding: 14px 30px;

    border: 1px solid white;

    color: white;
    text-decoration: none;

    font-size: 13px;
    letter-spacing: 2px;

    transition: 0.3s;
}

.botao:hover {
    background: white;
    color: black;
}

/* SEÇÕES */

section {
    padding: 120px 7%;
}

.titulo {
    text-align: center;
    margin-bottom: 70px;
}

.titulo span {
    display: block;
    color: #888;
    font-size: 12px;
    letter-spacing: 4px;
    margin-bottom: 15px;
}

.titulo h2 {
    font-size: clamp(35px, 5vw, 60px);
    letter-spacing: -2px;
}

/* SOBRE */

.sobre {
    max-width: 850px;
    margin: auto;
    text-align: center;
}

.sobre p {
    font-size: 20px;
    line-height: 1.8;
    color: #bbb;
}

/* CATEGORIAS */

.categorias {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 18px;
}

.categoria {
    min-height: 350px;

    display: flex;
    align-items: flex-end;

    padding: 35px;

    position: relative;

    overflow: hidden;

    background-size: cover;
    background-position: center;

    transition: 0.4s;
}

.categoria::after {
    content: "";

    position: absolute;

    inset: 0;

    background: linear-gradient(
        transparent,
        rgba(0,0,0,0.9)
    );
}

.categoria:hover {
    transform: scale(1.015);
}

.categoria h3 {
    position: relative;
    z-index: 2;

    font-size: 32px;
}

/* IMAGENS TEMPORÁRIAS */

.ensaios {
    background-image:
    url("https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=1200&q=90");
}

.shows {
    background-image:
    url("https://images.unsplash.com/photo-1501386761578-eac5c94b800a?auto=format&fit=crop&w=1200&q=90");
}

.baladas {
    background-image:
    url("https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=1200&q=90");
}

.bares {
    background-image:
    url("https://images.unsplash.com/photo-1514933651103-005eec06c04b?auto=format&fit=crop&w=1200&q=90");
}

/* CONTATO */

.contato {
    background: #111;
    text-align: center;
}

.contato p {
    color: #aaa;
    font-size: 18px;
    margin-bottom: 35px;
}

.contato-links {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
}

/* FOOTER */

footer {
    padding: 35px;
    text-align: center;

    color: #666;

    font-size: 12px;
    letter-spacing: 1px;
}

/* CELULAR */

@media (max-width: 700px) {

    nav {
        padding: 18px 5%;
    }

    nav ul {
        gap: 12px;
    }

    nav a {
        font-size: 10px;
    }

    .hero h1 {
        letter-spacing: -2px;
    }

    section {
        padding: 90px 5%;
    }

    .categorias {
        grid-template-columns: 1fr;
    }

    .categoria {
        min-height: 280px;
    }

}

</style>
</head>

<body>

<!-- MENU -->

<nav>

<div class="logo">
JL
</div>

<ul>

<li>
<a href="#sobre">SOBRE</a>
</li>

<li>
<a href="#trabalho">TRABALHO</a>
</li>

<li>
<a href="#contato">CONTATO</a>
</li>

</ul>

</nav>


<!-- HERO -->

<header class="hero">

<div class="hero-content">

<small>FOTOGRAFIA • FLORIANÓPOLIS</small>

<h1>
JEFFERSON<br>
LINS
</h1>

<p>
Fotografia que transforma momentos em histórias.
</p>

<a href="#trabalho" class="botao">
VER MEU TRABALHO
</a>

</div>

</header>


<!-- SOBRE -->

<section id="sobre">

<div class="titulo">

<span>QUEM SOU</span>

<h2>Sobre mim</h2>

</div>

<div class="sobre">

<p>

Sou Jefferson Lins, fotógrafo apaixonado por pessoas,
momentos e histórias.

Meu trabalho busca capturar aquilo que acontece
naturalmente — seja em um ensaio, no meio de um show,
na energia de uma balada ou na atmosfera de um bar.

Mais do que registrar uma imagem,
quero criar fotografias que façam você lembrar
do momento.

</p>

</div>

</section>


<!-- TRABALHO -->

<section id="trabalho">

<div class="titulo">

<span>PORTFÓLIO</span>

<h2>Meu trabalho</h2>

</div>


<div class="categorias">


<div class="categoria ensaios">

<h3>
Ensaios femininos
</h3>

</div>


<div class="categoria shows">

<h3>
Shows
</h3>

</div>


<div class="categoria baladas">

<h3>
Baladas
</h3>

</div>


<div class="categoria bares">

<h3>
Bares
</h3>

</div>


</div>

</section>


<!-- CONTATO -->

<section id="contato" class="contato">

<div class="titulo">

<span>VAMOS TRABALHAR JUNTOS?</span>

<h2>Entre em contato</h2>

</div>

<p>
Quer fazer um ensaio ou contratar meu trabalho?
</p>


<div class="contato-links">

<a
href="https://instagram.com/linsjefferson"
class="botao"
target="_blank"
>
INSTAGRAM
</a>


<a
href="https://wa.me/5500000000000"
class="botao"
target="_blank"
>
WHATSAPP
</a>

</div>

</section>


<footer>

© 2026 Jefferson Lins — Fotografia

</footer>

</body>
</html>
