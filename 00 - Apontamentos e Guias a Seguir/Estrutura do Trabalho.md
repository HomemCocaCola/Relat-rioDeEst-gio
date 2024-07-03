---
toc: true
---

# Estado de Arte

# Estágio

## Introdução

### Metodologia

### Ferramentas

> Talvez juntar a um outro capítulo, por ser algo tão simples, mas tentar falar coisas como "ah, escolhi o WordPress porque assim eles podem alterar facilmente o design das páginas
> 
> Usei o Figma porque ele me permite facilmente fazer protótipos

- Tecnologias Utilizadas - HTML, CSS, JAVASCRIPT, WORDPRESS, CMS
- Foram Utilizadas Estas Tecnologias Porque
  - HTML como complemento de design, quando não era possível desenvolver algum design mais complexo com o editor gutenberg
  - CSS para complementar o HTML e também para editar partes do tema default do Wordpress, quando não existia opçõa no editor
  - Javascript quando existiu a necessidade de acrescentar elementos de forma dinâmica, ou para recriar efeitos complexos
  - WordPress como principal "framework / base" do projeto já que isto permitiu um trabalho mais rápido e que fosse possível, depois de eu sair da empresa, qualquer pessoa facilmente mudar o meu trabalho, como forma de o atualizar ou similar

### Planeamento e Pesquisa

> Necessidade dos Clientes (Quem Vai Ver o Site)
> 
> Métodos de Pesquisa Usados (Análise de Concorrentes)
> 
> Principais Descobertas que Influenciaram o Design

## Páginas Figma

> Descrever o processo de design de cada página
> 
> Objetivos Específicos das Páginas (aumentar a retenção, melhorar a usabilidade, ...)
> 
> Como foi o processo de criação (wireframes, esboços e protótipos)
> 
> Quais escolhas de design foram feitas (cores, tipografias, layout, ...)
> 
> Como as entrevistas com os stakeholders(pessoal do estágio) influenciou o resultado final
> 
> Que desafios/problemas surgiram e como foram resolvidos

### Homepage

> O que foi feito (descrever as ações e ou decisões)
>
> Porque foi feito (justificar as ações, com base em pesquisas, melhores práticas, feedback dos stackeholders,...)
>
> Qual foi o resultado? (descrever os resultados obtidos ou os benefícios esperados)



- Para a homepage, eu necessito ter em atenção que esta é a primeira impressão que um utilizador do website tem com ele, ou seja, necessito o "apanhar". Com esta mentalidade, eu não posso o bombardear com informação em abundância. 
- Com isso em mente, é lógico que preciso precisei colocar o míninmo de texto corrido possível neste página. Alías, não existe grandes extensões de texto em todos os elementos que foram colocados nesta página
- Outra forma de reter a atenção do utilizador é com o uso de interações, desta forma, o utilizador sente a necessidade de interagir com o website. Uma forma simples e efetiva que adotei para todas as páginas do website, mas em especial na homepage, foi a de colocar animações de chegada. Com estas animações, muitos utilizadores acabam por ficar presos ao site, como forma de verificarem todas as animações e interações animadas que podem fazer ao navegar pelo website. Desta forma, existe sempre um novo estimulo para o utilizador, ou seja, ele tem mais razões para ficar no website.
- Preciso é ter em consideração que não se pode exagerar estas animações, já que elas, em especial num website como este, que tem toda uma proposta mais formal, é um erro. Esta opinião é igual para ambos os lados, não só eu acredito nessa teoria, como também as pessoas do meu estágio que trabalham na empresa.
- > Talvez tirar toda a ramble de animações e colocar no código
- A página é composta por 3 elementos principais, um carrossel onde apresento informação rápida dos festivais parceiros, e dois call to actions, sendo um para subscrever a newsletter da empresa e o outro, sendo um para publicitar a ferramente de inscrição de filmes para o festival da empresa
- O resultado final foi algo simples e chamativo, o que casa com a expectativas das pessoas do meu estágio


#### Carrossel

