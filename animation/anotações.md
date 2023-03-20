## animation-name: slideInLeft;
Seleciona o nome da animação

## animation-duration: 1s;
Duração da animação, define quanto tempo a animação leva para dar uma volta completa.O padrão é 0s, mas se deixarmos 0 a animação não inicia

## animation-timing-function: ease-in;
Define a curva de aceleração para a animação. o padrão é ease.
    - ease-in; ease-out; ease-in-out; linear; ease

## animation-delay: 1s;
Define o atraso do início da animação

Define quantas vezes a animação sera executada.
    - O padrão é 1, isso significa que a animação completará uma volta e depois parará de executar, e assim por diante.

## animation-iteration-count: 1;
- Se definirmos infinite, ela será executada infinitamente.

## animation-direction: normal;
Define a direção da animação 
    - normal; reverse

## animation-fill-mode: both;
none; forwards; backwards; both;

## Short-hand
Valores padrões podem ser removidos
animation: slideInLeft 1s ease-in 1s;
transform: translateX(-150px);
    