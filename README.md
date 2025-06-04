# 01_projetoFII
DIO - entrega do projeto com objetivo de aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos em fundos imobiliários

# FIINVEST
# Simulador de Investimentos em Fundos Imobiliários (FIIs)

Esta planilha em Excel permite simular investimentos em Fundos Imobiliários (FIIs) com base em parâmetros definidos pelo usuário como: valor inicial de investimentos, aportes mensais, prazo e FII escolhido.

Também será exibida a sugestão de investimento mensal com base no salário do usuário.

## Funcionalidades

- Cálculo do patrimônio acumulado no cenário de prazo escolhido;
- Cálculo do patrimônio acumulado nos cenários de 2, 5, 10, 15, 20, 25 e 30 anos;
- Simulação de dividendos mensais nos cenários acima;
- Gráfico de evolução patrimonial;
- Base de dados com exemplos de FIIs;
- Simulação entre papéis no cenário de prazo escolhido;
- Validação de dados (listas suspensas, campos obrigatórios).

## Parâmetros de Entrada

Disponíveis na aba **"FIINVEST"**:
1) Informações Gerais de Salário e Sugestão de Investimento			
- Salário  (R$)

2) Informações para Investimento			
- Valor Inicial de Investimento (R$)
- Aporte Mensal (R$)
- Prazo do Investimento (em meses)
- FII Escolhido (KNRI11, HGLG11, MXRF11)

## Parâmetros Automáticos
1) Informações Gerais de Salário e Sugestão de Investimento			
- Sugestão de investimento (30%) - cálculo de 30% sobre o salário mensal

2) Informações para Investimento
- Segmento - segmento do fundo obtido automaticamente da base de FIIs;
- Preço Médio da Cota (por FII) - preço médio do fundo obtido automaticamente da base de FIIs;
- Dividend Yield (%) - rendimento mensal em dividendos do fundo obtido automaticamente da base de FIIs;


## Estrutura da Planilha

- **FIINVEST**: Onde o usuário configura a simulação.
- **BaseFIIs**: Tabela com informações de alguns FIIs.

## Tecnologias Utilizadas
- Microsoft Excel

## Como Usar
1. Abra o arquivo "Projeto_SimuladorFII_FIINVEST.xlsx" no Excel.
2. Preencha a aba **"FIINVEST"** com os valores desejados.
3. Veja os resultados nas tabelas e gráficos na própria aba **"FIINVEST"**.

## Observações
- Os dados de FIIs são exemplos e devem ser atualizados conforme o mercado.
- A planilha simula rendimento constante, sem considerar oscilações de mercado.

## Objetivo e Licença
Este projeto é gratuito e foi criado para o projeto DIO:
-Aplicar os conceitos de Excel no desenvolvimento de uma ferramenta prática de simulação de investimentos em fundos imobiliários.


