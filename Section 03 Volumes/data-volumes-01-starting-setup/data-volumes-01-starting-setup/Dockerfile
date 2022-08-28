FROM node:14

WORKDIR /app

COPY package.json .
# COPY package.json /app

RUN npm install

COPY . .

EXPOSE 80

# VOLUME [ "/app/feedback"  ]
# VOLUME [ "/app/node_modules"  ]

CMD [ "node", "server.js" ]