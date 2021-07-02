FROM node
WORKDIR /bva
COPY package*.json ./
RUN npm i --silent
COPY . .
EXPOSE 8080
CMD ["node", "app.js"]