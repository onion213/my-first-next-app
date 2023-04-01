# My First Next App

Next.js Tutorial
Ref: https://nextjs.org/learn/basics/create-nextjs-app

## Development
Use Docker container for development

Ref: https://zenn.dev/temple_c_tech/articles/setup-next-on-docker

## initial work
1. get template
```
docker-compose build
docker-compose run --rm app sh -c 'npx create-next-app@latest /app --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"'
```

2. start service and check http://localhost:3000
```
docker-compose up
```