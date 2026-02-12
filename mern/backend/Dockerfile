FROM node:latest 

WORKDIR /app

COPY package-lock.json package.json .

COPY . . 

RUN npm install

EXPOSE 5050

CMD ["npm", "start"]
