# challenge-churn-clientes-telecomx
Projeto "Churn de Clientes". Empresa enfrenta um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes.
Desafio: coletar, tratar e analisar os dados, utilizando Python e suas principais bibliotecas para extrair insights.
Praticado no projeto: 
✅ Importar e manipular dados de uma API de forma eficiente.
✅ Aplicar os conceitos de ETL (Extração, Transformação e Carga) na preparação dos dados.
✅ Criar visualizações de dados estratégicas para identificar padrões e tendências.
✅ Realizar uma Análise Exploratória de Dados (EDA) e gerar um relatório com insights relevantes.

Introdução
Projeto desenvolvido como parte do programa Oracle Next Education - Alura, na trilha de Data Science.
O objetivo é analisar a evasão de clientes (churn) de uma empresa de telecomunicações, utilizando ferramentas de ciência de dados para identificar padrões e fatores que influenciam na perda de clientes.

---

## ❓ Problema

A empresa enfrenta um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes. Identificar esses fatores é essencial para criar estratégias de retenção mais eficazes.

---

## 🎯 O que o projeto faz
Limpeza e Tratamento de Dados:
- Realizada a importação de arquivo em json
-Leitura de dicionário em md para entendimento das colunas que posteriormente foram ampliadas
- Coleta, tratamento e análise dos dados. Ao identificar valores vazios na coluna churn, opto por não usá-las ara inicio das análises e realizo exclusão. Criado uma variável dos churns vazios para possíveis análises futuras.-Após limpeza dos dados (exclusão de valores nulos em Churn), restaram 7.043 registros válidos.
-A base foi expandida de 6 para 21 colunas para facilitar a análise dos serviços e comportamento dos clientes.
-Análises para: distribuição valores mensais, suporte técnico, onlineBackup, streaming TV e de filmes, segurança online, tipo de contrato, formas de pagamentos, senioridade dos clientes (sim ou não), gênero, fatura em boletos, serviço de telefone e se há múltiplas linhas, proteção de aparelho, tipo de internet. Para melhor visualização dessas análises, gráficos foram criados cruzando as informações com o Churn – Yes.
-Tecnologias: de Python e suas principais bibliotecas (Pandas, Seaborn, Matplotlib, etc.)
-Ambiente: Jupyter Notebook (utilizado via Google Colab).


## 📁 Estrutura do Projeto

```bash
📄 challenge_telecom.ipynb           # Notebook principal do projeto
📄 TelecomX_BR.ipynb                 # Análise no Colab
📄 TelecomX_Data.json                # Base de dados original
📄 TelecomX_dicionario.md            # Dicionário de dados

---

📊 Insights e Conclusões
    • O churn representa 26,5% do total, com 1.869 cancelamentos e 5.174 clientes retidos.
    • Há uma tendência a não adesão de serviços x churn ‘Yes’
    • Cliente com suporte técnico tem o maior índice de permanência, o mesmo para segurança online. 
    • Faturas mensais demostram maior evasão . Para contrato de dois anos a evasão é ínfima. 
    • Pagamentos realizados em cartões de crédito, cheque e transferências bancárias são superiormente duradouros como clientes
    • Seniores (acima 65 anos) são mais fiéis em permanecer 
    • Clientes antigos são mais fiéis
    • A faixa de pagamentos entre 70 e 110 reais aproximadamente, demostram maior evasão.
Principais Tendências Associadas ao Churn:

Fator	% de Cancelamento
Pagam entre R$70–110	66,4%
Não utilizam suporte técnico	41,6%
Sem backup online	39,9%
Sem segurança online	41,8%
Contrato mensal	42,7%
Pagamento por electronic check	45,3%
Clientes com 65+ anos	41,7%
Sem proteção de aparelho	39,1%

Recomendações: 
Com o entendimento de que serviços extras tendem a manter mais o cliente, assim bem como os números para proteção e apoio tem maior relevância na amostragem coletada, uma boa estratégia seria estimular, dar treinamentos e poder de barganha para equipe de vendas melhor ofertar o portifólio, explorando as vantagens da aderência dos pacotes completos.



👤 Autor
    • Veronica Carvalho
🔗 LinkedIn https://www.linkedin.com/in/ver%C3%B4nica-carvalho
💻 GitHub https://github.com/VeronicaDSC
