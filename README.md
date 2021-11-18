# Proyecto-Final-postman
Repositorio utilizado para descargar las entidades del proyecto y cargar los datos a traves de POSTMAN

# Pasos

1) Si se desea utilizar la informacion ya precargada de ejemplo (Municipios, ejes, sub ejes, indicadores,etc) de nanera local,
se debe copiar el contenido del archivo .json ubicado en este repositorio, y pegarlo en la herramienta POSTMAN.
2) Utilizando una peticion POST, se debe colocar la direccion "http://localhost:1026/v2/entities" o bien la direccion donde se aloje el servidor que
desea utilizar para cargar los datos.

Es importante que la maquina utilizada, tenga instalado previamente una instancia de Orion Context Broker (Manualmente o a traves de Docker Compose)
