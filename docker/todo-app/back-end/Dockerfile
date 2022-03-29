# ref https://dockerlabs.collabnix.com/beginners/dockerfile/ADD-command.html
FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "start" ]