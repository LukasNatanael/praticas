## h1

*Negrito*
_Itálico_
~~Riscado~~
*_Negrito e Itálico_*

/* Seleciona o nome da animação */
animation-name: slideInLeft;

/* Duração da animação, define quanto tempo a animação leva para dar uma volta completa.O padrão é 0s, mas se deixarmos 0 a animação não inicia*/
animation-duration: 1s;

/* Define a curva de aceleração para a animação. o padrão é ease.
    - ease-in; ease-out; ease-in-out; linear; ease
*/
animation-timing-function: ease-in;

/* Define o atraso do início da animação */
animation-delay: 1s;

/* Define quantas vezes a animação sera executada.
    - O padrão é 1, isso significa que a animação completará uma volta e depois parará de executar, e assim por diante.
    - Se definirmos infinite, ela será executada infinitamente. */
animation-iteration-count: 1;

/* Define a direção da animação 
    - normal; reverse
*/
animation-direction: normal;

/* none; forwards; backwards; both */
animation-fill-mode: both;

/* Short-hand */
/* Valores padrões podem ser removidos */
/* animation: slideInLeft 1s ease-in 1s; */

transform: translateX(-150px);
    