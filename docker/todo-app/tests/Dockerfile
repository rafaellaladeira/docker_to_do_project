FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /
ADD node_modules.tar.gz ./
COPY . .
CMD ["npm", "test"]