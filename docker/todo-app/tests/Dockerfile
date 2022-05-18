FROM mjgargani/puppeteer:trybe1.0 AS build
ADD node_modules.tar.gz ./
COPY . .
WORKDIR .
RUN npm install
CMD ["npm", "test"]