# Módulo 2: Conceptos fundamentales

En este módulo vamos a tocar los conceptos fundamentales de blockchain:

- Descentralización
- Ledgers
- Consensos
- Peer-to-peer networking
- Criptografía

Estos conceptos primitivos cuando trabajan juntos son la escencia de blockchain.

## Descentralización

La descentralización es el proceso de dispersar funciones, poderes, personas o cosas fuera de una ubicación o autoridad central.
En la cadena de bloques, la descentralización se refiere a la transferencia del control y la toma de decisiones de una entidad centralizada (individuo, organización o grupo de la misma) a una red distribuida.

### Beneficios de la descentralización

#### Entorno confiable

En una red de blockchain descentralizada, nadie tiene que conocer ni confiar en nadie más. Cada miembro de la red tiene una copia de los mismos datos en forma de un "libro mayor distribuido". Si este libro se modifica o se corrompe de alguna manera será rechazado por la mayoría de miembros de la red.

#### Mejora la reconciliación de datos

Las empresas comparten datos e información con sus socios. Esta información se almancena en los silos de datos de cada parte y solo aparecen nuevamente cuando se necesita transferirse de manera descendente.

Cada vez que esta transferencia de datos se realiza existe la posibilidad de perdida de datos o de que entren datos incorrectos.

Teniendo un almacen de datos descentralizado, cada entidad tiene acceso a una vista compartida de los datos en tiempo real.

#### Reduce los puntos de debilidad

Ayuda a reducir puntos débiles de los sistemas en los que puede existir una dependencia excesiva de actores específicos. Estos puntos débiles podrían provocar fallos en el sistema, como la falta de prestación de servicios prometidos o un servicio ineficiente debido al agotamiento de los recursos, a interrupciones periódicas, a cullos de botella, a la falta de incentivos para un buen servicio o a la corrupción.

#### Reduce los puntos de debilidad

Ayuda a optimizar la distribución de los recursos para que los servicios prometidos se preseten con un mejor rendimiento y coherencia, así como una menor probabilidad de errores.

### Comparación de descentralización

|                    Característica                   |        Centralizada        |        Distribuida         |       Descentralizada      |
|----------------------------------------------------|----------------------------|----------------------------|----------------------------|
| Recursos de red/hardware                           | Mantenidos y controlados por una sola entidad en una ubicación centralizada | Distribuidos en varios centros de datos y geografías; propiedad del proveedor de red | Los miembros de la red poseen y comparten los recursos; son difíciles de mantener ya que nadie es propietario de ellos |
| Componentes de la solución                        | Mantenidos y controlados por una entidad central | Mantenidos y controlados por el proveedor de soluciones | Cada miembro tiene exactamente la misma copia del libro mayor distribuido |
| Datos                                              | Mantenidos y controlados por una entidad central | Por lo general, son propiedad del cliente y él los administra | Solo se agregan mediante consenso grupal |
| Control                                            | Controlado por la entidad central | Por lo general, una responsabilidad compartida entre el proveedor de red, el proveedor de soluciones y el cliente | Nadie es propietario de los datos y todos son propietarios de los datos |
| Punto único de error                              | Sí                         | No                         | No                         |
| Tolerancia a errores                              | Baja                       | Alta                       | Extraordinariamente alta  |
| Seguridad                                          | Mantenidos y controlados por una entidad central | Por lo general, una responsabilidad compartida entre el proveedor de red, el proveedor de soluciones y el cliente | Aumenta a medida que aumenta el número de miembros de la red |
| Rendimiento                                       | Mantenidos y controlados por una entidad central | Aumenta a medida que escalan vertical y horizontalmente los recursos de red/hardware | Disminuye a medida que aumenta el número de miembros de la red |
| Ejemplo                                           | Sistema ERP               | Computación en la nube     | Cadena de bloques         |

### Un ejemplo del mundo real

Contura Energy, uno de los principales proveedores de carbón con sede en EE. UU., ha dependido muchos años de un sistema anticuado de cartas de crédito para gestionar sus pagos de comercio internacional. Estas cartas de crédito, emitidas por un banco intermediario en nombre de su cliente, sirven como garantía de pago para los compradores. Si bien este sistema es fiable, se acciona de forma manual, es lento y altamente ineficiente.

Contura Energy comprende la importancia y el valor de digitalizar y automatizar el proceso de sus cartas de crédito. Sin embargo, el desafío al que se enfrentan es permitir la confianza y la verificación mutuas entre vendedores y compradores. Están trabajando con AWS en una innovación descentralizada basada en la cadena de bloques que proporciona un sistema más eficiente, económico y menos arriesgado para administrar los pagos del comercio internacional. Esta solución descentralizada también aumenta la transparencia, ya que brinda a todas las partes visibilidad en tiempo real de los datos y la documentación.

[Más información sobre como Contura Energy utilizá Blockchain](Contura Energy - Forbes EN)

## Libros mayores o ledgers distribuidos

Es un sistema electrónico para registrar información que es ejecutada por más de una entidad.
Esta nos permite almacenar y usar datos que pueden ser descentralizados (almacenados en varios lugares) y distribuidos (concectados y, por lo tanto pueden comunicarse) tanto de forma privada o pública.

Se requiere una red de igual a igual, así como algoritmos de consenso para garantizar la replicación entre los nodos. Una forma de diseño de libro mayor distribuido es el sistema blockchain, que puede ser público o privado.

### DLT

Es simplemente una base de datos que gestionan varios participantes y no está centralizada. No existe una autoridad central que ejerza de árbitro y verificador.

El registro distribuido aumenta la transparencia, dificultando cualquier tipo de fraude o manipulación.

## Comprendiendo mecanismos de concenso

"Consensus" es un conjunto de reglas o protocolos que permiten a sistemas distribuidos agregar mutuamente un valor para un estado o información distribuida.

Son utiles para verificar las transacciones y mantener la seguridad de la cadena de bloques subyacente.

Existen diferentes tipos de mecanismos de consensos los cuales diferentes aspecto con sus ventajas y desventajas.

La Prueba de trabajo (PoW) y la Prueba de participación (PoS) son dos de los mecanismos de consenso más utilizados.

### Tipos de mecanismos de consenso

![Diferentes tipos de mecanismos de concensos - Crypto.com](image.png)

## Funciones hash criptograficas

### Función hash



[Contura Energy - Forbes EN]: https://www.forbes.com/sites/amazonwebservices/2019/12/10/improving-international-trade-with-blockchain/?sh=3f05e4391254