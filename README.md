# Do-campo-a-cidade-como-chega-o-alimento
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Do Campo à Cidade: Como Chega o Alimento</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <div class="container">
        <h1>Do Campo à Cidade</h1>
        <p>Como Chega o Alimento na Sua Mesa?</p>
    </div>
</header>

<nav>
    <ul>
        <li><a href="#campo">Do Campo</a></li>
        <li><a href="#logistica">Logística</a></li>
        <li><a href="#processamento">Processamento</a></li>
        <li><a href="#consumo">Consumo</a></li>
        <li><a href="#curiosidades">Curiosidades</a></li>
        <li><a href="#contato">Contato</a></li>
    </ul>
</nav>

<main>

    <section id="campo">
        <div class="section-header">
            <h2>Como Tudo Começa: A Produção no Campo</h2>
        </div>
        <div class="content">
            <p>O alimento começa sua jornada no campo. Agricultores plantam e colhem os produtos em grandes áreas, utilizando tecnologias modernas e práticas sustentáveis para garantir uma produção eficiente.</p>
            <img src="campo.jpg" alt="Produção no Campo">
        </div>
    </section>

    <section id="logistica">
        <div class="section-header">
            <h2>Transporte e Logística</h2>
        </div>
        <div class="content">
            <p>Após a colheita, os alimentos são transportados para centros de distribuição. Caminhões, trens e até barcos fazem esse trajeto, garantindo que os alimentos cheguem às grandes cidades de forma segura e rápida.</p>
            <img src="logistica.jpg" alt="Transporte de Alimentos">
        </div>
    </section>

    <section id="processamento">
        <div class="section-header">
            <h2>Processamento dos Alimentos</h2>
        </div>
        <div class="content">
            <p>Após a chegada nas indústrias, os alimentos são processados. Aqui, eles passam por etapas de limpeza, embalagem e conservação, como congelamento, enlatamento ou até mesmo a produção de alimentos prontos para o consumo.</p>
            <img src="processamento.jpg" alt="Processamento de Alimentos">
        </div>
    </section>

    <section id="consumo">
        <div class="section-header">
            <h2>Consumo na Cidade</h2>
        </div>
        <div class="content">
            <p>Depois de processados, os alimentos chegam ao mercado ou supermercado. É lá que você faz suas compras e leva os alimentos para casa, pronto para prepará-los e consumir!</p>
            <img src="consumo.jpg" alt="Consumo de Alimentos">
        </div>
    </section>

    <section id="curiosidades">
        <div class="section-header">
            <h2>Curiosidades sobre o Alimento</h2>
        </div>
        <div class="content">
            <ul>
                <li>Você sabia que mais de 30% dos alimentos produzidos são desperdiçados no mundo?</li>
                <li>A agricultura no Brasil responde por 23% do PIB nacional.</li>
                <li>O transporte de alimentos pode durar até 7 dias, dependendo da distância.</li>
            </ul>
        </div>
    </section>

    <section id="contato">
        <div class="section-header">
            <h2>Fale Conosco</h2>
        </div>
        <div class="content">
            <form action="#" method="POST">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

</main>

<footer>
    <p>&copy; 2025 Do Campo à Cidade | Todos os direitos reservados.</p>
</footer>

</body>
</html>
/* Reset de Estilos */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    text-align: center;
    padding: 20px;
}

header {
    background-color: #3e8e41;
    color: white;
    padding: 30px 0;
}

header h1 {
    font-size: 3em;
}

header p {
    font-size: 1.2em;
}

nav {
    background-color: #333;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 10px 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.1em;
}

nav ul li a:hover {
    text-decoration: underline;
}

main {
    padding: 30px 20px;
}

.section-header {
    text-align: center;
    margin-bottom: 20px;
}

section {
    margin-bottom: 40px;
}

section img {
    width: 100%;
    max-width: 600px;
    display: block;
    margin: 20px auto;
}

section .content {
    text-align: center;
    font-size: 1.1em;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
}

form label {
    margin: 10px 0 5px;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
}

form button {
    background-color: #3e8e41;
    color: white;
    border: none;
    padding: 10px;
    font-size: 1.1em;
    cursor: pointer;
}

form button:hover {
    background-color: #2d6b2a;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
