FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
COPY . .
RUN tar -xf /tests/node_modules.tar.gz
CMD ["npm", "test"]
