FROM node:20-alpine3.16

WORKDIR /client

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm","dev"]