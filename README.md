A sintaxe é a seguinte:

color-function(from origin-color channel1 channel2 channel3 / alpha(optional))

Eu tenho um elemento com borda preta e quero aplicar uma opacidade de 10%. Com a sintaxe de cores relativas, ficará assim: 

 border-color: rgb(from #000 r g b / 0.1);

é como se estivesse dizendo "Obtenha os valores rgb de `#000` e altere o alfa para `0.1`"

Eu também posso modificar qualquer canal usando calc(). Por exemplo:

 background-color: hsl(from hashtag#FF0000 h s calc(l + 10));

Nesse exemplo, ele está pegando o valor atual do canal de luminosidade e adicionando 10 a ele. A cor ficará mais clara!
Para deixar a cor mais escura, basta subtrair 10.

Há muito mais do que isso sobre cores relativas e aqui está a fonte: 
https://lnkd.in/dHJUGMF7
