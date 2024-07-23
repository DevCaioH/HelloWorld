---

## Exemplo de Página HTML

Este projeto é uma página HTML simples que serve como uma introdução ao desenvolvimento web utilizando HTML e CSS. A página inclui várias seções que fornecem informações sobre o autor, seus hobbies e como entrar em contato.

### Estrutura do Projeto

O projeto consiste em um arquivo HTML principal (`index.html`) e uma folha de estilo CSS (`style.css`). A estrutura da página é organizada em seções claras e de fácil navegação.

### Funcionalidades

- **Cabeçalho**: Inclui um título de boas-vindas e um divisor horizontal.
- **Seção "Sobre Mim"**: Fornece uma breve introdução sobre o autor, incluindo nome e descrição de sua profissão como desenvolvedor web iniciante.
- **Seção "Hobbies"**: Lista os hobbies do autor, apresentando-os em uma lista não ordenada.
- **Seção "Contato"**: Inclui um parágrafo com informações de contato e um link de e-mail clicável.
- **Rodapé**: Contém uma mensagem de copyright.

### Código HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Exemplo de Página HTML</title>
    <link rel="stylesheet" href="CSS/style.css" />
  </head>
  <body>
    <div class="container">
      <header>
        <h1 class="tituloHeader">Bem-vindo à Minha Página HTML</h1>
        <hr />
      </header>
      <main>
        <section id="about">
          <h2>
            Sobre Mim
            <hr />
          </h2>
          <p>
            Olá! Meu nome é <b class="negrito-estilizado">Caio Antonio</b> e sou
            um <b class="negrito-estilizado">desenvolvedor web iniciante</b>.
            Estou aprendendo HTML e CSS para criar websites incríveis.
          </p>
        </section>
        <section id="hobbies">
          <h2>
            Hobbies
            <hr />
          </h2>
          <p>
            Nos meus tempos livres, gosto de fazer várias atividades. Aqui estão
            algumas delas:
          </p>
          <ul>
            <li>Programar</li>
            <li>Ler livros</li>
            <li>Praticar esportes</li>
            <li>Viajar</li>
          </ul>
        </section>
        <section id="contato">
          <h2>
            Contato
            <hr />
          </h2>
          <p>
            Se você deseja entrar em contato comigo, por favor, envie um e-mail
            para
            <a href="mailto:caiocontatovagas@gmail.com"
              >caiocontatovagas@gmail.com</a
            >.
          </p>
        </section>
      </main>
      <footer>
        <p>&copy; 2024 Caio. Todos os direitos reservados.</p>
      </footer>
    </div>
  </body>
</html>
```

### Estilos CSS

Os estilos CSS estão definidos no arquivo `style.css` e são usados para estilizar os elementos da página, como títulos, parágrafos e listas.

### Como Executar

Para visualizar a página, basta abrir o arquivo `index.html` em qualquer navegador web.

---
