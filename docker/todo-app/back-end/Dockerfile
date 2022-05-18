FROM node:14-alpine AS build
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY . .
WORKDIR /
RUN npm install
CMD ["npm", "start"]