# Desafio Técnico Power BI — Dashboard Financeiro

## Tratamento de Dados

Os dados foram tratados no Power Query com foco em qualidade, padronização e integridade das informações. Foram realizados os seguintes processos:

* Conversão de valores monetários armazenados como texto para formato numérico.
* Conversão de datas em formato texto para tipo Date.
* Padronização de IDs utilizando trim e uppercase para garantir o funcionamento correto dos relacionamentos.
* Remoção de registros duplicados na tabela de lançamentos financeiros.
* Tratamento de valores nulos e exclusão de registros inválidos para o cálculo do PMP.
* Validação de fornecedores inexistentes através de merge com a dimensão de fornecedores.
* Criação da coluna Prazo_Dias para apoio ao cálculo do Prazo Médio de Pagamento.
* Implementação de modelagem Star Schema com tabelas fato e dimensões separadas.
* Criação de tabela calendário (d_Calendario) para análises temporais.
* Medidas DAX

# Foram desenvolvidas medidas DAX para análise financeira e operacional, incluindo:

* Receita Total
* Despesa Total
* Saldo Financeiro
* Resultado Operacional %
* Quantidade de Notas Fiscais
* Notas Fiscais em Atraso
* Despesa por Fornecedor
* Valor Total de NF
* Prazo Médio de Pagamento (PMP) com média ponderada
* Dashboard

# O relatório foi dividido em duas páginas principais:

* Visão Financeira Executiva
* KPIs financeiros
* Evolução mensal de receitas vs despesas
* Despesas por centro de custo
* Top planos de receita e despesa
* Despesas por segmento de fornecedor
* Análise de Fornecedores
* PMP por fornecedor
* Notas fiscais por status
* UFs com maior quantidade de atrasos
* Top fornecedores por despesa
* Matriz analítica com formatação condicional

O dashboard foi desenvolvido com foco em clareza visual, organização executiva e boas práticas de modelagem em Power BI.
