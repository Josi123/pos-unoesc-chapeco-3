#### Unoesc Chapecó
#### Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob
#### Disciplina: HTML5+CSS3
#### Professor: Jean Carlo Nascimento
#### Acadêmico(a): Juliano Gustavo Hermes
### Artigo de revisão de CSS3
##### Funcionalidade: Animations
##### O que é?
São mudanças de estado de um objeto na página, essas mudanças podem ser de cor, tamanho, posição. As transições podem ocorrer tantas vezes quanto for especificado. O principal foco da animação é realizar a mesma em um período de tempo, assim executando a tranisação como um animação e não como um degrau de mudança.
##### Onde usar:
Em qualquer elemento.
##### Como usar:
Antes da utilização do atributo animation é necessária a declaração do Keyframe que define a animação a ser executada.
```css
@keyframes animationname {keyframes-selector {css-styles;}}

animation: name duration timing-function delay iteration-count direction fill-mode play-state;
```
##### Exemplo de uso
um exemplo de sintaxe atuando sobre uma div, executando a troca de valor do atributo background-color.

```css
/* Chrome, Safari, Opera */
div {
    width: 100px;
    height: 100px;
    background-color: red;
    -webkit-animation:example 1s linear infinite;
	animation:example 1s linear infinite;
}

/* Chrome, Safari, Opera */
@-webkit-keyframes example {
    0%   {background-color: red;}
    50%  {background-color: yellow;}
    100% {background-color: red;}
}

/* Standard syntax */
@keyframes example {
    0%   {background-color: red;}
    50%  {background-color: yellow;}
    100% {background-color: red;}
}
```
### Referencia:
[Animation](http://www.w3schools.com/cssref/css3_pr_animation.asp)
[Keyframe](http://www.w3schools.com/cssref/css3_pr_animation-keyframes.asp)
[CSS3 Animations](http://www.w3schools.com/css/css3_animations.asp)






http://www.noupe.com/essentials/freebies-tools-templates/css3-exciting-functions-and-features-30-useful-tutorials.html
http://tutorialzine.com/2013/10/12-awesome-css3-features-you-can-finally-use/