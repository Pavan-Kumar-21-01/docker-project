FROM node:26-alpine
WORKDIR /opt/user
COPY server.js .
COPY package.json .
RUN npm install
ENV MONGO=true
CMD ["node","server.js"]