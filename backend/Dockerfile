FROM node:26-alpine
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node","index.js"]