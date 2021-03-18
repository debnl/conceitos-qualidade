# Alguns conceitos de qualidade importantes para o dia-a-dia!

**Ei, você! É novo no mundo de qualidade e tá se sentindo um pouco perdido?**

![](https://media0.giphy.com/media/xTiTnlU40nShI05woo/giphy.gif?cid=ecf05e47ohnl1sdj6ik04lopz2ipth16qwk5lyl7j0h63e1i&rid=giphy.gif)

Então você tá no repositório certo! Aqui vamos rever alguns conceitos de qualidade de software, desde os mais básicos para os mais avançados e entender como podemos aplicá-los no nosso dia-a-dia. Então, se você se interessou, já pode parar para dar uma estrelhinha por aqui e comece a acompanhar! ⭐

# 1 - O que é a qualidade dentro de um projeto/produto?

> No contexto de desenvolvimento de software, qualidade pode ser entendida como um conjunto de características a serem satisfeitas, de modo que o produto de software atenda às necessidades de seus usuários.  (DevMedia)

Um ponto importante para começarmos: O time **todo** é responsável pela qualidade, não só o QA! A qualidade começa beeeeem antes dos testes, como você pode imaginar! Para entregar um produto de qualidade, precisamos começar entendendo onde ela começa dentro de um projeto!

![](https://media1.giphy.com/media/K4Oo3RmM9QnMk/giphy.gif?cid=ecf05e47iy5auhkyht8321k9tm6hfyixp12cb2axqidcu0vd&rid=giphy.gif)

**Então onde ela começa, Deb?**

A qualidade começa bem no pré-game do projeto! Toda a orientação ao comportamento do produto (escrita de user story, documentação, refinamento) tem um pouco da qualidade em seu processo. O papel do QA é ser um *promotor* da qualidade dentro do time, ensinar e aconselhar os outros membros com os conceitos para que o produto seja um sucesso!

**Como a gente pode aplicar isso na prática, hein?**

-  O QA deve participar de **todas** as cerimônias em um projeto ágil
-  Faça perguntas em todas as fases, entenda as regras de negócios! Elas definem os critérios de aceite do produto
-  Entenda toda a documentação, ela será sua aliada na validação
-  Ao desenvolver, garanta que o que você fez de fato funciona (ou seja, teste antes de chegar no QA)

# 2 - Os conceitos iniciais

Acho que sempre que pensamos em qualidade, pensamos em bugs! Que tal aprendermos um pouco mais sobre eles? 

![](https://media1.giphy.com/media/hfBvI2Pq6zCYo/giphy.gif?cid=ecf05e475a1wtmtefslq0k8xr02dcaupkw7xuoolxrw1www4&rid=giphy.gif)
> Viscoso, mas gostoso! - Rei Leão

**Erro, defeito e falha**

![](https://i.ibb.co/y626KKG/github-com-debnl.png )

**Bug vs. Melhoria**

![](https://media4.giphy.com/media/D5H2pksUeW6Va/giphy.gif)

💡  Um **bug** pode ser detectado na forma de **defeito ou de falha**. Normalmente, ele é observado como:

- Uma divergência de regra de negócio (comportamento atual x comportamento esperado)
- Uma falha (como um endpoint que não é chamado, que gera um erro para o usuário)

É importante lembrar que um bug impacta na entrega / no resultado esperado para o produto. Por isso, os bugs são geralmente abertos na sprint atual quando detectados. Ou seja, eles são de grande prioridade :)

💡 Uma **melhoria** é uma sugestão de **adição na estória** que beneficia o produto, ou seja, uma coisa **não mapeada** na user story. Deve ser analisado:

- Essa melhoria é válida para o cliente (quando não aberta por ele)?
- Essa melhoria cabe no tempo da sprint atual?

Diferente do bug, uma melhoria não impacta na sua entrega! Então, é bom que ao mapear uma seja conversado com o time e agile master se ela cabe ou não na sprint atual!
