# Get a Pet ✨

---

## 🚀 Sobre o Projeto

O "Get a Pet" é uma plataforma dedicada a conectar pessoas que desejam adotar animais de estimação com tutores ou ONGs que estão disponibilizando animais para adoção. O objetivo principal é facilitar o processo de adoção, tornando mais fácil para os usuários encontrarem seu novo companheiro e para os doadores encontrarem lares amorosos para os pets.

---

## 💻 Tecnologias Utilizadas

Este projeto é uma aplicação Full-Stack, desenvolvida com as seguintes tecnologias:

**Frontend:**
* `ReactJS` (para a interface do usuário)
* `HTML5`, `CSS3`, `JavaScript`
* `Axios` (para requisições HTTP)
* `React Router DOM` (para navegação)

**Backend:**
* `Node.js` (ambiente de execução)
* `Express` (framework web para Node.js)
* `MongoDB` (Banco de Dados NoSQL)
* `Mongoose` (ODM para MongoDB, para modelagem de dados)
* `Bcrypt` (para criptografia de senhas)
* `JSON Web Token (JWT)` (para autenticação de usuário)
* `Multer` (para upload de arquivos, como fotos de pets)
* `Cookie-parser`

---

## 🛠️ Instalação

Siga os passos abaixo para ter uma cópia local do projeto rodando em sua máquina.

### Pré-requisitos

Certifique-se de ter os seguintes softwares instalados:
* `Node.js` (versão LTS recomendada)
* `npm` ou `yarn` (gerenciador de pacotes)
* `MongoDB` (servidor de banco de dados rodando localmente ou acesso a um serviço de nuvem como MongoDB Atlas)

### Passos

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/BeatrizCosta01/Get-a-Pet.git](https://github.com/BeatrizCosta01/Get-a-Pet.git)
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd Get-a-Pet
    ```
3.  **Configuração do Backend:**
    * Navegue para a pasta `backend`:
        ```bash
        cd backend
        ```
    * Instale as dependências:
        ```bash
        npm install
        # ou
        yarn install
        ```
    * Crie um arquivo `.env` na raiz do diretório `backend` e adicione as seguintes variáveis de ambiente (substitua pelos seus valores):
        ```
        DB_URI=mongodb://localhost:27017/getapet (ou a URI do seu MongoDB Atlas)
        JWT_SECRET=sua_chave_secreta_jwt
        ```
    * Execute o servidor backend em modo de desenvolvimento:
        ```bash
        npm run dev
        # ou
        yarn dev
        ```
        O servidor iniciará na porta `5000` (ou outra porta configurada) - acesse `http://localhost:5000`.

4.  **Configuração do Frontend:**
    * Abra um novo terminal e navegue de volta para a raiz do projeto e depois para a pasta `frontend`:
        ```bash
        cd ..
        cd frontend
        ```
    * Instale as dependências:
        ```bash
        npm install
        # ou
        yarn install
        ```
    * Execute a aplicação frontend:
        ```bash
        npm start
        # ou
        yarn start
        ```
        A aplicação será aberta em seu navegador, geralmente em `http://localhost:3000`.

---

## 💡 Como Usar

* **Visualizar Pets:** Na página inicial, os usuários podem navegar por uma lista de pets disponíveis para adoção.
* **Criar Conta:** Crie uma conta de usuário para interagir com a plataforma, como marcar encontros ou adicionar pets.
* **Adicionar Pets:** Usuários e ONGs podem cadastrar novos pets para adoção, incluindo informações e fotos.
* **Marcar Encontros:** Após criar uma conta, é possível entrar em contato com o tutor do pet para agendar um encontro.

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você tiver alguma ideia, encontrou um bug ou quer adicionar uma nova funcionalidade, por favor:

1.  Faça um `fork` deste repositório.
2.  Crie uma `branch` para sua feature (`git checkout -b feature/minha-nova-feature`).
3.  Faça suas alterações e `commit` (`git commit -m 'feat: Adiciona minha nova funcionalidade'`).
4.  Envie para a `branch` original (`git push origin feature/minha-nova-feature`).
5.  Abra um `Pull Request` descrevendo suas alterações.

---

## 📞 Contato

* Beatriz Costa - https://www.linkedin.com/in/ana-beatriz-queiroz-costa-816147341?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
* Link do Projeto: https://github.com/BeatrizCosta01/Get-a-Pet

---
