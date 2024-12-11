# Buscador de Clima - React y TypeScript

Este proyecto es una aplicación web que permite buscar información climática en tiempo real de cualquier ciudad del mundo. La aplicación se conecta a la API de **OpenWeather** para obtener los datos de temperatura actual, mínima y máxima del día. Fue desarrollada con **React**, **TypeScript**, y hace uso de **Axios** y **ValidBot** para manejar la conexión con la API.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Funcionalidades](#funcionalidades)
- [Aprendizajes Clave](#aprendizajes-clave)
- [Créditos](#créditos)

---

## Descripción del Proyecto

El **Buscador de Clima** permite a los usuarios:
1. **Ingresar una ciudad**: Se escribe el nombre de la ciudad en el formulario.
2. **Seleccionar un país**: Se elige el país correspondiente al que pertenece la ciudad.
3. **Obtener información climática**: Muestra la temperatura actual, la mínima y la máxima del día de hoy.

Este proyecto utiliza la API de OpenWeather para obtener los datos, y se implementa **Axios** para gestionar las solicitudes HTTP. Dado que TypeScript no puede conectarse directamente a la API, se utiliza **ValidBot** para facilitar la validación y el manejo de datos en la interacción con la API.

---

## Tecnologías Utilizadas

- **React**: Biblioteca para la construcción de interfaces de usuario.
- **TypeScript**: Tipado estático que proporciona mayor robustez al código.
- **Tailwind CSS**: Framework para diseño responsivo y rápido.
- **Axios**: Cliente HTTP para manejar solicitudes y respuestas a la API.
- **OpenWeather API**: Fuente de datos climáticos en tiempo real.
- **ValidBot**: Herramienta para validación y manejo de datos de TypeScript con APIs externas.

---

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tuusuario/buscador-clima.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd buscador-clima
    ```

3. Instala las dependencias:
    ```bash
    npm install
    ```

4. Configura tu API Key de OpenWeather:
    - Crea un archivo `.env` en la raíz del proyecto.
    - Añade tu clave de API:
      ```
      REACT_APP_OPENWEATHER_API_KEY=tu_api_key
      ```

5. Inicia el servidor de desarrollo:
    ```bash
    npm run dev
    ```

---

## Funcionalidades

- **Búsqueda de Clima**: Obtén información climática en tiempo real ingresando una ciudad y seleccionando un país.
- **Datos Detallados**: Muestra:
  - Temperatura actual.
  - Temperatura mínima del día.
  - Temperatura máxima del día.
- **Interfaz Intuitiva**: Un diseño sencillo y limpio utilizando Tailwind CSS.

---

## Aprendizajes Clave

Este proyecto me permitió aprender y reforzar conocimientos importantes, incluyendo:

1. **Uso de Axios con APIs**: Cómo realizar solicitudes HTTP para obtener datos desde APIs externas.
2. **Integración con OpenWeather API**: Comprensión de cómo consumir y manejar datos climáticos en tiempo real.
3. **TypeScript y ValidBot**:
   - ValidBot facilita la validación de datos al interactuar con APIs externas, especialmente en casos donde el tipado puede ser complejo.
   - Aprendí a manejar respuestas asíncronas de manera segura y tipada.
4. **Diseño Responsivo**: Práctica de diseño moderno y adaptable utilizando Tailwind CSS.
5. **Manejo de Estados y Efectos**: Cómo manejar estados locales y realizar llamadas asíncronas con React.

---

## Créditos

Este proyecto fue desarrollado como parte del curso **React y TypeScript** impartido por **codigoconjuan**. Puedes acceder al curso y su contenido educativo para aprender más sobre desarrollo moderno con estas tecnologías.

- [Curso de React y TypeScript - codigoconjuan](https://codigoconjuan.com)

---

## Enlace al Proyecto

Puedes probar el proyecto en el siguiente enlace:  
🔗 **[Buscador de Clima](https://buscadorclima-typescript-react.netlify.app)**

---

Este proyecto refuerza la importancia de conectar aplicaciones React con APIs externas y utilizar herramientas modernas como Axios y ValidBot para simplificar el manejo de datos. ¡Espero que lo disfrutes y te sea útil para explorar el desarrollo con React y TypeScript!

