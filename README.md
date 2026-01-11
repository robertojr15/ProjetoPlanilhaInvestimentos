# ProjetoPlanilhaInvestimentos
Projeto de Simulação de Investimentos em Excel - Desafio DIO
--------------------------------------------------------------------------
# Visão Geral

Este projeto consiste em uma planilha de Excel desenvolvida para **simulação de investimentos periódicos**, permitindo ao usuário projetar a evolução do patrimônio ao longo do tempo com base em renda mensal, taxa de juros e aportes recorrentes.
O objetivo principal é fornecer uma ferramenta simples e didática para **educação financeira e planejamento de investimentos**, sendo também um projeto demonstrativo para versionamento e documentação em GitHub.

# Estrutura do Arquivo

O repositório contém o seguinte arquivo principal:
**PROJETO INVESTIMENTO DIO - EXCEL.xlsx**
A planilha está organizada em blocos lógicos, com campos de entrada, cálculos intermediários e resultados consolidados.
Foram utilizadas diversas fórmulas (DESLOC, ÍNDICE, PROCV, VF, FILTRAR, MÁXIMO) e conceitos com CONTROLES da guia Desenvolvedor.

# Funcionalidades da Planilha

1. Informações Iniciais
--------------------------------------------------------------------------

Nesta seção, o usuário informa os principais dados de entrada:

**Renda Mensal:** valor total recebido mensalmente.

**% Rendimentos Mensais:** valor em percentual correspondente ao rendimento da carteira (rendimentos/dividendos).

**Valor do Aporte Mensal:** valor aportado todos os meses (este valor para simulação não sofre variação).

**Sugestão de Aportes (25%):** cálculo automático sugerindo um percentual da renda para investimento.

Esses valores servem como base para todas as simulações subsequentes.

2. Conversão de Taxas de Juros e Período
--------------------------------------------------------------------------

A planilha realiza automaticamente a conversão de taxas.

**Taxa anual (%) em Taxa mensal equivalente (%):** se faz necessário o imput da taxa de juros anual.

**Tempo em meses para Tempo em anos:** se faz necessário o imput da quantidade de meses a ser avaliada.

Essa conversão garante maior precisão nos cálculos de juros compostos aplicados mensalmente.


3. Simulação por Período
--------------------------------------------------------------------------

A simulação é feita ao longo de períodos (meses), considerando:

**Aporte Mensal | Juros Mensais | Total Investido Acumulado | Total de Juros Acumulados R$ | Patrimônio Total (investimentos + rendimentos)**

Essa abordagem permite visualizar claramente o impacto dos juros compostos ao longo do tempo.

# Objetivo Educacional
Este projeto foi desenvolvido com foco em:

1.Compreensão de juros compostos

2.Planejamento financeiro pessoal

3.Demonstração prática de conceitos financeiros em Excel e do aprendizado no *Curso Santander - Excel com Inteligência Artificial - 2º Semestre*.

4.Organização e documentação de projetos para GitHub

# Como Utilizar

Faça o download do arquivo Excel.
Edite os campos que estão destacados na cor amarelo.
Ajuste a taxa de juros anual conforme o cenário desejado.
Analise a evolução do patrimônio ao longo dos períodos simulados.

**Recomenda-se não alterar as células de cálculo para evitar inconsistências.**

# Tecnologia Utilizada

Microsoft Excel 
Conceitos de matemática financeira

# Melhorias Futuras

Inclusão de gráficos automáticos de outros cenários

Simulação de diferentes perfis de risco

Comparação entre múltiplos cenários de investimento

Versão automatizada em Python ou Power BI


# Autor

Roberto Luiz

# Licença

Este projeto é disponibilizado apenas para fins educacionais. Sinta-se à vontade para estudar, adaptar e evoluir o conteúdo.
