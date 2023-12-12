FROM node:18-slim
WORKDIR /usr/src
COPY app/package*.json ./
RUN npm install 
COPY . .
EXPOSE 8080
CMD [ "node", "app.js" ]

