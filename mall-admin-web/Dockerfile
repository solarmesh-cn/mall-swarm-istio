FROM node:latest

RUN npm install -g http-server

ADD ./dist ./dist

CMD ["http-server", "dist"]
