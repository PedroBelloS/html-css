
IMAGE

background-image: url(teste.png)


Note que ao usar o no-repeat, isso não obriga o navegador a aumentar ou diminuir o tamanho da imagem para caber no tamanho da caixa. Para realizar essa adaptação, devemos usar outra propriedade, que veremos mais adiante.

Além de escolher o nível de repetição do background, também podemos mudar a posição de referência de início das repetições. Por padrão, é considerado o canto esquerdo superior (left top), mas podemos ter várias opções. Use a imagem abaixo como referência sempre que precisar definir a posição do fundo com a propriedade background-position no seu código.


| left top    | center top    | right top    |
| ----------- | ------------- | ------------ |
| left center | center center | right center |
| left bottom | center bottom | right bottom |

---

Outra coisa que podemos fazer é redimensionar a imagem para forçá-la a caber na caixa. Por padrão, nenhum redimensionamento será aplicado, e a imagem será exibida do seu tamanho natural. Porém, podemos usar a propriedade [background-size] para alterar esse comportamento.

## Propriedade `background-size`

Os valores aceitos por essa propriedade são:

- **`auto` (padrão):** A imagem de fundo é exibida em seu tamanho original.
    
- **`[length]px` / `[length]%`:** Redimensiona a largura da imagem e ajusta a altura automaticamente (se passar apenas um valor). Podemos também informar as duas dimensões na sequência (ex: `200px 100px`) ou usar porcentagens.
    
- **`cover`:** Redimensiona a imagem para que ela **cubra todo o contêiner**, mesmo que para isso ocorra algum corte na imagem.
    
- **`contain`:** Redimensiona a imagem para que ela seja **sempre totalmente exibida** na tela/contêiner, sem nenhum corte (podendo deixar espaços vazios nas laterais ou em cima/em baixo).
  
  

---

background-attachment: scroll; - padrão: o fundo rola junto com o conteúdo


background-attachment: fixed; - o fundo fica fixo na tela conforme o conteúdo rola 


background: [color] [image] [position] / [size] [repeat] [attachment];


Exemplo: 

<style>

background: black url('imagens/wallpaper002.jpg') center center / cover no-repeat fixed;

</style>

[[CSS]]
