FROM node:22.9.0-alpine

WORKDIR /opt/

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3001

# instale nodemon, para que reinicie automaticamente cualquier cambio en el codigo, si surgiera. 

CMD ["npm", "run", "start:nodemon"]  