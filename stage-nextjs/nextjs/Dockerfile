FROM node:latest AS builder
WORKDIR /app
COPY ./src/package.json ./src/yarn.lock ./
RUN yarn install
COPY ./src ./
RUN yarn build

# 実行に必要なファイルのみを含む最終ステージ
FROM node:latest
WORKDIR /app
CMD ["yarn", "dev"]
