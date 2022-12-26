FROM node:15.4.0

COPY . /app
WORKDIR /app

EXPOSE 3000
ENV NODE_ENV development
ENV MONGO_DB_CONNECTION_STRING mongodb+srv://hannehue:<password>@evaclocal.2jo2sx6.mongodb.net/?retryWrites=true&w=majority
ENV MONGO_DB_NAME EvacLocal
ENV REDIS_URI rediss://default:<password>@evacredis-hansrpedersen-c086.aivencloud.com:22313

RUN npm install

CMD ["npm", "start"]
