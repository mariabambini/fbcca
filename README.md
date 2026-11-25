# OPT098 - Tópicos Especiais Em Sistemas De Computação (ICO-CM)

* Estudante: Maria Eduarda Bambini
* Data última atualização: 25/11/2026


Repositório para estudo dos dados do dataset referente à este artigo \[1\] Yijun Wang, Xiaogang Chen, Xiaorong Gao, Shangkai Gao (2017). A Benchmark Dataset for SSVEP-Based Brain–Computer Interfaces ([https://ieeexplore.ieee.org/document/7740878](https://ieeexplore.ieee.org/document/7740878)).

## Estrutura

Os arquivos estão estruturados conforme ilustrado abaixo. Em `data/`, há os arquivos referentes aos dados do dataset, em `docs/`, há referências (documentação) do artigo utilizado como base, e em `src/`, há a implementação de cada etapa
requisitada pelo professor.

```
├── data
│   ├── input
│   │   ├── 64-channels.loc             # descrição de todos os canais
│   │   ├── Freq_Phase.mat              # 
│   │   └── S1.mat                      # arquivo referente aos dados do participante 'S1'
│   └── output                          # arquivos processados
│       ├── S1_cca_features.npy
│       ├── S1_epo.fif
│       ├── S1_features.npy
│       ├── S1_filtered_epo.fif
│       ├── S1_labels.npy
│       ├── S1.npy
│       └── S1_pre_pros.npy
├── docs                                # documentação sobre o dataset e este repositório
│   ├── README.md
│   ├── Readme.txt
│   └── Sub_info.txt
├── README.md
├── requirements.txt                    # arquivo de tecnologias necessárias para executar os notebooks
└── src
    ├── features.ipynb                  # notebook de extração de características
    ├── loading_dataset.ipynb           # notebook de carregamento inicial do dataset
    ├── pre_processing.ipynb            # notebook de pré-processamento dos dados
    └── visualizations.ipynb            # notebook de visualizações (dos pré-processamentos, como aplicação de filtros)
```
