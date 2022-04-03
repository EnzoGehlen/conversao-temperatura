FROM node:16.14.2
WORKDIR /app
COPY package* .
RUN npm i
COPY . /app
EXPOSE 8080
CMD ["node", "server.js"]