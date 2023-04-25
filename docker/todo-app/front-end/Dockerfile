FROM node:16-alpine

EXPOSE 3000

WORKDIR /app/front-end

ADD node_modules.tar.gz .

COPY . .

CMD ["start"]

ENTRYPOINT ["npm"]
