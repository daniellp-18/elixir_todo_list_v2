# Elixir Todo List – Phoenix - LiveView

# Informações do Projeto

* Aluno: Daniel Lindoso Penha

* Professor: Sergio Souza Costa
  
* Curso: Engenharia da Computação

* Instituição: Universidade Federal do Maranhão – UFMA
  
* Disciplina: Topicos em Emgenharia da Computação II - Introdução a Programaçao Funcional

# Tutorial Base

Como Criar um App Todo List com Elixir e LiveView do Zero (Notion):

https://profsergiocosta.notion.site/Como-Criar-um-App-Todo-List-com-Elixir-e-LiveView-do-Zero-2a8cce97509380eba53fc82bbeb08435.

# Descrição do Projeto

Este projeto consiste no desenvolvimento de uma Lista de Tarefas (Todo List) utilizando a linguagem Elixir com o Phoenix Framework e Phoenix LiveView, permitindo uma interface reativa e dinâmica sem recarregamento de página.

A aplicação utiliza Ecto para persistência de dados, com SQLite como banco de dados, além de TailwindCSS e daisyUI para estilização moderna e responsiva.

O projeto foi desenvolvido com fins acadêmicos, seguindo rigorosamente o tutorial proposto em aula, respeitando boas práticas de organização, versionamento e estrutura de projetos Elixir/Phoenix.

# Funcionalidades:

* Adicionar novas tarefas

* Marcar tarefas como concluídas

* Remover tarefas

* Interface dinâmica sem reload de página (LiveView)

* Persistência de dados com banco SQLite

* Interface estilizada com TailwindCSS e daisyUI

# Tecnologias Utilizadas

* Elixir 1.15+ (utilizado: 1.17.2)

* Erlang/OTP (utilizado: 26.2.2)

* Phoenix Framework 1.8+

* Phoenix LiveView

* Ecto

* SQLite

* TailwindCSS

* daisyUI

* Node.js (para assets)

* Git (versionamento)

# Como Executar o Projeto

* Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

Elixir 1.15 ou superior

Erlang/OTP compatível com a versão do Elixir

Node.js (necessário para TailwindCSS e esbuild)

Git (opcional, para clonar o repositório)

* Passo a Passo:
  
git clone <URL_DO_REPOSITORIO>

cd elixir_todo_list

* Instale as dependências:

mix deps.get

* Prepare o banco de dados:

mix ecto.create

mix ecto.migrate

* Instale dependências de assets:

mix assets.setup

mix assets.build

* Inicie o servidor Phoenix:

mix phx.server

* Abra o navegador e acesse:
  
http://localhost:4000/

Para mudar o tema ou cores do projeto, altere as classes do TailwindCSS ou configure o daisyUI em tailwind.config.js.

# 📂 Estrutura do Projeto

elixir_todo_list/

├─ lib/elixir_todo_list_web/live/todo_live.ex  # LiveView da lista de tarefas

├─ lib/elixir_todo_list/tasks/task.ex         # Schema Task

├─ priv/repo/migrations/                       # Migrações Ecto

├─ assets/css/app.css                           # CSS (Tailwind)

├─ config/config.exs                            # Configuração geral

├─ mix.exs                                      # Configuração do projeto e dependências

└─ README.md                                    # Documentação

# Saiba mais:

* Official website: https://www.phoenixframework.org/
* Guides: https://hexdocs.pm/phoenix/overview.html
* Docs: https://hexdocs.pm/phoenix
* Forum: https://elixirforum.com/c/phoenix-forum
* Source: https://github.com/phoenixframework/phoenix
