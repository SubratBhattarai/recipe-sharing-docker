
FROM node:20-bookworm-slim
WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

RUN mkdir -p /app/data

EXPOSE 5000

CMD ["npm", "start"]
