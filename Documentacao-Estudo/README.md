# Documentação de Estudo — Trabalho 3

Esta pasta reúne o material de apoio para estudar e apresentar o projeto de classificação de risco de crédito com o algoritmo **Gaussian Naïve Bayes**.

## Arquivos

- [Documentação detalhada do código](DOCUMENTACAO_CODIGO.md): explicação técnica, bloco por bloco, do arquivo `trabalho_3_naive_bayes.py`.
- [Roteiro para apresentação](ROTEIRO_APRESENTACAO.md): sequência sugerida de fala, resultados e possíveis perguntas da professora.

## Arquivos principais do projeto

- `trabalho_3_naive_bayes.py`: versão completa em Python.
- `TRABALHO_3_PARTE_1_Algoritmo_Naive_Bayes_RESOLVIDO.ipynb`: notebook executado.
- `risco_credito.csv`: base original com 14 registros.
- `risco_credito.pkl`: dados pré-processados gerados pelo código.

## Como executar

Instale as dependências:

```bash
pip install numpy pandas scikit-learn
```

Execute o programa a partir da raiz do projeto:

```bash
python trabalho_3_naive_bayes.py
```

O script procura o CSV na mesma pasta em que ele está e gera o arquivo `risco_credito.pkl` nessa pasta.
