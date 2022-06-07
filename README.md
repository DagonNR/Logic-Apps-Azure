# Uso de Logic App con un analizador de sentimientos
En este repositorio tenemos una demostración del uso de Logic App, incluyendo un analizador de sentimientos de tweets, además de mandarlos a un Google sheets y a un canal de Microsoft Teams.

![Microsoft-Azure-Logic-Apps](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/Microsoft-Azure-Logic-Apps.png)
![Microsoft-Azure-Cognitive-Services](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/Microsoft-Azure-Cognitive-Services.png)

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com)
- Un dispositivo, por ejemplo una computadora
- Acceso a internet
- Navegador de internet como Google Chrome, Opera, Mozilla Firefox, etc.

---

## Importante
- Para poder usar "Cognitive Services", antes se debe crear "Cuentas de varios servicios de Cognitive Services", dentro del mismo.

---

## Pasos a seguir
- Para comenzar debemos entrar en [Microsoft Azure](https://portal.azure.com) y buscar "Logic Apps" y crear uno nuevo, nos pedirá lo mismo que piden todos los recursos de Azure, suscripción, grupo de recursos, nombre y región, además de alguna otra cosa.
![P1](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P1.png)

- Al terminar, vamos a ir al apartado de "Revisar y crear" y si todo sale bien, daremos clic en "Crear"
![P2](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P2.png)

- Al terminar la implementación del recurso, entramos en él y clicamos en "Aplicación lógica en blanco"
![P3](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P3.png)

- En este caso usaremos "Twitter".
![P4](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P4.png)

- Entonces usaremos la barra de búsqueda para encontrarlo.
![P5](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P5.png)

- Entonces nos pedirá asignarle un nombre a la conexión e iniciar sesión.
![P6](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P6.png)

- Entonces nos volverá a pedir diversos datos, como la frecuencia de comprobación y sobre que se hará la búsqueda.
![P7](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P7.png)

- Ahora en otra pestaña buscaremos "Cognitive Services", y crearemos una "Cuenta de varios servicios de Cognitive Services" para poder crear un "Servicio de Lenguaje".
![P8](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P8.png)

- Nos pedirá los datos de siempre, además de una que otra cosa.
![P9](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P9.png)

- En este caso usaremos "Google Sheets".
![P10](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P10.png)

- Ahora dentro de la "Logic App", crearemos un nuevo paso, en el que buscaremos "sentiment" y para la "Clave de cuenta" y "URL del sitio", usaremos el "Servicio de Lenguaje" que creamos antes.
![P11](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P11.png)

- Entonces nos pedirá como analizará (en este caso los tweets).
![P12](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P12.png)

- Ahora conectaremos "Google Sheets", igual que cuando buscamos "Twitter", nos pedriá iniciar sesión.
![P13](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P13.png)

- Buscaremos el archivo, hoja de cálculo y añadiremos los parámetros.
![P14](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P14.png)

- En este caso también añadiremos "Microsoft Teams", para que los mensaje se manden a un grupo, en un canal en específico.
- Entonces si estamos contentos con el resultado, guardamos y ejecutamos.
![P15](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P15.png)

- Si todo salió bien, quedaría algo parecido a esto.
![P16](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P16.png)
![P17](https://github.com/DagonNR/Logic-Apps-Azure/blob/main/images/P17.png)
