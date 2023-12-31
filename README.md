# E-commerce Fullstack (Dashboard).

Full Stack E-Commerce + Dashboard & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL

Essa dashboard é para esse repositório [E-commerce](https://github.com/gabrielgxrcia/ecommerce-store)

## Features

- Utilizei o Shadcn UI para o painel de administração!
- Nosso painel de administração servirá como CMS, Admin e API, tudo em um só lugar!
- Você poderá controlar múltiplos fornecedores/lojas através deste único CMS! (Por exemplo, você pode ter uma "Loja de Sapatos", uma "Loja de Laptops" e uma "Loja de Ternos", e nosso CMS irá gerar rotas de API individualmente para cada uma delas!)
- Você poderá criar, atualizar e deletar categorias!
- Você poderá criar, atualizar e deletar produtos!
- Você poderá fazer upload de múltiplas imagens para os produtos e alterá-las sempre que desejar!
- Você poderá criar, atualizar e deletar filtros como "Cor" e "Tamanho" e, em seguida, associá-los ao formulário de criação de "Produto".
- Você poderá criar, atualizar e deletar "Painéis de Publicidade", que são grandes textos exibidos no topo da página. Você poderá vinculá-los a uma única categoria ou utilizá-los de forma independente (Nosso Admin gera rotas de API para todos esses casos!)
- Você poderá pesquisar através de todas as categorias, produtos, tamanhos, cores, painéis de publicidade com paginação inclusa!
- Você poderá controlar quais produtos são "destacados" para que sejam exibidos na página inicial!
- Você poderá visualizar seus pedidos, vendas, etc.
- Você poderá ver gráficos de sua receita, etc.
- Você faz autenticação usando Clerk!
- Criação de pedidos
- Finalização de compra usando Stripe
- Webhooks do Stripe
- MySQL + Prisma + PlanetScale

### Funcionamento

```shell
git clone https://github.com/gabrielgxrcia/ecommerce-admin.git
```

### Instale os pacotes

```shell
npm i
```

### Arquivo .env

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=''
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=""
STRIPE_API_KEY=
FRONTEND_STORE_URL=http://localhost:3001
STRIPE_WEBHOOK_SECRET=
```

### Conectando ao PlanetScale e executando o Push do Prisma

```shell
npx prisma generate
npx prisma db push
```

## Agradecimentos

- [ShadcnUI](https://ui.shadcn.com/)

## Feedback

Se você tiver algum comentário, entre em contato comigo em gabrielgrazeffi12@gmail.com

## Licença

[MIT](https://choosealicense.com/licenses/mit/)
