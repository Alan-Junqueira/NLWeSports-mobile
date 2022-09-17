# NLWeSports-mobile

- O que é o NLWeSports? 
É uma aplicação para conectar jogadores em busca de um duo para jogar.

Para usar essa aplicação, baixar o servidor node no link: 
https://github.com/Alan-Junqueira/NLWeSports-api
As rotas de conexão com o bd, estão sendo feitas com o axios.
Como o servidor esta sendo executado localmente, na porta 3333, é possível que o expo não se conecte e tenha que usar o ngrok.

- Ngrok https://ngrok.com/
O Ngrok é uma ferramenta CLI (Comand Line Interface) que te permite criar um túnel seguro, atrás de NATs e Firewalls,
que expõem serviços locais para a Internet, tudo isso de forma fácil e segura.

Com a aplicação da api do backend rodando, basta seguir o passo a passo do ngrog e colocar http 3333.

- Iniciando o app mobile
É possível executar o preview da aplicação pelo Expo Go (app mobile), podendo ser baixado em emulador ou no celular.
Com o backend já funcionando, basta abrir o terminal do app mobile, pegar o link que foi gerado pelo ngrok, 
substituir as rotas do axios e executar a aplicação, digitando no terminal:
expo start



https://user-images.githubusercontent.com/104371202/190827844-86b91540-2162-4500-a58b-080155991c48.mp4

