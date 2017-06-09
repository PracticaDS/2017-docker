FROM node:6

COPY package.json .
RUN yarn

COPY . . 

EXPOSE 3000

CMD node server.js

