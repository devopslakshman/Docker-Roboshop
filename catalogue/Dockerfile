FROM node:20
WORKDIR /app
COPY *.js .
RUN npm install
ENV MOngo="true"\
 MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node", "server.js"]
CMD ["node", "server.js"]

