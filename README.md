# Photobooks

Este repositorio forma parte del proyecto https://github.com/EliasBF/photobooks-real-example-app

## Requerimientos

- [Nodejs](https://nodejs.org/en/download/current/) >= 8
- [RethinkDb](https://rethinkdb.com/docs/install/) >= 2.3.6

## Configuración

- Para iniciar esta aplicación es recomendable utilizar la version completa del proyecto en https://github.com/EliasBF/photobooks-real-example-app.

- Para iniciar esta aplicación localmente debes tener también las demás partes de este proyecto en un mismo directorio, debido a que cada parte esta definida en el package.json como una dependencia local (ve al proyecto https://github.com/EliasBF/photobooks-real-example-app para acceder a cada parte).

- Inicia cada microservicio del proyecto photobooks-api (rethinkdb debe estar en ejecución).

- Construye la aplicación

  '''
  npm install
  npm run build
  '''

##### Listo, para iniciar ejecuta '''npm start'''.