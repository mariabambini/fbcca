# OPT098 - Tópicos Especiais Em Sistemas De Computação (ICO-CM)

Aluna: Maria Eduarda Bambini
Data última atualização: 25/11/2026

Repositório para estudo dos dados do dataset referente à este artigo \[1\] Yijun Wang, Xiaogang Chen, Xiaorong Gao, Shangkai Gao (2017). A Benchmark Dataset for SSVEP-Based Brain–Computer Interfaces ([https://ieeexplore.ieee.org/document/7740878](https://ieeexplore.ieee.org/document/7740878)).

## Estrutura

Os arquivos estão estruturados dessa forma:

```
├── data
│   ├── input
│   │   ├── 64-channels.loc
│   │   ├── Freq_Phase.mat
│   │   └── S1.mat
│   └── output
│       ├── S1_cca_features.npy
│       ├── S1_epo.fif
│       ├── S1_features.npy
│       ├── S1_filtered_epo.fif
│       ├── S1_labels.npy
│       ├── S1.npy
│       └── S1_pre_pros.npy
├── docs
│   ├── README.md
│   ├── Readme.txt
│   └── Sub_info.txt
├── README.md
├── requirements.txt
└── src
    ├── features.ipynb
    ├── loading_dataset.ipynb
    ├── pre_processing.ipynb
    └── visualizations.ipynb
```

Em data, há os arquivos referentes aos dados do dataset, em docs, há referências (documentação) do artigo utilizado como base, e em src/, há a implementação de cada etapa
requisitada pelo professor.
