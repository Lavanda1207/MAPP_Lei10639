# Desafio de Replicação

## Descrição

Este repositório reúne os materiais desenvolvidos para um projeto de replicação científica utilizando a linguagem **R**.

O objetivo do projeto é reproduzir, analisar e avaliar os principais resultados do estudo:

> **Lei 10.639/03: a atuação das Secretarias Municipais de Educação no ensino de história e cultura africana e afro-brasileira.**

Instituto Alana & Geledés – Instituto da Mulher Negra (2023).

A análise foi realizada utilizando a base de dados disponibilizada juntamente com o relatório, contendo informações de **1.187 Secretarias Municipais de Educação**.

---

# Objetivos

O projeto contempla as seguintes etapas:

- Importação da base de dados;
- Tratamento e organização dos dados;
- Auditoria da base de dados;
- Construção dos principais indicadores apresentados no estudo;
- Estatísticas descritivas;
- Testes de robustez;
- Construção de índices alternativos de institucionalização;
- Geração de tabelas;
- Geração de gráficos;
- Registro do ambiente computacional (`sessionInfo()`).

---

# Estrutura do repositório

```
MAPP_Lei10639/
│
├── Artigo Base/
│   └── Relatório original utilizado como referência para a replicação
│
├── cod_projeto/
│   └── Scripts em R responsáveis pela importação, tratamento,
│       análise dos dados e geração dos resultados
│
├── Dados/
│   └── Base Escuta dos Municípios.xlsx
│
├── Artigo Final Kenya/
│   └── Versão final do artigo desenvolvido ao término do projeto
│
└── README.md
```

---

# Requisitos

O projeto foi desenvolvido utilizando **R (versão 4.3 ou superior)**.

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
tibble
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
  "readr",
  "tibble"
))
```

---

# Como executar

1. Faça o download (ou clone) deste repositório.

2. Certifique-se de que a base de dados esteja localizada na pasta **Dados**.

3. Abra o script localizado na pasta **cod_projeto**.

4. Execute o script completo no RStudio (ou outro ambiente compatível).

Ao final da execução serão gerados automaticamente:

- Auditoria da base;
- Estatísticas descritivas;
- Indicadores do estudo;
- Índices de institucionalização;
- Tabelas;
- Gráficos;
- Registro do ambiente computacional (`sessionInfo()`).

---

# Resultados produzidos

O código permite reproduzir análises como:

- Auditoria da base de dados;
- Indicadores de implementação da Lei nº 10.639/03;
- Estatísticas descritivas;
- Construção de índices alternativos de institucionalização;
- Testes de robustez;
- Comparações entre grupos e unidades federativas;
- Geração automática de tabelas e gráficos.

Esses resultados servem de apoio às análises apresentadas no relatório de replicação.

---

# Metodologia

O projeto foi desenvolvido seguindo os princípios da pesquisa replicável.

As análises foram organizadas em quatro dimensões:

- **Verifiability** – reprodução dos principais resultados publicados;
- **Robustness** – avaliação da estabilidade dos resultados sob diferentes especificações;
- **Reproducibility** – reconstrução independente das análises utilizando a base disponibilizada;
- **Generalizability** – discussão sobre o potencial de aplicação da metodologia em outros contextos.

---

# Limitações

Este projeto realiza uma **replicação independente** dos principais resultados apresentados no estudo.

Embora a base de dados e a documentação metodológica tenham sido disponibilizadas, os **scripts computacionais originais utilizados pelos autores não foram disponibilizados**.

Dessa forma, a replicação foi construída a partir da documentação metodológica e dos resultados publicados, não sendo possível reproduzir exatamente o fluxo computacional utilizado no estudo original.

---

# Referência

INSTITUTO ALANA; GELEDÉS – Instituto da Mulher Negra.

**Lei 10.639/03: a atuação das Secretarias Municipais de Educação no ensino de história e cultura africana e afro-brasileira.**

São Paulo, 2023.

---

# Licença

Este repositório foi desenvolvido exclusivamente para fins acadêmicos.

Todos os direitos relativos ao relatório original, à base de dados e aos demais materiais pertencem às instituições responsáveis pela pesquisa.
