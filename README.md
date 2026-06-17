# Educação Adaptativa com Apache Spark e Microdados do ENEM

## 📖 Descrição do Projeto

Este projeto tem como objetivo aplicar tecnologias de Big Data na análise dos microdados do Exame Nacional do Ensino Médio (ENEM), utilizando o Apache Spark para processamento distribuído de grandes volumes de dados.

A proposta está inserida no contexto da **Educação Adaptativa**, buscando identificar padrões de desempenho acadêmico e perfis de estudantes a partir de características socioeconômicas e educacionais. Os resultados obtidos podem auxiliar na compreensão de fatores relacionados ao desempenho escolar e no desenvolvimento de estratégias de ensino mais personalizadas.

---

## 🎯 Objetivos

### Objetivo Geral

Utilizar técnicas de processamento distribuído para analisar os microdados do ENEM e identificar perfis educacionais que contribuam para estratégias de educação adaptativa.

### Objetivos Específicos

- Implementar um ambiente de processamento distribuído utilizando Apache Spark;
- Realizar processos ETL para tratamento e padronização dos dados;
- Aplicar técnicas de Análise Exploratória de Dados (EDA);
- Investigar relações entre fatores socioeconômicos e desempenho acadêmico;
- Construir perfis educacionais com base nas características dos estudantes;
- Produzir visualizações e relatórios analíticos;
- Avaliar o desempenho do processamento distribuído para diferentes volumes de dados.

---

## 📚 Tema

**Educação Adaptativa utilizando Tecnologias Big Data**

O projeto explora como ferramentas de processamento distribuído podem auxiliar na extração de conhecimento a partir de grandes bases de dados educacionais, apoiando iniciativas de ensino personalizado.

---

## 🗂️ Base de Dados

Os dados utilizados são provenientes dos **Microdados do ENEM 2023**, disponibilizados pelo Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP).

O conjunto de dados contém informações sobre:

- Perfil demográfico dos participantes;
- Características socioeconômicas;
- Tipo de escola;
- Recursos tecnológicos disponíveis;
- Notas obtidas nas áreas avaliadas pelo ENEM.

### Principais Variáveis Utilizadas

| Variável | Descrição |
|-----------|------------|
| TP_FAIXA_ETARIA | Faixa etária do participante |
| TP_SEXO | Sexo do participante |
| TP_ESCOLA | Tipo de escola |
| Q001 | Escolaridade do pai |
| Q002 | Escolaridade da mãe |
| Q006 | Faixa de renda familiar |
| Q024 | Possui computador em casa |
| Q025 | Possui acesso à internet |
| NU_NOTA_CN | Nota de Ciências da Natureza |
| NU_NOTA_CH | Nota de Ciências Humanas |
| NU_NOTA_LC | Nota de Linguagens |
| NU_NOTA_MT | Nota de Matemática |
| NU_NOTA_REDACAO | Nota da Redação |

---

## 🛠️ Tecnologias Utilizadas

- Python
- Apache Spark (PySpark)
- Pandas
- Matplotlib
- Google Colab
- GitHub

---

## 🔬 Metodologia

O projeto foi desenvolvido seguindo as seguintes etapas:

### 1. ETL Distribuído

- Extração dos microdados do ENEM;
- Limpeza e tratamento dos registros;
- Seleção das variáveis relevantes;
- Armazenamento dos dados tratados.

### 2. Análise Exploratória de Dados (EDA)

- Distribuição dos participantes;
- Distribuição das notas;
- Caracterização socioeconômica.

### 3. Estatística Descritiva

- Médias;
- Desvios padrão;
- Distribuições de frequência.

### 4. Análise Socioeconômica

- Relação entre renda e desempenho;
- Relação entre escolaridade familiar e desempenho;
- Relação entre acesso à tecnologia e desempenho.

### 5. Construção de Perfis Educacionais

Identificação de grupos de estudantes com características semelhantes, permitindo apoiar estratégias de educação adaptativa.

### 6. Visualização dos Resultados

Geração de gráficos e relatórios para interpretação dos resultados.

---

## 📁 Estrutura do Repositório

```text
.
├── dataset/
│   └── MICRODADOS_ENEM_2023.csv
├── notebooks/
│   └── educacao_adaptativa_spark.ipynb
├── imagens/
├── README.md
└── requirements.txt
```

---

## 🚀 Como Executar

### Instalar Dependências

```bash
pip install pyspark pandas matplotlib
```

### Executar o Notebook

Abra o arquivo `.ipynb` no Google Colab ou em um ambiente Jupyter Notebook e execute as células sequencialmente.

---

## 📊 Resultados Esperados

Espera-se identificar padrões de desempenho acadêmico associados a características socioeconômicas dos participantes, bem como construir perfis educacionais capazes de apoiar futuras iniciativas de educação adaptativa.

Além disso, o projeto busca demonstrar a aplicabilidade do Apache Spark no processamento distribuído de grandes bases de dados educacionais.

---

## 👨‍💻 Autor

Projeto desenvolvido para a disciplina de Big Data e Processamento Distribuído, pelos alunos Alec dos Santos, João Gabriel Massuda, Juan Gabriel Cardoso e Sandy Luany Mendes.
