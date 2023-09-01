# Imagem base
FROM node:latest

# Diretório dentro da imagem que vamos trabalhar
WORKDIR /frontend

# 
COPY . .

# 
RUN npm i 

EXPOSE 3000

# 
CMD ["node", "server.js"]
