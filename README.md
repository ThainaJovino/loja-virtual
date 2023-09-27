##continuação loja virtual...
</head>
<body <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
    <title>Barbearia Alura</title>
</head>
<body>
    <header>
        <h1 class="titulo-principal">Barbearia Alura</h1>
    </header>
    <img id="banner" src="banner.jpg">
    <h2 class="titulo-centralizado">Sobre a loja virtual</h1>
    <img id="banner" src="banner.jpg" alt="Banner da Barbearia Alura">
    <h2 class="titulo-centralizado">Sobre a Barbearia Alura</h2>
    <div class="principal">
        <p>Localizada no coração da cidade a <strong> loja vitual </strong> traz para a loja o que há de melhor para oseu visual e estilo.
        <p>Localizada no coração da cidade, a <strong>loja virtual</strong> traz para o mercado o que há de melhor para o seu etilo.
        Fundada em 2019, a loja virtual já é destaque na cidade e conquista novos clientes a cada dia.</p>

        <p id="missao"> <em> <strong> Nossa missão é: "Proporcionar auto-estima e qualidade de vida aos clientes".</strong> </em></p>
        <p id="missao"> <em> <strong>Nossa missão é: "Proporcionar auto-estima e qualidade de vida aos clientes".</strong> </em></p>

        <p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. 
        O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
    </div>
    <div class="beneficios">
        <h3 class="titulo-centralizado">Benefícios</h2>
        <h3 class="titulo-centralizado">Benefícios</h3>
        <ul>
            <li class="itens">Atendimento aos Clientes</li>
            <li class="itens">Espaço diferenciado</li>
            <li class="itens">Localização</li>
            <li class="itens">Profissionais Qualificados</li>
        </ul>
        <img src="beneficios.jpg" class="imagembeneficios">
        <img src="beneficios.jpg" class="imagembeneficios" alt="Benefícios da loja virtual">
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <img id="banner" src="banner.jpg">
    <h1>Sobre a Barbearia Alura</h1>
    <div class="principal">
        <p>Localizada no coração da cidade a <strong> Barbearia Alura </strong> traz para o mercado o que há de melhor para o seu visual.
        Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

        <p id="missao"> <em> <strong> Nossa missão é: "Proporcionar auto-estima e qualidade de vida aos clientes".</strong> </em></p>

        <p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. 
        O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
    </div>
    <div class="beneficios">
        <h2>Benefícios</h2>
        <ul>
            <li class="itens">Atendimento aos Clientes</li>
            <li class="itens">Espaço diferenciado</li>
            <li class="itens">Localização</li>
            <li class="itens">Profissionais Qualificados</li>
        </ul>
        <img src="beneficios.jpg" class="imagembeneficios">
    </div>
</body>
</html>
 58 changes: 58 additions & 0 deletions58  
style.css
@@ -0,0 +1,58 @@
body {
    background: #CCCCCC
}


.principal{
    background: #b8b6b6;
    padding: 10px;
}

p {
    text-align: center;
}

em strong {
    color: #FF0000;
}

h1 {
    text-align: center;
}

p {
    font-size: 20px;
}

#missao {
    font-size: 30px
}

#banner {
    width: 100%;
}

.itens {
    font-style: italic;
    font-size: 30px;
}

.beneficios {
    background: #ccbaba;
    padding: 20px;
}

h2 {
    text-align: center;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
}

.imagembeneficios {
    width: 50%;
}
/* Reset de estilos para garantir uma base consistente */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    background: #CCCCCC;
    font-family: Arial, sans-serif;
    background-color: #CCCCCC;
    text-align: center;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

.titulo-principal {
    font-size: 36px;
    margin-bottom: 10px;
    text-align: left; /* Alinhar à esquerda */
    padding-left: 20px; /* Adicionar espaço à esquerda */
}

#banner {
    width: 100%;
    height: auto;
    margin: 20px 0;
}

.titulo-centralizado {
    font-size: 24px;
    margin: 20px 0;
    text-align: center; /* Centralizar texto */
}

