FROM node:16

WORKDIR /usr/src/docker-skeleton-rails-nextjs/frontend

COPY ./package.json ./

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "dev"]
