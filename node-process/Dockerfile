FROM node:22-alpine

WORKDIR /dist

COPY . .

RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]