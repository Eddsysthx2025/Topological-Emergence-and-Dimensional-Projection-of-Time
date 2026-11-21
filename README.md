[![DOI](https://zenodo.org)](https://doi.org)

# Emergência Topológica e Projeção Dimensional do Tempo
**Topological Emergence and Dimensional Projection of Time**

**Autor:** E. R. dos Santos  
**Licença:** GNU General Public License v3.0 (GPLv3)

---

## Visão Geral / Overview

Este repositório contém a formulação teórica e a implementação computacional de um modelo fenomenológico que investiga a emergência de escalas da física de partículas e da escala quântico-atômica a partir de invariantes topológicos discretos e da projeção dimensional do tempo basal.

*This repository provides the theoretical formulation and computational implementation of a phenomenological framework investigating the emergence of particle physics and atomic scales from discrete topological invariants and the dimensional projection of fundamental time.*

---

## Estrutura Conceitual / Conceptual Framework

1. **Princípio da Não-Nulidade:** O vácuo estático absoluto ($\Delta E = 0, \Delta t = 0$) é interditado pela relação de incerteza fundamental ($\Delta E \cdot \Delta t \ge \hbar / 2$), impondo uma ação basal mínima $S_0 = 1/2$.
2. **Estabilidade Dinâmica (Teorema KAM):** No regime não-linear pré-espacial, modos racionais sofrem destruição ressonante, preservando a razão áurea ($\phi$) como atrator estável.
3. **Frustração Topológica:** A cristalização em redes de empacotamento denso 3D ($z_{3d} = 12$) e 4D ($z_{4d} = 24$) sobre uma topologia esférica ($\chi_0 = 2$) induz um defeito discreto de curvatura $d^* = \frac{1}{2}\phi^{-1/3}$ e uma densidade de vórtices $\rho_v^* = \frac{1}{z_{3d} - 2} = 0.1$.
4. **Projeção Dimensional:** O deslocamento topológico ($\chi = 2 \to 2.1$) conduz à expansão exponencial do tempo de Planck ($t_{\mathrm{Planck}} \to \tau_c$), projetando a escala espacial infravermelha ($\mu_{\mathrm{IR}} \approx 234.97\,\mathrm{MeV}$).
5. **Expansão Espinorial (LO e NLO):** Férmions de spin $1/2$ são tratados como defeitos topológicos de dupla cobertura na rede 4D ($2 z_{4d} = 48$), unificando a Ordem Dominante (**LO**) e a correção de recuo cinético (**NLO**).

---

## Como Executar / Usage

O código principal é autocontido e utiliza apenas a biblioteca padrão do Python 3 (`math`), sem dependências externas:

```bash
python3 topological_emergence_model.py
```

### Estrutura do Repositório
* `topological_emergence_model.py`: Implementação numérica completa (LO e NLO), cálculo de incertezas sistemáticas e saída formatada para LaTeX.
* `Topological_Emergence_and_Dimensional_Projection_of_Time.tex` / `.pdf`: Documento técnico em Inglês.
* `Emergencia_Topologica_e_Projecao_Dimensional_do_Tempo.tex` / `.pdf`: Documento técnico em Português.
* `LICENSE`: Texto integral da licença GNU GPLv3.

---

## Resumo dos Resultados / Summary of Results

| Observável | Modelo (LO) | Modelo (NLO) | Valor Experimental (PDG) | Tensão (NLO) |
| :--- | :---: | :---: | :---: | :---: |
| **$M_p$ (GeV)** | $0.9416$ | $0.9416 \pm 0.0022$ | $0.9383$ | $1.5\sigma$ |
| **$\alpha^{-1}(0)$** | $137.1069$ | $137.1050 \pm 0.2943$ | $137.0360$ | $0.2\sigma$ |
| **$m_e$ (MeV)** | $0.5182$ | $0.5136 \pm 0.0016$ | $0.5110$ | $2.2\sigma$ |
| **$m_\mu$ (MeV)** | $106.5782$ | $105.6326 \pm 0.2474$ | $105.6584$ | $0.1\sigma$ |
| **$m_\tau$ (MeV)** | $1793.2838$ | $1777.3743 \pm 4.1771$ | $1776.8600$ | $0.1\sigma$ |
| **$v_{\mathrm{Higgs}}$ (GeV)** | $245.1447$ | $245.1447 \pm 0.7752$ | $246.2197$ | $1.4\sigma$ |
| **$m_t$ (GeV)** | $172.8308$ | $172.8308 \pm 0.5465$ | $172.6900$ | $0.3\sigma$ |
| **$M_W$ (GeV)** | $80.6378$ | $80.6378 \pm 0.2286$ | $80.3770$ | $1.1\sigma$ |
| **$M_Z$ (GeV)** | $91.2262$ | $91.2262 \pm 0.2586$ | $91.1876$ | $0.1\sigma$ |
| **$M_H$ (GeV)** | $125.4396$ | $125.4396 \pm 0.3966$ | $125.2500$ | $0.5\sigma$ |

### Escala Quântica e Alvos Experimentais
* **Anomalia Magnética do Elétron ($a_e$):** $0.0011585$ (Exp: $0.0011597$ — erro de $0.10\%$)
* **Raio de Bohr ($a_0$):** $0.5267\,\mathrm{\AA}$ (Exp: $0.5292\,\mathrm{\AA}$ — erro de $0.46\%$)
* **Energia de Rydberg ($R_\infty$):** $13.6621\,\mathrm{eV}$ (Exp: $13.6057\,\mathrm{eV}$ — erro de $0.41\%$)
* **Observáveis Candidatos (BSM):** Escalar pesado $M_{H2} \approx 600.48\,\mathrm{GeV}$ (HL-LHC) e áxion topológico $m_a \approx 0.376\,\mathrm{neV}$ (DMRadio-GUT).

---

## Nota de Transparência e Metodologia

A formulação conceitual, os axiomas teóricos e a arquitetura deste modelo foram idealizados por **E. R. dos Santos**. A implementação lógica em Python, a estruturação matemática e a refatoração do código foram desenvolvidas com o auxílio de Inteligência Artificial.

Este trabalho não visa, de forma alguma, esgotar o tema, sobrepor-se a pesquisas similares ou fornecer respostas definitivas de qualquer espécie, sob qualquer aspecto. Todos os resultados numéricos, equações e rotinas computacionais estão disponíveis para leitura, auditoria, testes e modificações nos termos da licença **GNU General Public License v3.0 (GPLv3)**.
