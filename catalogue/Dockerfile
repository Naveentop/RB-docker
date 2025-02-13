FROM node:20.18.3-alpine3.21
EXPOSE 8080
WORKDIR /opt/server
COPY package.json .
COPY server.js .
RUN npm install
ENV MONGO=true
CMD ["node", "server.js"]