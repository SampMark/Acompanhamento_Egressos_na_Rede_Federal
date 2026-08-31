### A. Arquitetura Medallion:
* *Bronze (Raw):* Tabelas de *staging* para ingestão de planilhas de respostas do Google Forms, extrações relacionais do SUAP e microdados do MTE.
* *Silver (Cleansing & Curadoria):* Deduplicação por maior elevação de vínculo acadêmico, pseudonimização com `ID_EGRESSO_HASH = SHA256(CPF)`, normalização de CBO-2002, CNAE 2.0 e Códigos IBGE de municípios.
* *Gold (Marts Dimensionais):* Tabelas de dimensões (`dim_egresso`, `dim_curso_campus`, `dim_tempo_conclusao`, `dim_municipio`) e tabelas de fatos (`fato_pae_avaliacao_curso`, `fato_trajetoria_trabalho`, `fato_hibrida_formal`).

* **Scripts DDL:** Scripts SQL para criação de tabelas particionadas e clusterizadas no Google BigQuery.

---
