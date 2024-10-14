# DE_PruebasUnitariasVue

Este repositorio contiene una aplicación web sencilla desarrollada en Vue.js que implementa pruebas unitarias utilizando Vue Test Utils y Jest. En este proyecto, se han añadido rutas para las vistas "About" y "Contact", y se han creado pruebas para validar la estructura HTML de los componentes mediante snapshots.

## Requisitos
- Node.js
- Vue.js
- Vue Router
- Jest
- Vue Test Utils

## Estructura del Proyecto
```
└── 📁DE_PruebasUnitariasVue
    └── 📁src
        └── 📁router
            └── index.js
        └── 📁views
            └── AboutView.vue
            └── ContactView.vue
            └── HomeView.vue
            └── PostsView.vue
        └── App.vue
        └── main.js
    └── 📁tests
        └── 📁unit
            └── 📁views
                └── 📁__snapshots__
                    └── aboutView.spec.js.snap
                    └── homeView.spec.js.snap
                └── aboutView.spec.js
                └── contactView.spec.js
                └── homeView.spec.js
                └── postsView.spec.js
```

## Instalación Para instalar las dependencias del proyecto, ejecuta el siguiente comando:  
` npm install`

## Pruebas

Para ejecutar las pruebas unitarias, utiliza el siguiente comando:
`npm run test:unit`

## Uso

Puedes iniciar la aplicación en modo de desarrollo con el siguiente comando:

`npm run serve`# DE_PruebasUnitariasVue
# DE_PruebasUnitariasVue
