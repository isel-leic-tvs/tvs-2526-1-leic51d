FROM node:alpine

ENV NODE_PORT=2345

WORKDIR /usr/src/app

COPY src/* ./
RUN npm install

EXPOSE 2345

CMD ["node", "app.js"]

