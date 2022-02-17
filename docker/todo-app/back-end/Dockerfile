FROM node:14-alpine

WORKDIR /app

EXPOSE 30001

ADD ./node_modules.tar.gz ./

COPY . .

ENTRYPOINT ["npm" "start"]



