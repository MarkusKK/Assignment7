FROM node:10
WORKDIR /express-6
COPY package.json /express-6
RUN npm install
COPY . /express-6
CMD ["npm", "start"]
EXPOSE 3000
