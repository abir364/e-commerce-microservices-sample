FROM node:18.20.8-bookworm

WORKDIR /app

COPY *.json .

RUN npm i

COPY . .

CMD ["npm","start"]