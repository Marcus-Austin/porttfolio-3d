<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Portfólio 3D Three.js</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f9;
        }
        header {
            background: linear-gradient(135deg, #1e1e2f, #4a4a8a);
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        h1 { margin: 0; font-size: 2.5em; }
        h2 { color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px; }
        .badge {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9em;
            margin-right: 5px;
        }
        section {
            background: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }
        code {
            background: #eee;
            padding: 2px 5px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
        }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .feature-item {
            background: #f9f9f9;
            padding: 15px;
            border-left: 4px solid #4a4a8a;
            border-radius: 4px;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9em;
            color: #777;
        }
    </style>
</head>
<body>

<header>
    <h1>✨ Meu Portfólio 3D</h1>
    <p>Uma experiência imersiva construída com Three.js e WebGL</p>
    <div style="margin-top: 15px;">
        <span class="badge">Three.js</span>
        <span class="badge">JavaScript</span>
        <span class="badge">WebGL</span>
        <span class="badge">GSAP</span>
    </div>
</header>

<section>
    <h2>🚀 Sobre o Projeto</h2>
    <p>Este projeto é um portfólio interativo desenvolvido para explorar as fronteiras da renderização 3D no navegador. Diferente de sites estáticos, aqui a navegação é uma jornada por um ambiente tridimensional, onde cada seção do meu trabalho é representada por elementos geométricos e interativos.</p>
</section>

<section>
    <h2>🛠️ Tecnologias Utilizadas</h2>
    <div class="features-grid">
        <div class="feature-item">
            <strong>Three.js:</strong> Motor principal para criação e exibição de gráficos 3D.
        </div>
        <div class="feature-item">
            <strong>GSAP (TweenMax):</strong> Utilizado para animações suaves de câmera e transições de elementos.
        </div>
        <div class="feature-item">
            <strong>GLSL Shaders:</strong> Efeitos personalizados de materiais e pós-processamento.
        </div>
        <div class="feature-item">
            <strong>Blender:</strong> Modelagem e otimização dos ativos 3D (formatos .GLB / .GLTF).
        </div>
    </div>
</section>

<section>
    <h2>🎮 Funcionalidades</h2>
    <ul>
        <li><strong>Navegação Interativa:</strong> Controle de câmera orbital ou baseado no scroll do mouse.</li>
        <li><strong>Iluminação Dinâmica:</strong> Sombras em tempo real e luzes pontuais que seguem o cursor.</li>
        <li><strong>Responsividade:</strong> Ajuste automático da razão de aspecto (aspect ratio) e densidade de pixels.</li>
        <li><strong>Raycasting:</strong> Detecção de cliques em objetos 3D para abrir detalhes dos projetos.</li>
    </ul>
</section>

<section>
    <h2>📦 Como Rodar Localmente</h2>
    <p>Certifique-se de ter o <a href="https://nodejs.org/">Node.js</a> instalado.</p>
    <pre>
<code># Clone o repositório
git clone https://github.com/seu-usuario/portfolio-3d.git

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev</code>
    </pre>
</section>

<footer>
    <p>Desenvolvido com 💜 e muita matemática de vetores.</p>
</footer>

</body>
</html>
