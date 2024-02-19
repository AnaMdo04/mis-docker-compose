# Utilizamos la imagen oficial de Node.js 14
FROM node:14

# Establecemos el directorio de trabajo dentro del contenedor
WORKDIR /var/app

# Copiamos el archivo package.json y package-lock.json para instalar las dependencias
COPY package*.json ./

# Instalamos las dependencias
RUN npm install

# Copiamos el resto de los archivos al directorio de trabajo
COPY . .

# Exponemos el puerto 8080
EXPOSE 8080

# Comando para iniciar la aplicación
CMD ["npm", "start"]
