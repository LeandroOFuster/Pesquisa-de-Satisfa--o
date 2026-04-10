📊 Pesquisa de Satisfação - TudoWeb
Algoritmo em Python para coleta e análise de respostas de uma pesquisa de satisfação com atendimento.

📋 Descrição
O programa coleta avaliações de múltiplos entrevistados sobre a qualidade do atendimento, contabilizando as respostas EXCELENTE e RUIM ao final da pesquisa.

⚙️ Funcionamento

O programa percorre um número definido de entrevistados (padrão: 10, recomendado: 50)
Para cada entrevistado, solicita:

Nome
Idade
Avaliação do atendimento


O entrevistado escolhe uma das opções:

1 → EXCELENTE
2 → BOM
3 → RUIM


Ao final, exibe o total de respostas EXCELENTE e RUIM


🚀 Como executar
Pré-requisitos

Python 3.x instalado

Execução
bashpython "Pesquisa de Satisfação.py"

🔧 Configuração
Para alterar o número de entrevistados, edite a linha:
pythontotal_entrevistados = 10  # Altere para 50 em produção

📁 Estrutura
📦 Pesquisa de Satisfação
 └── Pesquisa de Satisfação.py   # Script principal

📌 Observações

Opções inválidas exibem a mensagem "Opção inválida!" e não são contabilizadas
Respostas BOM (opção 2) não entram no resultado final