- Para funcionar com a filosofia principal que defeni para a homepage eu decidi desenvolver esta elemento a pensar na habilidade do hover.
- Com o hover, eu tenho bastantes pontos positivos, como a capacidade de conseguir apresentar imensa informação, de uma forma discreta, já que esta apenas aparece se o utilizador necessita. Sem este método, acabaria por ter que fazer uma página muito longa, similar a uma da wikipédia e isso não funciona para uma homepage de um website de empresa, já que precisamos de entregar a informação de forma rápida e bem elaborada, ao contrário da wikipédia que tem como propósito de apresentar muita informação. aliás, a própria wikipédia tem como homepage algo mais simples e só depois te termos a atenção do utilizar é que sim podemos entregar mais do que o normal
- Um outro ponto positivo é que o efeito hover por si só, já aumenta a interatividade do website, assim aumentado a retenção do utilizador
- Ao utilizar o efeito hover, eu consigo criar um design mais complexo, como um do carrossel interativo.
- Este elemento, como forma de explicar melhor, é uma tabela de 6 colunas e uma linha. Com as mudanças de ecrã, este esquema de tabela se altera, onde por exemplo, na versão tablet, este é composto por 3 colunas e duas linhas. 
- No total, 6 elementos são dispostos nesta tabela e cada elemento, é composto por dois estados, o inativo e o em hover
- inativo, cada elemento tem o logotipo do parceiro de festival e um degradê único
- em hover, este elemento expande, encolhendo os outros elementos inativos, e dentro dele, informação surge
- Desta forma, eu consigo apenas mostrar a informação que o utilizar procura e também consigo colocar imensa informação na homepage, de forma compacta, moderna e única
- Uma versão deste sistema, era utilizado na versão anterior do website, mas eu acabei por a melhorar e adaptar para a identidade nova da marca
- Não apenas isso, como fiz alguns ajustes, como aumentar o espaço para apresentar a informação, ao utilizar um formato bem mais vertical que o anterior
- Desta forma, eu tenho mais liberdade de organizar a informação, como por exemplo, eu agora a posso dividir em botões, textos, imagens e títulos, ao contrário da versão anterior que apenas me permitia utilizar um bloco de texto grande
- Uma outra mudança que fiz foi a de acrescentar uma imagem de fundo com o trofeu do festival, nesta infobox que aparece com o hover. Desta forma, o utilizador é "chamado" para se inscrever no festival, devido à imagem do trofeu que remete para prestigio e similares  
- Como em todo o design e seguindo o pedido das pessoas da empresa, eu desta forma também consigo acrescentar um botão para o link deste mesmo festival, de forma a que o público não tão experiente com as tecnologias, consiga identificar imediatamente que existe essa funcionalidade, ao contrário do design do website antigo, onde era necessário carregar em qualquer lado da infobox. Não é uma má utilização deste recurso, pois aumenta a acessibilidade, mas o problema é não indicar que isso é uma opção. Portanto, ao ter o botão, fica claro no meu design essa funcionalidade

> Coisas que Posso Acrescentar, talvez


- [X] EXPLICAR COMO É UMA IDEIA DO ANTIGO MAS EU MELHOREI, POR EXEMPLO NA INFORMAÇÃO ENTREGUE E TAL
- [ ] EXPLICAR QUE TEM UMA ANIMAÇÃO NO DEGRADÊ
- [X] Adicionar imagens do antigo site e do novo



---

### About Page

- Organizei nestes "detailers" já que assim, é listado todos os festivais que a empresa trabalha e se o utilizador quiser conhecer mais sobre, basta ele carregar num e este se expande para entregar a devida informação
- Desta forma, eu consigo apenas apresentar a informação que o utilizador procura e a consigo fazer de uma forma simples que não subrecarrege a página, a deixando repleta de texto
- Com estes detailers, também consigo organizar de uma forma coesa todos os textos, imagens e links, de forma a ter um design bonito e organizado
- dentro de cada um destes festivais, foram colocados links para as redes sociais e o website oficial do festival
- com base no conhecimento e a pedido do Hugo, ele sugeriu colocar o link para o website, separado das redes sociais e o colocar sem qualquer ícone para não distrair o utilizador. Pelas palavras dele, se o ícone existir, as pessoas não irão encontrar o link, mesmo que este seja disposto com um link e um icon ao lado. Então, a solução é o de colocar apenas um texto com hiperligação e este deve ficar separado das redes sociais
- com base nas redes sociais, apenas coloquei com ícones, como forma de contrastar com o link do site e também como forma de conseguir colocar toda essa informação, de uma forma mais simples e organizada. Isto deve se ao facto que os nomes nas redes sociais, dos festivais, são muito extensos e complexos, dificultando a usabilidade e estética do website. desta forma, com o site indicativo do festival e os ícones das redes sociais ao lado, o utilizador associa facilmente. ele apenas pensa "festival cifft, facebook" 

---

### Biografia

- Esta página é uma inteiramente focada em apresentar texto e imagem, logo, por natureza, ela é muito simples
- não tinha número predefinidas de imagens para usar, mas optei por 3 já que assim tenho uma quantidade equivalente de texto e imagens, deixando o design harmonioso
- os textos foram organizados em duas colunas, de forma a não ocuparem uma enorme mancha na página. Se não fosse este o caso, não teria o visual refinado e moderno desejado.
- é importante lembrar, que a mancha deixada pelas imagens e o texto necessita ser igual, em prol de um melhor design 

---

### Timeline

---

### Ficha Técnica

---

### Google Maps

---

## Wordpress

### Carrossel

