FROM node:22-alpine

WORKDIR /app

COPY package-lock.json package.json .

COPY . .

RUN npm install

EXPOSE 5173

CMD ["npm", "run", "dev"]

