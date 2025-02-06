# Dashboard de Compras de Eletrodomésticos

## 📖 Descrição:
Este projeto de dashboard de compras de eletrodomésticos foi desenvolvido utilizando o Power BI. Foram realizadas várias alterações no Power BI Query para otimizar a análise dos dados. Abaixo estão os principais ajustes realizados:

## 🌟 Configurações no Power BI Query: 

### Separação de Colunas:
Havia uma coluna com os valores "Preço Original/Preço com Desconto". Foi necessário mesclá-las e depois separá-las para uma análise mais detalhada.

### Ajuste de Nomes:
A coluna “Comprador” continha o sobrenome antes do nome. Fizemos os ajustes necessários usando o guia de adicionar coluna e a opção de coluna de exemplo. Renomeamos duas linhas manualmente e o preenchimento foi completado automaticamente.

### Nova Coluna “DescontoTotal”:
Adicionamos uma nova coluna chamada “DescontoTotal”, que consiste em subtrair o valor da coluna “Valor TotalDesconto” da coluna “Valor TotalOriginal”.

## 🌟 Análise do Dashboard:

### Total de Gastos:
Utilizamos a tabela de “Cartão” para demonstrar o total de gastos.

### Produto Mais Comprado:
Para identificar o produto mais comprado, usamos a tabela de “Cartão” com o filtro de “N superior”, configurado para exibir o primeiro produto com a maior “quantidade de compras”.

### Região de Destino:
Utilizamos um gráfico de mapa para mostrar as regiões de destino. Adicionamos a soma do valor total de desconto e a soma da quantidade de produtos nas dicas de ferramentas para tornar o mapa mais explicativo e dinâmico.

### Valores Originais e com Desconto:
Para demonstrar o valor total original e o valor total com desconto, usamos um gráfico de colunas clusterizadas. No eixo X, utilizamos a coluna “data de compra”, e no eixo Y, as colunas “valor totaloriginal” e “valor totaldesconto”.

### Valor Gasto por Fornecedor:
Utilizamos um gráfico de barras empilhadas para mostrar o valor gasto por fornecedor. No eixo Y, usamos a coluna “fornecedores”, e no eixo X, a coluna “valor totalDesconto”.

## 🚀 Tecnologias Utilizadas?
- Excel
- Power BI
  
## 💻 Como Executar o Projeto:
- Power BI
