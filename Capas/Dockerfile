# Capa 1: La imagen base es ubuntu:latest
FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y curl && \
    rm -rf /var/lib/apt/lists/*

# Capa 3: Copiar el contenido de la carpeta actual a la carpeta /app
COPY . /app

# Capa 4: Ejecutar el comando echo "Hello World!"
CMD ["echo", "Hello World!"]