FROM node:18.9.1-alpine3.19
EXPOSE 8080
RUN addgroup -S roboshop && adduser -S roboshop -G roboshop 
WORKDIR /opt/server
COPY package.json /opt/server/
COPY server.js /opt/server/
RUN npm install 
CMD ["node", "server.js"]