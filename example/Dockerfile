# Usa la imagen base oficial de nginx desde Docker Hub
FROM nginx:latest

# Copia los archivos locales en el contenedor
COPY . /usr/share/nginx/html

# Expone el puerto 80 para el contenedor
EXPOSE 80

# Comando por defecto para ejecutar cuando se inicia el contenedor
CMD ["nginx", "-g", "daemon off;"]
