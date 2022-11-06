FROM node:14.17.5

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]




# CRIAÇÃO DA IMAGEM 

# docker image build -t nandocloud/app-conversao-temperatura .

# docker container run -d -p 8080:8080 nandocloud/app-conversao-temperatura:1.0

# docker push nandocloud/app-conversao-temperatura:latest

# docker tag nandocloud/app-conversao-temperatura:latest nandocloud/app-conversao-temperatura:2.0

# sudo netstat -tlpn | grep 8080

# # Mata processo que está rodando na porta 8080
# sudo kill -9 `sudo lsof -t -i:8080`
# sudo kill -9 $(lsof -t -i:8081)
