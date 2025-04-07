# Sistema de Detecção de Fraudes em Transações Bancárias

Este projeto simula a análise de transações bancárias para detectar fraudes utilizando técnicas de aprendizado de máquina. Através da geração de logs fictícios de transferências financeiras (PIX, TED, DOC), o sistema classifica e gera alertas para transações suspeitas ou críticas com base no valor da transferência.

## Funcionalidades

1. **Geração de Logs Fictícios**: Criação de um arquivo JSON com transações bancárias simuladas, contendo detalhes como ID de transferência, contas de origem e destino, valor da transferência, data e IP de origem.

2. **Análise de Dados**: Carregamento e pré-processamento dos dados, como conversão de tipos de dados e normalização dos valores das transferências.

3. **Modelo de Classificação (Regressão Logística)**: Um modelo de regressão logística é treinado para classificar as transações em três categorias:
   - **0**: Normal
   - **1**: Suspeito
   - **2**: Crítico (Fraude)

4. **Classificação de Novas Transações**: Capacidade de classificar novas transações com base no valor da transferência e gerar alertas automatizados para transações críticas.

5. **Visualização**: Geração de gráficos para análise de dados, como a distribuição dos valores das transferências.

## Tecnologias Utilizadas

- **Python 3.x**
- **Bibliotecas**:
  - `json` (para manipulação de arquivos JSON)
  - `random` (para geração de dados aleatórios)
  - `datetime` (para manipulação de datas)
  - `pandas` (para manipulação de dados em DataFrames)
  - `sklearn` (para treinamento de modelos de aprendizado de máquina)
  - `numpy` (para manipulação de arrays numéricos)
  - `matplotlib` e `seaborn` (para visualização de dados)

## Como Executar

### Pré-requisitos

Antes de rodar o código, você precisa ter o Python instalado em sua máquina. Também será necessário instalar as dependências.

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/RocketFR/EntregaProjeto-Estudodecaso1.git
   cd Estudodecaso1

2. faça o pip das seguintes bibliotecas


 ```bash
pip install pandas scikit-learn numpy matplotlib seaborn


   
  
