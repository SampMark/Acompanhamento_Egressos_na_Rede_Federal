### C. `docs/03_regras_negocio_etl.md`

* **Algoritmo de Deduplicação de Vínculos Acadêmicos:**

$$\text{Doutorado} (6) > \text{Mestrado} (5) > \text{Especialização} (4) > \text{Graduação} (3) > \text{Técnico Subsequente} (2) > \text{Técnico Integrado} (1)$$



*Desempate:* Maior `ANO_CONCLUSAO` seguido de maior `IRA`.
* **Função SQL da Matriz `TRAB_OCUPACAO` (Trabalho $\times$ Estudo):**
* `1`: Apenas Trabalha (`TRAB_SITUACAO = 1` $\land$ `ESTUDO_CONTINUIDADE` $\in \{0, 4\}$).
* `2`: Trabalha e Estuda (`TRAB_SITUACAO = 1` $\land$ `ESTUDO_CONTINUIDADE` $\in \{1, 2, 3\}$).
* `3`: Apenas Estuda - Fora da Força (`TRAB_SITUACAO` $\in \{2, 3\}$ $\land$ `ESTUDO_CONTINUIDADE` $\in \{1, 2, 3\}$).
* `4`: Sem Trabalho e Sem Estudo - STSE (`TRAB_SITUACAO` $\in \{2, 3\}$ $\land$ `ESTUDO_CONTINUIDADE` $\in \{0, 4\}$).


* **Anonimização e Ponderação:** Função Python para hashing com *salt* e cálculo do peso amostral pós-estratificado $w_i = \frac{N_h}{n_h}$.

---
