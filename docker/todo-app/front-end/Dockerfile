FROM node:16-alpine

WORKDIR /app/front-end

ADD node_modules.tar.gz /app/front-end

COPY . /app/front-end

RUN npm install

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
