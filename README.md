Análise de Dados de Produtos de Supermercado
Este projeto realiza uma análise de dados de produtos de um supermercado, focando em entender as médias de preços, descontos e comportamentos estatísticos por categoria de produto e marca. Utilizando bibliotecas como pandas, matplotlib e plotly, o projeto gera visualizações informativas e interativas.

Índice
Instalação
Uso
Análise Realizada
Resultados
Licença
Instalação
Para executar este projeto, você precisa ter o Python 3 e as seguintes bibliotecas instaladas:

bash
Copiar código
pip install pandas matplotlib plotly
Certifique-se de ter um ambiente virtual configurado (opcional, mas recomendado).

Uso
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu_usuario/projeto_supermercado.git
cd projeto_supermercado
Execute o script Python: Certifique-se de que o arquivo CSV de dados esteja no diretório correto e atualize o caminho no código, se necessário. Em seguida, execute:

bash
Copiar código
python analise_supermercado.py
Análise Realizada
O projeto consiste nas seguintes etapas:

Leitura de Dados:

O conjunto de dados é carregado a partir de um arquivo CSV.
Média e Mediana dos Preços:

Cálculo da média e mediana dos preços normais por categoria de produto.
Identificação de categorias com média significativamente diferente da mediana.
Desvio Padrão por Categoria:

Cálculo do desvio padrão dos preços normais por categoria.
Análise do comportamento da média e mediana nas categorias com maior desvio.
Visualização da Distribuição de Preços:

Geração de um boxplot para a categoria com o maior desvio padrão, mostrando a distribuição dos dados e a presença de outliers.
Gráfico de Médias de Descontos:

Criação de um gráfico de barras que apresenta a média de descontos por categoria de produto.
Gráfico Interativo de Descontos:

Desenvolvimento de um gráfico de barras interativo que mostra a média de descontos por categoria e marca, permitindo melhor visualização e interação.
Resultados
Os resultados da análise são apresentados por meio de gráficos e estatísticas que facilitam a compreensão das tendências e padrões nos dados. O projeto destaca:

Categorias com preços normais acima ou abaixo da mediana.
Comportamento dos preços em relação ao desvio padrão.
Distribuição de preços, incluindo identificação de outliers.
Médias de desconto, com um foco nas categorias e marcas.
