# Usar la imagen base de NGINX
FROM nginx:stable-alpine

# Crear volumen (como pide el enunciado)
VOLUME /tmp

# Eliminar contenido anterior de la carpeta html de NGINX
RUN rm -rf /usr/share/nginx/html/*

# Copiar archivos de configuración
COPY nginx.conf /etc/nginx/nginx.conf
COPY mime.types /etc/nginx/mime.types

# Copiar el build de Angular ya compilado
COPY dist/sistema-ventas-front /usr/share/nginx/html

# Exponer el puerto 80
EXPOSE 80

# Comando para mantener nginx activo en primer plano
CMD ["nginx", "-g", "daemon off;"]
