FROM strapi/base
WORKDIR /srv/app
COPY . .
RUN yarn build
EXPOSE 1337
ENV NODE_ENV production
CMD ["yarn", "start"]
