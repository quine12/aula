Consideremos duas coisas:
Primeiro, como 1 é o elemento neutro da multiplicação, qualquer valor pode implicitamente ser descrito como estar sendo multiplicado por 1.

$$a=(1)\cdot a$$

E como a divisão é a operação invers da multiplicação, ela também divide o elemento neutro - logo, todo número pode ser descrito como estar sendo dividido por 1.

$$a=\frac{a}{1}$$

E, finalmente, se 1 é o elemento neutro, qualquer "1" pode ser **expandido como a divisão de qualquer coisa por si mesma**

$$1=\frac{a}{a}=\frac{b}{b}=\frac{c}{c}... etc.$$

Multiplicar e dividir por 1 é uma técnica que envolve multiplicar e dividir por um valor ao mesmo tempo, dessa forma conservando a igualdade mas permitindo uma manipulação mais livre sobre como se expressa um determinado elemento matemático.

Dominar essa técnica é um dos processos mais importantes para um entendimento amplo da álgebra e passo fundamental para manipulações algébricas mais avançadas. Você pode usá-la em qualquer elemento sendo operacionalizado dentro do campo da álgebra linear - raízes quadradas, exponenciais, funções... O que for pertinente e conveniente pode ser por meio deste operado, expandido e então simplificado.


Exemplo:
Um exemplo comum no ensino superior para a aplicação dessa técnica é mostrado abaixo.

$$\frac{x-1}{\sqrt{x}-1}$$

Essa expressão, em x=1, leva a uma divisão de 0/0, uma indeterminação. Porém, essa não é a verdadeira natureza desta expressão, é um artifício matemático feito para camuflar o que ela de fato faz e é possível desvelá-lo ao multiplicar e dividir por 1. 
As possibilidades são muitas, então é importante desenvolver certas intuições no que pode funcionar ou não.
  
Por exemplo, recordemos a propriedade distributiva

$$c\cdot(a+b)=ca+cb$$

Se exprimirmos c como, também, uma soma de dois elementos, por exemplo x e y.

$$c\cdot(a+b)=(x+y)\cdot(a+b)$$

Tanto x quanto y são distribuídos a cada um dos elementos da soma que estão multiplicando

$$(x+y)\cdot(a+b)=xa+xb+ya+yb$$

Isso tem particular importância quando estamos multiplicando, por exemplo, expressões no formato (x+a). No caso deste exemplo:

$$(x+a)\cdot(x-a)=x²+ax-xa-a²=x²-a²+(ax-ax)=x²-a²+0$$

Multiplicar uma expressão desse tipo só trocando os sinais produz um efeito interessante onde os dois elementos ficam elevados ao quadrado isoladamente. É uma boa forma de elevar uma raíz quadrada ao quadrado, assim desfazendo-a. 

$$\frac{x-1}{\sqrt{x}-1}$$

Precisamos incluir a expressão abaixo no nosso problema.
  
$$(\sqrt{x}+1)$$

Mas perceba, sempre há um 1 implicito multiplicando qualquer elemento matemático. O que quer dizer que

$$1\cdot\frac{x-1}{\sqrt{x}-1}$$

E como 1 pode ser qualquer coisa dividida por si mesma, por que não substituir raiz de x + 1 dividido por si mesmo?

$$\frac{\sqrt{x}+1}{\sqrt{x}+1}\cdot\frac{x-1}{\sqrt{x}-1}$$

Sabemos que (x+a)(x-a)=x²-a² e vemos um formato muito semelhante se desenhando na expressão acima. Raiz quadrada de x elevada ao quadrado é o próprio x, a raíz foi quebrada.

$$\frac{\sqrt{x}+1}{\sqrt{x}+1}\cdot\frac{x-1}{\sqrt{x}-1}=\frac{(\sqrt{x}+1)(x-1)}{(\sqrt{x})²-1²}=\frac{(\sqrt{x}+1)(x-1)}{(x-1)}$$

Fica evidente a repetição de (x-1) tanto no numerador quanto no denominador, o que quer dizer que é possível simplificar a expressão.

$$\frac{(\sqrt{x}+1)(x-1)}{(x-1)}=(\sqrt{x}+1)\cdot\frac{x-1}{x-1}=(\sqrt{x}+1)\cdot1=\sqrt{x}+1$$

Assim revelando a verdadeira natureza da expressão que fora velada por artifícios matemáticos. A expressão do final e a expressão do começo continuam equivalentes, a igualdade nunca foi quebrada - mas se você substituir 1 agora, não chegará ao misterioso 0 dividido por 0. Este exemplo busca apenas demonstrar a importância que essa técnica tem na manipulação algébrica, embora mesmo nos cursos de exatas ela não recebe mais que uma pincelada.

