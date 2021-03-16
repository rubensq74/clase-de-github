
#
# Mi sitio web
#

# Se construye sobre la imagen de nginx
FROM nginx:1.11-alpine

# Se agregan metadatos a la imagen

LABEL Descripción="Mi servicio web" Autor="Rubén Soria" Version="v1.0.0"

# Se copian los ficheros hacia la carpeta de nginx

COPY /html /usr/share/nginx/html
