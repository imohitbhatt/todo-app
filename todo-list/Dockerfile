FROM node:16

LABEL AUTHOR = "Mohit Bhatt"

WORKDIR /app

COPY package.json .

RUN npm install

RUN npm fund

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
