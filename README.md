!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bem-vindo à Adaptplay, onde você encontra diversão e entretenimento de qualidade.">
    <title>Empresa de Jogos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Cabeçalho com navegação  -->
    <header>
        <h1>ADAPTPLAY</h1>

        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#about">Sobre Nós</a></li>
                <li><a href="#games">Jogos</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Seção principal com conteúdo principal -->
    <main>
        <!-- Seção de introdução -->
        <section id="home">
            <h2>Bem-vindo à Adaptplay</h2>
            <p>Explore nosso jogo e divirta-se com as melhores experiências de entretenimento digital.</p>
        </section>

        <!-- Seção sobre a empresa -->
        <section id="about">
            <h2>Sobre Nós</h2>
            <p>Somos uma empresa dedicada a criar jogos acessiveis para PCD. São jogos educativos que proporcionam diversão para todos. Nossa missão é levar alegria e aventura para nossos jogadores especiais.</p>
        </section>

    

        <!-- Seção de contato -->
        <section id="contact">
            <h2>Contato</h2>
            <p>Tem alguma dúvida ou deseja falar conosco? Envie uma mensagem pelo formulário abaixo:</p>
            <form action="mailto:contato@empresaexemplo.com" method="post" enctype="text/plain">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Empresa de Jogos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>



/* styles.css */

/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilo do body */
body {
    font-family: Arial, sans-serif;
    color: #FFD700; /* Amarelo dourado */
    background-color: #000000; /* Preto */
    line-height: 1.6;
}

/* Cabeçalho */
header {
    background-color: #111111; /* Preto mais claro */
    padding: 1rem;
    text-align: center;
}

header h1 {
    color: #FFD700; /* Amarelo */
}

nav ul {
    list-style-type: none;
    margin-top: 0.5rem;
}

nav ul li {
    display: inline;
    margin-right: 1rem;
}

nav ul li a {
    color: #FFD700;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #ffffff; /* Branco para destaque */
}

/* Seção principal */
main {
    padding: 2rem;
}

section {
    margin-bottom: 2rem;
}

h2 {
    color: #FFD700; /* Amarelo */
    border-bottom: 2px solid #FFD700;
    padding-bottom: 0.5rem;
    margin-bottom: 1rem;
}

p {
    color: #ffffff;
}

/* Estilo dos jogos em destaque */
.game-list {
    display: flex;
    gap: 1rem;
}

.game {
    background-color: #222222; /* Cinza escuro para contraste */
    padding: 1rem;
    border-radius: 5px;
    color: #FFD700;
}

.game h3 {
    color: #FFD700; /* Amarelo */
}

.game p {
    color: #ffffff; /* Branco */
}

/* Formulário de contato */
form {
    background-color: #222222;
    padding: 1.5rem;
    border-radius: 5px;
    color: #FFD700;
}

form label {
    color: #FFD700;
    font-weight: bold;
}

form input, form textarea {
    width: 100%;
    padding: 0.5rem;
    margin-top: 0.5rem;
    margin-bottom: 1rem;
    border: 1px solid #FFD700;
    border-radius: 5px;
    background-color: #111111;
    color: #FFD700;
}

form button {
    background-color: #FFD700;
    color: #000000;
    padding: 0.7rem 1.5rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
}

form button:hover {
    background-color: #e6c200; /* Amarelo um pouco mais escuro */
}

/* Rodapé */
footer {
    background-color: #111111;
    color: #FFD700;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}

