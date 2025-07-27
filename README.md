📈 Telecom X — Análise de Evasão de Clientes

🧠 Introdução

A empresa fictícia Telecom X enfrenta uma alta taxa de cancelamentos de clientes (churn) e precisa entender os fatores que influenciam esse comportamento.
Este projeto tem como objetivo realizar um processo completo de ETL (Extração, Transformação e Carga) e aplicar uma análise exploratória de dados para investigar o perfil dos clientes que tendem a abandonar a empresa.
A partir desses insights, serão propostas ações estratégicas para retenção de clientes.

🔗 Fonte dos Dados

Os dados utilizados estão disponíveis em:

TelecomX_Data.json

⚙️ Etapas do Projeto

1. Extração

Importação dos dados diretamente de um arquivo JSON hospedado no GitHub.
Conversão para DataFrame Pandas.

2. Transformação
Verificação e tratamento de valores ausentes.
Conversão de colunas binárias (Yes/No) para valores numéricos (0/1).
Ajuste dos tipos de dados para facilitar análises.
Renomeação de variáveis e rótulos para melhor visualização.

3. Análise
Estatísticas descritivas por grupo de churn.
Visualização da distribuição de churn (gráficos de barras e pizza).
Análise de churn por variáveis categóricas (contrato, método de pagamento, dependentes, etc.).
Análise de churn por variáveis numéricas (tempo de contrato, gastos mensais e totais).

📊 Principais Resultados

Taxa de churn: Aproximadamente 26,5% dos clientes cancelaram o serviço.
Tipo de contrato: Contratos mensais apresentaram maior evasão; contratos de 1 ou 2 anos mostraram maior fidelidade.
Método de pagamento: Cheque eletrônico está associado a maior churn; métodos automáticos têm menor evasão.
Perfil de clientes: Clientes sem dependentes ou parceiros e com pouco tempo de contrato são mais propensos a cancelar.
Gasto total: Clientes que cancelaram tinham, em média, menor gasto total e menor tempo de contrato.

💡 Insights e Recomendações
Foco em novos clientes: Programas de fidelidade ou benefícios nos primeiros meses podem reduzir churn precoce.
Incentivo a contratos longos: Oferecer descontos ou bônus para contratos anuais ou bienais.
Promoção de pagamentos automáticos: Incentivar métodos automáticos com cashback ou bônus.
Atenção a perfis de risco: Monitorar clientes com contrato mensal, sem dependentes e com alta mensalidade.
