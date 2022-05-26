FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app-tests
COPY . .
ADD node_modules.tar.gz .
CMD ["npm", "test"]
