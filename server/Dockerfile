
FROM node:10
WORKDIR /server
COPY package.json ./
RUN npm install
EXPOSE 3080
COPY . .
CMD ["npm", "run", "dev"]