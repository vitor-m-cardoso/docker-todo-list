FROM node:16-alpine

WORKDIR /app/back-end

ADD node_modules.tar.gz /app/back-end

COPY . /app/back-end

RUN npm install

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
