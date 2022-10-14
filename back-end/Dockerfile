FROM node:16.14

WORKDIR /app

COPY . .

RUN npm i

RUN npm run build

CMD [ "npm", "start" ]
