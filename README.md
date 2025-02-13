# VidFlow

**VidFlow** é um web app criado com o objetivo de aprender a consumir e tratar dados de uma API utilizando JavaScript. O projeto simula uma plataforma de compartilhamento de vídeos, semelhante ao YouTube, permitindo aos usuários buscar e filtrar vídeos de uma API externa e exibi-los na interface de forma interativa.

## Objetivo

O principal objetivo deste projeto foi aplicar os conhecimentos adquiridos no curso ["JavaScript: consumindo e tratando dados de uma API"  da Alura](https://cursos.alura.com.br/course/javascript-consumindo-tratando-dados-uma-api) onde aprendi a consumir e tratar os dados de uma API usando JavaScript, apliquei conceitos de manipulação do DOM, aprendi a fazer requisições HTTP (como ``fetch``), aprendi a fazer tratamento de respostas em formato JSON e implementações de filtros dinâmicos para melhorar a experiência do usuário.

## Funcionalidades

- **Exibição de vídeos:** O app consome uma API de vídeos e exibe os resultados na interface de maneira simples e intuitiva.
- **Pesquisa de vídeos:** É possível buscar vídeos por palavras-chave e filtrar o conteúdo desejado de acordo com o que é mais relevante para o usuário.
- **Interface limpa e objetiva:** O layout do VidFlow foi projetado para ser simples, focando na exibição de vídeos e interação com os filtros de pesquisa.

## Tecnologias Utilizadas

- **HTML5:** Estruturação da página e exibição do conteúdo.
- **CSS3:** Estilização da interface para uma melhor experiência de uso.
- **JavaScript:** Para manipulação do DOM, criação de filtros e consumo da API de vídeos.
- **API de Vídeos:** Consumida através de requisições HTTP para buscar e exibir os vídeos.

## Como rodar o projeto localmente

1. Clone este repositório:
   ```git
    git clone https://github.com/seu-usuario/vidflow.git
   ```
2. Navegue até o diretório do projeto:
   ```git
    cd vidflow
   ```
3. Abra o arquivo ``index.html`` no seu navegador.

## Como Funciona

1. O app realiza uma requisição à API de vídeos quando carregado ou quando o usuário faz uma busca.
2. Os dados recebidos são tratados e formatados para exibição na tela.
3. O conteúdo é mostrado em cards de vídeo, com informações como título, descrição e uma miniatura.
4. O usuário pode buscar vídeos por palavras-chave, e a interface será atualizada dinamicamente com os resultados filtrados.

## Contribuições

Este projeto está em desenvolvimento e você está convidado a contribuir com melhorias ou correções. Se você deseja contribuir, basta seguir os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para a sua melhoria ou correção:
   ```git
    git checkout -b minha-melhoria
   ```
3. Faça as alterações necessárias.
4. Faça commit das suas mudanças:
   ```git
    git commit -m "Descrição das mudanças"
   ```
5. Envie para o seu repositório:
   ```git
    git push origin minha-melhoria
   ```
6. Abra um pull request.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE]() para mais detalhes.
