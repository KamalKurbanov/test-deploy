FROM node:22.12.0-alpine

COPY package.json package.json
RUN npm install
COPY . .

EXPOSE 3000



CMD ["node", "index.js"]


