# Alura Store Brasil

---

O AluraStoreBrasil consiste em um desafio de Ciência de Dados, feito do zero, durante o ONE - Oracle Next Education, na trilha de Ciência de Dados.

---

## Problema de negócio:
Você foi contratado como pessoa analista de dados para ajudar Sr. João a decidir **qual loja ele deve vender.**

O Sr. João tem uma rede de quatro lojas, que pertencem ao e-commerce Alura Store. Ele quer vender uma dessas lojas para ter um capital e investir em um novo negócio. 

Você, como pessoa analista de dados, vai **analisar qual dessas lojas tem o menor desempenho comparado às outras e, baseado nisso, fazer um relatório e mostrar para Sr.João qual loja ele deve vender.**

Para isso, você vai analisar as seguintes métricas: `faturamento total de cada loja`, `categorias mais populares`, `média de avaliação dos clientes`, `produtos mais e menos vendidos` e `custo médio do frete`. 

Com essas métricas, você será capaz de decidir qual loja Sr.João deve vender.

---

## Faturamento total de cada loja

O faturamento é a principal métrica a ser analisada e que terá maior peso na avaliação de qual loja deve ser vendida.

O faturamento por loja, em milhões de reais (R$) foi de:

**- Loja 01:** `R$1.535M`

**- Loja 02:** `R$1.488M`

**- Loja 03:** `R$1.464M`

**- Loja 04:** `R$1.384M`

Abaixo, segue o gráfico de faturamento por loja:
<img width="851" height="318" alt="image" src="https://github.com/user-attachments/assets/543dffb3-47bf-4c20-a2ae-467dda3ab87a" />


Podemos concluir com essa análise que:
- A **Loja 01 possui maior faturamento**
- Por outro lado, **Loja 04 possui o menor faturamento**.

## Vendas por categoria

As vendas por categoria nos ajudam a identificar quais são as categorias mais e menos compradas em cada loja.

Abaixo, segue o gráfico de vendas por categoria de cada loja:
<img width="852" height="319" alt="image" src="https://github.com/user-attachments/assets/b2eb09c5-a98c-4847-9480-3ecc836b5722" />
<img width="843" height="313" alt="image" src="https://github.com/user-attachments/assets/98ebdcf2-ddd7-4f26-b308-2be1240c22f7" />


Com base nas análises, obtemos chegar às seguintes conclusões: 
- Em todas as lojas, a categoria de **móveis foi a mais vendida**, totalizando a quantidade de 1886 vendas, o que representa 20% do total de vendas por categoria em todas as lojas.
  
- Seguido da categoria de móveis, temos a categoria de **eletrônicos**, que é a segunda mais vendida, contabilizando 1772 vendas e representando 18.8% do total de vendas.
  
- Em todas as lojas, a categoria de brinquedos foi procurada e obteve uma quantidade de vendas superior à 300. Partindo do ponto que a maior quantidade de vendas registrada entre todas as lojas foi de 499, **a categoria de brinquedos apresenta um bom desempenho nas vendas, ocupando portanto a terceira posição no ranking de categorias mais procuradas.**

- Em todas as lojas, as categorias **Utilidades domésticas**, **Instrumentos musicais** e **Livros** apresentaram uma quantidade de vendas abaixo de 250, sendo essas **as categorias menos procuradas em todas as lojas.**

## Média de avaliação das lojas

As médias de avaliação das lojas representam a satisfação dos clientes em cada loja.

As médias, de 1 a 5, foram, respectivamente:

- **Loja 03:** `4.05`
- **Loja 02:** `4.04`
- **Loja 04:** `4.00`
- **Loja 01:** `3.98`

Pode-se perceber, com essa análise, que:
- A **Loja 3 possui uma maior avaliação**
- A **Loja 01, responsável pelo maior faturamento dentre todas as lojas do Sr.João, é que possui pior avaliação.**
- A **Loja 04, de menor faturamento, apresenta uma média de avaliações razoável**, não estando nem alta como as médias das lojas 03 e 02, e nem muito baixa como a avaliação da loja 01.

## Produtos mais e menos vendidos por loja

