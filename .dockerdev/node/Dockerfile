FROM node:14-alpine

RUN npm config set registry http://registry.npmjs.org/

WORKDIR /usr/src/app/

CMD yarn install && npm run start:docker
