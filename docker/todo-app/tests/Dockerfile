FROM mjgargani/puppeteer:trybe1.0 AS todotests

 # WORKDIR: É um diretório gerado dentro do Docker onde nossa aplicação será mantida.

WORKDIR /app

# EXPOSE: Expõe uma porta para o container.

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm"]

CMD [ "test" ]
