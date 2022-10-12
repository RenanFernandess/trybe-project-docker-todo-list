FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests

ADD node_modules.tar.gz .

COPY *.json .
COPY ./e2e ./e2e
COPY jest.config.js .

CMD [ "npm", "test" ]
