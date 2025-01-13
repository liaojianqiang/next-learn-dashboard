# Learn Next.js Course - Build a Dashboard

This is copy of [starter templates](https://github.com/vercel/next-learn/tree/main/dashboard) for [Learn Next.js](https://nextjs.org/learn) Course , and This repository modified for using Local Postgres instance with Docker. 





# How to use

### 1. Creating a new project
```bash
npm install -g pnpm

npx create-next-app@latest nextjs-dashboard --example "https://github.com/liaojianqiang/next-learn-dashboard/tree/main/starter-example" --use-pnpm
```
### 2. Start your local Postgres instance by using Docker
```bash
cd nextjs-dashboard

docker-compose up -d
```
### 3. Running the development server
```bash
pnpm i

pnpm dev
```
pnpm dev starts your Next.js development server on port 3000. Let's check to see if it's working. open http://localhost:3000 on your browser. 



## Resource
- [Learn Next.js](https://nextjs.org/learn) 
- [Vercel GitHub issue](https://github.com/vercel/storage/issues/123#issuecomment-2500543485)
- [Vercel blogpost](https://vercel.com/docs/storage/vercel-postgres/local-development#local-development-with-vercel-postgres)

