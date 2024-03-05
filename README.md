<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Portfólio de Hitalo</title>
</head>
<body>
    <header>
        <h1>Portfólio de Hitalo</h1>
        <p>Estudante de Ciência da Computação</p>
    </header>
    <main>
        <section id="projects">
            <h2>Meus Projetos</h2>
            <div class="project">
                <h3>Projeto 1: Nome do Projeto</h3>
                <p>Descrição do projeto</p>
                <a href="#">Link para o projeto</a>
            </div>
            <div class="project">
                <h3>Projeto 2: Nome do Projeto</h3>
                <p>Descrição do projeto</p>
                <a href="#">Link para o projeto</a>
            </div>
        </section>
    </main>
    <footer>
        <p>Email: seuemail@example.com</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/seulinkedin/">Seu LinkedIn</a></p>
    </footer>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

header p {
    font-size: 1.2em;
}

main {
    padding: 20px;
}

#projects {
    max-width: 800px;
    margin: 0 auto;
}

.project {
    background-color: #fff;
    border: 1px solid #ccc;
    padding: 20px;
    margin-bottom: 20px;
    transition: box-shadow 0.3s;
}

.project:hover {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.project h3 {
    margin-top: 0;
}

.project a {
    color: #333;
    text-decoration: none;
    font-weight: bold;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

footer a {
    color: #fff;
    text-decoration: none;
}

</body>
</html>
