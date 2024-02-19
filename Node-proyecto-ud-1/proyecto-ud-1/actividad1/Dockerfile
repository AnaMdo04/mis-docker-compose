# Utiliza la imagen oficial de Node.js versión 14
FROM node:14

# Crea el directorio de la aplicación en el contenedor
WORKDIR /var/app

# Copia los archivos necesarios para la aplicación
COPY . .

# Instala las dependencias
RUN npm install

# Expone el puerto 8080
EXPOSE 8080

# Comando para arrancar el proyecto
CMD ["npm", "start"]
