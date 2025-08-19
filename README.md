Análise de Evasão de Clientes - Telecom X
🎯 Sobre o Projeto
Este repositório contém uma análise exploratória de dados (EDA) focada em entender os principais fatores que levam à evasão de clientes (churn) na empresa fictícia Telecom X. O objetivo é transformar dados brutos em insights acionáveis que possam guiar a criação de estratégias de retenção mais eficazes, visando a sustentabilidade e o crescimento do negócio.

🛠️ Metodologia
A análise foi conduzida utilizando Python com as bibliotecas Pandas, Matplotlib e Seaborn. O processo seguiu as seguintes etapas:

Extração e Carga: Os dados foram extraídos de uma API em formato JSON.

Limpeza e Tratamento (ETL):

Normalização: Conversão da estrutura aninhada do JSON para um DataFrame tabular.

Tratamento de Dados Ausentes: Preenchimento de valores nulos na coluna Fatura_Total para clientes novos.

Padronização: Unificação de categorias inconsistentes (ex: 'No internet service' para 'No').

Transformação: Conversão de colunas binárias ('Yes'/'No') para formato numérico (1/0) para viabilizar cálculos e modelagem futura.

Tradução: Renomeação de todas as colunas para o português para maior clareza.

📊 Principais Achados da Análise
A taxa geral de evasão na base de clientes analisada é de 26.5%. A análise revelou os seguintes fatores como os mais influentes no churn:

Tipo de Contrato: Clientes com contrato 'Mês a mês' possuem uma taxa de cancelamento drasticamente superior. A falta de um compromisso de longo prazo é um fator de vulnerabilidade chave.

Tempo de Contrato (Fidelidade): Clientes com poucos meses de casa são os mais propensos a cancelar. Os primeiros meses são críticos para a retenção.

Fatura Mensal: A evasão se concentra em clientes com faturas mais altas (faixa de $70 a $100), sugerindo uma baixa percepção de custo-benefício.

Método de Pagamento: O pagamento via 'Cheque eletrônico' está associado a uma taxa de churn muito superior, pois cria um ponto de fricção mensal para o cliente.

Serviço de Internet: Clientes com 'Fibra óptica' cancelam mais, o que pode indicar problemas de qualidade, suporte ou preço percebido como injusto para este serviço premium.

👤 Conclusões: A Persona do Cliente em Risco
A análise permitiu construir um perfil claro do cliente com maior probabilidade de evasão:

É um cliente novo (com poucos meses de contrato), que optou por um plano de Fibra Óptica com um valor mensal elevado. Ele possui um contrato flexível 'Mês a mês' e realiza o pagamento mensalmente através de cheque eletrônico, o que o força a reavaliar o serviço a cada fatura.

💡 Recomendações Estratégicas
Com base nos insights, as seguintes ações são recomendadas para a Telecom X:

Blindar o Início da Jornada do Cliente: Desenvolver um programa de onboarding robusto para clientes nos primeiros 3 meses.

Converter Contratos de Curto Prazo: Criar campanhas agressivas para migração de contratos 'Mês a mês' para planos anuais, oferecendo incentivos.

Auditoria do Serviço de Fibra Óptica: Realizar uma investigação aprofundada sobre a qualidade e o suporte do serviço para identificar a causa raiz do alto churn.

Reduzir Fricção no Pagamento: Incentivar a migração de 'Cheque eletrônico' para métodos de pagamento automáticos, oferecendo pequenos descontos.
