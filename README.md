# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome:Arthur Nunes Linhares
- Matricula:856984
- Proposta de projeto escolhida:fãpage para uma banda
- Breve descrição sobre seu projeto:fãpage para a banda deftones com a pagina inicial ja sendo um carrosel com imagem do album e uma breve discrição sobre ele além de cada slide tocar uma musica e mudar as cores no fundo representando a de cada album

## Print da Home-Page

<img width="1919" height="1064" alt="main" src="https://github.com/user-attachments/assets/594fa235-5ec4-4f96-b9ff-39e54ee4b8f6" />


## Print da página de detalhes do item

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8d5350ef-1765-4510-beb4-44d643ba05fe" />


## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const dados = [
  {
    "id": 1,
    "titulo": "Diamond Eyes",
    "descricao": "O álbum “Diamond Eyes” do Deftones, lançado em 2010 equilibra a agressividade característica do metal alternativo com passagens atmosféricas e melódicas, criando uma sensação de contraste entre intensidade e delicadeza.'.",
    "autor": "Deftones",
    "data": "2010-05-04",
    "imagem": "img/diamond-eyes.jpg",
    "audio": "audio/diamond-eyes.mp3"
  },
  {
    "id": 2,
    "titulo": "White Pony",
    "descricao": "Lançado em 2000, 'O álbum “White Pony”, lançado em 2000, é amplamente considerado a obra-prima do Deftones. Nele, a banda expandiu seu som além do nu metal tradicional, explorando paisagens sonoras mais experimentais, atmosféricas e sensuais,'.git push -u origin main
",
    "autor": "Deftones",
    "data": "2000-06-20",
    "imagem": "img/white-pony.jpg",
    "audio": "audio/white-pony.mp3"
  }
];
```
