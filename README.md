<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESPORTES</title>
    <style>
        /* Variáveis de cores para facilitar mudanças */
        :root {
            --primaria: #2563eb;
            --escura: #1e293b;
            --clara: #f8fafc;
            --texto: #334155;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background-color: var(--clara);
            color: var(--texto);
        }

        /* Cabeçalho com Degradê */
        header {
            background: linear-gradient(135deg, var(--escura), var(--primaria));
            color: white;
            padding: 60px 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 { margin: 0; font-size: 2.5rem; }

        /* Menu de Navegação */
        nav {
            background: white;
            display: flex;
            justify-content: center;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        nav a {
            color: var(--escura);
            padding: 15px 25px;
            text-decoration: none;
            font-weight: 600;
            transition: 0.3s;
        }

        nav a:hover {
            color: var(--primaria);
            background: #eff6ff;
        }

        /* Conteúdo Principal */
        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            background: white;
            border-radius: 12px;
            box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1);
        }

        .botao {
            display: inline-block;
            background: var(--primaria);
            color: white;
            padding: 12px 24px;
            border-radius: 8px;
            text-decoration: none;
            margin-top: 20px;
            transition: transform 0.2s;
        }

        .botao:hover {
            transform: scale(1.05);
            background: #1d4ed8;
        }

        footer {
            text-align: center;
            padding: 40px;
            color: #64748b;
            font-size: 0.9rem;
        }

        /* Ajuste para Celular */
        @media (max-width: 600px) {
            header h1 { font-size: 1.8rem; }
            nav { flex-direction: column; text-align: center; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Explorando o Digital</h1>
        <p>Criando algo novo todos os dias</p>
    </header>

    <nav>
        <a href="#home">Início</a>
        <a href="#projetos">Projetos</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="container" id="home">
        <h2>Bem-vindo ao Próximo Nível</h2>
        <p>Agora nosso site tem uma estrutura mais limpa. Adicionamos <strong>CSS moderno</strong> para que a leitura seja agradável e o design pareça profissional.</p>
        
        <p>O que mudamos:</p>
        <ul>
            <li>Cores em variáveis (fácil de trocar tudo de uma vez).</li>
            <li>Menu que "gruda" no topo ao rolar a página.</li>
            <li>Sombras para dar profundidade (efeito Card).</li>
        </ul>

        <a href="#" class="botao">Saiba Mais</a>
    </div>

    <footer>
        <p>&copy; 2026 - Desenvolvido com ❤️ e Código.</p>
    </footer>

</body>
</html>

    
