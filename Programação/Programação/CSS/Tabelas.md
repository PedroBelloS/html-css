
Hierarquia de tabelas simples:


table (tabela)
	table row	(tr - linha)
		table header (th -cabeçalho)
			table data	(td - dado)
			

<table>
		<tr>
			<td>A1</td>
            <td>B1</td>
            <td>C1</td>
         </tr>
		 <tr>
            <td>A2</td>
		    <td>B2</td>
            <td>C2</td>
        </tr>
         <tr>
           	   <td>A3</td>
            <td>B3</td>
            <td>C3</td>
        </tr>
         <tr>
            <td>A4</td>
            <td>B4</td>
            <td>C4</td>
         </tr>
</table>   

- De forma mais prática podemos escrever: table>tr*4>td*3  +  Enter
  
  Estilo:

	<style>
        		body {
            		 font-family: Arial, Helvetica, sans-serif;
        		}

        		table {
            		width: 400px;
            		border-collapse: collapse;	  (junta as bordas das células)
       		        }

       		    tr.linha {
            		background-color: lightgrey;
        		}

        		td {
            		border: 1px solid black;
          		     padding: 8px;
        		}

        		td.dado {
            		background-color: yellow;
        		}
    </style>
    

---


> Observações:

>    - W3C: os fechamentos das tags <tr> e <td> não são obrigatórios, porém recomendados;
>    - Se a hierarquia não for respeitada, os elementos vão aparecer antes ou depois da tabela.


Dentro de uma célula de tabela (dado de tabela), é possível alterar o alinhamento do texto dessa célula... Tanto o Alinhamento Horizontal (coluna esquerda, central e direita) quanto o Alinhamento Vertical (linha do topo, centro e base).

Para fazer o alinhamento horizontal: Devemos abrir um seletor para o elemento " td " e usar a Propriedade de Estilo " text-align ", onde podemos alinhar os textos atribuindo os valores " left ", " center " ou " right ".

Para fazer o alinhamento vertical: Devemos abrir um seletor para o elemento " td " e usar a Propriedade de Estilo " vertical-align ", onde podemos alinhar os textos atribuindo os valores " top ", " middle " e " bottom ".

> Observação: Você pode configurar uma identificação (id ou class) para uma célula específica ( td ) que você queira mudar o alinhamento do texto, dessa forma isso acontecerá de forma isolada, alinhando o texto só daquela célula de você identificou.


[[Tabelas 2]]

[[HTML]]

[[CSS]]