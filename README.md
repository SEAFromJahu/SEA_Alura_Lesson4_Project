# SEA_Alura_Lesson4_Project
# Obter a quantidade de combinações de sequencias sonoras distintas são consideradas musicais. 
*Considerações, sabendo-se que:*
1.  A faixa de frequência audível para humanos é normalmente entre 20 Hz e 20.000 Hz.
2.  Baixas frequências (20 Hz - 200 Hz): Essas frequências são sentidas mais como vibrações do que como sons e são produzidas por objetos grandes como terremotos, trovões e graves profundos.
3.  Médias frequências (200 Hz - 2.000 Hz): Esta faixa contém a maioria dos sons fundamentais da fala humana e de muitos instrumentos musicais.
4.  Altas frequências (2.000 Hz - 20.000 Hz): Sons agudos, como assobios, canto de pássaros e harmônicos de instrumentos musicais, caem nesta faixa.
5.  Embora a faixa de audição humana seja frequentemente descrita como 20 Hz a 20.000 Hz, não é tão simples quanto contar os números entre esses dois limites.
Isso ocorre porque a frequência é medida em uma escala logarítmica, não linear.
6.  Calculando o Número de Frequências Audíveis
Embora seja tecnicamente impossível contar o número exato de frequências audíveis entre 20 Hz e 20.000 Hz devido à natureza contínua da escala de frequência, podemos aproximar um número usando o conceito de discriminação de frequência.
7.  A discriminação de frequência refere-se à nossa capacidade de distinguir entre duas frequências ligeiramente diferentes. Os humanos geralmente conseguem discriminar entre frequências que diferem em cerca de 0,3% em uma faixa de frequência moderada.
8.  Usando essa informação, podemos fazer uma estimativa aproximada:
Dividimos a faixa de frequência em partes menores: Dividiríamos a faixa de 20 Hz a 20.000 Hz em pequenos intervalos que diferem em 0,3%.
Calcular o número de intervalos: Para fazer isso, podemos usar a fórmula:
Número de intervalos = (log2(f2) - log2(f1)) / log2(1 + d)
Onde:
f1 é a frequência mais baixa (20 Hz)
f2 é a frequência mais alta (20.000 Hz)
d é a diferença justa perceptível (0,003)
# Conectar os valores:
# Número de intervalos = (log2(20.000) - log2(20)) / log2(1,003) ≈ 3283.
Portanto, podemos estimar que existem aproximadamente 3.283 frequências perceptíveis entre 20 Hz e 20.000 Hz.

11.  Combinações de sequencias de frequências sonoras são finitas.
12.  Cada pais ou região em função de costumes prévios pode considerar sequencias (combinações e sequencias de frequências) como músicas. 
13.  Cada pais ou região em função de costumes prévios pode considerar sequencias (combinações e sequencias de frequências) como ruido ou não as considerar músicas. 
14.  Combinações de sequencias de frequências sonoras são finitas.
   
*# Este projeto tem como propósito utilizar IA via Gemini para que, escolhendo-se um pais ou região, a IA consiga calcular quantas combinações de frequência consideradas musicas podem ser produzidas e entendidas como tal.*
