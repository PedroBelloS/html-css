
TAG DE LISTAS

Usar o OL e entre as OL´S usar li
dentro da tag OL voce pode usar type"" e dentro das aspas voce pode colcoar um numero e a lista irá inicar a partir daquele numero (tambem pode mudar o simbulo da lista tipo A)


Um atalho legal pra cria varias tag iguais com uma digitação e o "*" 
Um exemplo as <li> voce digita li*7 por exemplo e vai cria 7 <li> quando der enter


Listas OL types: 
1 - Numero
A - Letra Maiuscula
a- Letra Minuscula
I- Numeros Romanos
i-Numeros romanos com Letra Minuscula

Lista não ordenada a tag é UL parecido com a ol

Listas UL types: 

disc - disco
circle - circulo
square - quadrado

Para alterar Rapidamente varias tags de uma vez voce pode clicar e dps segurar o alt / clicar segurar o alt (isso me cada tag e no espaço que voce quer) e assim vai

Lista de Definição

tag <dl>


ul {
  list-style-type: '\2714\0020\0020';
  columns: 2;
  list-style-position: inside;
}

A primeira linha de declarações faz com que o marcador seja personalizado com o parâmetro list-style-type. O valor \2714 corresponde ao símbolo ✔️ que tem o código Unicode U+2714 (confira no site da Emojipedia). O valor \0020 corresponde a um espaço em branco (também pode ser \00A0).

A segunda declaração vai organizar a lista em duas colunas. O total de elementos da lista com <li> será dividido em duas partes iguais (ou quase) e o resultado será colunado.

Por fim, a última declaração vai fazer com que os marcadores sejam exibidos na parte interna da caixa que contém a lista. Analise as imagens abaixo e perceba que, por padrão, a caixa de uma lista não inclui os marcadores. Alteramos essa característica usando a declaração list-style-position com o valor inside, já que a lista vai estar dentro de um <aside> no nosso documento HTML.

[[HTML]]

[[CSS]]

[[Emoji em HTML]]