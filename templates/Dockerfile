FROM mhart/alpine-node:6.9.1

EXPOSE 5000

ADD . /app
WORKDIR /app

RUN npm install

ENV NODE_ENV production
ENV PORT 5000

CMD ["npm", "run", "bs"]
