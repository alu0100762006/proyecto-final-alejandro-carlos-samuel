# MYLIB

# Uso

1. Clonar el repo
2. Ejectuar `npm install`
3. Ejectuar `npm run start`
4. Acceder desde un navegador a `localhost:4000`

# Autores

* [Alejandro Arzola](http://aleag.github.io)
* [Carlos de Armas](http://alu0100816167.github.io)
* [Samuel Valcárcel](http://cosaca.github.io)

.
├── LICENSE
├── README.md
├── app
│   ├── models 
│   │   └── users_db.js -> definimos la base de datos
│   └── routes.js -> rutas de la app
├── config -> irá configuración de passport
├── package.json
├── server.js
└── views
    ├── landing
    │   └── landing.ejs
    └── login
        ├── login.ejs
        └── register.ejs