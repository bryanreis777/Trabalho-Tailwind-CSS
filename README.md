# Trabalho-Tailwind-CSS
<p>O Tailwind CSS é uma ferramenta criada para transformar a forma como construímos o visual de páginas na web. Para quem já entende o básico de HTML e CSS, o modelo tradicional funciona assim: você cria a estrutura no HTML (como uma div class= 'cartao'), vai até um arquivo CSS separado e escreve regras para essa classe, definindo largura, cor de fundo, espaçamentos e fontes. Embora esse método funcione, ele traz alguns desafios com o passar do tempo: os arquivos CSS ficam gigantescos, você precisa ficar inventando nomes de classes para cada elemento e, muitas vezes, alterar o estilo de um botão em uma página acaba quebrando o layout de outra sem você perceber.

É exatamente para resolver esses problemas que o Tailwind foi criado. Em vez de funcionar como um arquivo de estilos separado onde você inventa suas próprias regras, o Tailwind adota o conceito chamado Utility-First (utilitário em primeiro lugar). Ele já vem com centenas de "micro-classes" pré-prontas que representam propriedades CSS individuais. Por exemplo, em vez de criar uma classe chamada .botao no seu CSS, você aplica diretamente no seu HTML classes como bg-blue-500 (para um fundo azul), text-white (para texto branco), p-4 (para um espaçamento interno/padding) e rounded-lg (para arredondar as bordas).

Na prática, isso significa que você constrói o design do seu site montando "blocos de montar" diretamente na estrutura do HTML, sem precisar abrir um arquivo CSS separado ou gastar tempo pensando em nomes de classes. Se você precisa que um texto fique grande e em negrito, basta adicionar text-xl font-bold. Se quer que um elemento fique visível apenas em telas grandes de computador, utiliza o prefixo de responsividade md:block. Tudo é feito de forma declarativa e direta no próprio código da página.

A principal finalidade do Tailwind CSS é dar velocidade, padronização e facilidade de manutenção ao desenvolvimento web. Ele impede que você use cores ou espaçamentos desalinhados, pois disponibiliza uma escala de design padronizada e harmoniosa. Além disso, ele elimina o medo de alterar o visual de um elemento e acabar desconfigurando outro lugar do site, já que cada conjunto de classes utilitárias afeta apenas a tag HTML onde foi inserido. Em resumo, o Tailwind serve para acelerar a criação de interfaces modernas, mantendo o código organizado e extremamente fácil de personalizar.
Curiosidades interessantes sobre elementos utilizados durante o trabalho:

A tag "pre" cria o "quadro estilo terminal" onde o código de exemplo fica visível para quem está assistindo à apresentação.

No HTML, para exibir o caractere de menor < e maior > como texto na tela (sem o navegador achar que é uma tag de verdade), usamos as entidades:

&lt; = < (Less Than)

&gt; = > (Greater Than)

Meta para as seções: </p>
<ul>
  <li>Introdução;</li>
   <li>História;</li>
  <li>Evolução;</li>
   <li>Por quê usar?;</li>
   <li>Exemplos de Uso;</li>
   <li>Venda e Suporte</li>
   <li>Integrantes;</li>
</ul>
