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
