RELEMBRANDO:

Alinhamento horizontal:

text-align: 	left; (padrão)
		    center;
			right;

Alinhamento vertical:	

vertical-align:	top;
			  middle;	(padrão)
			  bottom;


Para números à direita (padrão do Excel):

	- Criar uma classe e alinhar os "td" dessa classe à direita (right).
	  

Usar a pseudo-classe	:nth-child( )

 - Para linhas pares usar (even) ou (2n);
 - Para linhas ímpares usar (odd) ou (2n-1).

 Ex:	tbody > tr:nth-child(odd) {
            	background-color: white;	(opcional quando o fundo já for branco)
	}

	tbody > tr:nth-child(even) {
            	background-color: lightgray;
	}


------------------------------------------------

📝 MESCLANDO CÉLULAS:

Expansão em forma de coluna:	<td colspan=" "></td>

  Ex: <td colspan="2">B</td> -> expandindo B para 2 colunas.

Expansão em forma de linha: <td rowspan=" "></td>

  Ex <td rowspan="3">D</td> -> expandindo D para 3 linhas.
  
  [[Tabelas]]
  
  [[CSS]]