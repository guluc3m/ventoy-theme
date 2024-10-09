# Tema de GUL para [ventoy](https://www.ventoy.net/en/download.html)

Ventoy es una herramienta open source para crear un medio booteable
directamente desde el USB, el cual te permite arrancar directamente desde archivos
ISO. Este te deja subirle todos los archivos que quieras y te los muestra en
un menú de inicio al encender el sistema.

### Como usar

1. Instalar ventoy desde la pagina web y seguir las instrucciones de la aplicación.
2. Crear una carpeta llamada ``ventoy`` y meter dentro la carpeta de ``theme`` y el archivo ``ventoy.json``.

  La estructura del sistema tiene que parecerse a:
  
```
/Ventoy
    ./ventoy
        ./theme/...
        ./ventoy.json

    ./"ISOs con los SO que quieras arrancar"
```


3. Elegir como medio de arranque el pendrive con ventoy.
