# Trabalho de Pesquisa Operacional

Implementação em Programação Linear Inteira (PLI) de cinco problemas clássicos de otimização em redes utilizando Python, Jupyter Notebook e IBM ILOG CPLEX (`cplex` e `docplex`).

## Estrutura

- `01_PFCM/`: Problema de Fluxo de Custo Mínimo (`pfcm.ipynb` e `in.txt`)
- `02_PT/`: Problema do Transporte (`pt.ipynb` e `in.txt`)
- `03_PD/`: Problema da Designação (`pd.ipynb` e `in.txt`)
- `04_PCM/`: Problema do Caminho Mínimo (`pcm.ipynb` e `in.txt`)
- `05_PFM/`: Problema de Fluxo Máximo (`pfm.ipynb` e `in.txt`)
- `202050081_trabalho.pdf`: relatório com a modelagem e os resultados obtidos

## Como executar

Crie um ambiente virtual e instale as dependências:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install cplex docplex ipykernel
```

Em seguida, abra o notebook (`.ipynb`) da pasta desejada no VS Code, selecione o kernel `.venv` e execute as células. Cada notebook lê automaticamente o arquivo `in.txt` presente na própria pasta.
