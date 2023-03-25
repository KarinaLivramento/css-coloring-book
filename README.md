# css-coloring-book

Esse projeto é um treinamento de css, criado para funcionar como um livro de colorir.

Durante o treinamento você exercitara seletores css como tags, classes e ids, propriedades para formatação de textos, botões e inputs de texto, além disso você também utilizara flex-box para definição do layout das páginas.

## Como funciona?

Neste projeto existe um arquivo chamado <u>components.html</u>, neste arquivo foi definidos componentes html com suas respectivas classes mas sem nenhuma propriedade CSS aplicada aos componentes.

Os componentes foram enumerados e organizados em ordem numérica, você aplicara as propriedades css para cada componente seguindo o guia de estilo fornecido nestas explicações, os componentes foram baseados no site https://godottutorials.com/.

todas as propriedades CSS devem ser definidas no arquivo <u>css/style.css</u>.

Você deve seguir a lista de atividades definidas abaixo, para cada atividade realizada marque o checkbox relativo a essa atividade na lista abaixo até que consiga completar a lista.

### Lista de atividades
- [ ] Definir as cores e fontes padrão para a página
- [ ] Definir o estilo dos titulos
- [ ] Definir o estilo dos texto
- [ ] Definir o estilo dos botões

## Componentes (Guia de estilo)

<details>
    <summary><b>body</b> (cores e fontes padrão)</summary>
    
    Para selecionar a tag <body> no <u>style.css</u> basta usar o nome da tag como no exemplo a baixo:

     body {
        # escreva as propriedades aqui dentro das chaves
     }
    

| descrição | propriedade | valor |
|----------:|-------------|-------|
| fonte     | font-family | Open Sans,sans-serif |
| tamanho da fonte | font-size | 1rem |    
| peso da fonte | font-weight | 400 |
| altura das linhas | line-height | 1.5    |
| alinhamento do texto | text-align | left |
| cor do texto | color | #525f7f    |
| cor de fundo | background-color | #fff    |
</details>

<details>
    <summary><b>h1,h2,h3,h4,h5</b> (titulos)</summary>
    
    Para selecionar varias tags ao mesmo tempo basta 
    adicionar a virgula como no exemplo abaixo:

     h1, h2, h3, h4, h5 {}
    

| descrição | propriedade | valor |
|----------:|-------------|-------|
| cor da fonte     | color | #32325d |
| margem de baixo | margin-bottom | .5rem |
</details>

<details>
    <summary><b>h1</b> (titulo principal)</summary>
    
    o h1 deve ter um tamanho diferenciado
    de todos outros titulos

| descrição | propriedade | valor |
|----------:|-------------|-------|
| tamanho da fonte     | font-size | 2.5rem |
</details>

<details>
    <summary><b>.texto</b> (classe de texto)</summary>
    
    Para selecionar a classe <u>texto</u> basta usar o nome da classe com um ponto no começo exemplo a baixo:

     .texto {
        # escreva as propriedades aqui dentro das chaves
     }

| descrição | propriedade | valor |
|----------:|-------------|-------|
| tamanho da fonte     | font-size | 1.25rem |
| peso da fonte     | font-weight | 300 |
| altura da linha     | line-height | 1.7 |
| margem de cima     | margin-top | 1.5rem |
</details>

<details>
    <summary><b>.texto-branco</b> (classe de texto)</summary>

| descrição | propriedade | valor |
|----------:|-------------|-------|
| cor do texto     | color | #fff |
</details>

<details>
    <summary><b>.texto-azul</b> (classe de texto)</summary>

| descrição | propriedade | valor |
|----------:|-------------|-------|
| cor do texto     | color | #5e72e4  |
</details>

<details>
    <summary><b>.titulo</b> (classe titulo)</summary>

| descrição | propriedade | valor |
|----------:|-------------|-------|
| tamanho da fonte     | font-size | 2.1875rem |
| peso da fonte     | font-weight | 600 |
| altura da linha     | line-height | 1.5 |
</details>

<details>
    <summary><b>.descrição</b> (component de texto descritivo)</summary>

component de texto descritivo com letras menores

| descrição | propriedade | valor |
|----------:|-------------|-------|
| tamanho da fonte     | font-size |.875rem |
</details>

<details>
    <summary><b>.texto-padrao</b> </summary>

| descrição | propriedade | valor |
|----------:|-------------|-------|
| cor do texto    | color |#172b4d |
</details>

<details>
    <summary><b>.btn</b> </summary>

a classe <u>btn</u> tem propriedades que são comuns a todos os botões


| descrição | propriedade | valor |
|----------:|-------------|-------|
| posição do componente    | position | relative |
| transformação de texto    | text-transformation | uppercase |
| espaço das letras    | letter-spacing | .025rem |
| tamanho da fonte    | font-size | .875rem |
| peso da fonte     | font-weight | 600 |
| alinhamento do texto     | text-align | center |
| altura da linha     | line-height | 1.5 |
| espaço interno    | padding | .625rem 1.25rem |
| arredondamento da borda    | border-radius | .25rem |
| alinhamento vertical    | vertical-align | middle |
</details>

<details>
    <summary><b>.btn-block</b> </summary>

a classe <u>btn-block</u> faz com que os botões sejam apresentados
em bloco e que preencham toda a largura do elemento pai


| descrição | propriedade | valor |
|----------:|-------------|-------|
| modo de apresentação    | display | block |
| largura   | width | 100% |
</details>

<details>
    <summary><b>.btn-aviso</b> </summary>

classe que representa o botão chamativo


| descrição | propriedade | valor |
|----------:|-------------|-------|
| cor do texto    | color | #fff |
| cor de fundo   | background-color | #fb6340 |
| cor da borda   | border-color | #fb6340 |
| sombreamento    | box-shadow | 0 4px 6px rgba(50,50,93,.11),0 1px 3px rgba(0,0,0,8%) |
</details>

<details>
    <summary><b>.btn-info</b> </summary>

classe que representa o botão de informação de cor azul turquesa


| descrição | propriedade | valor |
|----------:|-------------|-------|
| cor do texto    | color | #fff |
| cor de fundo   | background-color | #11cdef |
| cor da borda   | border-color | #11cdef |
| sombreamento    | box-shadow | 0 4px 6px rgba(50,50,93,.11),0 1px 3px rgba(0,0,0,8%) |
</details>

<details>
    <summary><b>.btn-azul</b> </summary>

classe que representa o botão azul


| descrição | propriedade | valor |
|----------:|-------------|-------|
| cor do texto    | color | #fff |
| cor de fundo   | background-color | #5e72e4 |
| cor da borda   | border-color | #5e72e4 |
| sombreamento    | box-shadow | 0 4px 6px rgba(50,50,93,.11),0 1px 3px rgba(0,0,0,8%) |
</details>


<details>
    <summary><b>.btn-lg</b> </summary>

classe responsavel por deixar os botões largos


| descrição | propriedade | valor |
|----------:|-------------|-------|
| espaço interno    | padding | .875rem 1rem |
| tamanho da fonte   | font-size | .875rem |
| altura da linha  | line-height | 1.5 |
| arredondamento    | border-radius | .3rem |
</details>
