FROM node:13-alpine

ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=password

RUN mkdir -p D:/DevOps/Js-docker-demo-app/app

COPY . D:/DevOps/Js-docker-demo-app/app

CMD ["node", "D:/DevOps/Js-docker-demo-app/app/server.js"]