# Pesquisa de Acompanhamento de Egressos — PAE/IFRN

---

## 📊 Dashboard 360º da Pesquisa de Acompanhamento de Egressos

O **[Dashboard 360º da Pesquisa de Acompanhamento de Egressos (PAE)](https://datastudio.google.com/reporting/65ae89e1-e001-426e-afa8-917c42104acf)** é um ambiente interativo de *Business Intelligence* e análise visual de dados, desenvolvido pelo **Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte (IFRN)**. Sua finalidade é sistematizar, modelar e disponibilizar publicamente os microdados acumulados pelas sucessivas edições da pesquisa longitudinal de egressos da instituição.

O painel integra registros acadêmicos censitários com levantamentos amostrais probabilísticos primários, permitindo investigar as trajetórias acadêmicas e profissionais dos ex-alunos sob uma perspectiva multidimensional. A plataforma conecta o perfil sociodemográfico às percepções sobre a formação recebida, à continuidade dos estudos (verticalização), à dinâmica de inserção laboral (formal e ampla) e aos fluxos de mobilidade espacial (migração e pendularidade).

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                                RECORTE AMOSTRAL CONSOLIDADO                            │
├──────────────────────────┬──────────────────────────┬──────────────────────────────────┤
│  👤 14.624 Participantes │  📝 22.441 Entrevistas / │  🎓 114 Cursos Avaliados         │
│     Únicos Identificados │     Formações Concluídas │     (Técnico, Graduação e Pós)   │
├──────────────────────────┼──────────────────────────┼──────────────────────────────────┤
│  🏢 22 Campi e Polos     │  ⚙️ 10 Eixos Tecnológicos│  🗓️ Coortes Decenais Acompanhadas│
│     (Presencial e EaD)   │     do Catálogo Nacional │     (Edições 2017/18 a 2022/23)  │
└──────────────────────────┴──────────────────────────┴──────────────────────────────────┘

```

> [!NOTE]
> **Distinção entre Participantes Únicos e Entrevistas:** Em virtude do princípio de verticalização educacional, um mesmo egresso pode ter concluído múltiplos cursos no IFRN ao longo do tempo (por exemplo: *Técnico Integrado $\rightarrow$ Graduação Tecnológica $\rightarrow$ Especialização*). O painel diferencia com precisão a contagem de **pessoas físicas únicas** da quantidade de **vínculos/trajetórias avaliadas**.
> **Número de Entrevistas**: Estamos trabalhando na harmonização dos dados da duas primeiras edições, **[PAE2013]** e **[PAE2015-2016]**, para inclusão no Painel BI.

---

## 🎯 Objetivos Estratégicos e Institucionais

O desenvolvimento do Dashboard 360º visa transformar microdados brutos em inteligência analítica para subsidiar:

* **Avaliação Institucional e Governança:** Fornecer evidências empíricas para a Comissão Própria de Avaliação (CPA/SINAES/Inep), apoiando a autoavaliação institucional (Dimensões 2, 8 e 9 do SINAES).
* **Monitoramento do Plano Nacional de Educação (PNE):** Subsidiar o acompanhamento das metas nacionais de educação profissional e superior, especialmente a **Meta 11** (expansão e qualidade da EPT), a **Meta 12** (elevação da taxa de escolarização superior e interiorização) e a **Meta 13** (qualidade e titulação).
* **Planejamento Acadêmico e Oferta Formativa:** Analisar o grau de aderência e sintonia entre as matrizes curriculares dos cursos e o dinamismo produtivo das microrregiões atendidas pelos campi.
* **Políticas de Relação com o Mundo do Trabalho:** Identificar gargalos de inserção profissional, sobreeducação (*overeducation*) e orientar ações de estágio, empreendedorismo e articulação setorial conduzidas pela Assessoria de Relações com o Mundo do Trabalho (ASREMT/PROEX).

---

## 🧭 Estrutura Analítica do Painel: As Sete Dimensões

O Dashboard 360º está estruturado em **sete grandes dimensões analíticas**, organizadas de forma hierárquica e complementar:

```
                                      PAE / IFRN
                                          │
                  ┌───────────────────────┴───────────────────────┐
                  ▼                                               ▼
       1. CARACTERIZAÇÃO AMOSTRAL                       2. AVALIAÇÃO DOS CAMPI
       (Perfil Sociodemográfico)                        (Infraestrutura e Gestão)
                  │                                               │
                  └───────────────────────┬───────────────────────┘
                                          ▼
                               3. AVALIAÇÃO DOS CURSOS
                               (Ensino, Docência e Prática)
                                          │
                  ┌───────────────────────┴───────────────────────┐
                  ▼                                               ▼
       4. VERTICALIZAÇÃO EDUCACIONAL                   5. MUNDO DO TRABALHO
       (Progressão e Pós-Graduação)                    (Ocupação, Aderência e Renda)
                                                                  │
                                                  ┌───────────────┴───────────────┐
                                                  ▼                               ▼
                                       6. ANÁLISE DA DESOCUPAÇÃO       7. MIGRAÇÃO E PENDULARIDADE
                                       (Barreiras e Mercado Local)     (Dinâmica Espacial do Trabalho)

```

---

### 1. Caracterização da Amostra (*Sample Characterization*)

Apresenta a composição demográfica e o perfil de entrada e conclusão dos participantes em cada edição da pesquisa:

* **Composição por Nível e Modalidade:** Técnico de Nível Médio (Integrado, Subsequente e Proeja), Graduação (Tecnologia, Bacharelado e Licenciatura) e Pós-Graduação (*Lato Sensu* e *Stricto Sensu*).
* **Perfil Sociodemográfico:** Distribuição por sexo, raça/cor autodeclarada, faixas etárias de ingresso e conclusão, e histórico escolar fundamental (escola pública vs. privada).
* **Ações Afirmativas:** Participação de beneficiários de políticas de cotas sociais e étnico-raciais.
* **Origem Geográfica:** Mapeamento municipal e interestadual dos discentes por campus de vínculo.

---

### 2. Avaliação dos Campi (*Campus Assessment*)

Analisa a percepção dos egressos quanto às condições materiais, organizacionais e pedagógicas oferecidas pelas unidades do IFRN, utilizando escalas psicométricas padronizadas (0 a 5):

1. **Infraestrutura Física e Operacional:** Salas de aula, áreas de convivência e acessibilidade.
2. **Localização e Conectividade:** Acesso ao campus e transporte.
3. **Gestão Institucional:** Qualidade do atendimento e organização acadêmica.
4. **Corpo Docente:** Dedicação, formação e relacionamento com a comunidade discente.
5. **Apoio Acadêmico:** Biblioteca, serviços psicopedagógicos e assistência estudantil.
6. **Atualização Tecnológica:** Modernização de equipamentos e materiais didáticos.
7. **Satisfação Global com a Unidade:** Avaliação sintética da experiência no campus.

---

### 3. Avaliação dos Cursos (*Course Evaluation*)

Mapeia a eficácia dos Projetos Pedagógicos de Curso (PPC) sob a ótica dos concluintes:

* **Dimensões Formativas:** Avaliação da competência docente, metodologias ativas de ensino-aprendizagem, equilíbrio entre conhecimentos teóricos e aplicações práticas.
* **Infraestrutura de Laboratórios:** Suficiência e adequação dos equipamentos para a realização de aulas práticas e experimentais.
* **Prática Profissional Articulada:** Desempenho e impacto de estágios curriculares, projetos integradores, iniciação científica, projetos de extensão e trabalhos de conclusão de curso (TCC).
* **Impacto no Desenvolvimento Humano:** Grau de atendimento das expectativas iniciais e percepção sobre melhorias na renda e na qualidade de vida após a diplomação.
* **Ranking Institucional de Cursos:** Ordenamento comparativo baseado em índices percentuais de aprovação e satisfação discente.

---

### 4. Verticalização e Continuidade dos Estudos (*Vertical Integration*)

Acompanha a progressão da escolaridade dos egressos após a conclusão no IFRN, permitindo mensurar a continuidade formativa:

* **Progressão de Nível:** Transição do nível técnico para o ensino superior e do superior para a pós-graduação (*Aperfeiçoamento, Especialização, Mestrado e Doutorado*).
* **Natureza da Instituição de Destino:** Absorção por instituições públicas (IFRN, UFRN, UERN, UFERSA, IFESP) versus faculdades e universidades privadas (recursos próprios ou programas de financiamento como FIES/ProUni).
* **Diagramas de Fluxo (Sankey):** Representação visual das rotas de transição entre o curso concluído no IFRN e a titulação acadêmica mais elevada alcançada.
* **Aderência da Continuidade:** Grau de afinidade curricular entre a nova formação e a área tecnológica original.

---

### 5. Panorama do Mundo do Trabalho (*Labor Market Overview*)

Concentra os indicadores essenciais sobre a inserção ocupacional efetiva e as características dos postos de trabalho ocupados:

* **Matriz Ocupacional Ampla ($NOE$ / $TOE$):** Diferenciação entre quem *apenas trabalha*, *trabalha e estuda*, *apenas estuda (fora da força)* e indivíduos em situação de *desocupação/inatividade*.
* **Aderência Formação-Ocupação ($IEE_f$ / $ATF$ / $AAF$):** Proporção de egressos ocupados que exercem atividades laborais correspondentes à profissão ou em áreas conexas.
* **Desajuste Vertical e Sobrequalificação ($SQP$ / *Overeducation*):** Percepção do egresso sobre a compatibilidade entre a formação recebida e o nível de capacitação exigido pelas tarefas do trabalho atual.
* **Formas de Inserção e Formalidade:** Participação do emprego formal privado (CLT com carteira), setor público (estatutário, celetista, comissionado), empreendedorismo (MEI e empresas com CNPJ), estágio remunerado e ocupações informais/autônomas.
* **Rendimento e Jornada:** Distribuição por faixas de remuneração bruta em salários mínimos e carga horária semanal.
* **Setorização Econômica:** Classificação das empresas empregadoras segundo as Seções da **Classificação Nacional de Atividades Econômicas (CNAE 2.0)**.

---

### 6. Análise da Não Inserção e Desocupação (*Unemployment & Insertion Barriers*)

Investiga as barreiras socioeconômicas e regionais enfrentadas pelos egressos que não conseguiram inserção profissional na área de formação:

* **Taxa de Desocupação Estrita ($TDE_{PAE}$):** Proporção de egressos na força de trabalho que buscaram ativamente uma ocupação nos 30 dias anteriores à pesquisa.
* **Diagnóstico da Demanda Local:** Percepção dos egressos sobre a escassez estrutural de postos de trabalho e a atratividade dos salários na microrregião de residência.
* **Fatores Condicionantes da Não Inserção:** Avaliação via escala de concordância sobre determinantes como:
* Escassez de vagas no mercado local;
* Baixa remuneração média da área;
* Exigências de mercado desalinhadas da formação;
* Mudança de vocação / desistência da carreira técnica;
* Desmotivação profissional.



---

### 7. Mobilidade Territorial: Migração e Pendularidade (*Spatial Mobility*)

Examina os padrões geográficos de redistribuição espacial do capital humano formado no interior:

* **Emigração Definitiva ($TEM$):** Proporção de egressos que transferiram seu domicílio para cidades polo (como Natal e Mossoró), outros estados ou outros países em busca de oportunidades.
* **Movimento Pendular Diário ($TPD$):** Parcela de egressos que preservam sua residência no município de origem, mas realizam deslocamentos rotineiros intermunicipais para trabalhar ou estudar.
* **Índice de Retenção Local ($IRT$):** Capacidade da economia municipal em fixar o profissional graduado no próprio território de funcionamento do campus.
* **Cartografia de Fluxos:** Mapas interativos de linhas de conexão entre os municípios do campus/residência e os polos econômicos de destino laboral.

---

## 🎛️ Filtros Multidimensionais e Recursos de Segmentação

O painel oferece um sistema integrado de filtros dinâmicos, permitindo análises desde o nível macroinstitucional até o microrecorte de turmas:

| Categoria do Filtro | Variáveis de Segmentação Disponíveis |
| --- | --- |
| **Acadêmico-Institucional** | Edição da PAE, Campus ofertante, Nível de Ensino, Modalidade, Eixo Tecnológico, Curso e Ano de Conclusão. |
| **Perfil Sociodemográfico** | Sexo biológico, Faixa etária, Raça/Cor, Ingresso por Ações Afirmativas (Cotas) e Natureza da Escola Fundamental. |
| **Desempenho Escolar** | Faixas de Índice de Rendimento Acadêmico (IRA). |
| **Geográfico / Territorial** | UF de residência, Microrregião geográfica, Município de formação, Município de moradia atual e Município de trabalho. |
| **Ocupacional e Renda** | Situação de trabalho, Grau de aderência à formação, Forma de vínculo, Faixa de remuneração (SM) e Setor CNAE. |

```text
Exemplo de Drill-Down Analítico:
[Campus IFRN] ➔ [Modalidade] ➔ [Eixo Tecnológico] ➔ [Curso] ➔ [Ano Conclusão] ➔ [Aderência IEEf] ➔ [Destino Migratório]

```

---

## 🔬 Matriz de Principais Indicadores do Painel

| Sigla | Indicador | Dimensão Analítica | Fórmula Operacional Sintética |
| --- | --- | --- | --- |
| **$NOE$** | Nível de Ocupação dos Egressos | Ocupação Geral | $\frac{\text{Total de Ocupados (Formal + Informal + Autônomo)}}{\text{Total de Respondentes Válidos}} \times 100$ |
| **$TDE$** | Taxa de Desocupação dos Egressos | Mercado de Trabalho | $\frac{\text{Desocupados em Busca Ativa}}{\text{Força de Trabalho da Coorte (Ocupados + Desocupados)}} \times 100$ |
| **$IEE_f$** | Índice de Empregabilidade Efetiva | Aderência Formativa | $\frac{\text{Egressos Ocupados Diretamente na Área}}{\text{Total de Egressos Ocupados}} \times 100$ |
| **$AAF$** | Aderência Ampliada à Formação | Aderência Formativa | $\frac{\text{Egressos Ocupados na Área Direta ou Correlata}}{\text{Total de Egressos Ocupados}} \times 100$ |
| **$SQP$** | Sobrequalificação Percebida | Desajuste / *Overeducation* | $\frac{\text{Ocupados em Trabalho com Exigência Inferior ao Curso}}{\text{Total de Egressos Ocupados}} \times 100$ |
| **$TEM$** | Taxa de Emigração Municipal | Mobilidade Espacial | $\frac{\text{Egressos Residentes em Outro Município/UF/País}}{\text{Total de Egressos com Localização Válida}} \times 100$ |
| **$TPD$** | Taxa de Pendularidade Diária | Mobilidade Espacial | $\frac{\text{Egressos com Deslocamento Rotineiro Intermunicipal}}{\text{Total de Egressos com Localização Válida}} \times 100$ |
| **$IRT$** | Índice de Retenção Territorial | Desenvolvimento Local | $\frac{\text{Egressos Ocupados Residentes no Município do Campus}}{\text{Total de Egressos Formados no Campus}} \times 100$ |

---

## 🔗 Links e Recursos Relacionados

* 📊 **[Acesso Direto ao Dashboard Looker Studio 360º](https://datastudio.google.com/reporting/e0f78380-588b-475c-988a-3103bd1f39e6)**
* 💻 **[Repositório Oficial no GitHub (Documentação e Schemas)](https://github.com/SampMark/Acompanhamento_Egressos_na_Rede_Federal/)**
* 📐 **[Dicionário de Dados e Schemas Técnicos](https://www.google.com/search?q=./docs/02_dicionario_dados_schema.md)**
* 📋 **[Catálogo Completo de Indicadores e Fórmulas](https://www.google.com/search?q=./docs/04_catalogo_indicadores.md)**
* 🏛️ **Assessoria de Relações com o Mundo do Trabalho (ASREMT/PRODE/IFRN):** `asremt@ifrn.edu.br`
