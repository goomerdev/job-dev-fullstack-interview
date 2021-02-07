![alt text](https://github.com/goomerdev/job-dev-backend-interview/raw/master/media/logo-azul.png "Goomer")

# Challenge - Developer Fullstack

Você provavelmente já está participando do nosso processo seletivo, mas se você caiu aqui por acaso, leia esse documento até o final e se você se interessar, pode começar o processo à partir daqui =]

Não esperamos que todas as pessoas consigam realizar esse desafio por completo, já que é destinado a todos os níveis de carreira.

A avaliação será baseada na sua capacidade de escrever um código simples, de fácil manutenção, e pela quantidade de funcionalidades que você entregar.

Este desafio é composto por dois projetos:
 - Backend: Aqui você deve criar uma API RESTful para servir os dados para o frontend
 - Frontend: Aqui você deve criar uma interface capaz de se comunicar com o backend criado

**Entregáveis:** Crie um repositório pessoal para cada projeto, siga as instruções abaixo e responda e-mail recebido com os links dos repositórios. Caso você resolveu fazer o teste por conta própria pode enviar para selecao.tech@goomer.com.br.
## Backend

### Instruções

- **Nome do Projeto:** Goomer API
- **Objetivo do Projeto:** Criar uma API RESTful capaz de gerenciar os restaurantes e os produtos do seu cardápio.
- **Tecnologia:** Node.js com banco de dados relacional.

### Desafio

- A sua API deverá ser capaz de:
    - Listar todos os restaurantes
    - Cadastrar novos restaurantes
    - Listar os dados de um restaurante
    - Alterar os dados um restaurante
    - Excluir um restaurante
    - Listar todos os produtos de um restautante
    - Criar um produto de um restaurante
    - Alterar um produto de um restaurante
    - Excluir um produto de um restaurante

- O cadastro do restaurante precisa ter os seguintes campos:
    - Foto do restaurante
    - Nome do restaurante
    - Endereço do restaurante
    - Horários de funcionamento do restaurante (ex.: De Segunda à Sexta das 09h as 18h e de Sabado à Domingo das 11h as 20h).
    
- O cadastro de produtos do restaurante precisa ter os seguintes campos:
    - Nome do produto
    - Foto do produto
    - Descrição do produto
    - Preço do produto
    - Preço promocional do produto

- Você é livre para incluir novos campos se sentir necessidade.
- Não é necessário implementar a parte de upload de imagens, salve apenas as urls :)

#### Formato de horários
- Deve ser possível definir horários de funcionamento diferentes para cada dia da semana.
- Deve ser possível definir mais de um horário de funcionamento para o mesmo dia da semana.

## Frontend
### Instruções

- **Nome do Projeto:** Goomer Restaurantes
- **Objetivo do Projeto:** Criar uma aplicação Web responsiva que consulte nossa API e exiba uma lista de restaurantes e o cardápio de cada um deles.
- **Tecnologia:** A que você preferir, mas apenas para contextualizar, aqui na Goomer usamos React e Ractive.js.
- **User Interface:** Você deve [usar esse link](https://xd.adobe.com/spec/f6e71782-ebba-4573-6f7a-005a1a6d391f-80d6/) como referência de UI durante o desenvolvimento.

### Desafio

- Consulte a API que você criou para buscar as informações.
- Crie uma tela para exibir a lista de restaurantes:
    - O usuário deve ser capaz de buscar por estabelecimento.
    - A página deve atualizar o status de aberto/fechado do restaurante de acordo com o horário de funcionamento, sem ser necessário recarregar ou reabrir a página.
- Crie uma tela para exibir os produto do cardápio de cada um dos restaurantes:
    - O usuário deve ser capaz de buscar os produtos. 
    - Para os produtos com promoção ativa, deve ser exibido o valor original e o valor promocional.

### O que nós vamos avaliar

- Vamos avaliar a qualidade do código, legibilidade, fidelidade da interface e a quantidade de funcionalidades implementadas.
- Você é livre para tomar as decisões técnicas com as quais você se sente mais confortável. Apenas se prepare para explicar as razões que fundamentaram suas escolhas =]
- Inclua um arquivo *README* que possua:
  - desafios/problemas com os quais você se deparou durante a execução do projeto.
  - maneiras através das quais você pode melhorar a aplicação, seja em performance, estrutura ou padrões. 
  - todas as intruções necessárias para que qualquer pessoa consiga rodar sua aplicação sem maiores problemas.

### Dicas

- Documente seu projeto em arquivos markdown explicando a estrutura, processo de setup e requisitos.
- Tenha sempre uma mentalidade de usabilidade, escalabilidade e colaboração.
- A organização das branches e os commits no repositório falam muito sobre como você organiza seu trabalho.
- Os testes unitários são mais do que desejados.
- O design/estrutura do código da aplicação deve ser *production ready*.
- Tenha em mente os conceitos de *SOLID, KISS, YAGNI e DRY*.
- Use boas práticas de programação.

### FAQ

#### Posso utilizar frameworks/bibliotecas?

Você pode usar bibliotecas como Express, mas queremos que a solução de arquitetura seja sua, portanto não use frameworks que impõem uma arquitetura específica.

#### Quanto tempo eu tenho?

Quanto mais tempo você demorar, mais críticos seremos na sua avaliação =]

#### Qual banco de Dados devo usar?

Escolha entre MySQL e PostgreSQL. Você pode utilizar um ORM.

### Happy coding 

![alt text](https://github.com/goomerdev/job-dev-backend-interview/raw/master/media/may-the-force-be-with-you.jpg "Happy Coding!!!")
