This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# Getting Started

First, run the development server:

```bash
yarn      # install dependencies
yarn dev  # run the dev server
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## State Management

- [Hooks for redux](https://github.com/generalui/hooks-for-redux)

## Testing

Unit tests written with Jest + @react-testing-library.
Integration tests written in Playwright.

```
yarn test       // Run all tests
yarn test:unit  // Run unit tests
yarn test:e2e   // Run integration tets
```

# Using this starter

### As static react app:

A static react app generated at build time and hosted as client side only. All static content is pre-rendered on the page.

- See [static generation](https://nextjs.org/docs/basic-features/pages#static-generation-recommended)
- Remove `/pages/api`
- Build app with `yarn build:static`
- See [Next unsupported static features](https://nextjs.org/docs/advanced-features/static-html-export#unsupported-features)

### As fullstack framework

A fullstack Nextjs app requires the app to be hosted in on most VMs that support Node.js. This server can be used to
server-side generate pages, host api logic, and optimize page loading. This is optional.

- See [server side rendering](https://nextjs.org/docs/basic-features/data-fetching/get-server-side-props)
- See [api routes](https://nextjs.org/docs/api-routes/introduction)
- See [next/server](https://nextjs.org/docs/api-reference/next/server)
