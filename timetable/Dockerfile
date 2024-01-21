FROM node:15
ENV HOST 0.0.0.0

# Create app directory
WORKDIR /timetable

COPY package*.json ./
RUN npm ci

COPY . .
RUN npm run build

CMD [ "npm", "run", "serve" ]
