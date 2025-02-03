FROM node

WORKDIR /app

# 모든 하위 폴더를 copy and 저장 위치 지정, workdir인 app에서 수행 ./
COPY . /app

RUN npm install

EXPOSE 80

CMD ["node", "server.js"]
