FROM node:16

WORKDIR /app

COPY index.html /app/index.html

RUN npm install express

COPY server.js /app/server.js

EXPOSE 3000

CMD ["node", "server.js"]
