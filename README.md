# FindTheBook
Proyecto de findthebook
 Estructura del Repositorio

/FindTheBook
│
├── /frontend               # Código fuente de la interfaz de usuario (React + Vite)
│   ├── /src
│   │   ├── /components     # Componentes reutilizables 
│   │   ├── /views          # Vistas principales 
│   │   └── /services       # Lógica de conexión con la API
│   ├── package.json
│   └── vite.config.js
│
├── /backend                # Código fuente del servidor web y API REST
│   ├── /controllers        # Lógica de las rutas
│   ├── /routes             # Definición de los endpoints
│   ├── /config             # Configuraciones de entorno y conexión a BD
│   ├── /db_scripts         # Scripts SQL para creación de tablas
│   └── server.js
│
├── /documentacion          # Documentos técnicos y de planificación
├── /manuales               # Guías y material de capacitación 
└── /pruebas                # Casos de prueba y scripts de validación