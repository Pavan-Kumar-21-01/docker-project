FROM node:26-alpine
EXPOSE 8080
WORKDIR /opt/catalogue
COPY package.json .
COPY server.js .
ENV MONGO="true" \
    MONGO_URL="mongodb://mongodb:27017/catalogue"
RUN npm install
CMD ["node","server.js"]