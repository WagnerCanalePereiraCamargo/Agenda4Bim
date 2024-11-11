# Documentação do Projeto: Agenda Telefônica

## Menu
1. [Resumo do Projeto](#resumo-do-projeto)
2. [Planejamento e Escopo](#planejamento-e-escopo)
   - [Requisitos Funcionais](#requisitos-funcionais)
   - [Requisitos Não Funcionais](#requisitos-não-funcionais)
3. [Tecnologias Utilizadas](#tecnologias-utilizadas)
4. [Modelo do Banco de Dados](#modelo-do-banco-de-dados)
   - [Tabela Contato](#tabela-contato)
   - [Tabela Grupo](#tabela-grupo)

---

## Resumo do Projeto
A Agenda Telefônica é um sistema desenvolvido para facilitar o gerenciamento de contatos telefônicos dos usuários, permitindo a criação, edição, exclusão e pesquisa de contatos. O projeto inclui uma aplicação mobile.

## Planejamento e Escopo

### Requisitos Funcionais
- **CRUD de Contato**: Adicionar, editar, excluir e visualizar detalhes dos contatos.
- **Interface Mobile**: Disponível exclusivamente para dispositivos móveis.

## Tecnologias Utilizadas
- **Frontend Mobile**: XML, Kotlin (Android)
- **Backend**: Node.js ou Spring Boot
- **Banco de Dados**: SQLite
- **Ferramentas de Desenvolvimento**: Android Studio, Git

## Modelo do Banco de Dados

### Tabela Contato
- `ID_Contato`: Chave primária, identifica cada contato de forma única.
- `Nome`: Nome do contato.
- `Telefone`: Número de telefone do contato.
- `ID_Grupo`: Chave estrangeira, vincula o contato.

### Tabela Grupo
- `ID_Grupo`: Chave primária, identifica cada grupo de forma única.
- `Nome`
- `Descricao`: Descrição opcional para melhor identificação.
