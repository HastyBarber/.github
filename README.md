## Hasty Barber ✂️

**Um ambiente descontraído para barbeiros e desenvolvedores**

O Hasty Barber é um aplicativo web open-source que conecta barbeiros e clientes, oferecendo agendamento de serviços, gestão de clientes e um marketplace para produtos de beleza.

### Tecnologias Utilizadas
* **Frontend:** React com TypeScript
  * **Biblioteca:** React para criar interfaces de usuário interativas.
  * **Tipagem:** TypeScript para garantir a segurança e a manutenibilidade do código.
  * **Gerenciamento de estado:** Redux ou Context API para gerenciar o estado da aplicação.
  * **Styling:** Styled-Components ou Material-UI para estilizar os componentes.
* **Backend:** NestJS com TypeScript
  * **Framework:** NestJS para construir APIs RESTful escaláveis e eficientes.
  * **Tipagem:** TypeScript para garantir a segurança e a manutenibilidade do código.
  * **ORM:** TypeORM para interagir com o banco de dados.
  * **Autenticação:** Passport.js para implementar diferentes estratégias de autenticação.
* **Banco de dados:** MongoDB (ou PostgreSQL) para armazenar os dados do aplicativo.

### Arquitetura
[Inserir um diagrama de arquitetura aqui, se disponível]

### Como Contribuir
1. **Clone um dos repositórios, conforme desejado exemplo:** `https://github.com/HastyBarber/HastyBarber-API.git`
2. **Instale as dependências:**
   * `npm install` ou `yarn install`
3. **Crie um branch:** `git checkout -b feature/minha-feature`
4. **Faça as alterações:** Faça as suas alterações e commit.
5. **Envie um pull request:** Envie um pull request para o repositório principal.

### Guia de Contribuição Detalhado
* **Frontend:**
  * **Componentes:** Crie componentes reutilizáveis para construir a interface do usuário.
  * **Redux:** Utilize Redux para gerenciar o estado global da aplicação (opcional).
  * **Styling:** Utilize Styled-Components para estilizar os componentes.
* **Backend:**
  * **Módulos:** Organize o código em módulos separados por funcionalidades.
  * **Controladores:** Crie controladores para lidar com as requisições HTTP.
  * **Serviços:** Crie serviços para encapsular a lógica de negócios.
  * **Entidades:** Defina as entidades que representam os dados do banco de dados.

### Próximos Passos
* **Desenvolver o frontend:** Criar a interface do usuário para agendamento de serviços, perfil de usuário, etc.
* **Desenvolver o backend:** Implementar a lógica de negócios para gerenciar usuários, serviços, agendamentos, etc.
* **Implementar autenticação:** Utilizar Passport.js com JWT para proteger as rotas da API.
* **Implementar pagamentos:** Integrar com uma plataforma de pagamento para permitir que os clientes paguem pelos serviços.
* **Implementar notificações:** Enviar notificações por e-mail ou SMS para os usuários.

### Licença
Este projeto é licenciado sob a licença MIT.