Seguem abaixo os gráficos dos 5 produtos mais e menos vendidos de cada loja:


<img width="848" height="527" alt="image" src="https://github.com/user-attachments/assets/b689bb59-c582-45b9-ad86-c28e22d99558" />


<img width="849" height="533" alt="image" src="https://github.com/user-attachments/assets/b7f94875-5646-492c-a3f3-ce0af0e697fc" />


<img width="851" height="535" alt="image" src="https://github.com/user-attachments/assets/aa243575-aab2-4fd4-8efe-491f40d40a85" />


<img width="848" height="534" alt="image" src="https://github.com/user-attachments/assets/4b8a1bf9-7b19-4617-b4b2-d9faa4252165" />


## Frete médio por loja

Segue abaixo o gráfico do preço médio de frete por loja:
<img width="851" height="349" alt="image" src="https://github.com/user-attachments/assets/2e63b24a-af2e-4b8d-b1bb-bd310d6ed5d9" />


Podemos concluir, com a visualização, que:
- A **loja 01**, que possui a maior parte do faturamento, também **possui o maior preço médio de frete**.

- As lojas 02 e 03, que possuem um faturamento intermediário, seguem a mesma linha, com valor de frete também médio.

- A **loja 04**, que possui o menor faturamento, também possui o **menor preço de frete.**


## Qual loja deve ser vendida? 

### Cenário 01 - Venda da pior faturamento:
Com base nos dados analisados, podemos perceber que a `Loja 04` é a que possui menor faturamento e média de avaliações razoável. O seu frete médio é baixo, mas isso possivelmente se deve à baixa quantidade de vendas e faturamento da loja.

Diante desse desempenho abaixo, pode-se concluir que a venda da Loja 4 seria um ótimo negócio, visto que traria lucro pela sua venda, principalmente levando em consideração o desempenho da loja ao nos últimos tempos em faturamento.

### Cenário 02 - Venda de uma das lojas de faturamento intermediário:
As `Lojas 02 e 03` possuem as melhores avaliações, com ambas tendo médias de avaliação extremamente próximas, faturamentos intermediários e preços de frete também intermediários.

Tendo em vista que ambas as lojas possuem uma boa percepção do cliente, com base nas avaliações, apresentam valores de faturamento parecidos e um preço de frete que não é extremamente alto, a venda de uma dessas lojas viria a ser um bom negócio, com preferência para a venda da Loja 3. 

A escolha da Loja 3 se dá pois a loja apresenta um faturamento menor, embora parecido, com o da Loja 02, e uma avaliação semelhante com a da Loja 02 (com ambos tendo uma diferença de apenas 0.01 em suas médias de avaliação). Além disso, a sua venda poderia vir a subir a quantidade de vendas de produtos da categoria de móveis nas demais lojas, o que poderia aumentar consequentemente os faturamentos.

### Visão geral dos possíveis cenários

**Venda da Loja 04:**
- É a loja com pior desempenho em faturamento;
- Possui uma média de avaliações razoável, não sendo nem a pior e nem uma das melhores;
- Sua venda traria o fortalecimento das demais lojas, e ainda traria um alívio quanto às despesas;
- É a escolha de venda mais segura.

**Venda da Loja 03:**
- Dentre as lojas intermediárias (Loja 2 e Loja 3), é a que possui o menor faturamento;
- Embora possua uma nota mais alta (4.05), a sua média de avaliações é muito próxima da média da Loja 2 (4.04), que também é uma média alta;
- Sua venda traria fortalecimento quanto aos produtos vendidos nas demais lojas, visto que, com sua venda, a tendência é que as vendas de imóveis nas demais lojas aumentem;

---


### Recomendação final

Como recomendação final, a escolha mais secura é a venda da loja 4, pois é a que possui o pior faturamento e consequentemente o menor impacto na receita total. Além disso, a sua venda iria reduzir despesas quanto à operação da loja no geral.

---

### 👨🏻‍💻 Autor
Luís Henrique

Data Scientist | UX/UI Designer 

[Conecte-se comigo no LinkedIn](https://www.linkedin.com/in/luishenrique-ia/)
