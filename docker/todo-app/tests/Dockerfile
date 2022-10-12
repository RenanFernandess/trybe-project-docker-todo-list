FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests

ADD node_modules.tar.gz .

COPY package-lock.json .
COPY package.json .
COPY ./e2e ./e2e
COPY jest.config.js .

CMD [ "npm", "test" ]
