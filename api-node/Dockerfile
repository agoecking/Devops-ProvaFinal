FROM node:18-alpine

WORKDIR /app


COPY ./  /app

RUN npm install express
RUN npm install axios

CMD ["node", "app.js"]


EXPOSE 3000
