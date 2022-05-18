FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /
COPY . .
ADD node_modules.tar.gz ./
CMD ["npm", "test"]