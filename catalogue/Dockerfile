FROM node:26-alpine
EXPOSE 8080
WORKDIR /opt/catalogue
COPY package.json .
COPY server.js .
RUN npm install
ENV MONGO=true
CMD ["node","server.js"]