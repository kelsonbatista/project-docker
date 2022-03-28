
# ref https://dockerlabs.collabnix.com/beginners/dockerfile/ADD-command.html
FROM mjgargani/puppeteer:trybe1.0
ADD ./front-end/node_modules.tar.gz ./
COPY ./tests ./
ENTRYPOINT [ "npm", "test" ]