# Instalar aplicação

Abrir a pasta
- npm install
Para instalar as dependencias

- npm run dev
Para rodar o servidor nodejs

abrir outro terminal na mesma pasta
- ngrok http 3000
Para rodar o servidor web

# Configurações Básicas Shopify
Depois tem que alterar dentro da plataforma da shopify o endereço de servidor retornado pelo ngrok.
Não esquecer de utilizar o https. As seguintes urls devem ser utilizadas:
- URL do app. Ex: https://7a3043c0.ngrok.io/
- URL(s) de redirecionamento na lista de permissões. Ex: https://7a3043c0.ngrok.io/auth/callback

~~ https://7a3043c0.ngrok.io/auth?shop=a474693fd418b031f4ad573fa14b4ce4.myshopify.com ~~
