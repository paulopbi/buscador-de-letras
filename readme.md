<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/API-lyrics.ovh-purple?style=flat" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

## Conteúdo

- [Conteúdo](#conteúdo)
- [Introdução](#introdução)
- [Demonstração](#demonstração)
- [Aprendizados](#aprendizados)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Licença](#licença)

## Introdução

O **Buscador de Letras** é uma aplicação que permite ao usuário pesquisar músicas pelo **nome do artista** ou pelo **título da música**.  
A partir do termo digitado, o projeto consulta a API pública **lyrics.ovh** e exibe uma lista de resultados paginados.

Cada item da lista contém um botão **"Ver letra"**, que ao ser clicado mostra a letra completa da música selecionada.  
O projeto também inclui paginação, mensagens de erro e navegação intuitiva entre resultados.

## Demonstração

<p align="center">
  <img src="./assets/demo.png" alt="Demonstração do Projeto" />
</p>

> Interface da lista de tarefas.

## Aprendizados

- **Replace:**
  - Utiliza o método `replace()` para transformar quebras de linhas na tag `<br/>`.
- **Páginação:**
  - Usando dados de `prev` e `next` fornecidos pela API para buscar mais músicas.
- **Regex:**
  - Permite adicionar quebra de linhas na letra da música.
- **Consumo de API:**
  - Consumo da API _Lyrics OVH_.
- **Validação de formulário:**
  - Exibição de mensagens adequadas ao usuário.
- **Heroku Cors Anywhere:**
  - Permite burlar o bloqueio de CORS da API partir do proxy do heroku.

## Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**

## Licença

Este projeto está sob a licença **MIT**, você é livre para **usar, modificar e distribuir** este código, desde que mantenha os créditos originais, consulte o arquivo [LICENSE](./LICENSE) para mais informações.
