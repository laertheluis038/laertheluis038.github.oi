# laertheluis038.github.oi
laertheluis038
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil no Github</title>
    <style>
        :root {
            --primary-color: #6e5494;
            --secondary-color: #4078c0;
            --background-color: #f5f5f5;
            --text-color: #333;
            --light-color: #fff;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--light-color);
            text-align: center;
            padding: 2rem 0;
            box-shadow: var(--shadow);
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid var(--light-color);
            margin-bottom: 1rem;
            object-fit: cover;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .section {
            background-color: var(--light-color);
            border-radius: 8px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: var(--shadow);
        }
        
        h1, h2, h3 {
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        p {
            margin-bottom: 1rem;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--primary-color);
            color: var(--light-color);
            padding: 0.8rem 1.5rem;
            border-radius: 4px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: var(--secondary-color);
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .skill {
            background-color: var(--secondary-color);
            color: var(--light-color);
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .project {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        
        .project:hover {
            transform: translateY(-5px);
        }
        
        .project-content {
            padding: 1.5rem;
        }
        
        footer {
            background-color: var(--primary-color);
            color: var(--light-color);
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 1rem;
        }
        
        .social-links a {
            color: var(--light-color);
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: #ddd;
        }
        
        @media (max-width: 768px) {
            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <img src="https://via.placeholder.com/150" alt="Foto de Perfil" class="profile-img">
            <h1>Seu Nome</h1>
            <p>Desenvolvedor Web | Entusiasta de Tecnologia</p>
        </div>
    </header>
    
    <main class="container">
        <section class="section">
            <h2>Sobre Mim</h2>
            <p>Olá! Sou um desenvolvedor apaixonado por tecnologia e programação. Adoro criar soluções inovadoras e aprender novas tecnologias.</p>
            <p>Atualmente, estou focado em desenvolvimento web e mobile, explorando frameworks modernos e boas práticas de código.</p>
            <a href="https://github.com/seu-usuario" class="btn">Ver Meu Github</a>
        </section>
        
        <section class="section">
            <h2>Habilidades</h2>
            <div class="skills">
                <span class="skill">HTML</span>
                <span class="skill">CSS</span>
                <span class="skill">JavaScript</span>
                <span class="skill">React</span>
                <span class="skill">Node.js</span>
                <span class="skill">Git</span>
                <span class="skill">Responsive Design</span>
            </div>
        </section>
        
        <section class="section">
            <h2>Projetos Destacados</h2>
            <div class="projects">
                <div class="project">
                    <div class="project-content">
                        <h3>Projeto 1</h3>
                        <p>Descrição breve do projeto. O que ele faz, tecnologias utilizadas e objetivo.</p>
                        <a href="#" class="btn">Ver Projeto</a>
                    </div>
                </div>
                
                <div class="project">
                    <div class="project-content">
                        <h3>Projeto 2</h3>
                        <p>Descrição breve do projeto. O que ele faz, tecnologias utilizadas e objetivo.</p>
                        <a href="#" class="btn">Ver Projeto</a>
                    </div>
                </div>
                
                <div class="project">
                    <div class="project-content">
                        <h3>Projeto 3</h3>
                        <p>Descrição breve do projeto. O que ele faz, tecnologias utilizadas e objetivo.</p>
                        <a href="#" class="btn">Ver Projeto</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2>Contato</h2>
            <p>Estou sempre aberto a novas oportunidades e colaborações. Sinta-se à vontade para entrar em contato!</p>
            <a href="mailto:laertheluis038@gmail.com " class="btn">Enviar Email</a>
        </section>
    </main>
    
    <footer>
        <div class="container">
            <p>&copy; 2023 Laerthe Luis. Todos os direitos reservados.</p>
            <div class="social-links">
                <a href="https://github.com/laertheluis038.github.oi" aria-label="Github">
                    <i class="fab fa-github"></i>
                </a>
                <a href="https://linkedin.com/in/larrtheluis" aria-label="LinkedIn">
                    <i class="fab fa-linkedin"></i>
                </a>
                <a href="https://twitter.com/@MLVRede" aria-label="Twitter">
                    <i class="fab fa-twitter"></i>
                </a>
            </div>
        </div>
    </footer>
    
    <!-- Font Awesome para ícones -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
