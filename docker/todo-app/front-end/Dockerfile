FROM node:14

WORKDIR /frontend

EXPOSE 3000

ADD node_modules.tar.gz .

COPY ./src ./src
COPY ./public ./public
COPY package-lock.json .
COPY package.json .
COPY .env .

CMD [ "npm", "start" ]