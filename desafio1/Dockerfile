FROM node:14.1-alpine

WORKDIR /home/node/app

COPY web-server.js .

USER node

EXPOSE 3000

CMD [ "node", "web-server.js" ]