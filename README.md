

# Conversor de Monedas

Este es un programa simple que permite convertir entre dólares estadounidenses y diversas monedas extranjeras. Utiliza una API de tipo de cambio para obtener las tasas de conversión actuales.

## Funcionamiento

El programa solicita al usuario que elija una opción de conversión entre diferentes monedas. A continuación, se detallan las opciones disponibles:

A). **Dólar a Moneda Local**: Convierte una cantidad en dólares estadounidenses a la moneda local especificada.
B). **Moneda Local a Dólar**: Convierte una cantidad en la moneda local especificada a dólares estadounidenses.

#ejemplos 

	Dólar ===> moneda peruana**
    	moneda peruana ====> dólar
    Dólar ===> peso argentino**
        Peso argentino ====> dólar
    Dólar ===> Real brasileño**
        Real brasileño ====> dólar
    Dólar ===> Peso colombiano**
        Peso colombiano ====> dólar
    Dólar ===> peso mexicano**
        Peso mexicano ====> dólar
    Dólar ===> Colón costarricense**
        Colón costarricense ====> dólar
      .Salir** 						

## Requisitos

- Java JDK 8 o superior
- Clave de API válida para la API de tipo de cambio (reemplazar `YOUR-API-KEY` en el código)

## Instrucciones de Uso

1. Ejecuta el programa desde tu entorno de desarrollo o terminal.
2. Sigue las instrucciones en pantalla para seleccionar la conversión deseada.
3. Se mostrará el resultado de la conversión en la consola.

## Dependencias

- `calcular.buscarMoneda`: Clase que utiliza la API de tipo de cambio para buscar las tasas de conversión.
- `calcular.calcularMoneda`: Clase que realiza los cálculos de conversión basados en las tasas obtenidas.
- `modelo.Moneda`: Clase que representa una moneda y su valor en dólares estadounidenses.

## Configuración

Reemplaza `YOUR-API-KEY` en el código por tu clave de API válida para la API de tipo de cambio.

## Limitaciones y Consideraciones

- El programa puede mostrar errores si la clave de API no es válida o si la API restringe el acceso.
- Las tasas de cambio obtenidas de la API pueden no estar actualizadas en tiempo real.

---

Este sería un ejemplo básico de cómo podrías estructurar un archivo `README.md` para explicar el funcionamiento y los detalles del código proporcionado. Puedes personalizarlo según tus necesidades y agregar más información si lo consideras necesario.
