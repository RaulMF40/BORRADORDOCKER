FROM node:22.9.0-alpine

WORKDIR /opt/

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "run", "start:nodemon"]