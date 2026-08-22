É um espaço na memória do computador utilizado para armazenar informações que serão usadas em seus programas ou em seus scripts.
Com um nome podendo conter um valor de algum tipo que no decorrer do código pode sofrer variação do seu conteúdo.

No C temos tipos específicos de variáveis 

o #int que serve para guardar números inteiros
o #float que serve para guardar números decimais
o #char que serve para guardar letras (caracteres) sendo representados por aspas simples ''

Sintaxe - _type_ _variableName_ = _value_;

int pontos = 67;

> Também dá para declarar a variável e depois dar um valor a ela

int Motoqueiro Fantasma;

Motoqueiro Fantasma = 1;


---

# Tipos de Data

Uma variável em C deve ter um **tipo de dado** específico , e você deve usar um **especificador de formato** dentro da `printf()`função para exibi-la.

Especifica tamanho (bytes) e o tipo da variável 

| Data Type | Size         | Description                                                                                           | Example |
| --------- | ------------ | ----------------------------------------------------------------------------------------------------- | ------- |
| `int`     | 2 or 4 bytes | Stores whole numbers, without decimals                                                                | `1`     |
| `float`   | 4 bytes      | Stores fractional numbers, containing one or more decimals. Sufficient for storing 6-7 decimal digits | `1.99`  |
| `double`  | 8 bytes      | Stores fractional numbers, containing one or more decimals. Sufficient for storing 15 decimal digits  | `1.99`  |
| `char`    | 1 byte       | Stores a single character/letter/number, or ASCII values                                              | `'A'`   |

Existem diferentes especificadores de formato para cada tipo de dado:

> %d ou %i é o int
> 
> %f ou %F é o float
> 
> %lf é o double
> 
> %c é o char
> 
> %s é o string


> Os bytes podem mudar dependendo do sistema se for 32 bits ou 64bits 


> [!NOTE] ASCII
> é um código padrão que traduz letras, números e símbolos em números binários que o computador entende


---

O char é usado para guardar uma letra só 

Sempre usando aspas simples ''

char tier = 'S';

printf("%c", tier);














[[C]]