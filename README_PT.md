# BEM-VINDO || WELCOME

**To read this README in english click [here](https://github.com/JoaoMuller99/FullStack-Ecommerce-Backend/blob/main/README.md)!**

## Esse projeto foi construído com

- [Strapi](https://strapi.io/)
- [Graphql](https://graphql.org/)
- [Cloudinary](https://cloudinary.com/)

**Para acessar o repositório contendo o Front-end clique [aqui](https://github.com/JoaoMuller99/FullStack-Ecommerce-Frontend)!**

## Começando

- Primeiro, instale os pacotes rodando o comando:

  ```bash
  npm install
  # or
  yarn install
  ```

- Depois disso, **EM OUTRO DIRETÓRIO** rode o seguinte comando:

  ```bash
  npx create-strapi-app@latest my-project
  ```

- Na pasta _my-project_ copie o arquivo **.env** e cole ele no diretório principal desse repositório clonado (_esse processo só é feito para conseguirmos as chaves necessárias para rodar essa aplicação strapi_).

- Agora você pode deletar a pasta _my-project_.

- No arquivo **.env**, adicione o seguinte (veja [mais](#cloudinary) sobre como configurar o Cloudinary):

  ```bash
  CLOUDINARY_NAME=SEU CLOUDINARY NAME
  CLOUDINARY_KEY=SUA CLOUDINARY KEY
  CLOUDINARY_SECRET=SEU CLOUDINARY SECRET
  ```

- Inicie o servidor de desenvolvimento rodando o comando:

  ```bash
  npm run develop
  # or
  yarn develop
  ```

- Vá para [http://localhost:1337/admin/auth/register-admin](http://localhost:1337/admin/auth/register-admin) e crie uma conta.

- Depois disso, vá para _Settings_, em _USERS & PERMISSIONS PLUGIN_ vá para _Roles > Public > Product_ e marque as opções _find_ e _findOne_ depois clique em _Save_.

- Agora vá para _Content Manager_ e clique em _Product_. Essa é a página onde você poderá criar os produtos par ao seu E-commerce. _Fique atento que a moeda está configurada para BRL no repositório do Front-end_.

- Você pode criar qualquer produto que quiser. Para te ajudar eu adicionei [imagens](https://github.com/JoaoMuller99/FullStack-Ecommerce-Backend/tree/main/public/products_imgs) e [descrições](https://github.com/JoaoMuller99/FullStack-Ecommerce-Backend/tree/main/public/products_descriptions) para alguns produtos.

<h2 id="cloudinary">Configurando o Cloudinary</h2>

1. Cria uma conta em [https://cloudinary.com/](https://cloudinary.com/).
2. Vá para _Dashboard_.
3. Copie e cole, no seu arquivo **.env**, as chaves necessárias.

## Finalmente

Esse projeto foi criado apenas por propósitos educacionais, então sinta-se livre pra fazer qualquer alteração que achar necessário. Muito obrigado por testar esse projeto!
