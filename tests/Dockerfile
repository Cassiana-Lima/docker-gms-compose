FROM cypress/included:16.2.1

WORKDIR /app

COPY package*.json ./

RUN npm ci

COPY . .

CMD ["npx", "cypress", "run"]
