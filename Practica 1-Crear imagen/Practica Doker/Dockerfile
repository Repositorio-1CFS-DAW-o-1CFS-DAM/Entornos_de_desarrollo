# Seleccionar una imagen base
FROM ubuntu:latest

# Etiqueta del creador
LABEL maintainer="tu_nombre"

# Instalar dependencias (en este caso, simplemente un editor de texto)
RUN apt-get update && apt-get install -y nano

# Copiar archivos de la aplicación al contenedor
COPY . /app

# Establecer el directorio de trabajo
WORKDIR /app

# Comando por defecto al iniciar el contenedor
CMD ["nano"]