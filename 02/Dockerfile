FROM  node:latest

WORKDIR /app

# Optimization
COPY package.json /app  

RUN npm install

COPY . /app

EXPOSE 80

CMD [ "node","server.js" ] 

