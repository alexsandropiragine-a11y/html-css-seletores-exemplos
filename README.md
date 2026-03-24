# html-css-seletores-exemplos
Projeto acadêmico demonstrando uso de HTML e CSS (inline, interno e externo), além da aplicação dos principais tipos de seletores CSS.
html-css-seletores-exemplos
1-index.html
2-interno.html
3-externo.html
4-style.css
5-README.md
6-gitignore


1. index.html (CSS INLINE + seletores básicos)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>CSS Inline</title>
</head>
<body>

    <h1 style="color: blue; text-align: center;">Exemplo de CSS Inline</h1>

    <p style="color: green; font-size: 18px;">
        Este parágrafo usa CSS inline.
    </p>

    <p style="background-color: yellow;">
        Outro exemplo de estilo aplicado diretamente na tag.
    </p>

</body>
</html>


3. externo.html (CSS EXTERNO)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>CSS Externo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Exemplo de CSS Externo</h1>

    <p class="texto">Texto com estilo externo</p>

    <p id="destaque">Texto destacado</p>

</body>
</html>
 4. style.css (5 TIPOS DE SELETORES)
/* 1. Seletor de elemento */
h1 {
    color: purple;
}

/* 2. Seletor de classe */
.texto {
    font-size: 18px;
    color: green;
}

/* 3. Seletor de ID */
#destaque {
    background-color: yellow;
}

/* 4. Seletor universal */
* {
    font-family: Arial, sans-serif;
}

/* 5. Seletor descendente */
div p {
    color: orange;
}
5. README.MD
# Projeto HTML e CSS - Seletores

## DESCRIÇÃO:
Este projeto foi desenvolvido como atividade acadêmica para demonstrar o uso de:

- CSS Inline
- CSS Interno
- CSS Externo
- Seletores CSS

## OBJETIVOS:
Apresentar diferentes formas de aplicar estilos em páginas HTML e demonstrar 5 tipos de seletores CSS.

## TIPOS DE SELETORES UTILIZADOS:

1. Seletor de elemento
2. Seletor de classe
3. Seletor de ID
4. Seletor universal
5. Seletor descendente
