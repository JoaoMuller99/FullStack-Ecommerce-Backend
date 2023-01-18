# WELCOME || BEM-VINDO

**Para ler esse README em português clique [aqui](https://github.com/JoaoMuller99/FullStack-Ecommerce-Backend/blob/main/README_PT.md)!**

## This project was built with

- [Strapi](https://strapi.io/)
- [Graphql](https://graphql.org/)
- [Cloudinary](https://cloudinary.com/)

**To access the Front-end repository click [here](https://github.com/JoaoMuller99/FullStack-Ecommerce-Frontend)!**

## Getting Started

- First, install the packages by running:

  ```bash
  npm install
  # or
  yarn install
  ```

- After that, **IN ANOTHER DIRECTORY** run the following:

  ```bash
  npx create-strapi-app@latest my-project
  ```

- In the _my-project_ folder copy the **.env** file and paste it in the root directory of this cloned repository (_this process is only made to get the keys needed to run the strapi project_).

- You can now delete the _my-project_ folder.

- In the **.env** file, add the following (see [more](#cloudinary) about how to set up Cloudinary):

  ```bash
  CLOUDINARY_NAME=YOUR CLOUDINARY NAME
  CLOUDINARY_KEY=YOUR CLOUDINARY KEY
  CLOUDINARY_SECRET=YOUR CLOUDINARY SECRET
  ```

- Start the development server by running:

  ```bash
  npm run develop
  # or
  yarn develop
  ```

- Go to [http://localhost:1337/admin/auth/register-admin](http://localhost:1337/admin/auth/register-admin) and create an account.

- After that, go to _Settings_, under _USERS & PERMISSIONS PLUGIN_ go to _Roles > Public > Product_ and check the options _find_ and _findOne_ then click _Save_.

- Now go to _Content Manager_ and click on _Product_. This is the page where you can create the products to your E-commerce. _Be aware that the currency is set to BRL in the Front-end repository_.

- You can create any product you want. To help you I added [images](https://github.com/JoaoMuller99/FullStack-Ecommerce-Backend/tree/main/public/products_imgs) and [descriptions](https://github.com/JoaoMuller99/FullStack-Ecommerce-Backend/tree/main/public/products_descriptions) to a few products.

<h2 id="cloudinary">Setting Up Cloudinary</h2>

1. Create an account at [https://cloudinary.com/](https://cloudinary.com/).
2. Go to _Dashboard_.
3. Copy and paste at your **.env** file the needed keys.

## Finally

This project was created for educational purposes only, so feel free to make some tweaks if you want to. Thank you so much for trying it out!
