### Content:
- NGINX 1.19 container to handle HTTP requests
- PHP 8.1.1 container to host your Symfony application
- MySQL 8.0 container to store databases

### Installation:
- Run `make build` to create all containers
- Run `make start` to initiate all the containers
- Enter the PHP container with `make ssh-be`
- Install your favourite Symfony version with `composer create-project symfony/skeleton:"6.1.*" my_project_directory`
- Move the content to the root folder with `mv project/* . && mv project/.env .`. This is necessary since Composer won't install the project if the folder already contains data.
- Copy the content from `project/.gitignore` and paste it in the root's folder `.gitignore`
- Remove `project` folder (not needed anymore)
- Navigate to `localhost:1000` so you can see the Symfony welcome page :)

### Alternatively may install:
- Run `make build` to create all the containers
- Run `make start` to initiate all the containers
- Enter the PHP container with `make ssh-be`
- Check the requirements with `symfony check:requirements`
- Install your favourite Symfony version with `symfony new my_project_directory --version="6.1.*"`
  - the version options are: ('lts', 'stable', 'next' or 'previous'
  - the project skeleton options are: ('--demo', '--full', '--webapp' or nothing by the minimum installation)
- Move the content to the root folder with `mv project/* . && mv project/.env .`. This is necessary since Composer won't install the project if the folder already contains data.
- Copy the content from `project/.gitignore` and paste it in the root's folder `.gitignore`
- Remove `project` folder (not needed anymore)
- Navigate to `localhost:1000` so you can see the Symfony welcome page :)

Happy coding!

### For testing
- Insert phpunit testing with composer 'composer require --dev phpunit/phpunit symfony/test-pack'
- Run `sf d:m:m -n --env=test` to apply migrations on test enviroment

composer dump-autoload --- when not found files after rename it

Olá, Luís.

Obrigado por se interessar em fazer parte da nossa equipe. O processo seletivo da vaga envolve três etapas:

1) Avaliação da Competência Técnica
2) Entrevista Técnica via Google Meet
3) Entrevista Financeira via Google Meet

Estou te enviando abaixo as informações referente à Avaliação da Competência Técnica.

AVALIAÇÃO DA COMPETÊNCIA TÉCNICA

1. Entrega Obrigatória

Utilizando a linguagem PHP, a partir do banco de dados fornecido, liste em uma tabela HTML apenas as mulheres com idade superior a 20 anos.

- Nesta lista deverá conter o nome, sexo, CPF, data de nascimento, e-mail, celular e profissão.

- É permitido a utilização de frameworks para estilização da lista.

2. Entrega Desejável

Crie as ações de incluir novos registros, editar e excluir registros listados na tabela HTML.

Prazo Limite para Entrega:
12/01 (quinta-feira) às 10:00

Banco de Dados

Host: 107.180.57.185
DB: dz_dev_test
Usuário: dz_dev
Senha: p?%3DY?#*LBW

Estamos à disposição.

Obrigado.
