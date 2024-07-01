# Sistema de Administración Inmobiliaria

##  🚀 Descripción

Este proyecto es un sistema de administración inmobiliaria que permite gestionar propiedades, clientes, agentes y contratos mediante el uso de archivos XML. Ofrece funcionalidades para actualizar datos, realizar consultas y visualizar información.

## ⚒️ Características

**Actualización de Datos**: Agrega propiedades, clientes, agentes y contratos.
**Consultas**: Permite consultar agentes, propiedades, clientes y contratos.
**Visualización de Datos**: Gráficas y análisis de datos de propiedades, agentes y contratos.

## 📄 Requisitos del Sistema

**Python >= 3.7**

Bibliotecas Python: 
* matplotlib 
* pandas 
* seaborn
* lxml

## ⚙️ Instalación

**Clona el repositorio**
```
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio`
```
**Instala las dependencias**
```
pip install -r requirements.txt
```

## ▶️ Uso

**Ejecuta el script principal**
```
python main.py
```

Sigue las instrucciones del menú para actualizar datos, realizar consultas o visualizar datos.

## 🕹️ Contribución
Para contribuir, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
3. Realiza tus cambios y haz commit (git commit -am 'Añadir nueva funcionalidad').
4. Sube tu rama (git push origin feature/nueva-funcionalidad).
5. Abre un Pull Request.

## 📜 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

Contacto
Para consultas o soporte, puedes contactarme en gmail [jarmando.rmz.19@gmail.com]().

## ©️ Autores
* [José Armando Ramírez Islas](https://github.com/JRI11930) - Desarrollador
* [Victor Hugo Mondragón Aguilar](https://github.com/Victor-nova) - Desarrollador

## 🧑🏽‍💻 Tecnologías Utilizadas
* Python
* XML
* Pandas
* Matplotlib
* Seaborn

## Estructura del Proyecto
```
.
├── data
│   ├── inmobiliaria.xml
│   └── prueba.xml
│   └── prueba.xsd
├── crud.py
├── queries.py
├── xml_util.py
├── main.py
└── README.md
```

## 📝 Notas Adicionales

Asegúrate de tener los archivos XML en la carpeta data antes de ejecutar el programa.

El archivo crud.py contiene las funciones para agregar datos.

El archivo queries.py contiene las funciones para realizar consultas.

El archivo xml_util.py contiene las funciones para cargar y guardar archivos XML.