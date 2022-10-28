#cascading

A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento.

Seu estilo é lido de cima para baixo, ou seja, caso haja algum selector com informações conflitantes, o mais embaixo é o que será atribuído.
São levados em consideração 3 fatores:

A origem do estilo;

A especificidade;

A importância;

##especificidade


É um cálculo matemático, onde cada tipo de seletor e origem do estilo possuem valores a serem considerados.

Os mais fracos são universal selector, combinators e negation pseudo-class, com o valor de 0. Em seguida, com valor de 1, são os element type selector e pseudo-elements.

Também temos os classes e attribute selectors, com valor de 10, ou seja, são mais fortes que os anteriores.

O segundo mais forte, ID selector, com um valor de 100, vence todos os selectors anteriores.

Por fim, temos o inline, com o valor 1000, quaisquer desses selectors anteriormente citado