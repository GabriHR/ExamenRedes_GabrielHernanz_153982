# ExamenRedes_GabrielHernanz_153982

---

## 1. El Mural de las Siete Capas
Te adentras en la sala principal del templo y descubres un gran mural compuesto por siete franjas horizontales superpuestas, decoradas con símbolos y jeroglíficos. Cada franja representa un nivel diferente en un ritual de comunicación. Los sabios de esta civilización entendían que un mensaje debía pasar por varias etapas desde su origen hasta su destino, refinándose o traduciendo su forma en cada nivel de la pirámide comunicativa.

Pregunta: ¿Qué representa el mural de las siete capas en términos de las redes de comunicación modernas? Identifica brevemente cada capa y explica cómo se relaciona este antiguo “modelo” con el proceso de comunicación de datos actual.

## Solución:
El mural de las siete capas puede interpretarse como una analogía del Modelo OSI (Open Systems Interconnection), que es un modelo conceptual utilizado para entender y diseñar redes de comunicación modernas. Este modelo divide el proceso de comunicación de datos en siete capas distintas, cada una con funciones específicas. A continuación, se identifican y explican brevemente cada una de estas capas:

![Mural de las siete capas](https://media.licdn.com/dms/image/v2/D4D12AQFLYO1ZO8uLwQ/article-inline_image-shrink_1000_1488/article-inline_image-shrink_1000_1488/0/1727106935790?e=2147483647&v=beta&t=xWebJ_nCQkcdaqfcbittWy8X-TgY1vBEDseOs8gmJA4)
- Capa Física: Representa el nivel más básico de la comunicación, donde se transmiten los bits a través de medios físicos como cables o señales inalámbricas. En el mural, esta capa podría simbolizar la base tangible de la comunicación.

- Capa de Enlace de Datos: Se encarga de la transferencia de datos entre dos nodos conectados directamente, gestionando errores y control de flujo. En el mural, esta capa podría representar la conexión directa y la integridad de los datos.


- Capa de Red: Gestiona el direccionamiento y el encaminamiento de los datos a través de múltiples redes. En el mural, esta capa podría simbolizar la ruta que sigue el mensaje para llegar a su destino.


- Capa de Transporte: Asegura la transferencia confiable de datos entre sistemas finales, gestionando la segmentación y reensamblaje de los datos. En el mural, esta capa podría representar la fiabilidad y la integridad de la comunicación.


- Capa de Sesión: Establece, gestiona y termina las sesiones de comunicación entre aplicaciones. En el mural, esta capa podría simbolizar la gestión de las interacciones y el mantenimiento del contexto de la comunicación.


- Capa de Presentación: Traduce los datos entre el formato de la red y el formato comprensible por la aplicación, incluyendo la encriptación y la compresión. En el mural, esta capa podría representar la transformación y el refinamiento del mensaje.


- Capa de Aplicación: Proporciona servicios de red directamente a las aplicaciones del usuario, como correo electrónico, transferencia de archivos y navegación web. En el mural, esta capa podría simbolizar la interacción final y el uso del mensaje por parte del destinatario.


Este antiguo "modelo" se relaciona con el proceso de comunicación de datos actual al mostrar cómo un mensaje debe pasar por varias etapas de procesamiento y refinamiento antes de llegar a su destino, similar a cómo los datos se procesan a través de las capas del Modelo OSI en las redes de comunicación modernas.

---

## 2. Los Dos Pergaminos del Mensajero

En una cámara oculta encuentras dos pergaminos polvorientos.

- El **primer pergamino** describe el **Ritual del Mensajero Confiable**: antes de entregar un mensaje, el mensajero realiza un saludo de tres pasos con el receptor para asegurarse de que ambos estén listos, luego entrega el mensaje y espera una confirmación de recibido. Si la confirmación no llega, reintenta el envío.

- El **segundo pergamino** narra el **Ritual del Mensajero Veloz**: un mensajero que sale disparado a entregar mensajes sucesivos sin aviso previo ni asegurarse de la recepción, cubriendo la mayor distancia en el menor tiempo, aunque a veces los mensajes se pierdan en el camino.

### Pregunta:
Interpreta los dos rituales descritos. ¿A qué protocolos de comunicación actuales equivalen el mensajero confiable y el mensajero veloz? Compara sus características, explicando las ventajas y desventajas de cada enfoque en redes modernas.



## Solución:

Los dos rituales descritos en los pergaminos pueden interpretarse como analogías de dos protocolos de comunicación actuales: **TCP (Transmission Control Protocol)** y **UDP (User Datagram Protocol)**.


### Comparación de Protocolos

| Característica          | **TCP - Mensajero Confiable** | **UDP - Mensajero Veloz** |
|------------------------|----------------------------|--------------------------|
| **Tipo de Conexión**   | Orientado a conexión (requiere establecer una conexión antes de enviar datos). | No orientado a conexión (envía datos sin establecer conexión). |
| **Fiabilidad**         | Garantiza la entrega de los datos y su orden correcto. | No garantiza la entrega ni el orden de los datos. |
| **Confirmación**       | Usa acuses de recibo (ACK) para confirmar la entrega de datos. | No hay confirmación de entrega. |
| **Reenvío de Datos**   | Si un paquete se pierde, TCP lo reenvía automáticamente. | No hay reenvío de paquetes perdidos. |
| **Control de Flujo**   | Regula la cantidad de datos enviados para evitar congestión. | No hay control de flujo. |
| **Velocidad**         | Más lento debido a la verificación de datos y reenvíos. | Más rápido debido a la menor sobrecarga. |
| **Uso Común**         | Transferencia de archivos, correos electrónicos, navegación web. | Streaming de video, juegos en línea, VoIP. |


### Ventajas y Desventajas

| Protocolo | Ventajas | Desventajas |
|-----------|---------|-------------|
| **TCP** | - Alta fiabilidad.<br>- Garantiza el orden de los datos.<br>- Asegura la entrega. | - Mayor sobrecarga.<br>- Menor velocidad por los controles de flujo y errores. |
| **UDP** | - Mayor velocidad y eficiencia.<br>- Menor sobrecarga en la red. | - No garantiza la entrega ni el orden.<br>- Pérdida de datos posible. |


### Conclusión

El **Mensajero Confiable** representa a **TCP**, asegurando la entrega y el orden de los datos, ideal para aplicaciones que requieren alta fiabilidad.  
El **Mensajero Veloz** representa a **UDP**, priorizando la velocidad sobre la fiabilidad, siendo útil en aplicaciones donde la pérdida ocasional de datos es aceptable.

Cada protocolo tiene su propio uso dependiendo de las necesidades de la red. 🚀

---

## 3. El Enigma de las Subredes
Avanzando por un pasillo, encuentras una losa de piedra con inscripciones que parecen ser direcciones numéricas. Una inscripción cuenta: "Nuestro reino digital tenía la dirección sagrada 192.168.50.0. Los cuatro grandes gremios de la ciudad exigían su propio distrito en la red, todos de igual tamaño". Junto a esto, ves un diagrama borroso de algo que parecen ser subredes emanando de la dirección principal, cada una con su propio identificador.

Pregunta: Descifra el enigma de la losa. Si la antigua red usaba la dirección 192.168.50.0 como base y necesitaba dividirse en 4 subredes de igual tamaño (una para cada gremio), ¿qué máscara de subred habrían utilizado los antiguos para lograrlo? ¿Cuántas direcciones de host (utilizables) tendría cada subred resultante? Explica brevemente tu razonamiento al calcular la máscara.

## Solución:

Para resolver el enigma de la losa y dividir la red 192.168.50.0 en 4 subredes de igual tamaño, debemos calcular la máscara de subred adecuada.

1. Determinar la cantidad de bits necesarios para las subredes
Para dividir una red en 4 subredes, necesitamos 2 bits adicionales en la máscara de subred, ya que 2^2 = 4.

2. Calcular la nueva máscara de subred
La dirección IP 192.168.50.0 pertenece a una red de clase C, cuya máscara de subred por defecto es 255.255.255.0 (o /24 en notación CIDR). Añadiendo 2 bits para las subredes, la nueva máscara de subred será /26.

3. Determinar las direcciones de host utilizables en cada subred
Con una máscara de /26, cada subred tendrá 2^(32-26) = 2^6 = 64 direcciones. De estas, 2 direcciones se reservan para la dirección de red y la dirección de broadcast, dejando 64 - 2 = 62 direcciones de host utilizables por subred.

### Resultado
- **Máscara de subred**: 255.255.255.192 (o /26 en notación CIDR)
- **Direcciones de host utilizables por subred**: 62

### Explicación
Al dividir la red 192.168.50.0/24 en 4 subredes, cada subred tendrá 64 direcciones (2^6), de las cuales 62 son utilizables para hosts. La máscara de subred resultante es 255.255.255.192, que en notación CIDR es /26.

### Subredes resultantes
1. **Subred 1**: 192.168.50.0/26 (Hosts: 192.168.50.1 - 192.168.50.62)
2. **Subred 2**: 192.168.50.64/26 (Hosts: 192.168.50.65 - 192.168.50.126)
3. **Subred 3**: 192.168.50.128/26 (Hosts: 192.168.50.129 - 192.168.50.190)
4. **Subred 4**: 192.168.50.192/26 (Hosts: 192.168.50.193 - 192.168.50.254)

Cada subred tiene 62 direcciones de host utilizables.

---

## 4. La Encrucijada de las Rutas
Llegas a una encrucijada dentro de las ruinas: cuatro caminos diferentes se extienden hacia distintas aldeas en los alrededores de la ciudad antigua. En el centro, un tótem tallado muestra flechas apuntando hacia cada camino, con inscripciones de destinos y distancias. Notas que algunas flechas parecen fijas e inmutables (talladas en la piedra), mientras que otras son piezas móviles que pudieron reorientarse si se abría o cerraba algún camino en el pasado. Este tótem se asemeja a un antiguo dispositivo de enrutamiento que dirigía el tráfico de datos por el camino adecuado.
   
Pregunta: ¿Qué concepto moderno de redes representa el tótem con flechas de la encrucijada? Explica qué es una tabla de enrutamiento y cómo funciona en un router actual. Además, interpreta la diferencia entre las flechas talladas en piedra y las flechas móviles en términos de enrutamiento estático vs. enrutamiento dinámico en redes.

## Solución:
El tótem con flechas de la encrucijada representa el concepto moderno de una **tabla de enrutamiento** en redes. Una tabla de enrutamiento es una base de datos utilizada por los routers para determinar el mejor camino para enviar paquetes de datos a su destino. Cada entrada en la tabla de enrutamiento contiene información sobre una red de destino y el siguiente salto (next hop) que debe tomar el paquete para llegar a esa red.

### Tabla de Enrutamiento
Una tabla de enrutamiento en un router actual contiene varias columnas, entre las cuales se incluyen:
- **Red de destino**: La dirección de la red a la que se dirige el paquete.
- **Máscara de subred**: Define el tamaño de la red de destino.
- **Puerta de enlace (Gateway)**: La dirección IP del siguiente salto hacia la red de destino.
- **Interfaz de salida**: La interfaz del router a través de la cual se debe enviar el paquete.
- **Métrica**: Un valor que indica la preferencia del camino; los caminos con métricas más bajas son preferidos.

### Enrutamiento Estático vs. Enrutamiento Dinámico
- **Enrutamiento Estático**: Representado por las flechas talladas en piedra. En este tipo de enrutamiento, las rutas son configuradas manualmente por un administrador de red y no cambian a menos que se modifiquen manualmente. Es simple y consume menos recursos, pero no se adapta automáticamente a cambios en la red, como fallos de enlace.

- **Enrutamiento Dinámico**: Representado por las flechas móviles. En este tipo de enrutamiento, las rutas se ajustan automáticamente en respuesta a cambios en la red. Los routers utilizan protocolos de enrutamiento dinámico (como OSPF, RIP, EIGRP) para intercambiar información de enrutamiento y actualizar sus tablas de enrutamiento en tiempo real. Esto permite una mayor flexibilidad y adaptabilidad, pero consume más recursos y puede ser más complejo de configurar.

### Funcionamiento de una Tabla de Enrutamiento
1. **Recepción del Paquete**: El router recibe un paquete de datos en una de sus interfaces.
2. **Consulta de la Tabla de Enrutamiento**: El router consulta su tabla de enrutamiento para encontrar la mejor ruta hacia la red de destino del paquete.
3. **Determinación del Siguiente Salto**: Basado en la información de la tabla, el router determina la puerta de enlace y la interfaz de salida.
4. **Reenvío del Paquete**: El router reenvía el paquete a través de la interfaz de salida hacia la puerta de enlace indicada.

En resumen, el tótem con flechas de la encrucijada es una analogía de una tabla de enrutamiento en un router moderno, con las flechas talladas en piedra representando rutas estáticas y las flechas móviles representando rutas dinámicas.

---

## 5. El Guardián de la Máscara Única

En la última sala del templo, frente a la salida, te encuentras con la estatua de un guardián con dos caras. Según una leyenda grabada en la base, este guardián protegía la ciudad oculta de los forasteros. Cuando un mensajero salía de la ciudad, el guardián reemplazaba su máscara por la suya propia, de modo que, para el mundo exterior, todos los mensajes parecían venir únicamente del guardián. Al regresar la respuesta, el guardián recordaba qué máscara original correspondía a cada mensaje y reenviaba la respuesta al habitante correcto dentro de la ciudad. Gracias a este ardid, la ciudad pudo ocultar la identidad de sus miembros y usar un único rostro para todas sus comunicaciones externas.

### Pregunta:
¿Qué técnica de redes moderna se refleja en la leyenda del Guardián de la Máscara? Nombra y describe brevemente este mecanismo, explicando cómo permite que múltiples dispositivos internos de una red compartan una única identidad (dirección) al comunicarse con el exterior, y menciona dos beneficios que brinda esta estrategia a las redes actuales.

---

## Solución:

La leyenda del Guardián de la Máscara refleja la técnica moderna de redes conocida como **NAT (Network Address Translation)**. NAT es un mecanismo que permite que múltiples dispositivos internos de una red compartan una única dirección IP pública al comunicarse con el exterior.

### Descripción de NAT

NAT funciona reemplazando las direcciones IP privadas de los dispositivos internos con una dirección IP pública única cuando los datos salen de la red local hacia Internet. Al recibir una respuesta, NAT recuerda la dirección IP privada original y reenvía la respuesta al dispositivo correcto dentro de la red.

---

### Funcionamiento de NAT

| Etapa | Descripción |
|-------|------------|
| **Salida de Datos** | Cuando un dispositivo interno envía datos a Internet, NAT reemplaza su dirección IP privada con la dirección IP pública de la red. |
| **Registro de la Traducción** | NAT guarda un registro de la dirección IP privada y el puerto de origen para cada conexión. |
| **Entrada de Datos** | Cuando la respuesta llega desde Internet, NAT utiliza el registro para traducir la dirección IP pública de vuelta a la dirección IP privada original y reenvía los datos al dispositivo correspondiente. |



### Beneficios de NAT

| Beneficio | Descripción |
|-----------|------------|
| **Conservación de Direcciones IP** | Permite que múltiples dispositivos compartan una única dirección IP pública, conservando direcciones IP. |
| **Seguridad** | Oculta las direcciones IP internas de la red, dificultando que dispositivos externos accedan directamente a los dispositivos internos. |



### Comparación Visual

| Característica | NAT |
|---------------|-----|
| **Dirección IP Pública** | Una única dirección IP pública compartida por múltiples dispositivos internos. |
| **Traducción de Direcciones** | Traduce direcciones IP privadas a una dirección IP pública y viceversa. |
| **Registro de Conexiones** | Mantiene un registro de las conexiones para reenviar las respuestas a los dispositivos correctos. |
| **Conservación de IPs** | Conserva direcciones IP al permitir que múltiples dispositivos usen una sola dirección IP pública. |
| **Seguridad** | Mejora la seguridad al ocultar las direcciones IP internas de la red. |


En resumen, **NAT permite que múltiples dispositivos internos de una red compartan una única identidad (dirección IP pública)** al comunicarse con el exterior, proporcionando beneficios como la **conservación de direcciones IP** y una **mayor seguridad**.
