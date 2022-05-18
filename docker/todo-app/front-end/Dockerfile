FROM node:14-alpine AS build
EXPOSE 3000
WORKDIR /
COPY . .
ADD node_modules.tar.gz ./
CMD ["npm", "start"]