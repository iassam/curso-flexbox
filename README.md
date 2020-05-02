# Curso de Flexbox

Extensões recomendadas (Vscode):

-Live Server (Ritwick Dey)


## Começando com flex
adicione o seguinte conteudo no inicio do arquivo .css

```
html,
body,
#app{
    height: 100%;
    margin: 0;
}
```

O codigo acima limpara toda formatação padrão dos elementos html, body e #app.


## Flex-direction

Responsavel por definir o eixo de alinhamento dos elementos.

```
flex-direction: row;

```
## Usando a propriedade justify-content:
E responsavel por alinhar no eixo declarado no flex-direction

```
justify-content: center;

```

O codigo acima linha o conteudo no centro do eixo definido definido na propriedade flex-direction.

## Usando a propriedade algin-items:
E responsavel por alinhar no eixo inverso ao declarado no flex-direction

```
align-items: center;
```

O codigo acima linha o conteudo inverso ao eixo definido no centro.

## Usando a propriedade flex-wrap:
E responsavel por permitir a quebra de linha

```
flex-wrap: wrap;
```

O codigo acima permite a quebra de linha quando os elementos exederem o espaço lateral disponivel.


### Propriedade align-content
Propriedade auxiliar a flex-wrap que permite alinhar o conteudo da quebra de linha, quando existe quebra de linha. Funciona apenas quando o flex-direction está setado como "row".

```
align-content: center;
```

O código acima faz as linhas quando exitir quebra ficarem centralizadas.


## Propriedades de redimensionamento

### Flex-grow

E responsavel por permitir o elemento "esticar" quando o tamanho de tela ainda possui espaço disponivel sem conteudo.

```
flex-grow: 1;
```

### Flex-shrink

Possibilita comprimir o elemento quando o tamanho da tela diminuir, e similar a propriedade flex-grow, porém com o feito contratio. Ele comprime o elemento. quando a tela não suporta o tamanho definido para o mesmo.

```
flex-shirink: 1;
```

### Propriedade flex

Unifica o uso do flex-grow com o flex-shrink, onde o primeiro parametro e o flex-grow e o segundo o flex-shrink.

```
flex: 1 0;
```

Onde: O flex-grow = 1, e o flex-shrink = 0;


## Propriedade de Ordenação order

Responsavel por ordernar os elementos que possuem a mesma na ordem definida.


```

.box1 {
    order: 1;
}


.box2 {
    order: 2;
}


```

O código acima exibe o box1 como primeiro elemento da lista e o box2 na segunda posição da lista.