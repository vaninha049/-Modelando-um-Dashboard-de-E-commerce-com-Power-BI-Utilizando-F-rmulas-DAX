# -Modelando-um-Dashboard-de-E-commerce-com-Power-BI-Utilizando-F-rmulas-DAX
## Projeto   Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX
### Descrição do Desafio de Projeto
Utilizaremos a tabela única de Financial Sample para criar as tabelas dimensão e fato do nosso modelo baseado em star schema.
O processo consiste na criação das tabelas com base na tabela original. A partir da cópia serão selecionadas as colunas que irão compor a visão da nova tabela. Sendo assim, a partir da tabela principal serão criadas as tabelas: 
Financials_origem (modo oculto – backup)

D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)
D_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price,  Units Sold, Manufactoring Price)
D_Descontos (ID_produto, Discount, Discount Band)
D_Detalhes (*)
D_Calendário – Criada por DAX com calendar()
F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount  Band, Segment, Country, Salers, Profit, Date (campos))

### Criação da Tabela Calendário Com Dax
![Captura de tela 2024-10-07 204554](https://github.com/user-attachments/assets/a0db538f-85f0-4afe-b7f1-ed2ae6fa00a8)

### Criação da Coluna condicional
![Captura de tela 2024-10-07 230518](https://github.com/user-attachments/assets/370ff34e-1f0f-408d-a9c5-95773adf99ab)

### Em resumo conforme solicitado foram realizados tambem alterações na ordem das colunas. Segue Aquivo salvo.

