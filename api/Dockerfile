FROM node

WORKDIR /api

COPY package*.json ./
RUN npm ci

COPY . .

CMD ["node", "src/index.js"]
