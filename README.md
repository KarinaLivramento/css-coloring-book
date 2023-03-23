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