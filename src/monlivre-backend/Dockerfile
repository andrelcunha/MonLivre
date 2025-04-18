FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm ci
COPY . .
# RUN npm run build
# CMD ["node", "dist/main.js"]
EXPOSE 3000
CMD ["sh", "-c", "npm run db:deploy && npm run start:dev"]


