FROM node:14

WORKDIR /app

COPY package.json .
# COPY package.json /app

RUN npm install

COPY . .

ARG DEFAULT_PORT=80

ENV PORT=$DEFAULT_PORT

EXPOSE $PORT

# VOLUME [ "/app/feedback"  ]
# VOLUME [ "/app/node_modules"  ]

CMD [ "npm", "start" ]