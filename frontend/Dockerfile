# syntax=docker/dockerfile:1

FROM node:12.18.1
#ENV
#ENV NODE_ENV=production
#Workdir
WORKDIR /usr/src/app
#COpy
COPY ["package.json", "./"]
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "index.js", "npm", "start"]
