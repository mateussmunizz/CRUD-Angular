**👨‍💻 CRUD com AngularJS e JSON Server**


📄 Descrição do Projeto

Este repositório apresenta o desenvolvimento de um Sistema Completo de Cadastro de Usuário (CRUD). O projeto tem como principal objetivo demonstrar a aplicação prática de técnicas modernas de desenvolvimento, utilizando um back-end simulado para persistência de dados e um robusto framework JavaScript para o front-end.

⚙️ Funcionalidades
O sistema implementa todas as operações essenciais de um CRUD:

Create (Inserir): Cadastro de novos usuários.

Read (Consultar): Listagem e visualização dos usuários cadastrados.

Update (Alterar): Edição das informações de um usuário existente.

Delete (Excluir): Remoção de usuários do sistema.

🛠️ Tecnologias Utilizadas
O desenvolvimento foi baseado nas seguintes tecnologias:

Back-end Simulado: Utilização do módulo NodeJS JSON Server para simular uma API RESTful e gerenciar a persistência dos dados de usuário em formato JSON.

Front-end: O framework AngularJS foi essencial para o desenvolvimento rápido da aplicação e criação de uma interface dinâmica.

Comunicação de Dados: Axios foi implementado para gerenciar todas as operações assíncronas de processamento de dados (Inserir, Consultar, Alterar e Excluir), garantindo a comunicação eficiente com o JSON Server.

Design e Usabilidade: O uso do Bootstrap proporcionou um design responsivo e acessível, enquanto o Font-Awesome foi utilizado para aprimorar a interface com ícones intuitivos.

✨ Destaques do Projeto
O uso do AngularJS permitiu o desenvolvimento rápido e a criação de uma interface responsiva. A implementação do Axios simplificou o gerenciamento das requisições HTTP, tornando a comunicação de dados limpa e eficaz para todas as operações do CRUD.

🚀 Como Executar o Projeto
Siga os passos abaixo para clonar e rodar a aplicação em sua máquina local.

1. Pré-requisitos
Você precisa ter o Node.js instalado em sua máquina, pois ele é necessário para rodar o JSON Server.

2. Passos para Execução
Clone o Repositório:

Bash

git clone [(https://github.com/mateussmunizz/CRUD-Angular)]
Instale o JSON Server: Se você ainda não o tem, instale o JSON Server globalmente através do npm:

Bash

npm install -g json-server
Inicie o Back-end Simulado: Navegue até o diretório do projeto e execute o comando abaixo para iniciar o JSON Server. Ele irá ler o arquivo db.json e criar a API RESTful.

Bash

json-server --watch db.json
O servidor estará ativo em http://localhost:3000 (ou porta padrão).

Acesse a Aplicação Front-end: Com o servidor JSON rodando, basta abrir o arquivo index.html do projeto em seu navegador. Recomenda-se usar uma extensão de servidor local, como o Live Server, para evitar problemas de CORS e caminhos.