.principal {
    background: #b8b6b6;
    padding: 10px;
    background-color: #b8b6b6;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

p {
    text-align: center;
    font-size: 20px;
}

em strong {
    color: #FF0000;
}

h1 {
    text-align: center;
    font-weight: bold; /* Adicionar negrito */
}

#missao {
    font-size: 30px;
}

#banner {
    width: 100%;
}

.itens {
    font-style: italic;
    font-size: 30px;
@@ -36,32 +62,29 @@ h1 {
.beneficios {
    background: #ccbaba;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

h2 {
    text-align: center;
ul {
    list-style: none; /* Remover marcadores de lista */
    margin: 0;
    padding: 0;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
ul li {
    font-size: 20px;
    margin-bottom: 10px;
}

.imagembeneficios {
    width: 50%;
    display: block; /* Centralizar imagem horizontalmente */
    margin: 0 auto;
}

.titulo-principal {
    padding-left: 20px;
}

.titulo-centralizado {
/* Adicionar estilo específico para h2 */
h2 {
    font-size: 24px;
    text-align: center;
}


.titulo-centralizado {
    text-align: center
    margin: 20px 0;
/* Reset de estilos para garantir uma base consistente */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    background: #CCCCCC;
    font-family: Arial, sans-serif;
    background-color: #CCCCCC;
    text-align: center;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

.titulo-principal {
    font-size: 36px;
    margin-bottom: 10px;
    text-align: left; /* Alinhar à esquerda */
    padding-left: 20px; /* Adicionar espaço à esquerda */
}

#banner {
    width: 100%;
    height: auto;
    margin: 20px 0;
}

.titulo-centralizado {
    font-size: 24px;
    margin: 20px 0;
    text-align: center; /* Centralizar texto */
}

.principal {
    background: #b8b6b6;
    padding: 10px;
    background-color: #b8b6b6;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

p {
    text-align: center;
    font-size: 20px;
}

em strong {
    color: #FF0000;
}

h1 {
    text-align: center;
    font-weight: bold; /* Adicionar negrito */
}

#missao {
    font-size: 30px;
}

#banner {
    width: 100%;
}

.itens {
    font-style: italic;
    font-size: 30px;
@@ -36,32 +62,29 @@ h1 {
.beneficios {
    background: #ccbaba;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

h2 {
    text-align: center;
ul {
    list-style: none; /* Remover marcadores de lista */
    margin: 0;
    padding: 0;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
ul li {
    font-size: 20px;
    margin-bottom: 10px;
}

.imagembeneficios {
    width: 50%;
    display: block; /* Centralizar imagem horizontalmente */
    margin: 0 auto;
}

.titulo-principal {
    padding-left: 20px;
}

.titulo-centralizado {
/* Adicionar estilo específico para h2 */
h2 {
    font-size: 24px;
    text-align: center;
}


.titulo-centralizado {
    text-align: center
    margin: 20px 0;
/* Reset de estilos para garantir uma base consistente */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    background: #CCCCCC;
    font-family: Arial, sans-serif;
    background-color: #CCCCCC;
    text-align: center;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

.titulo-principal {
    font-size: 36px;
    margin-bottom: 10px;
    text-align: left; /* Alinhar à esquerda */
    padding-left: 20px; /* Adicionar espaço à esquerda */
}

#banner {
    width: 100%;
    height: auto;
    margin: 20px 0;
}

.titulo-centralizado {
    font-size: 24px;
    margin: 20px 0;
    text-align: center; /* Centralizar texto */
}

.principal {
    background: #b8b6b6;
    padding: 10px;
    background-color: #b8b6b6;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

p {
    text-align: center;
    font-size: 20px;
}

em strong {
    color: #FF0000;
}

h1 {
    text-align: center;
    font-weight: bold; /* Adicionar negrito */
}

#missao {
    font-size: 30px;
}

#banner {
    width: 100%;
}

.itens {
    font-style: italic;
    font-size: 30px;
@@ -36,32 +62,29 @@ h1 {
.beneficios {
    background: #ccbaba;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

h2 {
    text-align: center;
ul {
    list-style: none; /* Remover marcadores de lista */
    margin: 0;
    padding: 0;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
ul li {
    font-size: 20px;
    margin-bottom: 10px;
}

.imagembeneficios {
    width: 50%;
    display: block; /* Centralizar imagem horizontalmente */
    margin: 0 auto;
}

.titulo-principal {
    padding-left: 20px;
}

.titulo-centralizado {
/* Adicionar estilo específico para h2 */
h2 {
    font-size: 24px;
    text-align: center;
}


.titulo-centralizado {
    text-align: center
    margin: 20px 0;
/* Reset de estilos para garantir uma base consistente */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    background: #CCCCCC;
    font-family: Arial, sans-serif;
    background-color: #CCCCCC;
    text-align: center;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

.titulo-principal {
    font-size: 36px;
    margin-bottom: 10px;
    text-align: left; /* Alinhar à esquerda */
    padding-left: 20px; /* Adicionar espaço à esquerda */
}

#banner {
    width: 100%;
    height: auto;
    margin: 20px 0;
}

.titulo-centralizado {
    font-size: 24px;
    margin: 20px 0;
    text-align: center; /* Centralizar texto */
}

.principal {
    background: #b8b6b6;
    padding: 10px;
    background-color: #b8b6b6;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

p {
    text-align: center;
    font-size: 20px;
}

em strong {
    color: #FF0000;
}

h1 {
    text-align: center;
    font-weight: bold; /* Adicionar negrito */
}

#missao {
    font-size: 30px;
}

#banner {
    width: 100%;
}

.itens {
    font-style: italic;
    font-size: 30px;
@@ -36,32 +62,29 @@ h1 {
.beneficios {
    background: #ccbaba;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

h2 {
    text-align: center;
ul {
    list-style: none; /* Remover marcadores de lista */
    margin: 0;
    padding: 0;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
ul li {
    font-size: 20px;
    margin-bottom: 10px;
}

.imagembeneficios {
    width: 50%;
    display: block; /* Centralizar imagem horizontalmente */
    margin: 0 auto;
}

.titulo-principal {
    padding-left: 20px;
}

.titulo-centralizado {
/* Adicionar estilo específico para h2 */
h2 {
    font-size: 24px;
    text-align: center;
}


.titulo-centralizado {
    text-align: center
    margin: 20px 0;
/* Reset de estilos para garantir uma base consistente */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    background: #CCCCCC;
    font-family: Arial, sans-serif;
    background-color: #CCCCCC;
    text-align: center;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

.titulo-principal {
    font-size: 36px;
    margin-bottom: 10px;
    text-align: left; /* Alinhar à esquerda */
    padding-left: 20px; /* Adicionar espaço à esquerda */
}

#banner {
    width: 100%;
    height: auto;
    margin: 20px 0;
}

.titulo-centralizado {
    font-size: 24px;
    margin: 20px 0;
    text-align: center; /* Centralizar texto */
}

.principal {
    background: #b8b6b6;
    padding: 10px;
    background-color: #b8b6b6;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

p {
    text-align: center;
    font-size: 20px;
}

em strong {
    color: #FF0000;
}

h1 {
    text-align: center;
    font-weight: bold; /* Adicionar negrito */
}

#missao {
    font-size: 30px;
}

#banner {
    width: 100%;
}

.itens {
    font-style: italic;
    font-size: 30px;
@@ -36,32 +62,29 @@ h1 {
.beneficios {
    background: #ccbaba;
    padding: 20px;
    text-align: center; /* Centralizar texto */
}

h2 {
    text-align: center;
ul {
    list-style: none; /* Remover marcadores de lista */
    margin: 0;
    padding: 0;
}

ul {
    display: inline-block;
    vertical-align: top;
    width: 20%;
    margin-right: 15%;
ul li {
    font-size: 20px;
    margin-bottom: 10px;
}

.imagembeneficios {
    width: 50%;
    display: block; /* Centralizar imagem horizontalmente */
    margin: 0 auto;
}

.titulo-principal {
    padding-left: 20px;
}

.titulo-centralizado {
/* Adicionar estilo específico para h2 */
h2 {
    font-size: 24px;
    text-align: center;
}









