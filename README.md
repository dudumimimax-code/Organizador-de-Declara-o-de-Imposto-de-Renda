# Organizador de Declaração de Imposto de Renda (Excel)

Planilha para juntar, em um só lugar, tudo o que se precisa na hora de declarar o Imposto de Renda: dados do titular, informes de rendimentos, despesas dedutíveis, entradas do ano e um **checklist de documentos** que mostra o que ainda falta. Todos os dados são **fictícios**, só para demonstração.

📁 Arquivo: [`Organizador de Declaração de Imposto de Renda.xlsx`](Organizador%20de%20Declara%C3%A7%C3%A3o%20de%20Imposto%20de%20Renda.xlsx)

> Material de estudo e organização pessoal. Não substitui o programa oficial da Receita Federal nem orientação de um contador. O resumo é uma **estimativa de organização**, não o cálculo do imposto devido.

## Como usar

Preencha só as **células amarelas**. Cada aba tem um menu no topo para ir às outras. Os campos de lista (tipo de rendimento, categoria, situação do comprovante) só aceitam valores válidos.

## O que tem em cada aba

| Aba | O que faz |
|---|---|
| **Início** | Checklist de 12 documentos com situação (Pendente, Recebido ou Não se aplica), barra de progresso e total de pendências de toda a planilha |
| **Titular** | Identificação, contato, endereço, estado civil, número de dependentes e conferência dos campos (como o tamanho do CPF) |
| **Rendimentos** | Até 20 informes, com fonte pagadora, tipo, valor, imposto retido e situação do comprovante. Cada tipo é marcado como tributável ou não, a partir da aba Parâmetros |
| **Despesas** | Até 30 lançamentos de saúde, educação, previdência privada, pensão e outras, com situação do comprovante |
| **Entradas** | Até 50 entradas do ano, com total por mês e gráfico |
| **Resumo** | Rendimentos totais, tributáveis e isentos, imposto retido, deduções estimadas, base estimada, pendências por aba e dois gráficos |
| **Parâmetros** | Tipos de rendimento, categorias de despesa e limites (educação, dependente e previdência privada), todos editáveis |

## Como o resumo estima as deduções

- **Dependentes:** número de dependentes × valor por dependente.
- **Educação:** soma das despesas, limitada ao teto por pessoa × (titular + dependentes).
- **Previdência privada:** soma das despesas, limitada a um percentual dos rendimentos tributáveis.
- **Saúde, pensão e outras:** soma sem limite.
- **Base estimada:** rendimentos tributáveis menos o total de deduções.

Os limites vêm da aba Parâmetros como valores de referência. Confira os do ano na Receita Federal e edite se mudarem.

## O que mudou nesta versão

- Planilha refeita do zero, com visual padronizado, menu entre abas e células de entrada destacadas.
- Novas abas: Início (checklist), Despesas, Entradas e Resumo, além da aba Parâmetros.
- Validação de dados, formatação condicional (pendências em amarelo, recebidos em verde) e gráficos.
- Todos os dados pessoais substituídos por dados fictícios.

## O que foi usado

`SOMASES` · `SOMARPRODUTO` · `ÍNDICE` + `CORRESP` · `MÍNIMO` · `CONT.SES` · validação de dados · formatação condicional · gráficos de barras · links internos entre abas
