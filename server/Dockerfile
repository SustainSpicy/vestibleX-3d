FROM node:20-alpine3.16

WORKDIR /server

COPY package.json .

RUN npm install

COPY . .

ENV OPENAI_API_KEY = 1234

EXPOSE 8080

CMD ["node","index.js"]
