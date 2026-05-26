# 🎓 Aluno Online API

API backend desenvolvida em Java com Spring Boot para gerenciamento acadêmico de alunos, matrículas e disciplinas. O projeto simula o funcionamento de um sistema acadêmico real, aplicando conceitos modernos de desenvolvimento backend, arquitetura em camadas e construção de APIs RESTful.

A aplicação foi estruturada visando organização, escalabilidade e manutenção, seguindo padrões utilizados no mercado para desenvolvimento de sistemas corporativos.

O sistema permite o gerenciamento completo das entidades acadêmicas, incluindo controle de alunos, matrículas e operações relacionadas ao ambiente universitário.

# 🧰 Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- PostgreSQL 


# ⭐ Diferenciais do Projeto

- Arquitetura backend profissional
- API RESTful organizada em camadas
- Estrutura semelhante a projetos corporativos
- Separação clara de responsabilidades
- Código escalável e de fácil manutenção
- Utilização de ORM com JPA/Hibernate
- Tratamento de entidades e relacionamentos
- Projeto preparado para futuras integrações

# ⚙️ Funcionalidades

## 👨‍🎓 Gestão de Alunos

- Cadastro de alunos
- Atualização de dados
- Busca por ID
- Listagem completa
- Remoção de alunos

## 📚 Gestão Acadêmica

- Controle de matrículas
- Gerenciamento de disciplinas
- Relacionamento entre entidades
- Operações acadêmicas

## 🔐 Sistema Backend

- Validação de dados
- Tratamento de exceções
- Respostas HTTP padronizadas
- Organização em arquitetura REST

# 🧱 Arquitetura do Projeto

O projeto segue arquitetura em camadas, padrão amplamente utilizado em aplicações Spring Boot.

Fluxo da aplicação:

Cliente / Frontend  
↓  
Controller (Endpoints REST)  
↓  
Service (Regras de negócio)  
↓  
Repository (Persistência de dados)  
↓  
Banco de Dados

Estrutura arquitetural:

Controller → Responsável pelas requisições HTTP  
Service → Regras de negócio e validações  
Repository → Comunicação com banco de dados  
Entity → Representação das tabelas do sistema  
DTO → Transferência de dados entre camadas

# 📁 Estrutura de Pastas

src  
└── main  
└── java  
└── br  
└── com  
└── alunoonline  
└── api  
├── controller  
├── service  
├── repository  
├── dto  
├── model  
├── entity  
├── config  
└── exceptions

# 🔄 Fluxo da Aplicação

1. O cliente envia uma requisição HTTP para a API
2. O Controller recebe a requisição
3. Os dados são validados
4. O Service aplica as regras de negócio
5. O Repository realiza operações no banco de dados
6. O sistema retorna uma resposta JSON padronizada

Exemplo de fluxo:

Cadastro de aluno → Validação → Persistência → Resposta HTTP

# 💾 Persistência de Dados

A aplicação utiliza banco de dados relacional integrado via JPA/Hibernate.

Recursos implementados:

- Persistência automática de entidades
- Relacionamentos entre tabelas
- Operações CRUD completas
- Mapeamento objeto-relacional (ORM)
- Consultas via Spring Data JPA

Estrutura preparada para:

- PostgreSQL
- MySQL
- H2 Database
- Oracle Database

# 🔌 Integrações

- API RESTful
- Integração com banco de dados relacional
- Compatível com frontend web/mobile
- Integração com Postman para testes
- Estrutura preparada para autenticação JWT

# 🚀 Como Executar o Projeto

1. Clonar o repositório do GitHub

2. Abrir o projeto em uma IDE Java

3. Configurar o banco de dados no arquivo de propriedades

4. Instalar as dependências Maven

5. Executar a aplicação Spring Boot

6. Acessar os endpoints via Postman ou navegador

# 🧪 Testes / Uso

Fluxo de testes recomendado:

- Cadastro de aluno
- Listagem de registros
- Atualização de dados
- Exclusão de registros
- Teste de relacionamentos acadêmicos

Métodos HTTP utilizados:

- GET
- POST
- PUT
- DELETE

Ferramentas recomendadas:

- Postman
- Insomnia

# 📚 Conceitos Aplicados

- Programação Orientada a Objetos
- API RESTful
- Spring Boot
- Arquitetura em camadas
- ORM com Hibernate
- Spring Data JPA
- CRUD completo
- Relacionamento entre entidades
- Injeção de dependência
- Validação de dados
- Estruturação de aplicações backend
- Persistência de dados
- Boas práticas de desenvolvimento

# 🎯 Objetivos do Projeto

- Simular um sistema acadêmico real
- Praticar desenvolvimento backend com Spring Boot
- Consolidar conceitos de APIs REST
- Trabalhar com persistência de dados
- Desenvolver organização arquitetural
- Criar uma base sólida para aplicações corporativas

# 👨‍💻 Autor

Desenvolvido por Bruno Araújo

Projeto desenvolvido com foco em aprendizado avançado de backend Java, arquitetura REST e desenvolvimento de aplicações utilizando Spring Boot.