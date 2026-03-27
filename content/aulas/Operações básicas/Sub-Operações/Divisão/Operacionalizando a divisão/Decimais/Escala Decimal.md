A Escala decimal
A divisão e multiplicação por 10 são casos de particular interesse devido à sua simplicidade e linearidade. A escala decimal assim é definida por utilizar a base 10. Essa base pode ser elevada à qualquer potência (10², 10³, 10⁴) que ela pouco altera os algarismos sendo representados e, da mesma forma, ela pode ser elevada à qualquer potência negativa, nesse caso representando uma divisão.

$$10^{-4}=\frac{1}{10^{4}}$$

O caso mais importante envolve o uso de Decimais, os números após uma vírgula. Cada algarismo após a vírgula representa um número ocupando decrescentes magnitudes de 10^-n
onde n indica qual algarismo após a vírgula estamos nos referindo contando a partir do primeiro. Cada algarismo é um espaço que pouco interage com os outros algarismos a menos que algo faça esse espaço conter o algarismo *10*, que nesse caso leva a elevar em 1 o algarismo à esquerda, 0,5+0,5 = 0,(10)=1,0.

Uma algoritmo para converter da notação decimal para a notação fracionária é 

1. Retirar a vírgula do seu valor
2. Contar o **número de algarismos** que compõem o valor
3. Dividir o valor sem vírgula por 1 seguido de (**número de algarismos** -1) zeros

* Exemplo
  Escolhamos o valor 0,541236 para o exemplo.
  
  1-  Retiramos a vírgula; *0541236* 
  2- Contamos o número de algarismos; |0|5|4|1|2|3|6| , **7** algarismos
  3- Dividimos 0541236 por 1 seguido de (**7**-1) zeros, 6 zeros, 1|0|0|0|0|0|0|, 1000000

  $$\frac{0541236}{1000000}=\frac{541236}{1000000}$$

* Um detalhe importante
  Por meio da propriedade associativa da soma, é possível descrever um número decimal a partir da soma de seus elementos

  $$0.541236=0.5+0.04+0.001+0.0002+0.00003+0.000006$$

	  E por meio disso é possível aglutinar novamente para operacionalizar apenas um ou outro algarismo que, em um dado contexto, se prove mais relevante. Por exemplo, quando há um número de escala muito elevada sendo somado a números de escalas micro ou nanométricas que realizam várias operações.

  $$0.541236=0.5412+0.000036$$

  Um Domínio pleno das propriedades associativas e distributivas  é importante para que se realize operações por vias mais ágeis.




