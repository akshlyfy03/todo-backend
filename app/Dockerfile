    FROM node:alpine3.18
    WORKDIR /app
    COPY package.json package-lock.json ./
    RUN npm ci
    COPY . .
    EXPOSE 3000
    CMD [ "node", "index.js" ]
