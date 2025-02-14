# Ponderada Programaçao
&emsp; Cada aluno deve comprovar matematicamente o valor da corrente I1 (malha 1) e I2 (malha 2), além do VR1 (tensão sobre o R1), VR2, VR3, VR4 e VR5 usando o LKT e a Lei de Ohm. Montar o circuito em seu TinkerCad, ligar as fontes CC, os resistores, e o amperímetro para medir o Itotal saindo da fonte de 45V, outro para medir o Itotal saindo da fonte de 10V e terceiro amperímetro para medir a corrente no ramo do R3. Além dos amperímetros, precisa ligar um voltímetro em cada resistor do circuito.

## Barema
Trabalho individual. O que precisa ser entregue?

Relatório em PDF contendo:

**(a) Print do Tinkercad com os instrumentos mostrando os valores medidos (tensão e corrente); [1 ponto]**
<div align="center">

  <sub>Figura 1 - tinkercad </sub>

  <img src="/assets/tinkercad.png"/>

</div>

**(b) Link do seu Tinkercad da sua montagem e simulação. Cuidado ao pegar essa URL. Pegue pelo botão ENVIAR PARA que fica no canto direito superior; [1 ponto]**

[Projeto no Tinkercad](https://www.tinkercad.com/things/dI1qGla4mvX/editel?returnTo=%2Fdashboard&sharecode=di6bk-xnDDslROyDvagN61tmuL6TjozE7txKSpoV7dE)

**(c) Explicar porque a corrente I1 e I2 deram sinal positivo ou negativo em seus cálculos; [2 pontos]**

&emsp; Nos meus calculos as correntes I1 e I2 deram sinal positivo porque o sentido assumido nos cálculos estava correto, ou seja, coincidiu com o fluxo real da corrente no circuito. Se tivessem dado valores negativos, isso indicaria que o sentido real era o oposto do que foi inicialmente considerado.

*(resposta da c e d junto na imagem 2)*

**(d) Apresentar as equações das respectivas malhas 1 e 2 (isto é, o sistema linear matemático); [2 pontos]**

**(e) Apresentar os resultados de I1 e de I2 calculados, VR1, VR2, VR3, VR4 e VR5 que precisam bater com os valores simulados; [2 pontos]**

<div align="center">

  <sub>Figura 2 - resolução </sub>

  <img src="/assets/resolucao.png"/>

</div>

*obs: alguns numeros não estão com exatamente o mesmo valor do multimetro devido a arredondamentos!*

**(f) Suponha que seu multímetro tenha 12 ohms de impedância interna na escala de tensão. O que aconteceria com o valor da tensão medido no R3? Justifique. [2 pontos]**

&emsp; Nesse caso o valor da tensão medido em R3 estaria incorreto porque o multímetro, ao ser conectado em paralelo, forma um divisor de tensão com R3. Como ambos têm a mesma resistência de 12 Ω, a tensão se divide igualmente, resultando em uma leitura de metade da tensão real, no caso 12,5. Quanto*maior a resistência do multímetro, menor será o erro, pois menos corrente será desviada. No melhor dos casos, se a resistência do multímetro fosse infinita, ele não alteraria a medição e mostraria a tensão correta.
