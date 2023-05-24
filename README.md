This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Other information about Next.js

Next.js DATA FETCHING =>

1. Server Side Rendering (SSR)
2. Static Side Generation (SSG)
3. Incremental Static Generation (ISR)

by default Next.js uses SSG

user.js

```bash
const express = require('express');
const app =  express();

app.get('/api/users', (req, res) => {
    //handle GET request for /api/users
    const users = [
        { id: 1, name: 'John' },
        { id: 2, name: 'Jane' },
        { id: 3, name: 'Bob' },
    ];

    //send the users as a response
    res.json(users);
});

app.listen(3000, () => {
    console.log('Server is listening on port 3000');
});

```

Next.js supports the following HTTP methods:

1. **GET** retrieves data resources from the server
2. **POST** submits data to the server to create a new resource
3. **PUT** updates or replaces an existing resource on the server
4. **PATCH** partially updates an existing resource on the server
5. **DELETE** removes a specific resource from the server
6. **HEAD** retrieves the headers of a resource without fetching its body
7. **OPTIONS** retrives the supported HTTP methods and other communication options for a resource
