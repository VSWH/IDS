# Detecção de Tráfego Malicioso em Redes Corporativas

Projeto prático desenvolvido para a disciplina de Inteligência Artificial (7º semestre do curso de Ciência da Computação - Universidade Presbiteriana Mackenzie).

## Integrantes do Grupo
* Henrique Higa (RA: 10402805)
* Lucas Crepalde (RA: 10425647)
* Mauricio Vicentini (RA: 10426074)
* Rafael Riki (RA: 10418331)
* Victor Hong (RA: 10425852)

---

## Sobre o Dataset (UNSW-NB15)

* **Origem:** O dataset foi criado pelo *Cyber Range Lab* do *Australian Centre for Cyber Security* (ACCS) na University of New South Wales (UNSW), utilizando a ferramenta IXIA PerfectStorm para sintetizar tráfego de rede realista contemporâneo.
* **Conteúdo:** A base contém registros estruturados de fluxos de rede, totalizando 175.341 linhas e 36 colunas no subconjunto utilizado. Os dados reúnem tráfego normal (31,9%) e 9 famílias de ataques cibernéticos (68,1%), como *Exploits*, *Generic*, *Fuzzers*, *DoS* e *Reconnaissance*.
* **Variáveis:** Registra atributos de conexão como duração (`dur`), contagem e volume de pacotes/bytes (`spkts`, `dpkts`, `sbytes`, `dbytes`), taxas de transferência (`rate`), latência TCP (`tcprtt`) e o rótulo final (`label`: 0 para normal, 1 para ataque).

---

## Estrutura do Repositório

```text
├── README.md
├── artigo_projeto_parcial.pdf
├── /dados
│   └── UNSW_NB15_training-set.parquet
└── /notebooks
    └── 01_analise_exploratoria.ipynb
