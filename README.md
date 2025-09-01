## Hi there 👋

<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Currículo Online - [Seu Nome]</title>
    <style>
/* Estilo geral */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Container principal */
.container {
    max-width: 900px;
    margin: auto;
    background: #fff;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Cabeçalho e navegação */
header {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
}

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #fff;
}

header h1 {
    margin: 10px 0 5px;
}

header p.job-title {
    margin: 0;
    font-size: 1.2em;
    color: #ccc;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #4CAF50;
}

/* Seções do currículo */
main {
    padding: 20px;
}

.section {
    margin-bottom: 30px;
    padding: 20px;
    background-color: #fff;
    border-left: 5px solid #4CAF50;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.section h2 {
    color: #4CAF50;
    border-bottom: 2px solid #eee;
    padding-bottom: 5px;
}

.item {
    margin-bottom: 20px;
}

.item h3 {
    margin: 0;
    color: #555;
}

.company, .university {
    margin: 5px 0;
    font-style: italic;
    color: #777;
}

.skills-list {
    list-style: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.skills-list li {
    background-color: #4CAF50;
    color: #fff;
    padding: 5px 10px;
    border-radius: 5px;
    font-size: 0.9em;
}

/* Rodapé */
footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: #fff;
    margin-top: 20px;
}

footer a {
    color: #4CAF50;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}

/* Responsividade básica */
@media (max-width: 600px) {
    nav ul {
        flex-direction: column;
        align-items: center;
    }
}
        
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <img src="https://via.placeholder.com/150" alt="Foto de Perfil" class="profile-pic">
            <h1>[Seu Nome Completo]</h1>
            <p class="job-title">[Sua Posição/Área de Atuação]</p>
        </div>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre Mim</a></li>
                <li><a href="#experiencia">Experiência</a></li>
                <li><a href="#formacao">Formação</a></li>
                <li><a href="#habilidades">Habilidades</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="sobre" class="section">
            <h2>Sobre Mim</h2>
            <p>[Escreva um breve parágrafo sobre você, suas paixões, objetivos e o que você busca na carreira.]</p>
        </section>

        <section id="experiencia" class="section">
            <h2>Experiência Profissional</h2>
            <div class="item">
                <h3>[Cargo/Posição]</h3>
                <p class="company">[Nome da Empresa] | [Cidade, Estado] | [Período: Mês Ano - Mês Ano]</p>
                <ul>
                    <li>[Descrição da sua principal responsabilidade ou conquista.]</li>
                    <li>[Outra responsabilidade/conquista.]</li>
                </ul>
            </div>
            <div class="item">
                <h3>[Cargo/Posição]</h3>
                <p class="company">[Nome da Empresa] | [Cidade, Estado] | [Período: Mês Ano - Mês Ano]</p>
                <ul>
                    <li>[Descrição da sua principal responsabilidade ou conquista.]</li>
                    <li>[Outra responsabilidade/conquista.]</li>
                </ul>
            </div>
        </section>

        <section id="formacao" class="section">
            <h2>Formação Acadêmica</h2>
            <div class="item">
                <h3>[Nome do Curso]</h3>
                <p class="university">[Nome da Instituição] | [Ano de Conclusão]</p>
            </div>
            <div class="item">
                <h3>[Nome do Curso]</h3>
                <p class="university">[Nome da Instituição] | [Ano de Conclusão]</p>
            </div>
        </section>

        <section id="habilidades" class="section">
            <h2>Habilidades</h2>
            <ul class="skills-list">
                <li>[Habilidade 1]</li>
                <li>[Habilidade 2]</li>
                <li>[Habilidade 3]</li>
                <li>[Habilidade 4]</li>
            </ul>
        </section>
    </main>

    <footer id="contato">
        <h2>Contato</h2>
        <p>Email: <a href="mailto:seuemail@exemplo.com">seuemail@exemplo.com</a></p>
        <p>Telefone: (00) 90000-0000</p>
        <p>LinkedIn: <a href="[Link do seu LinkedIn]" target="_blank">[Seu Perfil do LinkedIn]</a></p>
        <p>Portfólio/GitHub: <a href="[Link do seu portfólio]" target="_blank">[Seu Portfólio/GitHub]</a></p>
    </footer>
</body>
</html>
