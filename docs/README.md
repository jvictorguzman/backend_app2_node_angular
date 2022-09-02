
## 1. Instalar sequelize
`````bash
npm install sequelize 

`````

## 2. Instalar sequelize-cli
`````bash
npm install --save-dev sequelize-cli

`````

### 3. Configurar .sequelizerc
````
const path = require('path');

module.exports = {
  'config': path.resolve('src/config', 'database.json'),
  'models-path': path.resolve('src', 'models'),
  'seeders-path': path.resolve('src', 'seeders'),
  'migrations-path': path.resolve('src', 'migrations')
};


````
## 4. Iniciar un nuevo proyecto con sequelize-cli
````bash
npx sequelize-cli init
````

--------

## Descargar e Instalar GIT
```
https://git-scm.com/
```
- Luego Instalar
- Para Configurar agregar usuario, correo  y luego ejecutar
```
git config --global user.name "nombre"
git config --global user.mail "micorreo@mail.com"
```

## Inicializar un nuevo repositorio local
- Para crear un nuevo repositorio
```
git init
```
- para ignorar archivos y o carpetas
- creamos un archivo (.gitignore) y registramos los archivos o carpetas
```
```

- Para clonar un repositorio existente
```
git clone
```

## Registrar el repositorio remote 
 ```
git remote add origin https://github.com/jvictorguzman/backend_app2_node_angular.git
 ```
-------

## Para agregar todos los archivos al index
```
git add .
```
## Para agregar o registrar los cambios agregamos un mensaje (commit) al head
```
git commit -m "mensaje"
```