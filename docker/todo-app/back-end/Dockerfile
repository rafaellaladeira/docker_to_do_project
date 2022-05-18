FROM node:14-alpine AS build
EXPOSE 3001
WORKDIR /
ADD node_modules.tar.gz ./
COPY . .
CMD ["npm", "start"]