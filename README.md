# Tema del GUL para Ventoy

<img width="1024" height="768" alt="theme overview" src="https://github.com/user-attachments/assets/ee035d5f-32df-4585-9be3-96a9ba788fe2" />

[Ventoy](https://www.ventoy.net/) es una herramienta open source para crear un medio booteable
directamente desde el USB, el cual te permite arrancar directamente desde archivos
ISO. Este te deja subirle todos los archivos que quieras y te los muestra en
un menú de inicio al encender el sistema.

## Como usarlo
1. Descarga [Ventoy](https://www.ventoy.net/en/download.html) e instálalo en el USB siguiendo
   [las instrucciones de la aplicación](https://www.ventoy.net/en/doc_start.html)
3. En la partición `Ventoy`, crea una carpeta `ventoy/` y mete dentro la carpeta `theme` y el archivo `ventoy.json`.  
   La carpeta tiene que parecerse a:  
    ```
    Ventoy/
    ├── ventoy/
    │   ├── theme/
    │   │   └── ...
    │   └── ventoy.json
    └── *.iso
    ```


## Más información
- [Ventoy Theme Plugin documentation](https://www.ventoy.net/en/plugin_theme.html)
