# Curso-Cypress-end2end
> Este projeto consiste no curso 'Testes end-to-end com Cypress', que tem como objetivo a automação da aplicação Scratch. A aplicação Scratch é uma plataforma educacional interativa e visual, amplamente utilizada para ensinar conceitos de programação a crianças e iniciantes.
>
> Esta documentação fornecerá uma descrição detalhada do projeto de automação, incluindo uma visão geral da aplicação Scratch, os objetivos do curso, os recursos utilizados e os passos necessários para configurar o ambiente de automação. Também serão abordados os desafios enfrentados durante o processo de automação e as soluções adotadas para superá-los.
>
> Através desta documentação, os leitores terão uma compreensão abrangente do projeto de automação e poderão acompanhar o desenvolvimento passo a passo, além de obter insights valiosos sobre as práticas recomendadas de automação de testes end-to-end com Cypress.
### Funcionalidades da aplicação - Scratch App
> Este projeto consiste no curso 'Testes end-to-end com Cypress', que tem como objetivo a automação da aplicação Scratch. A aplicação Scratch é uma plataforma educacional interativa e visual, amplamente utilizada para ensinar conceitos de programação a crianças e iniciantes.
>
> Esta documentação fornecerá uma descrição detalhada do projeto de automação, incluindo uma visão geral da aplicação Scratch, os objetivos do curso, os recursos utilizados e os passos necessários para configurar o ambiente de automação. Também serão abordados os desafios enfrentados durante o processo de automação e as soluções adotadas para superá-los.
>
> Através desta documentação, os leitores terão uma compreensão abrangente do projeto de automação e poderão acompanhar o desenvolvimento passo a passo, além de obter insights valiosos sobre as práticas recomendadas de automação de testes end-to-end com Cypress.
### Funcionalidades da aplicação - Scratch App
> A principal funcionalidade da aplicação Scratch é um CRUD (Create, Read, Update, Delete) de anotações. Ou seja, o(a) usuário(a) pode criar, ler, editar e deletar anotações.
>
> Para poder criar anotações, o(a) usuário(a) precisa estar autenticado. Ou seja, a aplicação conta com a funcionalidade de Login.
>
> Para poder se autenticar, o(a) usuário(a) precisa estar registrado(a) no sistema. Ou seja, a aplicação também conta com a funcionalidade de Sign up. Além disso, tal funcionalidade exige a leitura de um email de confirmação para que o registro do(a) novo(a) usuário(a) seja completo (um desafio que irei te ensinar a contornar).
> Visto que o(a) usuário(a) pode estar autenticado(a), a aplicação também conta com a funcionalidade de Logout.
>
> Por fim, quando autenticado(a), o(a) usuário(a) deve ser capaz de preencher e submeter com sucesso um formulário de cartão de crédito, simulando uma compra, trazendo uma situação do mundo real.
### Desafio do Curso
> Durante o curso de Testes end-to-end com Cypress da Escola TAT, o desafio é testar todas as funcionalidades da aplicação Scratch, além de configurar um pipeline de integração contínua com múltiplas fases, paralelização e integração com o serviço do Cypress na nuvem.
### Setup
>
1. Comece criando um diretório
2. Via terminal de linha de comando, visite o diretório recém criado 
3. Execute o comando `git init`
4. Na raiz do projeto, crie um arquivo oculto chamado `.gitignore` com o seguinte conteúdo:
> .gitignore.DS_Store
> cypress.env.json
> cypress/screenshots/
> cypress/videos/
> node_modules/
5. Ainda na raiz do projeto, crie um arquivo chamado `README.md` 
6. Execute o comando npm `init -y`
7. Execute o comando `npm install cypress --save-dev`
8. Também na raiz do projeto, crie um arquivo chamado cypress.env.json e outro chamado cypress.env.example.json. Inicialize ambos como um objeto vazio ({})
9. Execute o comando `npx cypress open` para abrir o Cypress pela primeira vez


