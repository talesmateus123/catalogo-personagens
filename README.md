## Catálogo de Personagens
A turma 27.2024 do Técnico Desenvolvedor de Sistemas do Serviço Nacional de Aprendizagem Comercial(SENAC-MS) desenvolveu um novo projeto utilizando Git Flow e ClickUp (para organizaçãõ e divisão de tarefas).
Um projeto simples de catálogo de personagens desenvolvido com HTML e CSS. O objetivo é exibir uma lista de personagens de forma organizada, com a possibilidade de adicionar detalhes sobre cada personagem, como nome, imagem e descrição.

## Funcionalidades
- Exibição de personagens: Lista de personagens com imagens e informações básicas (nome, descrição, etc.).

- Estilos personalizados: Utiliza CSS para criar um layout agradável e fácil de navegar.

## Tecnologias Utilizadas
- Frontend: HTML, CSS

> HTML: Para estruturação do conteúdo.

> CSS: Para estilização e layout.

## Instalação
Este projeto não possui backend, portanto, basta abrir os arquivos HTML diretamente no seu navegador. Siga os passos abaixo para executar o projeto:

## Passos para rodar o projeto
> Clone o repositório:

bash
Copiar
git clone https://github.com/talesmateus123/catalogo-personagens.git
Acesse a pasta do projeto:

bash
Copiar
cd catalogo-de-personagens
Abra o arquivo index.html em seu navegador para visualizar o catálogo de personagens.

> Não é necessário servidor para rodar o projeto, basta abrir o arquivo diretamente no navegador.

## Estrutura do Projeto
A estrutura do projeto é simples e organizada da seguinte maneira:

bash
Copiar
catalogo-de-personagens/
│
├── index.html            # Arquivo principal com a estrutura HTML
|
├── style                 # Pasta de estilos CSS
├── img/                  # Pasta com imagens dos personagens
│   ├── personagem1.jpg
│   ├── personagem2.jpg
│   └── ...
└── README.md             # Este arquivo de documentação


## Como Contribuir
Contribuições são bem-vindas! Para contribuir com este projeto:

> Faça um fork deste repositório.

> Crie uma branch para a sua modificação (git checkout -b minha-branch).

> Faça o commit das suas mudanças (git commit -am 'Adicionando novo personagem').

> Envie para o repositório remoto (git push origin minha-modificacao).

> Abra um pull request.

## Exemplo de Uso
- Aqui está um exemplo simples de como o catálogo de personagens pode ser exibido:

html
Copiar
<div class="personagem">
  <img src="img/personagem1.jpg" alt="Personagem 1">
  <h2>Nome do Personagem 1</h2>
  <p>Descrição do personagem 1.</p>
</div>


> Esse bloco pode ser repetido para cada personagem que você deseja adicionar ao catálogo.