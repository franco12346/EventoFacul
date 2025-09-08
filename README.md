# EventoFacul

# Sistema de Eventos (Console) - Java

Este projeto é um sistema de cadastro e notificação de eventos, desenvolvido em **Java**, seguindo o paradigma **orientado a objetos**.

## Funcionalidades

- Cadastro de usuário (username, nome completo, email, cidade, idade)
- Cadastro de eventos (nome, endereço, categoria, horário, descrição, cidade)
- Participação e cancelamento de participação em eventos
- Listagem de eventos:
  - Todos
  - Por cidade
  - Ocorrendo agora
  - Eventos passados
- Ordenação de eventos por horário
- Persistência de eventos em `events.data`

## Estrutura de pastas

- `src/main/java/model` → classes de modelo (`User`, `Event`, `EventCategory`)
- `src/main/java/service` → classe de gerenciamento de eventos (`EventManager`)
- `src/main/java/app` → classe principal (`ConsoleApp`)
- `src/resources` → arquivo de dados (`events.data`)

## Como executar

1. Clone o repositório:

```bash
git clone <URL-do-repo>
cd EventSystem
