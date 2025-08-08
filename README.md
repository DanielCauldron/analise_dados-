# 📊 Análise de Dados de Salários de Profissionais de Tecnologia nos EUA
Este notebook realiza uma análise exploratória de um dataset contendo informações sobre salários de profissionais de tecnologia nos Estados Unidos.
O objetivo é entender o perfil dos profissionais, tipos de contratação, regimes de trabalho e características das empresas.

📂 Estrutura do Projeto
analise.ipynb → Notebook principal com toda a análise.

salaries.csv → Fonte de dados original.

data_processed/ → Pasta sugerida para salvar dados tratados.

🔍 Principais Etapas do Notebook

1️⃣ Importação de Bibliotecas
Utiliza pandas para manipulação de dados.

2️⃣ Leitura dos Dados
Carrega o arquivo CSV com pd.read_csv.

3️⃣ Exploração Inicial
Visualização das primeiras linhas (head),

Informações gerais (info),

Estatísticas descritivas (describe),

Formato do dataset (shape).

4️⃣ Renomeação das Colunas
Colunas renomeadas do inglês para o português para facilitar a análise.

5️⃣ Análise de Colunas Categóricas
Identificação de categorias em:

Nível de experiência

Tipo de contratação

Regime de trabalho remoto

Porte da empresa

6️⃣ Mapeamento de Categorias
Tradução para o português, por exemplo:

'SE' → senior

'FT' → integral

7️⃣ Estatísticas Descritivas
Estatísticas para colunas categóricas

Verificação das alterações realizadas

8️⃣ Respostas a Perguntas-Chave
O notebook responde questões como:

Qual o nível de experiência mais comum?

Qual o tipo de contrato mais frequente?

Qual o cargo mais frequente?

Qual o país de residência mais comum dos profissionais?

Onde estão sediadas a maioria das empresas?

Qual o regime de trabalho mais comum?

Qual o porte mais comum das empresas?

ℹ️ Observações
O notebook está em português e os nomes das colunas/categorias foram adaptados para facilitar a compreensão.

O dataset analisado é público e contém informações fictícias ou anonimizadas.

💡 Exemplo de Uso
Notebook desenvolvido para fins de estudo e análise de dados de salários em tecnologia.

📎 Veja o notebook completo em analise.ipynb
