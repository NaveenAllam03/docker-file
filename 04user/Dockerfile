FROM node:18.9.1-alpine3.19
EXPOSE 8080
WORKDIR /opt/server
ENV MONGO=true
COPY package.json /opt/server/
COPY server.js /opt/server/
RUN npm install 
CMD ["node", "server.js"]