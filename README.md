# 📊 Desafio Power BI — Análise Financeira

## 📑 Índice
- Contexto
- Objetivos
- Fontes
- Construção do Relatório
- Arquivos
- Nota sobre a Publicação

# Contexto:
- Este projeto é a entrega do desafio de Power BI da trilha de Analista de Dados da [DIO](https://www.dio.me/), com base no conteúdo ensinado no curso e nos dados de amostra disponibilizados no repositório original: [julianazanelatto/power_bi_analyst](https://github.com/julianazanelatto/power_bi_analyst).

# Objetivos:
- Replicar as duas páginas construídas durante o curso com a base `financials`;
- Criar uma terceira página do zero, treinando a criação de visuais de mapa e de pizza;
- Organizar a disposição dos visuais e renomear títulos de forma clara e direta;
- Ajustar os tooltips para exibir as métricas complementares de cada visual;
- Publicar o relatório e compartilhar como suplemento no PowerPoint.

# Fontes:
- Base de dados `financials`: [dataset do repositório original do desafio](https://github.com/julianazanelatto/power_bi_analyst/tree/main/dataset)
- Conteúdo de referência: módulos do curso de Power BI Analyst da DIO

# Construção do Relatório

**Página 1 — Relatório de Vendas Considerando Produtos e Segmento**
- Pizza de soma de Sales por Product
- Área de média de Sale Price por Product
- Colunas de soma de Sales por Year, Product e Segment
- Slicer por Ano/Mês

**Página 2 — Relatório de Vendas Considerando Países e Lucro**
- Cards de total de Sales e de Units Sold
- Pizza de soma de Profit por Country
- Colunas de soma de Profit por Ano e Mês
- Colunas de soma de Sales por Country

**Página 3 — Distribuição de Lucro, Vendas e Unidades vendidas por País e Segmento** *(criada para este desafio)*
- Mapa 1: soma de Sales e soma de Units Sold por Country (Units Sold disponível via tooltip)
- Mapa 2: soma de Profit por Country
- Pizza: soma de Profit por Segment

# Arquivos

| Arquivo | Descrição |
|---|---|
| `Power BI - Financeiros.pbix` | Projeto completo do Power BI Desktop, com as 3 páginas |
| `Power BI - Financeiros.pdf` | Exportação em PDF das 3 páginas do relatório |
| `Power BI - Financeiros.pptx` | Suplemento em PowerPoint, com uma página do relatório por slide |

# Nota sobre a Publicação
- O desafio original pede para publicar o relatório no Power BI Service e compartilhar como suplemento no PowerPoint a partir de lá. Isso não foi possível porque o cadastro no Power BI Service exige um e-mail corporativo ou institucional, e esta conta é pessoal. Como alternativa, o relatório foi entregue completo em `.pbix`, com exportação em PDF e em PowerPoint geradas diretamente a partir do Power BI Desktop.

# Autor
- Kelwin Paschoal
