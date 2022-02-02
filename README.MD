## Descrição

Script que extrai uma lista contendo o nome e a URL da imagem dos 100 filmes com melhor rating do site [imdb](https://www.imdb.com/).

## Implementações, metodologias e tecnologias usadas

Script utilizando Node.JS.

- [x] Extrair o outerHTML do site que contem a lista e salvar em um objeto JS;
- [x] Utilizando o cheerio, a partir do HTML salvo no objeto feito no passo anterior, percorrer o html e salvar os elementos 'img' que são referente as imagens dos filmes;
- [x] Fazer o tratamento das tags img retornadas, separando somente as tags cujo src termina com '.jpg';
- [x] Fazer a substituição das dimensoes salvas no HTML, para o código que dispõe a imagem em seu tamanho original. *Nesse caso, substituindo o final da string da URL da imagem por um @.*;
- [x] Extrair as informações do título do filme através do atributo 'alt' encontrado nas mesmas tags 'img' extraídas anteriormente.
- [x] Gerar um arquivo JSON a partir dos dados coletados, a fim de organizá-los. Para gerar o arquivo JSON, utilizou-se da biblioteca *fs*, nativa do próprio NODE.JS

### Bibliotecas utilizadas:

- Cheerio
- File System - fs


<div align="center">

## Get in touch 👇🏽
[![Linkedin Badge](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/soaresmilton/)](https://www.linkedin.com/in/soaresmilton/)
[![Youtube Badge](https://img.shields.io/badge/youtube-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCMsbUh0LDOMQCTBdBXwkFiQ/)
[![Instagram Badge](https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white&link=https://www.instagram.com/soaresmiltinho/)](https://www.instagram.com/soaresmiltinho/)

</div>