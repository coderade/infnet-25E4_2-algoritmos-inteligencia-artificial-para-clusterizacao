# infnet-25E4_2-algoritmos-inteligencia-artificial-para-clusterizacao

## Pré-requisitos

1. **Python 3.9+** instalado no sistema
2. **pip** (gerenciador de pacotes do Python)

## Configuração do Ambiente

### Opção 1: Usando venv (recomendado)

```bash
# Criar ambiente virtual
python -m venv venv_atividade

# Ativar ambiente virtual
# No Windows:
venv_atividade\Scripts\activate
# No macOS/Linux:
source venv_atividade/bin/activate

# Instalar dependências
pip install -r requirements.txt
```

### Opção 2: Usando conda

```bash
# Criar ambiente virtual
conda create -n atividade_cluster python=3.9

# Ativar ambiente
conda activate atividade_cluster

# Instalar dependências
pip install -r requirements.txt
```

## Download dos Dados

1. Acesse: https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data
2. Baixe o arquivo `Country-data.csv`
3. Coloque o arquivo na mesma pasta do notebook

## Execução

1. **Iniciar Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Abrir o arquivo:** `atividade_clusterizacao.ipynb`

3. **Executar as células** sequencialmente (Shift + Enter)

## Estrutura dos Arquivos

```
projeto/
├── atividade_clusterizacao.ipynb  # Notebook principal
├── requirements.txt               # Dependências
├── INSTRUCOES.md                 # Este arquivo
├── Country-data.csv              # Dados (baixar do Kaggle)
└── readme.md                     # Descrição da atividade
```

## Troubleshooting

- **Erro de importação:** Verifique se o ambiente virtual está ativo
- **Arquivo não encontrado:** Certifique-se de que o `Country-data.csv` está na pasta correta
- **Erro de kernel:** Reinicie o kernel (Kernel → Restart)