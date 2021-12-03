# Trabalhando com pug

Precisamos lembrar que ele não trabalha com fechamento de tags e para que ele funcione corretamente é necessario trabalhar muito bem a indentação do seu arquivo.

## exemplo

    html
        head
            title Trabalhando com pug

        body
            h1 Ola

Alem disso podemos estilizar nossas classes utilizando uma separação por .

## exemplo

    html
        head
            title Trabalhando com pug
            style.
                .exemplo{
                    color:#0022ff;
                }

        body
            h1.exemplo Ola

Porem não nos limitamos a uma classe apenas podemos colocar quantas forem necessarias adicionando .exemplo.exemplo2.exemplo3

porem se desejat trabalhar com id você pode usar a #sequido do nome

## exemplo

body
h1#id.exemplo Ola

Caso você queira criar divs você pode usar a seguinte extrutura

body
h1.exemplo Ola
.exemplo
p Texto dentro da div de exemplo
