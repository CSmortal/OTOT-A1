FROM node:bullseye-slim
ENV NODE_ENV production
WORKDIR /app
COPY package.json ./
RUN npm i
COPY . .
CMD ["node", "index.js"]
EXPOSE 3000