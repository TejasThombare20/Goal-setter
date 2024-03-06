FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY  . . 

EXPOSE 80

ENV MONGO_USERNAME="tejas"

ENV MONGO_PASSWORD="tejas"

CMD ["node" , "app.js"]