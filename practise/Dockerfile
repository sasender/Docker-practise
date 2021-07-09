FROM node:13-alpine
ENV mongo_db_username=admin \
    mongo_db_pwd=password

RUN mkdir -p /home/app

COPY . /home/app
CMD ["node", "server.js"]

