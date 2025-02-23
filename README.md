# Gestor de Archivos 

Este es un programa en Java que permite gestionar archivos de manera eficiente a través de un menú interactivo. Facilita tareas como renombrado, organización, eliminación de publicidad y limpieza de archivos duplicados.

## Características

- **Eliminar** la primera parte del nombre de un archivo según un criterio definido por el usuario.
- **Sustituir** una parte del nombre de un archivo por otra especificada.
- **Organizar** archivos en carpetas según su tipo.
- **Mover** archivos de un determinado tipo a una carpeta específica.
- **Crea** paquetes de java a partir de los archivos java encontrados. Útil cuando tenemos varios archivos java desperdigados y no los tenemos organizados por su package, pues esta opción lo ordenará.
- **Eliminar archivos duplicados** en la carpeta de trabajo. Esto se hace internamente con el uso de expresiones regulares.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/alejandrorodm/Gestor-de-Archivos-Java
   cd Gestor-de-Archivos-Java
   ```
2. Asegúrate de tener Python instalado en tu sistema.

## Uso

Ejecuta el .exe, que proviene del .jar.

```bash
python menu.py
```

### Opciones del menú:

1. Eliminar la primera parte del nombre de un archivo (tu delimitas cual es esta)
2. Sustituir la primera parte del nombre de un archivo (tu delimitas cual es esta) por el nombre que quieras
3. Crear una carpeta para un tipo de archivo y mover todos los archivos que cumplan ese tipo a ella
4. Crea paquetes de java a partir de los archivos java encontrados para su organizacion
5. Organiza todos los archivos por carpetas con el nombre del tipo que sean (pdf: todos los pdf, docx: todos los docx...)
6. Elimina todos los archivos repetidos que haya en la carpeta
7. Borra wuolah-free y gulag-free (esto lo que hace es borrar del nombre la publicidad que le añaden dichas páginas)
8. Exit

## Autor

- **Alejandro Rodríguez*


