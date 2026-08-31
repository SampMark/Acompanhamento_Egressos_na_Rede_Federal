# Acompanhamento de Egressos na Rede Federal de EPCT: Sistema Híbrido de Indicadores e Engenharia de Dados

[![Status](https://img.shields.io/badge/Status-Produção%20%7C%20Open%20Source-brightgreen)](#)
[![Plataforma](https://img.shields.io/badge/Plataforma-Google%20Cloud%20%7C%20BigQuery%20%7C%20Looker%20Studio-blue)](#)
[![Metodologia](https://img.shields.io/badge/Metodologia-Sistema%20Híbrido%20PAE%20%2B%20RAIS%2FNovos%20CAGED-orange)](#)
[![Instituição](https://img.shields.io/badge/Instituição-IFRN%20%7C%20PRODE%20%7C%20ASREMT-green)](#)

Documentação técnica, modelagem dimensional, dicionário de dados e pipelines de engenharia do **Sistema Híbrido de Acompanhamento de Egressos**, fundamentado na experiência decenal (2013–2025) do **Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte (IFRN)**.

---

## 📌 Sumário Executivo

A avaliação da efetividade educacional e da inserção profissional de egressos da Educação Profissional e Tecnológica (EPT) e da Educação Superior integra três fontes:
1. **Registros Acadêmicos Internos (SUAP/IFRN):** Trajetórias acadêmicas e vínculos censitários.
2. **Pesquisas Amostrais Probabilísticas (PAE/IFRN):** Microdados primários declaratórios de avaliação da formação, ocupação ampla (formal/informal/autônomo), aderência profissional, sobreeducação percebida e mobilidade territorial.
3. **Bases Administrativas Nacionais (MTE e Inep/MEC):** Registros longitudinais contínuos de emprego formal (RAIS/Novo CAGED) e verticalização educacional externa (Censo da Educação Superior / Sucupira).

---

## 📂 Módulos de Documentação

* **[01. Arquitetura de Dados e Modelagem Dimensional](./docs/01_arquitetura_dados.md):** Especificação do fluxo de ingestão, camadas *Bronze*, *Silver* e *Gold*, esquema estrela (*Star Schema*) e scripts DDL para BigQuery.
* **[02. Dicionário de Dados e Schema Completo](./docs/02_dicionario_dados_schema.md):** Mapeamento integral de 100% das variáveis do Google Forms (Edição 2025/Contínua), tipos de dados, domínios e regras de pulo condicional.
* **[03. Regras de Negócio e Pipelines ETL/ELT](./docs/03_regras_negocio_etl.md):** Algoritmos de deduplicação de múltiplos vínculos acadêmicos (Critério de Maior Elevação Educacional), anonimização compatível com LGPD (SHA-256) e matriz Trabalho $\times$ Estudo.
* **[04. Catálogo Operacional de Indicadores](./docs/04_catalogo_indicadores.md):** Fórmulas matemáticas, denominadores, ponderação amostral e matriz de comparabilidade técnica (PAE vs. RAIS/CAGED vs. PNAD Contínua).
* **[05. Guia de Integração para BI e Looker Studio](./docs/05_guia_integracao_bi.md):** Modelagem semântica, campos calculados, métricas customizadas e otimização de performance no Looker Studio.
