from node:16

WORKDIR /dust-front
COPY package*.json ./

RUN npm install
COPY . .

EXPOSE 3000
CMD ["npm", "run", "dev"]
