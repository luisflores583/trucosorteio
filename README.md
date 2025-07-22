🎴 Sorteador de Torneio de Truco
Sistema web para gerenciamento de torneios de Truco Paulista com eliminação dupla (repescagem), incluindo cadastro de equipes, sorteios automáticos e manuais, controle de resultados, disputa de 3º lugar e exportação de histórico.

✅ Funcionalidades Principais
📋 Cadastro de Equipes com nomes personalizados.

🎲 Sorteio Automático com restrição de prefixo na 1ª fase (evita confronto entre equipes com o mesmo prefixo).

🧮 Controle de Derrotas: equipes com 2 derrotas são eliminadas (marcadas em vermelho).

🔁 Chave A (Invictos) e Chave B (Repescagem) com cruzamento na fase final.

🟨 Confrontos entre invictos destacados com fundo amarelo.

⚔️ Disputa de 3º lugar automática.

💾 Salvar e Reabrir Torneios (JSON).

⏪ Desfazer Última Ação e Refazer Sorteio (sem computar resultados).

🕓 Histórico de Fases colorido por etapa.

📝 Exportação de histórico em PDF.

❌ Registro de W.O. com controle para não repetir contra a mesma equipe, salvo exceções.

🔧 Como Usar
Abrir o arquivo index.html em qualquer navegador moderno (Google Chrome, Firefox, Edge, etc.).

Cadastrar as equipes no campo específico.

Clique em "Sortear" para iniciar a primeira fase.

Registre os resultados de cada confronto.

Após cada fase, o sistema reorganiza automaticamente as chaves.

Acompanhe o histórico e salve os dados ao final.

📁 Estrutura dos Arquivos
bash
Copiar
Editar
📁 sorteio-truco/
├── index.html      # Página principal do sorteador
├── style.css       # Estilos customizados (opcional)
├── script.js       # Lógica principal do torneio
└── README.md       # Este documento
💡 Tecnologias Utilizadas
HTML5

CSS3

JavaScript (puro)

jsPDF (para gerar o histórico em PDF)

🚀 Possíveis Melhorias Futuras
Interface mobile responsiva.

Ranking geral dos participantes.

Compartilhamento de chave em tempo real (via QR Code ou link).

Modo "melhor de 3 partidas".

📌 Observações
O sistema não requer internet para funcionar.

Todos os dados são armazenados localmente no navegador enquanto a aba estiver aberta.
