FROM node:18.9.1

WORKDIR /app

COPY package*.json ./

RUN npm ci

COPY . .

CMD ["npm","start"]


EXPOSE 4000


# simple Dockerfile for backend
