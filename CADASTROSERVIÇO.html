[CADASTRO DE SERÇIVO.html](https://github.com/user-attachments/files/23525861/CADASTRO.DE.SERCIVO.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THOR04 INFORMATICA - Sistema de Gestão</title>
    <!-- Adicionando a biblioteca jsPDF -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, #2c3e50, #4a6491);
            color: white;
            padding: 20px 0;
            text-align: center;
            border-radius: 8px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .nav-tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 30px;
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }
        
        .nav-tab {
            padding: 15px 30px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s ease;
            text-align: center;
            flex: 1;
        }
        
        .nav-tab.active {
            background: #4a6491;
            color: white;
        }
        
        .nav-tab:hover:not(.active) {
            background: #f0f4ff;
        }
        
        .page {
            display: none;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
        }
        
        .page.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .form-group {
            margin-bottom: 20px;
            position: relative;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #2c3e50;
        }
        
        input, textarea {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 6px;
            font-size: 16px;
            transition: border 0.3s ease;
        }
        
        input:focus, textarea:focus {
            outline: none;
            border-color: #4a6491;
            box-shadow: 0 0 0 2px rgba(74, 100, 145, 0.2);
        }
        
        input.error {
            border-color: #e74c3c;
            box-shadow: 0 0 0 2px rgba(231, 76, 60, 0.2);
        }
        
        .error-message {
            color: #e74c3c;
            font-size: 14px;
            margin-top: 5px;
            display: none;
        }
        
        button {
            background: #4a6491;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            font-weight: 600;
            transition: background 0.3s ease;
        }
        
        button:hover {
            background: #3a547e;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .service-card {
            background: white;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            border-left: 4px solid #4a6491;
            transition: transform 0.3s ease;
            position: relative;
        }
        
        .service-card.concluded {
            border-left: 4px solid #27ae60;
        }
        
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }
        
        .service-card h3 {
            color: #2c3e50;
            margin-bottom: 10px;
            border-bottom: 1px solid #eee;
            padding-bottom: 10px;
        }
        
        .service-card p {
            margin-bottom: 8px;
            color: #555;
        }
        
        .service-actions {
            display: flex;
            justify-content: flex-end;
            margin-top: 15px;
            padding-top: 15px;
            border-top: 1px solid #eee;
            gap: 10px;
        }
        
        .delete-btn {
            background: #e74c3c;
            padding: 8px 15px;
            font-size: 14px;
        }
        
        .delete-btn:hover {
            background: #c0392b;
        }
        
        .pdf-btn {
            background: #27ae60;
            padding: 8px 15px;
            font-size: 14px;
        }
        
        .pdf-btn:hover {
            background: #219653;
        }
        
        .complete-btn {
            background: #3498db;
            padding: 8px 15px;
            font-size: 14px;
        }
        
        .complete-btn:hover {
            background: #2980b9;
        }
        
        .search-box {
            margin-bottom: 20px;
            display: flex;
            gap: 10px;
        }
        
        .search-box input {
            flex: 1;
        }
        
        .filters {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
            flex-wrap: wrap;
        }
        
        .filter-btn {
            background: #e0e6ef;
            color: #2c3e50;
            border: none;
            padding: 8px 15px;
            border-radius: 20px;
            cursor: pointer;
            font-size: 14px;
            transition: all 0.3s ease;
        }
        
        .filter-btn.active {
            background: #4a6491;
            color: white;
        }
        
        .no-services {
            text-align: center;
            padding: 40px;
            color: #777;
            font-style: italic;
        }
        
        .json-actions {
            display: flex;
            gap: 15px;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #eee;
        }
        
        .json-btn {
            background: #3498db;
        }
        
        .json-btn:hover {
            background: #2980b9;
        }
        
        .export-btn {
            background: #27ae60;
        }
        
        .export-btn:hover {
            background: #219653;
        }
        
        .import-btn {
            background: #e67e22;
        }
        
        .import-btn:hover {
            background: #d35400;
        }
        
        .json-view {
            background: #2c3e50;
            color: #ecf0f1;
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
            max-height: 300px;
            overflow: auto;
            font-family: monospace;
            white-space: pre-wrap;
        }
        
        /* Modal de confirmação */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }
        
        .modal-content {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            width: 90%;
            max-width: 500px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .modal h3 {
            margin-bottom: 15px;
            color: #2c3e50;
        }
        
        .modal p {
            margin-bottom: 20px;
            color: #555;
        }
        
        .modal-buttons {
            display: flex;
            justify-content: flex-end;
            gap: 10px;
        }
        
        .modal-cancel {
            background: #95a5a6;
        }
        
        .modal-cancel:hover {
            background: #7f8c8d;
        }
        
        .modal-confirm {
            background: #e74c3c;
        }
        
        .modal-confirm:hover {
            background: #c0392b;
        }
        
        @media (max-width: 768px) {
            .nav-tabs {
                flex-direction: column;
            }
            
            .services-grid {
                grid-template-columns: 1fr;
            }
            
            .json-actions {
                flex-direction: column;
            }
            
            .service-actions {
                flex-direction: column;
            }
            
            .modal-content {
                width: 95%;
                padding: 20px;
            }
        }
        
        .print-btn {
            background: #3498db;
            padding: 8px 15px;
            font-size: 14px;
        }
        
        .print-btn:hover {
            background: #2980b9;
        }
        
        .concluded-badge {
            background: #27ae60;
            color: white;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 12px;
            position: absolute;
            top: 15px;
            right: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>THOR04 INFORMATICA</h1>
            <p class="subtitle">Sistema de Gestão de Ordens de Serviço</p>
        </header>
        
        <div class="nav-tabs">
            <div class="nav-tab active" data-page="register">Nova Ordem</div>
            <div class="nav-tab" data-page="consult">Consultar Ordens</div>
            <div class="nav-tab" data-page="concluded">Serviços Concluídos</div>
            <div class="nav-tab" data-page="json">Gerenciar Dados</div>
        </div>
        
        <div id="register" class="page active">
            <h2>Cadastrar Nova Ordem de Serviço</h2>
            <form id="service-form">
                <div class="form-group">
                    <label for="nome">Nome do Cliente</label>
                    <input type="text" id="nome" required placeholder="Digite o nome completo">
                </div>
                
                <div class="form-group">
                    <label for="telefone">Telefone</label>
                    <input type="tel" id="telefone" required placeholder="(11) 99999-9999">
                    <div class="error-message" id="telefone-error">Telefone inválido. Formato esperado: (11) 99999-9999</div>
                </div>
                
                <div class="form-group">
                    <label for="cpf">CPF</label>
                    <input type="text" id="cpf" required placeholder="000.000.000-00">
                    <div class="error-message" id="cpf-error">CPF inválido. Verifique o número digitado.</div>
                </div>
                
                <div class="form-group">
                    <label for="modelo">Modelo do Aparelho</label>
                    <input type="text" id="modelo" required placeholder="Ex: Dell Inspiron 15, iPhone 12">
                </div>
                
                <div class="form-group">
                    <label for="defeito">Defeito Relatado</label>
                    <textarea id="defeito" rows="4" required placeholder="Descreva o problema relatado pelo cliente"></textarea>
                </div>
                
                <div class="form-group">
                    <label for="data">Data de Entrada</label>
                    <input type="date" id="data" required>
                </div>
                
                <button type="submit">Cadastrar Ordem</button>
            </form>
        </div>
        
        <div id="consult" class="page">
            <h2>Ordens de Serviço Cadastradas</h2>
            
            <div class="search-box">
                <input type="text" id="search-input" placeholder="Buscar por nome, modelo ou defeito...">
                <button id="search-btn">Buscar</button>
            </div>
            
            <div class="filters">
                <div class="filter-btn active" data-filter="all">Todos</div>
                <div class="filter-btn" data-filter="recent">Recentes</div>
                <div class="filter-btn" data-filter="last-week">Semana Passada</div>
                <div class="filter-btn" data-filter="last-month">Mês Passado</div>
            </div>
            
            <div id="services-list" class="services-grid">
                <!-- As ordens de serviço serão carregadas aqui -->
            </div>
        </div>
        
        <div id="concluded" class="page">
            <h2>Serviços Concluídos</h2>
            
            <div class="search-box">
                <input type="text" id="search-concluded-input" placeholder="Buscar por nome, modelo ou defeito...">
                <button id="search-concluded-btn">Buscar</button>
            </div>
            
            <div class="filters">
                <div class="filter-btn active" data-concluded-filter="all">Todos</div>
                <div class="filter-btn" data-concluded-filter="recent">Recentes</div>
                <div class="filter-btn" data-concluded-filter="last-week">Semana Passada</div>
                <div class="filter-btn" data-concluded-filter="last-month">Mês Passado</div>
            </div>
            
            <div id="concluded-list" class="services-grid">
                <!-- Os serviços concluídos serão carregados aqui -->
            </div>
        </div>
        
        <div id="json" class="page">
            <h2>Gerenciamento de Dados</h2>
            <p>Visualize, exporte e importe seus dados em formato JSON</p>
            
            <div class="json-actions">
                <button id="view-json-btn" class="json-btn">Visualizar JSON</button>
                <button id="export-json-btn" class="export-btn">Exportar JSON</button>
                <button id="import-json-btn" class="import-btn">Importar JSON</button>
                <input type="file" id="import-json-file" accept=".json" style="display: none;">
            </div>
            
            <div id="json-view" class="json-view" style="display: none;">
                <!-- JSON será exibido aqui -->
            </div>
        </div>
    </div>

    <!-- Modal de confirmação de exclusão -->
    <div id="delete-modal" class="modal">
        <div class="modal-content">
            <h3>Confirmar Exclusão</h3>
            <p>Tem certeza que deseja excluir esta ordem de serviço? Esta ação não pode ser desfeita.</p>
            <div class="modal-buttons">
                <button id="modal-cancel" class="modal-cancel">Cancelar</button>
                <button id="modal-confirm" class="modal-confirm">Excluir</button>
            </div>
        </div>
    </div>

    <!-- Modal de confirmação de conclusão -->
    <div id="complete-modal" class="modal">
        <div class="modal-content">
            <h3>Confirmar Conclusão</h3>
            <p>Tem certeza que deseja marcar esta ordem de serviço como concluída?</p>
            <div class="modal-buttons">
                <button id="complete-modal-cancel" class="modal-cancel">Cancelar</button>
                <button id="complete-modal-confirm" class="complete-btn">Concluir</button>
            </div>
        </div>
    </div>

    <script>
        // Inicialização da data atual
        document.getElementById('data').valueAsDate = new Date();
        
        // Variáveis para armazenar o ID do serviço a ser excluído ou concluído
        let serviceToDelete = null;
        let serviceToComplete = null;
        
        // Funções de validação e máscara para telefone e CPF
        function aplicarMascaraTelefone(input) {
            let value = input.value.replace(/\D/g, '');
            
            if (value.length > 11) {
                value = value.slice(0, 11);
            }
            
            if (value.length <= 10) {
                value = value.replace(/(\d{2})(\d{4})(\d{4})/, '($1) $2-$3');
            } else {
                value = value.replace(/(\d{2})(\d{5})(\d{4})/, '($1) $2-$3');
            }
            
            input.value = value;
            return value;
        }
        
        function validarTelefone(telefone) {
            const telefoneLimpo = telefone.replace(/\D/g, '');
            return telefoneLimpo.length >= 10 && telefoneLimpo.length <= 11;
        }
        
        function aplicarMascaraCPF(input) {
            let value = input.value.replace(/\D/g, '');
            
            if (value.length > 11) {
                value = value.slice(0, 11);
            }
            
            value = value.replace(/(\d{3})(\d)/, '$1.$2');
            value = value.replace(/(\d{3})(\d)/, '$1.$2');
            value = value.replace(/(\d{3})(\d{1,2})$/, '$1-$2');
            
            input.value = value;
            return value;
        }
        
        function validarCPF(cpf) {
            cpf = cpf.replace(/\D/g, '');
            
            if (cpf.length !== 11) return false;
            
            // Verifica se todos os dígitos são iguais (ex: 111.111.111-11)
            if (/^(\d)\1{10}$/.test(cpf)) return false;
            
            // Validação do CPF usando algoritmo de verificação
            let soma = 0;
            let resto;
            
            for (let i = 1; i <= 9; i++) {
                soma += parseInt(cpf.substring(i-1, i)) * (11 - i);
            }
            
            resto = (soma * 10) % 11;
            
            if ((resto === 10) || (resto === 11)) resto = 0;
            if (resto !== parseInt(cpf.substring(9, 10))) return false;
            
            soma = 0;
            for (let i = 1; i <= 10; i++) {
                soma += parseInt(cpf.substring(i-1, i)) * (12 - i);
            }
            
            resto = (soma * 10) % 11;
            
            if ((resto === 10) || (resto === 11)) resto = 0;
            if (resto !== parseInt(cpf.substring(10, 11))) return false;
            
            return true;
        }
        
        // Aplicar máscaras aos campos
        document.getElementById('telefone').addEventListener('input', function() {
            aplicarMascaraTelefone(this);
            
            // Validar e mostrar erro se necessário
            const telefoneValido = validarTelefone(this.value);
            const errorElement = document.getElementById('telefone-error');
            
            if (!telefoneValido && this.value.length > 0) {
                this.classList.add('error');
                errorElement.style.display = 'block';
            } else {
                this.classList.remove('error');
                errorElement.style.display = 'none';
            }
        });
        
        document.getElementById('cpf').addEventListener('input', function() {
            aplicarMascaraCPF(this);
            
            // Validar e mostrar erro se necessário
            const cpfValido = validarCPF(this.value);
            const errorElement = document.getElementById('cpf-error');
            
            if (!cpfValido && this.value.length > 0) {
                this.classList.add('error');
                errorElement.style.display = 'block';
            } else {
                this.classList.remove('error');
                errorElement.style.display = 'none';
            }
        });
        
        // Navegação entre abas
        document.querySelectorAll('.nav-tab').forEach(tab => {
            tab.addEventListener('click', () => {
                document.querySelectorAll('.nav-tab').forEach(t => t.classList.remove('active'));
                document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
                
                tab.classList.add('active');
                document.getElementById(tab.dataset.page).classList.add('active');
                
                if (tab.dataset.page === 'consult') {
                    loadServices();
                } else if (tab.dataset.page === 'concluded') {
                    loadConcludedServices();
                } else if (tab.dataset.page === 'json') {
                    document.getElementById('json-view').style.display = 'none';
                }
            });
        });
        
        // Carregar serviços do localStorage
        function getServices() {
            const services = localStorage.getItem('techServices');
            return services ? JSON.parse(services) : [];
        }
        
        // Carregar serviços concluídos do localStorage
        function getConcludedServices() {
            const services = localStorage.getItem('concludedServices');
            return services ? JSON.parse(services) : [];
        }
        
        // Salvar serviços no localStorage
        function saveServices(services) {
            localStorage.setItem('techServices', JSON.stringify(services));
        }
        
        // Salvar serviços concluídos no localStorage
        function saveConcludedServices(services) {
            localStorage.setItem('concludedServices', JSON.stringify(services));
        }
        
        // Formatar data para exibição
        function formatDate(dateString) {
            const options = { day: '2-digit', month: '2-digit', year: 'numeric' };
            return new Date(dateString).toLocaleDateString('pt-BR', options);
        }
        
        // Função para gerar o PDF da ordem de serviço
        function generateServiceOrderPDF(service) {
            const { jsPDF } = window.jspdf;
            const doc = new jsPDF();
            
            // Configurações do documento
            const margin = 20;
            const pageWidth = doc.internal.pageSize.getWidth();
            const contentWidth = pageWidth - (margin * 2);
            
            // Cabeçalho do documento
            doc.setFontSize(20);
            doc.setFont(undefined, 'bold');
            doc.setTextColor(40, 40, 40);
            doc.text("THOR04 INFORMATICA", pageWidth / 2, margin, { align: 'center' });
            
            // Informações da empresa
            doc.setFontSize(12);
            doc.setFont(undefined, 'normal');
            doc.setTextColor(80, 80, 80);
            doc.text("ORDEM DE SERVIÇO", pageWidth / 2, margin + 10, { align: 'center' });
            doc.text("Tel: (21) 97094-9439 | Email: thor4consultoria.varejista@gmail.com", pageWidth / 2, margin + 16, { align: 'center' });
            
            // Linha separadora
            doc.setDrawColor(200, 200, 200);
            doc.setLineWidth(0.5);
            doc.line(margin, margin + 22, pageWidth - margin, margin + 22);
            
            // Número da ordem de serviço
            doc.setFontSize(16);
            doc.setFont(undefined, 'bold');
            doc.setTextColor(60, 60, 160);
            doc.text(`Nº da Ordem: ${service.id}`, pageWidth / 2, margin + 35, { align: 'center' });
            
            // Data de emissão
            doc.setFontSize(12);
            doc.setFont(undefined, 'normal');
            doc.setTextColor(80, 80, 80);
            const today = new Date();
            doc.text(`Data de Emissão: ${today.toLocaleDateString('pt-BR')}`, pageWidth - margin, margin + 30, { align: 'right' });
            
            let yPosition = margin + 50;
            
            // Dados do cliente
            doc.setFontSize(14);
            doc.setFont(undefined, 'bold');
            doc.setTextColor(40, 40, 40);
            doc.text("DADOS DO CLIENTE", margin, yPosition);
            yPosition += 10;
            
            doc.setFontSize(12);
            doc.setFont(undefined, 'normal');
            doc.setTextColor(80, 80, 80);
            doc.text(`Nome: ${service.nome}`, margin, yPosition);
            yPosition += 8;
            
            doc.text(`Telefone: ${service.telefone}`, margin, yPosition);
            yPosition += 8;
            
            doc.text(`CPF: ${service.cpf}`, margin, yPosition);
            yPosition += 15;
            
            // Dados do equipamento
            doc.setFontSize(14);
            doc.setFont(undefined, 'bold');
            doc.setTextColor(40, 40, 40);
            doc.text("DADOS DO EQUIPAMENTO", margin, yPosition);
            yPosition += 10;
            
            doc.setFontSize(12);
            doc.setFont(undefined, 'normal');
            doc.setTextColor(80, 80, 80);
            doc.text(`Modelo: ${service.modelo}`, margin, yPosition);
            yPosition += 8;
            
            doc.text(`Data de Entrada: ${formatDate(service.data)}`, margin, yPosition);
            yPosition += 15;
            
            // Defeito relatado
            doc.setFontSize(14);
            doc.setFont(undefined, 'bold');
            doc.setTextColor(40, 40, 40);
            doc.text("DEFeito RELATADO", margin, yPosition);
            yPosition += 10;
            
            doc.setFontSize(12);
            doc.setFont(undefined, 'normal');
            doc.setTextColor(80, 80, 80);
            const defects = doc.splitTextToSize(service.defeito, contentWidth);
            doc.text(defects, margin, yPosition);
            yPosition += (defects.length * 6) + 15;
            
            // Observações
            doc.setFontSize(14);
            doc.setFont(undefined, 'bold');
            doc.setTextColor(40, 40, 40);
            doc.text("OBSERVAÇÕES", margin, yPosition);
            yPosition += 10;
            
            doc.setFontSize(12);
            doc.setFont(undefined, 'normal');
            doc.setTextColor(80, 80, 80);
            const observations = [
                "1. O equipamento será avaliado e o cliente será contactado com o orçamento.",
                "2. O prazo para execução do serviço inicia após a aprovação do orçamento.",
                "3. O equipamento não retirado em até 90 dias será considerado abandonado.",
                "4. A loja não se responsabiliza por dados eventualmente perdidos.",
                "5. É Cobrado uma taxa de R$50,00 para avaliação."
            ];
            
            observations.forEach(obs => {
                const obsLines = doc.splitTextToSize(obs, contentWidth);
                doc.text(obsLines, margin, yPosition);
                yPosition += (obsLines.length * 6) + 5;
            });
            
            yPosition += 10;
            
            // Assinaturas
            doc.setDrawColor(200, 200, 200);
            doc.line(margin, yPosition, pageWidth - margin, yPosition);
            yPosition += 15;
            
            doc.setFontSize(12);
            doc.setFont(undefined, 'bold');
            doc.setTextColor(40, 40, 40);
            doc.text("ASSINATURAS", pageWidth / 2, yPosition, { align: 'center' });
            yPosition += 15;
            
            doc.setFontSize(10);
            doc.setFont(undefined, 'normal');
            doc.text("_________________________________________", margin, yPosition);
            doc.text("Cliente", margin, yPosition + 8);
            
            doc.text("_________________________________________", pageWidth - margin, yPosition, { align: 'right' });
            doc.text("THOR04 INFORMATICA", pageWidth - margin, yPosition + 8, { align: 'right' });
            
            // Rodapé
            doc.setFontSize(10);
            doc.setTextColor(150, 150, 150);
            doc.text("Documento gerado automaticamente pelo sistema THOR04 INFORMATICA", pageWidth / 2, doc.internal.pageSize.getHeight() - margin, { align: 'center' });
            
            // Salvar o PDF
            doc.save(`Ordem_Servico_${service.id}_${service.nome.replace(/\s/g, '_')}.pdf`);
        }
        
        // Cadastrar nova ordem de serviço
        document.getElementById('service-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Validar campos antes de enviar
            const telefone = document.getElementById('telefone').value;
            const cpf = document.getElementById('cpf').value;
            
            const telefoneValido = validarTelefone(telefone);
            const cpfValido = validarCPF(cpf);
            
            if (!telefoneValido) {
                document.getElementById('telefone').classList.add('error');
                document.getElementById('telefone-error').style.display = 'block';
                document.getElementById('telefone').focus();
                return;
            }
            
            if (!cpfValido) {
                document.getElementById('cpf').classList.add('error');
                document.getElementById('cpf-error').style.display = 'block';
                document.getElementById('cpf').focus();
                return;
            }
            
            const newService = {
                id: Date.now(),
                nome: document.getElementById('nome').value,
                telefone: document.getElementById('telefone').value,
                cpf: document.getElementById('cpf').value,
                modelo: document.getElementById('modelo').value,
                defeito: document.getElementById('defeito').value,
                data: document.getElementById('data').value
            };
            
            const services = getServices();
            services.push(newService);
            saveServices(services);
            
            alert('Ordem de serviço cadastrada com sucesso!');
            
            // Gerar o PDF da ordem de serviço
            generateServiceOrderPDF(newService);
            
            this.reset();
            document.getElementById('data').valueAsDate = new Date();
        });
        
        // Carregar serviços na página de consulta
        function loadServices(filter = 'all', searchTerm = '') {
            const services = getServices();
            const servicesList = document.getElementById('services-list');
            
            if (services.length === 0) {
                servicesList.innerHTML = '<div class="no-services">Nenhuma ordem de serviço cadastrada ainda.</div>';
                return;
            }
            
            // Aplicar filtros
            let filteredServices = services;
            
            if (filter !== 'all') {
                const today = new Date();
                filteredServices = services.filter(service => {
                    const serviceDate = new Date(service.data);
                    
                    if (filter === 'recent') {
                        return serviceDate.toDateString() === today.toDateString();
                    } else if (filter === 'last-week') {
                        const oneWeekAgo = new Date();
                        oneWeekAgo.setDate(today.getDate() - 7);
                        return serviceDate >= oneWeekAgo;
                    } else if (filter === 'last-month') {
                        const oneMonthAgo = new Date();
                        oneMonthAgo.setMonth(today.getMonth() - 1);
                        return serviceDate >= oneMonthAgo;
                    }
                    return true;
                });
            }
            
            // Aplicar busca
            if (searchTerm) {
                const term = searchTerm.toLowerCase();
                filteredServices = filteredServices.filter(service => 
                    service.nome.toLowerCase().includes(term) ||
                    service.modelo.toLowerCase().includes(term) ||
                    service.defeito.toLowerCase().includes(term)
                );
            }
            
            // Ordenar por data (mais recente primeiro)
            filteredServices.sort((a, b) => new Date(b.data) - new Date(a.data));
            
            // Exibir serviços
            servicesList.innerHTML = '';
            
            if (filteredServices.length === 0) {
                servicesList.innerHTML = '<div class="no-services">Nenhuma ordem de serviço encontrada com os critérios selecionados.</div>';
                return;
            }
            
            filteredServices.forEach(service => {
                const serviceCard = document.createElement('div');
                serviceCard.className = 'service-card';
                serviceCard.innerHTML = `
                    <h3>${service.nome}</h3>
                    <p><strong>Nº da Ordem:</strong> ${service.id}</p>
                    <p><strong>Telefone:</strong> ${service.telefone}</p>
                    <p><strong>CPF:</strong> ${service.cpf}</p>
                    <p><strong>Aparelho:</strong> ${service.modelo}</p>
                    <p><strong>Defeito:</strong> ${service.defeito}</p>
                    <p><strong>Data de Entrada:</strong> ${formatDate(service.data)}</p>
                    <div class="service-actions">
                        <button class="pdf-btn" data-id="${service.id}">Gerar PDF</button>
                        <button class="print-btn" data-id="${service.id}">Imprimir</button>
                        <button class="complete-btn" data-id="${service.id}">Concluir</button>
                        <button class="delete-btn" data-id="${service.id}">Excluir</button>
                    </div>
                `;
                servicesList.appendChild(serviceCard);
            });
            
            // Adicionar event listeners aos botões de exclusão
            document.querySelectorAll('.delete-btn').forEach(btn => {
                btn.addEventListener('click', function() {
                    const serviceId = parseInt(this.getAttribute('data-id'));
                    showDeleteModal(serviceId);
                });
            });
            
            // Adicionar event listeners aos botões de conclusão
            document.querySelectorAll('.complete-btn').forEach(btn => {
                btn.addEventListener('click', function() {
                    const serviceId = parseInt(this.getAttribute('data-id'));
                    showCompleteModal(serviceId);
                });
            });
            
            // Adicionar event listeners aos botões de PDF
            document.querySelectorAll('.pdf-btn').forEach(btn => {
                btn.addEventListener('click', function() {
                    const serviceId = parseInt(this.getAttribute('data-id'));
                    const services = getServices();
                    const service = services.find(s => s.id === serviceId);
                    if (service) {
                        generateServiceOrderPDF(service);
                    }
                });
            });
            
            // Adicionar event listeners aos botões de impressão
            document.querySelectorAll('.print-btn').forEach(btn => {
                btn.addEventListener('click', function() {
                    const serviceId = parseInt(this.getAttribute('data-id'));
                    const services = getServices();
                    const service = services.find(s => s.id === serviceId);
                    if (service) {
                        printServiceOrder(service);
                    }
                });
            });
        }
        
        // Carregar serviços concluídos
        function loadConcludedServices(filter = 'all', searchTerm = '') {
            const services = getConcludedServices();
            const concludedList = document.getElementById('concluded-list');
            
            if (services.length === 0) {
                concludedList.innerHTML = '<div class="no-services">Nenhum serviço concluído ainda.</div>';
                return;
            }
            
            // Aplicar filtros
            let filteredServices = services;
            
            if (filter !== 'all') {
                const today = new Date();
                filteredServices = services.filter(service => {
                    const serviceDate = new Date(service.dataConclusao || service.data);
                    
                    if (filter === 'recent') {
                        return serviceDate.toDateString() === today.toDateString();
                    } else if (filter === 'last-week') {
                        const oneWeekAgo = new Date();
                        oneWeekAgo.setDate(today.getDate() - 7);
                        return serviceDate >= oneWeekAgo;
                    } else if (filter === 'last-month') {
                        const oneMonthAgo = new Date();
                        oneMonthAgo.setMonth(today.getMonth() - 1);
                        return serviceDate >= oneMonthAgo;
                    }
                    return true;
                });
            }
            
            // Aplicar busca
            if (searchTerm) {
                const term = searchTerm.toLowerCase();
                filteredServices = filteredServices.filter(service => 
                    service.nome.toLowerCase().includes(term) ||
                    service.modelo.toLowerCase().includes(term) ||
                    service.defeito.toLowerCase().includes(term)
                );
            }
            
            // Ordenar por data (mais recente primeiro)
            filteredServices.sort((a, b) => new Date(b.dataConclusao || b.data) - new Date(a.dataConclusao || a.data));
            
            // Exibir serviços
            concludedList.innerHTML = '';
            
            if (filteredServices.length === 0) {
                concludedList.innerHTML = '<div class="no-services">Nenhum serviço concluído encontrado com os critérios selecionados.</div>';
                return;
            }
            
            filteredServices.forEach(service => {
                const serviceCard = document.createElement('div');
                serviceCard.className = 'service-card concluded';
                serviceCard.innerHTML = `
                    <span class="concluded-badge">Concluído</span>
                    <h3>${service.nome}</h3>
                    <p><strong>Nº da Ordem:</strong> ${service.id}</p>
                    <p><strong>Telefone:</strong> ${service.telefone}</p>
                    <p><strong>CPF:</strong> ${service.cpf}</p>
                    <p><strong>Aparelho:</strong> ${service.modelo}</p>
                    <p><strong>Defeito:</strong> ${service.defeito}</p>
                    <p><strong>Data de Entrada:</strong> ${formatDate(service.data)}</p>
                    <p><strong>Data de Conclusão:</strong> ${formatDate(service.dataConclusao)}</p>
                    <div class="service-actions">
                        <button class="pdf-btn" data-id="${service.id}">Gerar PDF</button>
                        <button class="print-btn" data-id="${service.id}">Imprimir</button>
                        <button class="delete-btn" data-id="${service.id}">Excluir</button>
                    </div>
                `;
                concludedList.appendChild(serviceCard);
            });
            
            // Adicionar event listeners aos botões de exclusão
            document.querySelectorAll('#concluded-list .delete-btn').forEach(btn => {
                btn.addEventListener('click', function() {
                    const serviceId = parseInt(this.getAttribute('data-id'));
                    showDeleteConcludedModal(serviceId);
                });
            });
            
            // Adicionar event listeners aos botões de PDF
            document.querySelectorAll('#concluded-list .pdf-btn').forEach(btn => {
                btn.addEventListener('click', function() {
                    const serviceId = parseInt(this.getAttribute('data-id'));
                    const services = getConcludedServices();
                    const service = services.find(s => s.id === serviceId);
                    if (service) {
                        generateServiceOrderPDF(service);
                    }
                });
            });
            
            // Adicionar event listeners aos botões de impressão
            document.querySelectorAll('#concluded-list .print-btn').forEach(btn => {
                btn.addEventListener('click', function() {
                    const serviceId = parseInt(this.getAttribute('data-id'));
                    const services = getConcludedServices();
                    const service = services.find(s => s.id === serviceId);
                    if (service) {
                        printServiceOrder(service);
                    }
                });
            });
        }
        
        // Função para imprimir a ordem de serviço
        function printServiceOrder(service) {
            const printWindow = window.open('', '_blank');
            printWindow.document.write(`
                <!DOCTYPE html>
                <html>
                <head>
                    <title>THOR04 INFORMATICA - Ordem de Serviço ${service.id}</title>
                    <style>
                        body {
                            font-family: Arial, sans-serif;
                            margin: 20px;
                            color: #333;
                        }
                        .header {
                            text-align: center;
                            margin-bottom: 20px;
                            border-bottom: 2px solid #4a6491;
                            padding-bottom: 10px;
                        }
                        .header h1 {
                            color: #2c3e50;
                            margin-bottom: 5px;
                        }
                        .header h2 {
                            color: #4a6491;
                            margin: 0;
                        }
                        .info-section {
                            margin-bottom: 20px;
                        }
                        .info-section h3 {
                            background-color: #f5f7fa;
                            padding: 8px;
                            border-left: 4px solid #4a6491;
                        }
                        .info-item {
                            margin: 8px 0;
                        }
                        .signatures {
                            margin-top: 40px;
                            display: flex;
                            justify-content: space-between;
                        }
                        .signature-line {
                            border-top: 1px solid #333;
                            width: 250px;
                            padding-top: 5px;
                            text-align: center;
                        }
                        @media print {
                            body {
                                margin: 0;
                                padding: 15px;
                            }
                            .no-print {
                                display: none;
                            }
                        }
                        .footer {
                            margin-top: 50px;
                            text-align: center;
                            font-size: 12px;
                            color: #777;
                        }
                    </style>
                </head>
                <body>
                    <div class="header">
                        <h1>THOR04 INFORMATICA</h1>
                        <h2>ORDEM DE SERVIÇO</h2>
                        <p>Tel: (11) 9999-9999 | Email: contato@thor04informatica.com</p>
                    </div>
                    
                    <div class="info-section">
                        <h3>NÚMERO DA ORDEM: ${service.id}</h3>
                        <p><strong>Data de Emissão:</strong> ${new Date().toLocaleDateString('pt-BR')}</p>
                    </div>
                    
                    <div class="info-section">
                        <h3>DADOS DO CLIENTE</h3>
                        <div class="info-item"><strong>Nome:</strong> ${service.nome}</div>
                        <div class="info-item"><strong>Telefone:</strong> ${service.telefone}</div>
                        <div class="info-item"><strong>CPF:</strong> ${service.cpf}</div>
                    </div>
                    
                    <div class="info-section">
                        <h3>DADOS DO EQUIPAMENTO</h3>
                        <div class="info-item"><strong>Modelo:</strong> ${service.modelo}</div>
                        <div class="info-item"><strong>Data de Entrada:</strong> ${formatDate(service.data)}</div>
                    </div>
                    
                    <div class="info-section">
                        <h3>DEFEITO RELATADO</h3>
                        <div class="info-item">${service.defeito}</div>
                    </div>
                    
                    <div class="info-section">
                        <h3>OBSERVAÇÕES</h3>
                        <ol>
                            <li>O equipamento será avaliado e o cliente será contactado com o orçamento.</li>
                            <li>O prazo para execução do serviço inicia após a aprovação do orçamento.</li>
                            <li>O equipamento não retirado em até 90 dias será considerado abandonado.</li>
                            <li>A loja não se responsabiliza por dados eventualmente perdidos.</li>
                            <li>É Cobrado uma taxa de R$50,00 para avaliação</li>
                        </ol>
                    </div>
                    
                    <div class="signatures">
                        <div class="signature-line">Cliente</div>
                        <div class="signature-line">THOR04 INFORMATICA</div>
                    </div>
                    
                    <div class="footer">
                        <p>Documento gerado automatizadamente pelo sistema THOR04 INFORMATICA</p>
                    </div>
                    
                    <div class="no-print" style="margin-top: 20px; text-align: center;">
                        <button onclick="window.print()">Imprimir</button>
                        <button onclick="window.close()">Fechar</button>
                    </div>
                    
                    <script>
                        window.onload = function() {
                            window.print();
                        };
                    <\/script>
                </body>
                </html>
            `);
            printWindow.document.close();
        }
        
        // Mostrar modal de confirmação de exclusão
        function showDeleteModal(serviceId) {
            serviceToDelete = serviceId;
            document.getElementById('delete-modal').style.display = 'flex';
        }
        
        // Mostrar modal de confirmação de conclusão
        function showCompleteModal(serviceId) {
            serviceToComplete = serviceId;
            document.getElementById('complete-modal').style.display = 'flex';
        }
        
        // Mostrar modal de confirmação de exclusão de serviço concluído
        function showDeleteConcludedModal(serviceId) {
            serviceToDelete = serviceId;
            document.getElementById('delete-modal').style.display = 'flex';
        }
        
        // Fechar modal de confirmação
        document.getElementById('modal-cancel').addEventListener('click', function() {
            document.getElementById('delete-modal').style.display = 'none';
            serviceToDelete = null;
        });
        
        // Fechar modal de conclusão
        document.getElementById('complete-modal-cancel').addEventListener('click', function() {
            document.getElementById('complete-modal').style.display = 'none';
            serviceToComplete = null;
        });
        
        // Confirmar exclusão
        document.getElementById('modal-confirm').addEventListener('click', function() {
            if (serviceToDelete !== null) {
                // Verificar se estamos na aba de concluídos
                const isConcludedTab = document.getElementById('concluded').classList.contains('active');
                
                if (isConcludedTab) {
                    deleteConcludedService(serviceToDelete);
                } else {
                    deleteService(serviceToDelete);
                }
                
                document.getElementById('delete-modal').style.display = 'none';
                serviceToDelete = null;
            }
        });
        
        // Confirmar conclusão
        document.getElementById('complete-modal-confirm').addEventListener('click', function() {
            if (serviceToComplete !== null) {
                completeService(serviceToComplete);
                document.getElementById('complete-modal').style.display = 'none';
                serviceToComplete = null;
            }
        });
        
        // Excluir serviço
        function deleteService(serviceId) {
            const services = getServices();
            const updatedServices = services.filter(service => service.id !== serviceId);
            saveServices(updatedServices);
            
            // Recarregar a lista de serviços
            const activeFilter = document.querySelector('.filter-btn.active').dataset.filter;
            const searchTerm = document.getElementById('search-input').value;
            loadServices(activeFilter, searchTerm);
            
            alert('Ordem de serviço excluída com sucesso!');
        }
        
        // Excluir serviço concluído
        function deleteConcludedService(serviceId) {
            const services = getConcludedServices();
            const updatedServices = services.filter(service => service.id !== serviceId);
            saveConcludedServices(updatedServices);
            
            // Recarregar a lista de serviços concluídos
            const activeFilter = document.querySelector('[data-concluded-filter].active').dataset.concludedFilter;
            const searchTerm = document.getElementById('search-concluded-input').value;
            loadConcludedServices(activeFilter, searchTerm);
            
            alert('Serviço concluído excluído com sucesso!');
        }
        
        // Concluir serviço
        function completeService(serviceId) {
            const services = getServices();
            const serviceIndex = services.findIndex(service => service.id === serviceId);
            
            if (serviceIndex !== -1) {
                // Adicionar data de conclusão
                const completedService = {
                    ...services[serviceIndex],
                    dataConclusao: new Date().toISOString().split('T')[0]
                };
                
                // Adicionar aos serviços concluídos
                const concludedServices = getConcludedServices();
                concludedServices.push(completedService);
                saveConcludedServices(concludedServices);
                
                // Remover dos serviços ativos
                services.splice(serviceIndex, 1);
                saveServices(services);
                
                // Recarregar a lista de serviços
                const activeFilter = document.querySelector('.filter-btn.active').dataset.filter;
                const searchTerm = document.getElementById('search-input').value;
                loadServices(activeFilter, searchTerm);
                
                alert('Serviço marcado como concluído com sucesso!');
            }
        }
        
        // Configurar busca na aba de serviços ativos
        document.getElementById('search-btn').addEventListener('click', () => {
            const searchTerm = document.getElementById('search-input').value;
            const activeFilter = document.querySelector('.filter-btn.active').dataset.filter;
            loadServices(activeFilter, searchTerm);
        });
        
        // Configurar busca na aba de serviços concluídos
        document.getElementById('search-concluded-btn').addEventListener('click', () => {
            const searchTerm = document.getElementById('search-concluded-input').value;
            const activeFilter = document.querySelector('[data-concluded-filter].active').dataset.concludedFilter;
            loadConcludedServices(activeFilter, searchTerm);
        });
        
        // Configurar filtros na aba de serviços ativos
        document.querySelectorAll('.filter-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                
                const searchTerm = document.getElementById('search-input').value;
                loadServices(btn.dataset.filter, searchTerm);
            });
        });
        
        // Configurar filtros na aba de serviços concluídos
        document.querySelectorAll('[data-concluded-filter]').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('[data-concluded-filter]').forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                
                const searchTerm = document.getElementById('search-concluded-input').value;
                loadConcludedServices(btn.dataset.concludedFilter, searchTerm);
            });
        });
        
        // Permitir busca com Enter na aba de serviços ativos
        document.getElementById('search-input').addEventListener('keyup', (e) => {
            if (e.key === 'Enter') {
                document.getElementById('search-btn').click();
            }
        });
        
        // Permitir busca com Enter na aba de serviços concluídos
        document.getElementById('search-concluded-input').addEventListener('keyup', (e) => {
            if (e.key === 'Enter') {
                document.getElementById('search-concluded-btn').click();
            }
        });
        
        // Visualizar JSON
        document.getElementById('view-json-btn').addEventListener('click', () => {
            const services = getServices();
            const concludedServices = getConcludedServices();
            const allData = {
                ativos: services,
                concluidos: concludedServices
            };
            
            const jsonView = document.getElementById('json-view');
            
            if (jsonView.style.display === 'none') {
                jsonView.textContent = JSON.stringify(allData, null, 2);
                jsonView.style.display = 'block';
            } else {
                jsonView.style.display = 'none';
            }
        });
        
        // Exportar JSON
        document.getElementById('export-json-btn').addEventListener('click', () => {
            const services = getServices();
            const concludedServices = getConcludedServices();
            const allData = {
                ativos: services,
                concluidos: concludedServices
            };
            
            const dataStr = JSON.stringify(allData, null, 2);
            const dataUri = 'data:application/json;charset=utf-8,'+ encodeURIComponent(dataStr);
            
            const exportFileDefaultName = 'thor04_ordens_servico.json';
            
            const linkElement = document.createElement('a');
            linkElement.setAttribute('href', dataUri);
            linkElement.setAttribute('download', exportFileDefaultName);
            linkElement.click();
        });
        
        // Importar JSON
        document.getElementById('import-json-btn').addEventListener('click', () => {
            document.getElementById('import-json-file').click();
        });
        
        document.getElementById('import-json-file').addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (!file) return;
            
            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const jsonData = JSON.parse(e.target.result);
                    
                    // Verificar se é o formato antigo (apenas array) ou novo (objeto com ativos e concluidos)
                    if (Array.isArray(jsonData)) {
                        // Formato antigo - apenas serviços ativos
                        const isValid = jsonData.every(item => 
                            item.hasOwnProperty('nome') && 
                            item.hasOwnProperty('telefone') && 
                            item.hasOwnProperty('modelo')
                        );
                        
                        if (isValid) {
                            saveServices(jsonData);
                            saveConcludedServices([]);
                            alert('Dados importados com sucesso!');
                            loadServices();
                            document.getElementById('json-view').textContent = JSON.stringify({ativos: jsonData, concluidos: []}, null, 2);
                            document.getElementById('json-view').style.display = 'block';
                        } else {
                            alert('O arquivo JSON não possui o formato correto.');
                        }
                    } else if (jsonData.ativos && jsonData.concluidos) {
                        // Formato novo - com serviços ativos e concluídos
                        const ativosValid = Array.isArray(jsonData.ativos) && jsonData.ativos.every(item => 
                            item.hasOwnProperty('nome') && 
                            item.hasOwnProperty('telefone') && 
                            item.hasOwnProperty('modelo')
                        );
                        
                        const concluidosValid = Array.isArray(jsonData.concluidos) && jsonData.concluidos.every(item => 
                            item.hasOwnProperty('nome') && 
                            item.hasOwnProperty('telefone') && 
                            item.hasOwnProperty('modelo')
                        );
                        
                        if (ativosValid && concluidosValid) {
                            saveServices(jsonData.ativos);
                            saveConcludedServices(jsonData.concluidos);
                            alert('Dados importados com sucesso!');
                            loadServices();
                            loadConcludedServices();
                            document.getElementById('json-view').textContent = JSON.stringify(jsonData, null, 2);
                            document.getElementById('json-view').style.display = 'block';
                        } else {
                            alert('O arquivo JSON não possui o formato correto.');
                        }
                    } else {
                        alert('O arquivo JSON deve conter um array de serviços ou um objeto com propriedades "ativos" e "concluidos".');
                    }
                } catch (error) {
                    alert('Erro ao processar o arquivo JSON: ' + error.message);
                }
            };
            reader.readAsText(file);
        });
        
        // Inicializar as páginas se necessário
        if (document.getElementById('consult').classList.contains('active')) {
            loadServices();
        }
        
        if (document.getElementById('concluded').classList.contains('active')) {
            loadConcludedServices();
        }
    </script>
</body>
</html>
