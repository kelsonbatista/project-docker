# ref https://dockerlabs.collabnix.com/beginners/dockerfile/ADD-command.html
FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests
ADD ./node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "test" ]