# Curso de Flexbox

Extensões recomendadas (Vscode):

-Live Server (Ritwick Dey)

---

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

---

## Flex-direction

Responsavel por definir o eixo de alinhamento dos elementos.

```
flex-direction: row;

```

## Usando a propriedade algin-items:
E responsavel por alinhar no eixo inverso ao declarado no flex-direction

```
align-items: center;

```

O codigo acima linha o conteudo inverso ao eixo definido no centro.

## Usando a propriedade justify-content:
E responsavel por alinhar no eixo declarado no flex-direction

```
justify-content: center;

```

O codigo acima linha o conteudo no centro do eixo definido definido na propriedade flex-direction.