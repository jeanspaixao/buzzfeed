# ProjectBuzzfeed

Esse projeto é parte do Bootcamp Cloud Fullstack Warburg Pincus da DIO.

Ele tem como objetivo conseguir criar um clone do site buzzfeed por meio de componentes.

Para começar criei um novo projeto do Angular, por meio do comando 'ng new projeto-buzzfeed'.

Depois excluí todos os arquivos de teste (.spec).

Na sequência foi executado o comando 'ng c components/quiz' para gerar o componente principal do site. Em seguida foi executado 'ng c components/home' para a gestão da página inicial. Assim ficou determinada a estrutura base do projeto.


Em seguida foi realizada a estilização do projeto, com as principais frases em HTML e com configurações de fontes, cores e espaçamentos em CSS.

Na sequência foi desenvolvida a classe QuizComponent, com as suas regras de negócio.

Depois foi criado o botão com o recurso *ngFor para varrer todas as perguntas e o texto de resultado final com *ngIf para aparecer apenas quando tudo estivesse resolvido.

Nesse desafio consegui aprender muito sobre Angular, um pouco sobre HTML, Javascript e CSS. Usando 'ng serve' consegui testar a implementação pelo endereço `http://localhost:4200/`.

Abaixo observações geradas pelo próprio Angular:

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
