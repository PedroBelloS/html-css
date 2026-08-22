
📝 Pseudo-classes em CSS 📝

Representadas por	:

  ex: 	:active	:checked	:enabled	   :disabled	:corner-present	
	        :empty	:end		:first	   :hover	        :double-button

:hover	->	quando passa o mouse por cima acontece algo

	ex:	div:hover {
            	background-color: yellow;
        	}

div > p	-> parágrafo que está dentro da div (p é filho de div)

Deixar texto de "p" invisível:
	
	div > p {
	   display: none;
	}

Deixar texto de "p" visível quando passar o mouse em cima:
  (útil para criar menu)

	div:hover > p {
	        display: block;
	}

<div>	->	é um espaço qualquer

<height>	->	altura

 <width>	->	largura

<border>	->	borda		ex:	border: 1px solid black; (shorthand)

display: inline-block; 	->	 tudo na mesma linha




# = id

. = class

: = pseudo-class

: : = pseudo-element

> = children

[[DIV]]

[[CSS]]