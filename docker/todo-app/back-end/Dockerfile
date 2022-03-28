# ref https://dockerlabs.collabnix.com/beginners/dockerfile/ADD-command.html
FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz /repos/node
COPY . /repos/node
ENTRYPOINT [ "npm", "start" ]