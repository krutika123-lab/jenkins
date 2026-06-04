From node:22.12.0

WORKDIR /app

COPY . .

RUN npm install -g serve

EXPOSE 3000

CMD ["serve", "-s", ".", "-l", "3000"]