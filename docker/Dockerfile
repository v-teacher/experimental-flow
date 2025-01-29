FROM nginx:alpine

# Configurar Nginx
COPY nginx.conf /etc/nginx/nginx.conf

# Agregar archivo HTML a la carpeta pública
COPY index.html /usr/share/nginx/html/index.html

# Exponer el puerto 80
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
