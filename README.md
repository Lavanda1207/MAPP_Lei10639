#Desafio de Replicação

## Descrição

Este repositório contém o código desenvolvido em **R** para o Desafio de Replicação da Lista 3.

O objetivo do trabalho é reproduzir e avaliar os principais resultados do estudo:

> **Lei 10.639/03: a atuação das Secretarias Municipais de Educação no ensino de história e cultura africana e afro-brasileira.**
> Instituto Alana & Geledés – Instituto da Mulher Negra (2023).

A análise foi realizada utilizando a base de dados disponibilizada juntamente com o artigo, contendo informações de **1.187 Secretarias Municipais de Educação**.

---

# Objetivos

O script realiza as seguintes etapas:

- Importação da base de dados;
- Tratamento do cabeçalho da planilha;
- Auditoria inicial dos dados;
- Construção dos principais indicadores apresentados no artigo;
- Estatísticas descritivas;
- Testes de robustez;
- Construção de índices alternativos de institucionalização;
- Geração de tabelas;
- Geração de gráficos;
- Registro do ambiente computacional (`sessionInfo()`).

---

# Estrutura do projeto

```
.
├── data/
│   └── base_lista3.xlsx
│
├── output/
│   ├── figuras/
│   ├── tabelas/
│   └── sessionInfo.txt
│
├── analise_lista3.R
│
└── README.md
```

---

# Requisitos

R versão 4.3 ou superior.

Pacotes utilizados:

```r
readxl
dplyr
tidyr
stringr
ggplot2
janitor
purrr
readr
```

Caso algum pacote não esteja instalado:

```r
install.packages(c(
"readxl",
"dplyr",
"tidyr",
"stringr",
"ggplot2",
"janitor",
"purrr",
"readr"
))
```

---

# Como executar

1. Coloque o arquivo da base dentro da pasta `data/`.

2. Abra o arquivo:

```
analise_lista3.R
```

3. Execute o script completo.

Ao final da execução serão gerados:

- tabelas;
- gráficos;
- indicadores;
- índices;
- informações da sessão do R.

---

# Resultados produzidos

O script produz automaticamente:

- Auditoria da base de dados;
- Indicadores de implementação da Lei nº 10.639/03;
- Estatísticas descritivas;
- Índice amplo de institucionalização;
- Índice restrito de institucionalização;
- Comparações entre estados;
- Testes de robustez;
- Gráficos de apoio;
- Arquivo `sessionInfo()`.

---

# Limitações

Este projeto realiza uma **replicação independente** dos principais resultados apresentados no relatório.

Embora a base de dados e a documentação metodológica estejam disponíveis, os **scripts originais utilizados pelos autores não foram disponibilizados**, impossibilitando a reprodução exata do fluxo computacional empregado no estudo original.

---

# Referência

INSTITUTO ALANA; GELEDÉS – Instituto da Mulher Negra.

**Lei 10.639/03: a atuação das Secretarias Municipais de Educação no ensino de história e cultura africana e afro-brasileira.**

São Paulo, 2023.

---

# Licença

Este código foi desenvolvido exclusivamente para fins acadêmicos como parte de um exercício de replicação científica.

A base de dados e o relatório pertencem aos respectivos autores e instituições responsáveis.
