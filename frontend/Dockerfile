FROM node:16-alpine

WORKDIR /usr/app/frontend

COPY package*.json ./

RUN npm ci -qy

COPY ./ ./

CMD ["npm", "start"]