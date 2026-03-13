# Análise de Produtividade e Saúde Mental Estudantil 

## Objetivo do Projeto
Este projeto analisa os padrões de produtividade, hábitos de estudo e indicadores de saúde mental de 5.000 estudantes. O objetivo principal é identificar quais fatores realmente impulsionam o sucesso acadêmico (notas) e quais são os principais gatilhos para o esgotamento mental (burnout), fornecendo insights baseados em dados para otimizar o desempenho sem sacrificar o bem-estar.

##  Tecnologias e Ambiente
* **Linguagem:** Python 3
* **Bibliotecas:** Pandas, Matplotlib, Seaborn, Scikit-Learn
* **Ambiente de Desenvolvimento:** Fedora Linux (Jupyter Notebooks em ambiente virtual com miniconda)
* **Técnicas Aplicadas:** Data Wrangling, Ordinal Encoding, Feature Engineering (Engenharia de Atributos), Análise de Correlação de Pearson, Visualização de Dados (Storytelling).

##  Estrutura do Projeto
* `notebooks/01_limpeza.ipynb`: Importação, tratamento de dados, encoding de variáveis categóricas e criação de novos atributos
* `notebooks/02_eda.ipynb`: Análise exploratória focada em estatística descritiva e correlações matemáticas.
* `notebooks/03_visualizacao.ipynb`: Construção de gráficos focados em responder às perguntas de negócio.
* `data/`: Diretório contendo os datasets bruto e processado.

## Principais Insights e Descobertas

**1. Qualidade supera Quantidade (O Poder do Foco)**
A análise de correlação revelou que o "Índice de Foco" (0.74) e a "Saúde Mental" (0.54) possuem um impacto muito maior na nota final do que as horas brutas de estudo (0.43).
![Gráfico de Foco vs Nota](link_da_sua_imagem_no_github_aqui)

**2. O Custo Real do Esgotamento**
O `burnout_level` se mostrou o maior detrator de notas do dataset (-0.40). A linha de tendência comprova que, à medida que o esgotamento aumenta, a performance acadêmica despenca severamente.
![Gráfico de Burnout vs Nota](link_da_sua_imagem_no_github_aqui)

**3. Os Gatilhos do Burnout**
Pressões externas são os maiores causadores de estresse. Estudantes lidando com prazos curtos (`upcoming_deadline`: 0.51) e empregos de meio período (`part_time_job`: 0.37) apresentam os picos mais altos de esgotamento.
![Gráfico de Gatilhos](link_da_sua_imagem_no_github_aqui)

**4. O Sono como Escudo Protetor**
Dormir é produtivo. A correlação negativa forte do sono (-0.49) com o burnout indica que alunos que mantêm uma higiene de sono ideal (6.5h a 8.5h) conseguem blindar sua saúde mental contra as pressões da rotina.
![Gráfico de Sono](link_da_sua_imagem_no_github_aqui)

## 🚀 Como Executar este Projeto
1. Clone este repositório: `git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git`
2. Crie um ambiente virtual: `python -m venv venv`
3. Ative o ambiente virtual (Linux): `source venv/bin/activate`
4. Instale as dependências: `pip install pandas matplotlib seaborn scikit-learn notebook`
5. Execute os notebooks na ordem numérica.

## 📬 Contato
Desenvolvido por [Seu Nome]
* [LinkedIn](link_do_seu_linkedin)
* [Portfólio/GitHub](link_do_seu_github)
