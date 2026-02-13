## Dicionário de Dados

A base de dados consiste em uma tabela única contendo o histórico de campanhas de marketing. Abaixo, a descrição de cada coluna:

| Coluna | Tipo de Dado | Descrição |
| :--- | :--- | :--- |
| **ID** | Int  | Identificador único do cliente no banco de dados.  | 
| **Ano Nascimento** | Int  | Ano de nascimento do cliente (usado para calcular a idade).| 
| **Escolaridade** | String | Nível de instrução formal do cliente.|
| **Estado Civil** | String | Estado civil do cliente. | 
| **Salario Anual** | Int | Renda anual familiar do cliente. |
| **Filhos em Casa** | int | Quantidade de crianças (pré-escolares) que residem com o cliente.|
| **Adolescentes em Casa** | Int | Quantidade de adolescentes que residem com o cliente.|
| **Data Cadastro** | Date |Data em que o cliente foi registrado no banco de dados da empresa.|
| **Dias Desde Ultima Compra** | Int | Recência: Número de dias decorridos desde a última transação do cliente. |
| **Gasto com Brinquedos** | Int | Valor total gasto na categoria de brinquedos. |
| **Gasto com Moveis** | Int | Valor total gasto na categoria de móveis e decoração. |
| **Gasto com Utilidades** | Int | Valor total gasto em itens de utilidades domésticas.|
| **Gasto com Alimentos** | Int | Valor total gasto na categoria de alimentos/mantimentos. |
| **Gasto com Vestuario** | Int | Valor total gasto em roupas e acessórios. |
| **Numero de Compras com Desconto** | Int | Quantidade de compras realizadas utilizando cupons ou ofertas especiais. |
| **Numero de Compras via Catalogo** | Int | Quantidade de compras efetuadas através de catálogos (venda direta/postal).|
| **Numero de Compras na Loja** | Int | Quantidade de compras realizadas presencialmente em lojas físicas. |
| **Numero Visitas WebSite Mes** | Int | Frequência de visitas ao site da empresa no último mês. |
| **Compra na Campanha 1** | Int | Variável binária (1: aceitou a oferta, 0: não aceitou) para cada campanha específica. |
| **Compra na Campanha 2** | Int | Variável binária (1: aceitou a oferta, 0: não aceitou) para cada campanha específica.|
| **Compra na Campanha 3** | Int | Variável binária (1: aceitou a oferta, 0: não aceitou) para cada campanha específica.|
| **Compra na Campanha 4** | Int | Variável binária (1: aceitou a oferta, 0: não aceitou) para cada campanha específica.|
| **Compra na Campanha 5** | Int | Variável binária (1: aceitou a oferta, 0: não aceitou) para cada campanha específica.|
| **Comprou** | String | Variável Alvo: Indica se o cliente realizou compra na última campanha (0 ou 1). |
| **Pais** | String | País de residência do cliente.|
| **Perfil Familiar** | String | Idade dos dependendentes do cliente(Ex: Apenas Crianças, Crianças e Adolescentes)|
| **Geração** | String | Classificação etária (Ex: Boomers, Gen X, Millennials, Gen Z).|


