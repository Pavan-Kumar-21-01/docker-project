FROM node:26-alpine
EXPOSE 8080
WORKDIR /opt/catalogue
COPY package.json .
COPY server.js .
RUN npm install
ENV MONGO=true \
    MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node","server.js"]