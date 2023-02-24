# APIPRINTER
Servicio de Impresion Direcata a USB desde Navegador

### REQUISITOS: 
```
COMO APLICACION PREDETERMINADA PARA ABRIR ARCHIVOS PDF
```
| Instalacion de software  |
| :---  |
| [ADOBE READER PDF](https://get.adobe.com/es/reader/) |
| ADOBE CREATE  |
|  *[Microsoft Visual C++ Redistributable 2015-2022](https://learn.microsoft.com/es-es/cpp/windows/latest-supported-vc-redist?view=msvc-170) | 

**vc_redist.x64 incluido en la descarga del Release*

## INSTALACION
**Descargar:** [WebPluginPrinter](https://github.com/AmericanaSoporteIT/APIPRINTER/releases/download/0.12/WebPluginPrinter.zip)
extraer todos los archivos en el siguiente ruta de:
**C:\Program Files\WebPluginPrinter**
```
C:\Program Files\WebPluginPrinter
```
### Ejecutar:  **Win + R** escribir en la ventana de ejecucion:
```
shell:startup
```
Abrira la ruta **C:\Users<Nombre del usuario>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup**
donde se copiara el archivo api.bat
para autoarranque al inicio

## COMPROBAR SERVICIO
[localhost:8000](http://localhost:8000/) mostrar un mensaje **Web Plugin Printer: It's Work!!**

```
http://localhost:8000/
```

 
## PREUBA DE IMPRESION
[localhost:8000/test](http://localhost:8000/test)

- SELECCIONAR IMPRESORA DE DESTINO
- ELEGIR ARCHIVO *.PDF

```
http://localhost:8000/test
```



## TERMINAR PROCESO:

### EJECUTAR CMD COMO ADMINISTRADOR

```
  TASKKILL /F /IM APIPRINTER.EXE
```

