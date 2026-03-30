FROM node:24
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]