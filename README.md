# Uso de Logic App con un analizador de sentimientos
En este repositorio tenemos una demostración del uso de Logic App, incluyendo un analizador de sentimientos de tweets, además de mandarlos a un Google sheets y a un canal de Microsoft Teams.

![Microsoft-Azure-Logic-Apps](images\Microsoft-Azure-Logic-Apps.png)
![Microsoft-Azure-Cognitive-Services](images\Microsoft-Azure-Cognitive-Services.png)

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
![P1](images\P1.png)

- Al terminar, vamos a ir al apartado de "Revisar y crear" y si todo sale bien, daremos clic en "Crear"
![P2](images\P2.png)

- Al terminar la implementación del recurso, entramos en él y clicamos en "Aplicación lógica en blanco"
![P3](images\P3.png)

- En este caso usaremos "Twitter".
![P4](images\P4.png)

- Entonces usaremos la barra de búsqueda para encontrarlo.
![P5](images\P5.png)

- Entonces nos pedirá asignarle un nombre a la conexión e iniciar sesión.
![P6](images\P6.png)

- Entonces nos volverá a pedir diversos datos, como la frecuencia de comprobación y sobre que se hará la búsqueda.
![P7](images\P7.png)

- Ahora en otra pestaña buscaremos "Cognitive Services", y crearemos una "Cuenta de varios servicios de Cognitive Services" para poder crear un "Servicio de Lenguaje".
![P8](images\P8.png)

- Nos pedirá los datos de siempre, además de una que otra cosa.
![P9](images\P9.png)

- En este caso usaremos "Google Sheets".
![P10](images\P10.png)

- Ahora dentro de la "Logic App", crearemos un nuevo paso, en el que buscaremos "sentiment" y para la "Clave de cuenta" y "URL del sitio", usaremos el "Servicio de Lenguaje" que creamos antes.
![P11](images\P11.png)

- Entonces nos pedirá como analizará (en este caso los tweets).
![P12](images\P12.png)

- Ahora conectaremos "Google Sheets", igual que cuando buscamos "Twitter", nos pedriá iniciar sesión.
![P13](images\P13.png)

- Buscaremos el archivo, hoja de cálculo y añadiremos los parámetros.
![P14](images\P14.png)

- En este caso también añadiremos "Microsoft Teams", para que los mensaje se manden a un grupo, en un canal en específico.
- Entonces si estamos contentos con el resultado, guardamos y ejecutamos.
![P15](images\P15.png)

- Si todo salió bien, quedaría algo parecido a esto.
![P16](images\P16.png)
![P17](images\P17.PNG)