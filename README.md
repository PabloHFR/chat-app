# Chat App

![imagem](https://i.imgur.com/8SE2FBo.png)

O [**Chat App**](https://chat-app-navy-omega.vercel.app) é um aplicativo feito com **_TypeScript_**, **_ReactJS_** e **_NextJS_**. Ele é um clone do Messenger e permite ao usuário criar sua conta ou acessar a aplicação por meio de sua conta Google ou do GitHub, personalizar seu perfil, iniciar conversas com outros usuários, criar conversas em grupo, trocar mensagens em tempo real, deletar essas conversas, acessar informações sobre os usuários ou grupos e saber quando outros usuários estão online!

![imagem](https://i.imgur.com/PYuHA5F.jpg)![imagem](https://i.imgur.com/Hs8SdOe.jpg)

Esta aplicação utiliza **_Tailwind CSS_**, **_CLSX_** e outros pacotes para _toasts_, _seletores_, _ícones_, _headless UI_ e _spinners_ na estilização, **_NextAuth_** com _JWT_ e _OAuth_ do Google e GitHub para autenticação e validação de usuário, **_BCrypt_** para a criptografia da senha, **_React Hook Form_** para o uso de formulários, **_Axios_** para lidar com as requisições HTTP, **_Prisma ORM_** para lidar com as informações que serão armazenadas no banco de dados **_MongoDB_**, **_Zustand_** como alternativa ao **_Redux_** no _state management_, **_Pusher_** para a troca de mensagens em tempo real e **_Cloudinary_** para o uso e envio de imagens.

Você pode acessar o projeto no site [**Chat App**](https://chat-app-navy-omega.vercel.app).

## Features

- O usuário poderá logar ou criar uma conta caso não seja registrado.
- O usuário poderá logar ou criar uma conta por meio do OAuth do Google ou do GitHub.
- O usuário poderá editar suas informações de perfil como seu nome de usuário e foto.
- O usuário poderá ver outros usuários do site na seção Usuários e iniciar uma conversa com eles.
- O usuário poderá criar grupos, selecionando quais usuários deseja chamar.
- O usuário poderá trocar mensagens em tempo real e saber se o outro visualizou sua mensagem.
- O usuário poderá enviar imagens nas conversas.
- O usuário poderá acessar informações sobre os usuários ou grupo em que esteja.
- O usuário poderá deletar o grupo ou a conversa que deseje.
- O usuário poderá utilizar a aplicação em qualquer dispostivo, pois o design responsivo se adequa às necessidades.
- O usuário não logado não terá acesso a determinadas abas e páginas do site, sendo automaticamente retornado para a página inicial.
- Todos os dados serão salvos em um banco de dados MongoDB com base em um _schema_ criado com o Prisma ORM.

## Tecnologias Utilizadas

- Tailwind CSS
- CLSX
- TypeScript
- ReactJS
- NextJS
- NextAuth
- Cloudinary
- Pusher
- React Hook Form
- Axios
- Prisma ORM
- MongoDB
- BCrypt
- Zustand
- Date-FNS

O deploy foi feito na plataforma Vercel.
