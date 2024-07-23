# Conversor de Monedas

## Descripción

En este emocionante desafío de programación, hemos desarrollado una aplicación de consola en Java para convertir monedas. El Conversor de Monedas permite realizar conversiones entre varias monedas utilizando la API de ExchangeRateAPI. Se realiza solicitudes a una API de tasas de cambio, manipular datos JSON y mostrar las conversiones a los usuarios. Además, se guarda un historial de conversiones en un archivo JSON al salir de la aplicación.

## Objetivo

Desarrollar una aplicación de consola que ofrezca conversiones entre distintas monedas, proporcionando al menos 6 opciones de conversión. La aplicación interactúa con la API de ExchangeRateAPI, procesa la respuesta JSON usando la librería GSON y muestra los resultados de la conversión al usuario.

## Menú de Opciones

La aplicación de consola ofrece las siguientes opciones:

1. **Dólar => Peso Argentino**: Convierte de Dólar a Peso Argentino.
2. **Peso Argentino => Dólar**: Convierte de Peso Argentino a Dólar.
3. **Dólar => Real Brasileño**: Convierte de Dólar a Real Brasileño.
4. **Real Brasileño => Dólar**: Convierte de Real Brasileño a Dólar.
5. **Dólar => Peso colombiano**: Convierte de Dólar a Peso colombiano.
6. **Peso colombiano => Dólar**: Convierte de Peso colombiano a Dólar.
7. **Salir**: Sale de la aplicación y guarda el historial de conversiones en un archivo JSON.

## Instalación

Sigue estos pasos para configurar y ejecutar el proyecto:

1. **Clonar el repositorio**
    ```bash
    git clone https://github.com/Garyn14/alura-conversor-monedas.git
    ```

2. **Configurar el proyecto**
    - Asegúrate de tener Java y Maven instalados en tu sistema.
    - Actualiza las credenciales de la API en el archivo de configuración.

3. **Instalar dependencias**
    ```bash
    mvn install
    ```
## Créditos

Este proyecto hace parte de los retos propuestos por Alura Latam

Este proyecto utiliza las siguientes tecnologías:

- [API de ExchangeRateAPI](https://www.exchangerate-api.com/)
- [Librería GSON](https://www.javadoc.io/doc/com.google.code.gson/gson/2.8.0/com/google/gson/Gson.html)
- Java

