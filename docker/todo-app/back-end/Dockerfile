FROM node:14 AS todobackend

 # WORKDIR: É um diretório gerado dentro do Docker onde nossa aplicação será mantida.

WORKDIR /app

# EXPOSE: Expõe uma porta para o container.

EXPOSE 3001 

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm"]

CMD [ "start" ]
