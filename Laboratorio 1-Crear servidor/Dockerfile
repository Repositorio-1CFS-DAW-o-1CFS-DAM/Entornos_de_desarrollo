# Usa la imagen base oficial de Nginx
FROM nginx:latest

# Etiqueta del creador
LABEL maintainer="tu_nombre"

# Copia tu contenido HTML al directorio predeterminado de Nginx en la imagen
COPY contenido_html /usr/share/nginx/html

# Expone el puerto 80 para que puedas acceder al servidor web
EXPOSE 80

# Comando por defecto al iniciar el contenedor (inicia Nginx en primer plano)
CMD ["nginx", "-g", "daemon off;"]