### Angular PWA with SSR
```
## Create an Angular app
npm install -g @angular/cli
ng new my-hilarious-app
cd my-hilarious-app
ng serve
## Enable SSR
ng add @nguniversal/express-engine
npm run dev:ssr

## Enable PWA
ng add @angular/pwa --project my-hilarious-app
npm run build:ssr
node dist/my-hilarious-app/server/main.js
http://localhost:4000 
```