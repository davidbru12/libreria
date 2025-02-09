# Libreria

Librería es una aplicación basada en XML que permite gestionar un catálogo de libros de manera estructurada y sencilla. Utiliza XML para almacenar la información de los libros y puede ser procesada mediante tecnologías como XSLT, JavaScript o Python.

## Características
- Almacenamiento de libros en formato XML.
- Organización de datos como título, autor, editorial, año de publicación y género.
- Posibilidad de transformación de XML a HTML mediante XSLT.
- Validación de la estructura con DTD o XSD.

##  Tecnologías
- XML
- XSLT (Opcional, para transformar datos en HTML).
- DTD/XSD (Para validar el esquema del XML).
- JavaScript o Python (Para procesar y manipular los datos).

##  Requisitos
- Un editor de texto compatible con XML (VS Code, Notepad++, etc.).
- Navegador web si se usa XSLT para visualizar los datos.
- (Opcional) Python si se quiere manipular los datos con scripts.

## Configuración
1. Clona el repositorio:
```
git clone https://github.com/tuusuario/Libreria.git
```
2. Abre libros.xml en un editor de texto o navegador.
3. (Opcional) Si hay una transformación XSLT, ábrela en el navegador junto con el XML.
4. (Opcional) Ejecuta scripts de procesamiento:
```
python scripts/procesar.py
```

##  Estructura del Proyecto
```
Libreria/
|-- data/
|   |-- libros.xml
|   |-- esquema.xsd  (Opcional)
|-- xslt/
|   |-- libros.xsl   (Opcional, para visualización)
|-- scripts/
|   |-- procesar.py  (Opcional, para manipulación con Python)
|-- README.md
```

## Contribuciones
1. Haz un fork.
2. Crea una rama:
   ```
   git checkout -b feature/nueva-funcionalidad
   ```
3. Haz un commit y abre un Pull Request.

## Licencia
Proyecto bajo la Licencia MIT. Consulta `LICENSE` para más detalles.

## Autor
Desarrollado por David Bru (https://github.com/davidbru12).

