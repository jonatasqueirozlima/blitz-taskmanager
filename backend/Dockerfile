FROM node:16-alpine

WORKDIR /usr/app/backend

COPY package*.json ./

RUN npm ci -qy

COPY ./ ./

CMD ["npm", "run", "dev"]