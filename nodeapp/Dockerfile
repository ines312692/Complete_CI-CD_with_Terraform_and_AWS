FROM node:14
WORKDIR /usr/app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 8082
CMD ["node","app.js"]