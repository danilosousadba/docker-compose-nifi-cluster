FROM danilo/nifi

LABEL maintainer="infra@smiles.com.br"

# Nifi
ADD ./nifi.properties conf
COPY ./start-nifi.sh .

CMD ["./start-nifi.sh"]
