# Desafio de Replicação

## Descrição

Este repositório contém o código, os dados e os documentos desenvolvidos para um projeto de replicação científica em linguagem **R**.

O objetivo do projeto é reproduzir e avaliar os principais resultados do estudo:

> **Lei 10.639/03: a atuação das Secretarias Municipais de Educação no ensino de história e cultura africana e afro-brasileira.**

Instituto Alana & Geledés – Instituto da Mulher Negra (2023).

A análise foi realizada utilizando a base de dados disponibilizada juntamente com o artigo, contendo informações de **1.187 Secretarias Municipais de Educação**.

---

# Objetivos

O projeto contempla as seguintes etapas:

- Importação da base de dados;
- Tratamento e organização dos dados;
- Auditoria da base;
- Construção dos principais indicadores apresentados no artigo;
- Estatísticas descritivas;
- Testes de robustez;
- Construção de índices alternativos;
- Geração de tabelas;
- Geração de gráficos;
- Registro do ambiente computacional (`sessionInfo()`).

---

# Estrutura do repositório

```
MAPP_Lei10639/
│
├── Artigo Base/
│   └── Relatório original utilizado na replicação
│
├── Código do Projeto/
│   └── Scripts em R para importação, tratamento, análise e geração dos resultados
│
├── Dados/
│   └── Base Escuta dos Municípios.xlsx
│
├── Artigo Final Kenya/
│   └── (Versão final do artigo desenvolvido durante o projeto)
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

1. Abra o script localizado na pasta **Código do Projeto**.

2. Certifique-se de que a base de dados esteja disponível na pasta **Dados**.

3. Execute o script completo.

Ao final da execução serão produzidos:

- indicadores;
- tabelas;
- gráficos;
- estatísticas descritivas;
- índices de robustez;
- informações da sessão do R.

---

# Resultados produzidos

O código gera automaticamente:

- Auditoria da base de dados;
- Indicadores de implementação da Lei nº 10.639/03;
- Estatísticas descritivas;
- Índices alternativos de institucionalização;
- Comparações entre grupos;
- Tabelas;
- Gráficos;
- Registro do ambiente computacional (`sessionInfo()`).

---

# Limitações

Este projeto realiza uma **replicação independente** dos principais resultados apresentados no estudo.

Embora a base de dados e a documentação metodológica estejam disponíveis, os **scripts computacionais originais utilizados pelos autores não foram disponibilizados**, impossibilitando a reprodução exata do fluxo analítico desenvolvido no estudo original.

---

# Referência

INSTITUTO ALANA; GELEDÉS – Instituto da Mulher Negra.

**Lei 10.639/03: a atuação das Secretarias Municipais de Educação no ensino de história e cultura africana e afro-brasileira.**

São Paulo, 2023.

---

# Licença

Este repositório foi desenvolvido exclusivamente para fins acadêmicos.

A base de dados, o relatório e demais materiais pertencem aos respectivos autores e instituições responsáveis.
