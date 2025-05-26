# Dockerイメージを指定
FROM node:22-slim

WORKDIR /frontend
RUN yarn install

# 別ホストからもアクセスできるように設定
ENV HOST=0.0.0.0

# Next.jsを起動
ENTRYPOINT ["yarn", "dev"]
