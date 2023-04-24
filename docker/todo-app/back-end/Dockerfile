FROM node:16-alpine

WORKDIR /app/back-end

COPY . .

EXPOSE 3001

ADD node_modules.tar.gz .

ENTRYPOINT [ "npm" ]

CMD [ "start" ]