FROM node:16

WORKDIR /app

COPY package.json ./
RUN npm install   # This ensures that all dependencies (including express) are installed

COPY . .

CMD ["node", "src/index.js"]
