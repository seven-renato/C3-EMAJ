#Projeto EMAJ
O projeto EMAJ surgiu com o objetivo de desenvolver um sistema para auxiliar o Escritório Modelo de Assessoria Jurídica (EMAJ) da Universidade Federal do Rio Grande. Nosso grupo utilizou, Express e React para o desenvolvimento do projeto, utilizando um Banco de dados PostgreSQL para a realização do dinamismo da aplicação.

O sistema foi criado visando facilitar o gerenciamento de processos jurídicos, proporcionando uma melhor organização e acompanhamento das atividades realizadas pelo EMAJ. A escolha dessas tecnologias foi feita com base na eficiência e na compatibilidade com as necessidades do escritório.

#Frameworks e Bibliotecas utilizados
## Front-End
 - Redux: Utilizado para gerenciar o estado da aplicação de forma centralizada, facilitando a comunicação entre os componentes, e principalmente a validação de usuário logado.
 - Axios: Biblioteca utilizada para fazer requisições HTTP em nossa API criada com NodeJs, permitindo a comunicação de forma eficiente.
 - Tailwind CSS: Exaustivamente utilizado como framework de CSS utilitário que facilitou a estilização dos componentes de forma rápida e consistente.
 - React Hook Form: Usado para gerenciar formulários de forma eficiente no projeto, facilitando a validação e o controle dos dados inseridos, dados os extensos requisitos do sistema.
 - Zod: Junto ao React Hook Form auxiliou na validação de esquema de dados, garantindo a integridade e consistência dos dados manipulados na aplicação.


# Características importantes
## Hierarquia de tipos de Classes
 - Todos os usuários eram definidos no momento de sua criação em um nivel de Hierarquia dividido em formatos nos padrões Aluno, Professor, Admnistrador, etc. 
 - Com base em seu nível era possível ou não realizar ações. Como por exemplo Admnistradores podiam criar contas de todos os tipos, desativar e/ou excluir contas e atribuir demandas. Já Alunos apenas podiam ver alguns processos em andamento e não eram permitidos a excluir nem desativar usuários.

## Imagens salvas em diferentes formas de Armazenamento