- Para converter o design, utilizei a flexibilidade da flexbox, para conseguir renderizar as colunas. Utilizei flexbox porque assim o design será renderizador de uma melhor forma em diferentes ecrãs, deixando o meu trabalho mais simples e duradouro, sendo compatível com diversos ecrãs
- Para os elementos apresentados, dividi em divs. Uma para alojar o container das colunas, já que é necessário ser assim para o flexbox funcionar e também como forma de organizar código. Um para cada uma das 6 colunas. Dentro de cada coluna, temos mais 2 divs. Uma é para o logotipo, outra para a informação dentro do hover.
- Também utilizei da pseudo classe hover para gerar os efeitos desejados para o carrossel. Desta forma, consigo a interacção que procuro e a consigo fazer de forma simples, pelo próprio CSS, não poluindo o código e o deixado demasiado esparguete.
- o hover do código age na expansão/escolher da width da coluna e as suas divs de dentro e também com as opacidades das divs do logo e da informação. Em suma, quando uma coluna é ativa por hover, ela aumenta a width e retira a opacidade do logo. Ao mesmo tempo, a opacidade que era 0 da informação vai para 1,fazendo com que ela se mostre e também, devido ao flexbox, as demais colunas encolhem para acomodar o aumento de uma das colunas
- Eu dividi em divs, pois isto permitiu uma organização e eficiecia melhor na hora de criar o código. Se não o tivesse feito dessa maneira, aumentaria a complexidade do código, o que por sua vez, iria aumentar o peso no load da página. É também por essa razão que não parti para um código Javascript ou similar, utilizando apenas CSS, tenho uma leveza enorme.

### Timeline

- Para conseguir implementar a página na sua essência, eu vi a necessidade de criar a mesma de forma dinâmica, com o uso do javascript. A minha decisão foi baseada com o facto que, se eu muda-se de monitor, as posições dos elementos iriam mudar, alterando assim a posição dos números.
- DAR CONTEXTO DE COMO DEVE SER É O ELEMENTO NA VERSÃO FINAL
- EXPLICAR COMO FUNCIONA O CÓDIGO, COM BASE NO LIVRO GAMER QUE EU ESCREVI


- Para gerar o elemento da timeline de forma responsiva, inteligente e dinâmica independente do ecrã usado, vi a necessidade de gerar um código dedicado a gerar este elemento.
- A timeline é um elemento visual muito essencial, porque é ela que dá vida a toda a página, de maneira que, a abordagem de a gerar completamente com código é necessária também para esse efeito e também porque o WordPress, com o editor Gutenberg não deixa criar estes elementos mais complexos.
- Para começar, a timeline é composta por uma barra vertical que acompanha todo o ecrã. Esta linha vertical é fácil de a gerar, já que posso definir a width da mesma e depois associar a sua weight com base na altura total da página, pelo JavaScript. Não consigo simplesmente a definir no CSS como um elemento com height=100%; devido à forma como estes códigos externos são renderizados no WordPress. No caso, eles tem prioridade dos elememtos do editor Gutenberg, portanto, quando eu digo no CSS para ocupar a página toda, o tamanho de página que ele tem é apenas a viewport sem nada nela, porque os outros elementos não foram renderizados ainda. Ao renderizar com JavaScript, não só o código será renderizado depois de todos os outros elementos já estarem na pagina, como eu tenho a capacidade de recriar esta linha como deve ser mas também consigo, com matemática, indicar com mais precisão quando é que quero que esta termine
- 
- 


### Headings

- Os headings, no wordpress, não podem ser colocados de forma nativa, com um estilo diferente para palavras, portanto, a solução será sempre a implementação do estilo com o uso do código
- Como forma de deixar o design responsivo e universal com os diferentes ecrãs que existem, optei por criar um código javascript, ao invés de simplesmente gerar as 3 versões possíveis
- Eu podia simplesmente editar o próprio HTML gerado pelo HTML, ao o forçar a colocar um spam no meio do H1, onde, esse heading teria um style inline. A minha tática para com o código Javascript é similar a essa abordagem, mas tenho a liberdade e poder de o fazer as vezes apenas necessárias
- O que o código faz, é procurar na página toda por elementos headings 1. Depois de os encontrar, ele calcula o espaço que estes ocupam no ecrã. Com este valor e o valor do tamanho da width da página, ele faz a conta de quantos mais elementos com o mesmo tamanho podem caber no ecrã.

## Externos do Website

### Posts Carroseel

### People Choice Awards

## Conclusão

- Mesmo que não tenha tido o melhor acompanhamento, devido ao facto que ninguém na empresa era da área que estava a focar, foi uma boa experiência
- se não estivesse neste ambiente, não seria capaz de aumentar a minha habilidade de procurar conhecer e aprender de forma autónoma ao invés de simplesmente pedir ajuda
- também é notável que, por estar envolvido numa actividade verdadeira, ao invés de um simples estudo, eu sou puxado a sempre melhorar
- senti que existiram muitos momentos que se eu estivesse sozinho em casa, a fazer só para "diversão" eu acabaria por estagnar e não procurar resolver problemas que me surgiram durante esta jornada
- claro que não sou de ferro e também é clara a ajuda possível por parte do pessoal do estágio, em me motivar e entregar possiceis soluções para os meus problemas. A atenção e dedicação deles é de louvar
- acredito que esta experiência foi uma mais valia, porque me entregou o gosto de trabalhar em equipa, numa empresa e sentir com mais veracidade o ambiente de trabalho e entregar soluções a problemas nas devidas datas
- posso não ter tido a melhor experiência, mas foi a experiência que tive e a ter já é melhor que ter nenhuma
- conheci colegas para a vida e amadureci como profissional



 Mesmo assim, quero agradecer a todos do estágio por tentarem me ajudar, mesmo quando não compreendiam aquilo a ser falado. A motivação deles 