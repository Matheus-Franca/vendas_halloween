# Festa em Cena
## Machine Learning e Visão Computacional - Turma 05

Projeto Avaliativo - Módulo 1 - Semana 07

#### Contextualização 

A Festa em Cena é uma rede fictícia que vende fantasias e acessórios para o Halloween pelos canais Mercado, Loja física e Web. Mercado representa vendas para consumidores finais nos caixas de supermercados parceiros; Loja física representa lojas próprias; Web representa pedidos feitos pelo site. A empresa precisa organizar seus registros e entender como os pedidos variam por canal e período.

Neste projeto foi utilizada uma base de dados fictícia no formato CSV. A partir dessses dados foi realizado:

- Carregamento dos dados em um DataFrame
- Análise Exploratória
- Validação e Tratamento de dados Ausentes
- Padronização de strings utilizando regex
- Formatação de datas utilizando DateTime
- Filtros e Validações das Regras de negócio

--- 

## **Passos para execução local:**

Para execução do projeto foi desenvolvido o arquivo "vendas_halloween.ipynb". Caso você tenha interesse em rodar o código localmente no seu computador você precisará ter instalado em sua máquina alguns recursos:

- Python versão 3.11 ou outra mais recente
- Editor de código-fonte (VScode ou Jupyter Notebook por exemplo)
- Caso utilize o VScode você precisará instalar a extensão Jupyter

Após ter baixado e instalado os recursos acima, prossiga:

### 1° Passo
Faça o download do diretório completo deste projeto. No github você pode baixar a pasta compactada no formato ZIP ou você pode utilizar o git e clonar o projeto diretamente para algum diretorio do seu computador. 

### 2° Passo
Caso tenha baixado no formato ZIP, descompacte a pasta.

Após ter a pasta do projeto completa no seu computador, abra o seu editor de código-fonte e carregue a pasta do projeto nele.

### 3° Passo
Abra um novo terminal de comando e instale as bibliotecas Pandas e Numpy, que foram utilizadas neste projeto. Para fazer a instalação, copie, cole e rode no terminal o seguinte comando:

`pip install pandas numpy`

### 4° Passo
Agora abra no editor de código o arquivo "vendas_halloween.ipynb" e execute as células de código. Você pode executar uma a uma e verificar o que está acontecendo em cada uma delas, ou pode optar por executar todas de uma vez e ir verificando o código e suas saídas.

---

### Fonte de Dados
O arquivo de dados já está presente na pasta do projeto, é o arquivo chamado "halloween_vendas.csv" e ao executar a segunda célula de código, os dados serão importados para o tratamento
