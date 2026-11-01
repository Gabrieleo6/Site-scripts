<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RBX Scripts - Canal Oficial</title>
    <style>
        :root {
            --bg-color: #0f0f11;
            --card-bg: #1e1e24;
            --primary-blue: #2563eb;
            --text-main: #ffffff;
            --text-muted: #a1a1aa;
            --border-color: #333338;
            --yt-red: #ff0000;
            --green: #16a34a;
            --red: #dc2626;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            max-width: 800px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            box-sizing: border-box;
            border-bottom: 1px solid var(--border-color);
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo span { color: var(--primary-blue); }

        .header-buttons {
            display: flex;
            gap: 10px;
            align-items: center;
            flex-wrap: wrap;
        }

        .yt-btn {
            background-color: var(--yt-red);
            color: white;
            text-decoration: none;
            padding: 8px 16px;
            border-radius: 6px;
            font-weight: bold;
            font-size: 14px;
            display: flex;
            align-items: center;
            transition: 0.2s;
        }
        .yt-btn:hover { background-color: #cc0000; }

        /* 🔒 Botão do dono: começa ESCONDIDO (display: none) */
        .admin-btn {
            display: none;
            background-color: #27272a;
            color: white;
            border: 1px solid var(--border-color);
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.2s;
            font-size: 14px;
        }

        /* Só aparece quando o body tem a classe "dono-logado" */
        body.dono-logado .admin-btn { display: inline-block; }

        .admin-btn:hover { background-color: #3f3f46; }
        .admin-btn.logado { background-color: #7f1d1d; border-color: #991b1b; }
        .admin-btn.logado:hover { background-color: #991b1b; }

        .user-btn {
            background-color: var(--primary-blue);
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.2s;
            font-size: 14px;
        }
        .user-btn:hover { background-color: #1d4ed8; }
        .user-btn.logado { background-color: var(--green); }
        .user-btn.logado:hover { background-color: #15803d; }
        .user-btn.dono { background-color: #7c3aed; }
        .user-btn.dono:hover { background-color: #6d28d9; }

        main {
            width: 100%;
            max-width: 800px;
            padding: 20px;
            box-sizing: border-box;
        }

        /* ===== PAINEL ADMIN ===== */
        #admin-panel {
            display: none;
            background-color: var(--card-bg);
            border: 1px solid var(--primary-blue);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(37, 99, 235, 0.2);
        }

        #admin-panel h3 { margin-top: 0; color: var(--primary-blue); }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            background-color: #27272a;
            border: 1px solid var(--border-color);
            color: white;
            border-radius: 6px;
            box-sizing: border-box;
            font-family: inherit;
        }

        input:focus, textarea:focus { outline: none; border-color: var(--primary-blue); }

        .image-options {
            background-color: #27272a;
            border: 1px dashed var(--border-color);
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 15px;
        }

        .image-options label {
            display: block;
            font-size: 14px;
            color: var(--text-muted);
            margin-bottom: 8px;
            font-weight: bold;
        }

        /* ===== BOTÃO DA GALERIA ===== */
        .galeria-btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            background-color: var(--primary-blue);
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 6px;
            font-size: 15px;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            transition: 0.2s;
            margin-bottom: 10px;
        }
        .galeria-btn:hover { background-color: #1d4ed8; }

        .divider-text {
            text-align: center;
            color: var(--text-muted);
            font-size: 12px;
            margin: 8px 0;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .preview-img {
            width: 100%;
            max-height: 150px;
            object-fit: cover;
            border-radius: 6px;
            margin-top: 10px;
            display: none;
            border: 1px solid var(--border-color);
        }

        .publish-btn {
            background-color: var(--primary-blue);
            color: white;
            border: none;
            padding: 12px;
            width: 100%;
            border-radius: 6px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.2s;
        }

        .publish-btn:hover { background-color: #1d4ed8; }

        /* ===== MODAL LOGIN/CADASTRO ===== */
        .modal-overlay {
            display: none;
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background-color: rgba(0, 0, 0, 0.75);
            z-index: 1000;
            justify-content: center;
            align-items: center;
            padding: 20px;
            box-sizing: border-box;
            backdrop-filter: blur(4px);
        }

        .modal-overlay.ativo { display: flex; }

        .modal-box {
            background-color: var(--card-bg);
            border: 1px solid var(--primary-blue);
            border-radius: 12px;
            padding: 25px;
            width: 100%;
            max-width: 400px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.6);
        }

        .modal-box h2 {
            margin-top: 0;
            color: var(--primary-blue);
            text-align: center;
        }

        .modal-tabs {
            display: flex;
            gap: 8px;
            margin-bottom: 20px;
        }

        .modal-tab {
            flex: 1;
            padding: 10px;
            background-color: #27272a;
            border: 1px solid var(--border-color);
            color: var(--text-muted);
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.2s;
        }

        .modal-tab.active {
            background-color: var(--primary-blue);
            color: white;
            border-color: var(--primary-blue);
        }

        .modal-form { display: none; }
        .modal-form.active { display: block; }

        .fechar-modal {
            background-color: #3f3f46;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            margin-top: 10px;
            transition: 0.2s;
        }
        .fechar-modal:hover { background-color: #52525b; }

        /* ===== BARRA DE PESQUISA ===== */
        .search-container {
            position: relative;
            margin-bottom: 25px;
        }

        .search-input {
            width: 100%;
            padding: 14px 45px 14px 16px;
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            color: white;
            border-radius: 10px;
            font-size: 15px;
            box-sizing: border-box;
            margin: 0;
        }

        .search-input:focus { border-color: var(--primary-blue); outline: none; }

        .search-icon {
            position: absolute;
            right: 16px;
            top: 50%;
            transform: translateY(-50%);
            font-size: 18px;
            color: var(--text-muted);
            pointer-events: none;
        }

        .search-locked {
            background-color: var(--card-bg);
            border: 1px dashed var(--border-color);
            border-radius: 10px;
            padding: 16px;
            text-align: center;
            color: var(--text-muted);
            font-size: 14px;
            margin-bottom: 25px;
        }

        .search-locked button {
            background-color: var(--primary-blue);
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            font-weight: bold;
            cursor: pointer;
            margin-left: 8px;
            transition: 0.2s;
        }
        .search-locked button:hover { background-color: #1d4ed8; }

        /* ===== CARDS DE SCRIPT ===== */
        .script-card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            overflow: hidden;
            margin-bottom: 25px;
            position: relative;
        }

        .delete-btn {
            display: none;
            position: absolute;
            top: 10px;
            right: 10px;
            background-color: rgba(220, 38, 38, 0.95);
            color: white;
            border: none;
            padding: 8px 14px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            font-size: 14px;
            backdrop-filter: blur(4px);
            transition: 0.2s;
            z-index: 10;
        }
        .delete-btn:hover { background-color: rgba(185, 28, 28, 1); }

        body.admin-logado .delete-btn { display: block !important; }

        .script-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-bottom: 1px solid var(--border-color);
            background-color: #000;
        }

        .script-content { padding: 20px; }
        .script-card h2 { margin: 0 0 10px 0; font-size: 22px; }
        .script-desc { color: var(--text-muted); font-size: 14px; margin-bottom: 15px; line-height: 1.4; }

        .copy-btn {
            background-color: var(--primary-blue);
            color: white;
            border: none;
            padding: 12px;
            width: 100%;
            border-radius: 6px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 8px;
            transition: 0.2s;
        }

        .copy-btn:hover { background-color: #1d4ed8; }
        .copy-btn.copiado { background-color: var(--green); }

        .copy-btn.bloqueado {
            background-color: #7c2d12;
            cursor: not-allowed;
        }
        .copy-btn.bloqueado:hover { background-color: #7c2d12; }

        .empty-message {
            text-align: center;
            color: var(--text-muted);
            padding: 40px 0;
            display: none;
        }

        @media (max-width: 600px) {
            header { flex-direction: column; gap: 15px; }
            .header-buttons { width: 100%; justify-content: space-between; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">⚡ RBX <span>Scripts</span></div>
        <div class="header-buttons">
            <a href="https://www.youtube.com/@RBX-o7y" target="_blank" class="yt-btn">
                ▶ Inscreva-se
            </a>
            <button class="user-btn" id="btn-user" onclick="abrirModal()">👤 Entrar / Criar Conta</button>
            <!-- 🔒 Botão do dono: só aparece quando VOCÊ estiver logado -->
            <button class="admin-btn" id="btn-admin" onclick="toggleAdmin()">👑 Painel do Dono</button>
        </div>
    </header>

    <main>
        <!-- PAINEL ADMIN -->
        <div id="admin-panel">
            <h3>🔒 Painel de Administrador</h3>
            <input type="text" id="titulo-input" placeholder="Título do Script (Ex: Inf Money Imperador Noobs)">
            
            <div class="image-options">
                <label>📸 Imagem do Script</label>

                <!-- 📱 BOTÃO QUE ABRE A GALERIA -->
                <button type="button" class="galeria-btn" onclick="document.getElementById('imagem-arquivo').click()">
                    📷 Escolher da Galeria
                </button>
                <!-- input escondido que é acionado pelo botão acima -->
                <input type="file" id="imagem-arquivo" accept="image/*" onchange="previewArquivo(event)" style="display:none;">

                <div class="divider-text">— ou —</div>

                <input type="text" id="imagem-input" placeholder="Cole o link da imagem (URL .jpg, .png...)" oninput="previewLink()">

                <img id="preview-img" class="preview-img" alt="Pré-visualização">
            </div>

            <textarea id="desc-input" placeholder="Descrição curta (Ex: Keyless, Funciona na versão mobile...)" rows="2"></textarea>
            <textarea id="codigo-input" placeholder="Cole aqui o código do script (loadstring)..." rows="5"></textarea>
            <button class="publish-btn" onclick="adicionarScript()">Publicar Script no Site</button>
        </div>

        <!-- BARRA DE PESQUISA -->
        <div id="search-area"></div>

        <!-- LISTA DE SCRIPTS -->
        <div id="lista-scripts"></div>
        <div id="mensagem-vazia" class="empty-message">Nenhum script postado ainda. Volte mais tarde!</div>
    </main>

    <!-- MODAL DE LOGIN / CADASTRO -->
    <div class="modal-overlay" id="modal-overlay">
        <div class="modal-box">
            <h2>🎮 RBX Scripts</h2>
            <div class="modal-tabs">
                <button class="modal-tab active" id="tab-login" onclick="mudarTab('login')">Entrar</button>
                <button class="modal-tab" id="tab-cadastro" onclick="mudarTab('cadastro')">Criar Conta</button>
            </div>

            <div class="modal-form active" id="form-login">
                <input type="text" id="login-user" placeholder="Nome de usuário">
                <input type="password" id="login-pass" placeholder="Senha">
                <button class="publish-btn" onclick="fazerLogin()">Entrar</button>
            </div>

            <div class="modal-form" id="form-cadastro">
                <input type="text" id="cad-user" placeholder="Escolha um nome de usuário">
                <input type="password" id="cad-pass" placeholder="Crie uma senha (mín. 4 caracteres)">
                <input type="password" id="cad-pass2" placeholder="Confirme a senha">
                <button class="publish-btn" onclick="criarConta()">Criar Conta</button>
            </div>

            <button class="fechar-modal" onclick="fecharModal()">Fechar</button>
        </div>
    </div>

    <script>
        /* ================= CONFIG ================= */
        const NOME_DONO = "Gabriel rbx";
        const SENHA_DONO = "2712cg";

        let isLogado = false;
        let usuarioAtual = null;
        let imagemBase64Atual = null;   // ⭐ guarda a imagem escolhida da galeria
        let termoPesquisa = "";

        /* ================= ELEMENTOS ================= */
        const btnAdmin = document.getElementById('btn-admin');
        const btnUser = document.getElementById('btn-user');
        const adminPanel = document.getElementById('admin-panel');
        const listaScripts = document.getElementById('lista-scripts');
        const msgVazia = document.getElementById('mensagem-vazia');
        const previewImg = document.getElementById('preview-img');
        const searchArea = document.getElementById('search-area');
        const modalOverlay = document.getElementById('modal-overlay');

        let bancoDeScripts = JSON.parse(localStorage.getItem('meusScripts')) || [];
        let bancoDeUsuarios = JSON.parse(localStorage.getItem('usuariosRBX')) || {};

        /* ================= IDENTIFICAÇÃO DO DONO ================= */
        function normalizarNome(nome) {
            return (nome || "").trim().toLowerCase().replace(/\s+/g, ' ');
        }

        function ehDono(nome) {
            return normalizarNome(nome) === normalizarNome(NOME_DONO);
        }

        function acharContaDono() {
            const alvo = normalizarNome(NOME_DONO);
            for (const chave in bancoDeUsuarios) {
                if (normalizarNome(bancoDeUsuarios[chave].nome) === alvo) {
                    return { chave, conta: bancoDeUsuarios[chave] };
                }
            }
            return null;
        }

        function garantirContaDono() {
            const existente = acharContaDono();

            if (existente) {
                bancoDeUsuarios[existente.chave].dono = true;
                bancoDeUsuarios[existente.chave].senha = SENHA_DONO;
                bancoDeUsuarios[existente.chave].nome = NOME_DONO;
            } else {
                const chave = normalizarNome(NOME_DONO);
                bancoDeUsuarios[chave] = {
                    nome: NOME_DONO,
                    senha: SENHA_DONO,
                    dono: true
                };
            }

            localStorage.setItem('usuariosRBX', JSON.stringify(bancoDeUsuarios));
        }

        /* ================= USUÁRIOS ================= */
        function abrirModal() {
            if (usuarioAtual) {
                if (confirm(`Logado como "${usuarioAtual}". Deseja sair?`)) {
                    usuarioAtual = null;
                    localStorage.removeItem('usuarioLogado');

                    isLogado = false;
                    adminPanel.style.display = 'none';
                    btnAdmin.classList.remove('logado');
                    document.body.classList.remove('dono-logado');

                    atualizarUIUsuario();
                    renderizarScripts();
                }
                return;
            }
            modalOverlay.classList.add('ativo');
        }

        function fecharModal() {
            modalOverlay.classList.remove('ativo');
        }

        function mudarTab(tab) {
            document.getElementById('tab-login').classList.toggle('active', tab === 'login');
            document.getElementById('tab-cadastro').classList.toggle('active', tab === 'cadastro');
            document.getElementById('form-login').classList.toggle('active', tab === 'login');
            document.getElementById('form-cadastro').classList.toggle('active', tab === 'cadastro');
        }

        function criarConta() {
            const user = document.getElementById('cad-user').value.trim();
            const pass = document.getElementById('cad-pass').value;
            const pass2 = document.getElementById('cad-pass2').value;

            if (user.length < 3) { alert("O nome de usuário precisa ter pelo menos 3 caracteres."); return; }
            if (pass.length < 4) { alert("A senha precisa ter pelo menos 4 caracteres."); return; }
            if (pass !== pass2) { alert("As senhas não coincidem!"); return; }

            if (ehDono(user)) {
                alert("❌ Este nome de usuário é reservado. Escolha outro.");
                return;
            }

            if (bancoDeUsuarios[normalizarNome(user)]) {
                alert("Este nome de usuário já existe. Escolha outro.");
                return;
            }

            bancoDeUsuarios[normalizarNome(user)] = { nome: user, senha: pass };
            localStorage.setItem('usuariosRBX', JSON.stringify(bancoDeUsuarios));

            usuarioAtual = user;
            localStorage.setItem('usuarioLogado', user);

            alert(`✅ Conta criada com sucesso! Bem-vindo, ${user}!`);

            fecharModal();
            atualizarUIUsuario();
            renderizarScripts();
        }

        function fazerLogin() {
            const user = document.getElementById('login-user').value.trim();
            const pass = document.getElementById('login-pass').value;

            let conta = bancoDeUsuarios[normalizarNome(user)];
            let chaveConta = normalizarNome(user);

            if (!conta) {
                for (const chave in bancoDeUsuarios) {
                    if (normalizarNome(bancoDeUsuarios[chave].nome) === normalizarNome(user)) {
                        conta = bancoDeUsuarios[chave];
                        chaveConta = chave;
                        break;
                    }
                }
            }

            if (!conta) { alert("Usuário não encontrado. Crie uma conta primeiro."); return; }
            if (conta.senha !== pass) { alert("Senha incorreta!"); return; }

            usuarioAtual = conta.nome;
            localStorage.setItem('usuarioLogado', conta.nome);

            if (ehDono(conta.nome) || conta.dono) {
                bancoDeUsuarios[chaveConta].dono = true;
                localStorage.setItem('usuariosRBX', JSON.stringify(bancoDeUsuarios));

                ativarAdminAutomatico();
                alert(`👑 Bem-vindo, DONO ${conta.nome}! Você tem acesso total ao site.`);
            } else {
                alert(`✅ Bem-vindo de volta, ${conta.nome}!`);
            }

            fecharModal();
            atualizarUIUsuario();
            renderizarScripts();
        }

        function ativarAdminAutomatico() {
            isLogado = true;
            adminPanel.style.display = 'block';
            btnAdmin.innerText = "👑 Painel do Dono (Sair)";
            btnAdmin.classList.add('logado');
            document.body.classList.add('dono-logado');
        }

        function atualizarUIUsuario() {
            if (usuarioAtual) {
                if (ehDono(usuarioAtual)) {
                    btnUser.innerText = `👑 ${usuarioAtual} (Sair)`;
                    btnUser.classList.add('logado');
                    btnUser.classList.add('dono');
                } else {
                    btnUser.innerText = `👤 ${usuarioAtual} (Sair)`;
                    btnUser.classList.add('logado');
                    btnUser.classList.remove('dono');
                }
            } else {
                btnUser.innerText = "👤 Entrar / Criar Conta";
                btnUser.classList.remove('logado');
                btnUser.classList.remove('dono');
            }
        }

        /* ================= PESQUISA ================= */
        function renderizarPesquisa() {
            if (!usuarioAtual) {
                searchArea.innerHTML = `
                    <div class="search-locked">
                        🔒 Crie uma conta ou faça login para pesquisar scripts.
                        <button onclick="abrirModal()">Entrar</button>
                    </div>
                `;
                return;
            }
            searchArea.innerHTML = `
                <div class="search-container">
                    <input type="text" class="search-input" id="search-input"
                           placeholder="🔍 Pesquisar scripts pelo nome ou descrição..."
                           value="${termoPesquisa.replace(/"/g, '&quot;')}"
                           oninput="filtrarScripts(this.value)">
                    <span class="search-icon">🔍</span>
                </div>
            `;
        }

        function filtrarScripts(valor) {
            termoPesquisa = valor.toLowerCase();
            renderizarScripts();
        }

        /* ================= IMAGEM (GALERIA + URL) ================= */
        // 📷 Chamado quando o usuário escolhe uma imagem da galeria
        function previewArquivo(event) {
            const file = event.target.files[0];
            if (!file) return;

            const reader = new FileReader();
            reader.onload = function(e) {
                imagemBase64Atual = e.target.result;   // guarda em Base64
                previewImg.src = imagemBase64Atual;
                previewImg.style.display = 'block';
                // limpa o campo de URL pra não conflitar
                document.getElementById('imagem-input').value = '';
            };
            reader.readAsDataURL(file);
        }

        // 🔗 Chamado quando o usuário cola uma URL
        function previewLink() {
            const url = document.getElementById('imagem-input').value.trim();
            if (url !== "") {
                previewImg.src = url;
                previewImg.style.display = 'block';
                imagemBase64Atual = null;   // descarta a imagem da galeria
                document.getElementById('imagem-arquivo').value = '';
            } else {
                previewImg.style.display = 'none';
            }
        }

        function resetarImagem() {
            imagemBase64Atual = null;
            previewImg.src = '';
            previewImg.style.display = 'none';
            document.getElementById('imagem-arquivo').value = '';
            document.getElementById('imagem-input').value = '';
        }

        /* ================= RENDERIZAÇÃO ================= */
        function renderizarScripts() {
            renderizarPesquisa();
            listaScripts.innerHTML = '';

            let scriptsFiltrados = bancoDeScripts;
            if (usuarioAtual && termoPesquisa.trim() !== "") {
                scriptsFiltrados = bancoDeScripts.filter(s =>
                    s.titulo.toLowerCase().includes(termoPesquisa) ||
                    (s.desc || "").toLowerCase().includes(termoPesquisa)
                );
            }

            if (scriptsFiltrados.length === 0) {
                msgVazia.style.display = 'block';
                msgVazia.innerText = (usuarioAtual && termoPesquisa)
                    ? "Nenhum script encontrado com esse termo. 🔍"
                    : "Nenhum script postado ainda. Volte mais tarde!";
            } else {
                msgVazia.style.display = 'none';
            }

            scriptsFiltrados.forEach((script) => {
                const indexReal = bancoDeScripts.indexOf(script);
                const novoCard = document.createElement('div');
                novoCard.className = 'script-card';

                const codigoSeguro = encodeURIComponent(script.codigo);
                const bloqueado = !usuarioAtual;

                novoCard.innerHTML = `
                    <button class="delete-btn" onclick="apagarScript(${indexReal})">🗑️ Apagar</button>
                    <img src="${script.imagem}" alt="Imagem do Script" class="script-image" onerror="this.src='https://via.placeholder.com/800x200/1e1e24/ffffff?text=Erro+na+Imagem'">
                    <div class="script-content">
                        <h2>${script.titulo}</h2>
                        <div class="script-desc">${script.desc || ""}</div>
                        <button class="copy-btn ${bloqueado ? 'bloqueado' : ''}"
                                onclick="${bloqueado
                                    ? "alert('🔒 Crie uma conta ou faça login para copiar o script sem anúncios!'); abrirModal();"
                                    : `copiarTexto(this, decodeURIComponent('${codigoSeguro}'))`}">
                            ${bloqueado ? "🔒 Copiar (requer login)" : "📋 Copiar Script"}
                        </button>
                    </div>
                `;
                listaScripts.appendChild(novoCard);
            });

            document.body.classList.toggle('admin-logado', isLogado);
        }

        /* ================= ADMIN ================= */
        function toggleAdmin() {
            if (!ehDono(usuarioAtual)) return;

            if (!isLogado) {
                ativarAdminAutomatico();
                renderizarScripts();
            } else {
                isLogado = false;
                adminPanel.style.display = 'none';
                btnAdmin.innerText = "👑 Painel do Dono";
                btnAdmin.classList.remove('logado');
                renderizarScripts();
            }
        }

        function adicionarScript() {
            if (!isLogado || !ehDono(usuarioAtual)) return;

            const titulo = document.getElementById('titulo-input').value;
            const imagemUrl = document.getElementById('imagem-input').value.trim();
            const desc = document.getElementById('desc-input').value;
            const codigo = document.getElementById('codigo-input').value;

            if (titulo.trim() === "" || codigo.trim() === "") {
                alert("Por favor, preencha pelo menos o título e o código do script.");
                return;
            }

            // ⭐ Prioridade: imagem da galeria > URL > placeholder
            let imagemFinal;
            if (imagemBase64Atual) {
                imagemFinal = imagemBase64Atual;
            } else if (imagemUrl !== "") {
                imagemFinal = imagemUrl;
            } else {
                imagemFinal = "https://via.placeholder.com/800x200/1e1e24/ffffff?text=Sem+Imagem";
            }

            const novoScript = { titulo, imagem: imagemFinal, desc, codigo };

            try {
                bancoDeScripts.unshift(novoScript);
                localStorage.setItem('meusScripts', JSON.stringify(bancoDeScripts));
            } catch (e) {
                alert("⚠️ Erro ao salvar: o armazenamento do navegador está cheio. Tente uma imagem menor ou use um link.");
                bancoDeScripts.shift();
                return;
            }

            document.getElementById('titulo-input').value = '';
            document.getElementById('desc-input').value = '';
            document.getElementById('codigo-input').value = '';
            resetarImagem();

            alert("Script salvo com sucesso!");
            renderizarScripts();
        }

        function apagarScript(index) {
            if (!isLogado || !ehDono(usuarioAtual)) return;

            const script = bancoDeScripts[index];
            if (!script) return;

            if (confirm(`Apagar o script "${script.titulo}"?\n\nEssa ação não pode ser desfeita.`)) {
                bancoDeScripts.splice(index, 1);
                localStorage.setItem('meusScripts', JSON.stringify(bancoDeScripts));
                renderizarScripts();

                const aviso = document.createElement('div');
                aviso.style.cssText = 'position:fixed;bottom:20px;left:50%;transform:translateX(-50%);background:#16a34a;color:#fff;padding:12px 20px;border-radius:8px;font-weight:bold;z-index:9999;box-shadow:0 4px 15px rgba(0,0,0,.4)';
                aviso.innerText = '✅ Script apagado!';
                document.body.appendChild(aviso);
                setTimeout(() => aviso.remove(), 2000);
            }
        }

        /* ================= COPIAR ================= */
        function copiarTexto(botao, texto) {
            if (!usuarioAtual) {
                alert("🔒 Crie uma conta ou faça login para copiar sem anúncios!");
                abrirModal();
                return;
            }
            navigator.clipboard.writeText(texto).then(() => {
                const original = botao.innerHTML;
                botao.innerHTML = "✅ Copiado!";
                botao.classList.add('copiado');
                setTimeout(() => {
                    botao.innerHTML = original;
                    botao.classList.remove('copiado');
                }, 2000);
            }).catch(() => {
                alert("Erro ao copiar. Copie manualmente.");
            });
        }

        /* ================= INICIALIZAÇÃO ================= */
        (function init() {
            garantirContaDono();

            const salvo = localStorage.getItem('usuarioLogado');
            if (salvo && bancoDeUsuarios[normalizarNome(salvo)]) {
                usuarioAtual = bancoDeUsuarios[normalizarNome(salvo)].nome;

                if (ehDono(usuarioAtual)) {
                    ativarAdminAutomatico();
                }
            }
            atualizarUIUsuario();
            renderizarScripts();
        })();
    </script>
</body>
</html>
