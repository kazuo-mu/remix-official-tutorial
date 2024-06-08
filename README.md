# Site image
<img width="832" alt="Screen Shot 0006-06-08 at 17 42 49" src="https://github.com/kazuo-mu/remix-official-tutorial/assets/11404775/1557d9f4-23f4-429c-9206-b3a75bb620f0">


# Welcome to Remix!

- [Remix Docs](https://remix.run/docs)

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `remix build`

- `build/server`
- `build/client`
