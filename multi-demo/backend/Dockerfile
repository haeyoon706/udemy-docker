FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . . 

EXPOSE 80

ENV MONGO_USERNAME=root
ENV MONGO_PASSWORD=secret

CMD ["npm", "start"]