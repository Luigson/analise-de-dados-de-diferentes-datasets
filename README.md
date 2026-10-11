# Análise de dados de diferentes datasets

Projeto da disciplina de Ciência de Dados (UFRN, 4º semestre).
Análise exploratória e inferência sobre aluguéis de imóveis por bairro, zona e tipo.

## Dados
- O arquivo `arquivo.csv` não está no repositório.
- Coloque-o na pasta `data/` antes de rodar o notebook.
- Fonte: [de onde veio, ou "fornecido pelo professor"]

## Como rodar

1. Criar o ambiente e instalar as dependências:

```bash
uv venv
.venv\Scripts\activate
uv pip install -r requirements.txt
```

2. Abrir `notebooks/[nome].ipynb` no VS Code, escolher o kernel do `.venv` e rodar as células em ordem.

## O que o projeto faz

1. Limpeza dos dados (nulos, tipos, duplicatas)
2. Análise exploratória e gráficos
3. Tratamento de outliers
4. Normalização com scikit-learn
5. Testes de hipótese (teste t, Mann-Whitney)

## Principais conclusões

- 

## Estrutura de pastas

```
projeto/
├── README.md
├── requirements.txt
├── data/
└── notebooks/
```

## Autor

Luigson, 2026