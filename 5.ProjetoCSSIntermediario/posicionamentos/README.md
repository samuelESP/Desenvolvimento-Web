# Static e Relative

Podemos trocar o posicionamento dos nossos elementos/blocos usando a propriedade chamada de position;
Por padrão a position é static, ou seja, se eu definir `position:Static` ele vai seguir o fluxo padrão do html;

<img src="Screenshot_1.png">

`position: relative`

usando o relative, o nosso bloco vai seguir um posicionamento relativo ao seu posicionamento de origem:

```css
.relative{
            border: 1px solid red;
            position: relative;
            left: 100px;
        }
```

<img src="Screenshot_2.png">


```css
.relative{
            border: 1px solid red;
            position: relative;
            left: 300px;
            top: 100px;
        }
```

<img src="Screenshot_3.png">


#Absolute e fix

Quando a gente define uma `position: absolute` ele sai do fluxo normal do documento e ele não afeta a posição dos outros elementos da página;

<img src="Screenshot_4.png">

Porém ele funciona como se fica-se por cima do elemento, então, ele pode acabar tampando o outro elemento, veja:

<img src="Screenshot_5.png">


Ele vai ser posicionado de acordo com o seu container, porém se o seu container não tiver uma `position!= static` ele vai ser posicionado de acordo com a página


```css
.absolute{
            position: absolute;
            border: 1px solid violet;
            top: 0px;
            background: #fff;
            left: 700px;
        }
```

<img src="Screenshot_7.png">

Pórem, ele pode ser posicionado de acordo com o meu container, basta colocar o meu container como relative:

<img src="Screenshot_8.png">


também existe o `position: fixed`, que ele fez com que o elemento fique fixo na minha página, ou seja, mesmo se eu rolar a página ele vai ficar fixo e acompanhar a página.