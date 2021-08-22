FROM node:10.16.0-alpine

RUN mkdir -p /srv/app/fr-shohin-admin-client
WORKDIR /srv/app/fr-shohin-admin-client

COPY package.json /srv/app/fr-shohin-admin-client
COPY package-lock.json /srv/app/fr-shohin-admin-client

RUN npm install

COPY . /srv/app/fr-shohin-admin-client

CMD ["npm","run","start"]


