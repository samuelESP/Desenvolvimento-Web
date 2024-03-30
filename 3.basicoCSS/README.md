# DIV

vem de divisão, ou seja, é uma divisão do espaço da página.
Ela é usada para separar minhas áreas.

Por padrão ela ocupa 100% do espaçamento da tela

# Span

É igual uma Div, porém, ele ocupa espaço inline.


# Border

Modificar a bordar do meu componente

`Border: border-width border-style border-color`

```css
border: Tamanho Tipo Cor
```

Ainda podemos modificar a bordar de forma mais especifica:

```css
border-top: Tamanho Tipo Cor
border-bottom: Tamanho Tipo Cor
border-left: Tamanho Tipo Cor
border-right: Tamanho Tipo Cor
```


A borda pode ser do tipo hidden, que é muito parecido com o none
A difenreça é que no none a bordar não existe, no hidden ela existe porém é invisivel

Eu ainda posso criar uma bordar mesclada:

```css
    border-color: red black blue violet;
	border-width: 1px 2px 5px 10px;
	border-style: dashed dotted solid ridge;
```


inset: borda em baixo relevo. É um efeito aplicado em uma tonalidade mais escura que a cor definida e faz com que o elemento tenha a aparência levemente pressionada. Ex: border-style: inset;

outset: borda em alto relevo. É um efeito inverso ao inset e faz com que o elemento tenha a aparência levemente elevada. Ex: border-style: outset.