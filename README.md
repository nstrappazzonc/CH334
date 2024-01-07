# CH334

Este es un simple IC para construir un HUB USB 2.0 de muy bajo coste, diseñado y fabricado en china por [Jiangsu Heng Qin Ltd. (WCH)](http://www.wch-ic.com). De momento nos vamos a centrar en el CH334U que tiene unas prestaciones muy versátiles, entre ellas destacan las siguientes:

- HUB USB 2.0 de 4 puertos de velocidad máxima de 480Mbps.
- Compatible con USB 1.1
- Posibilidad de configurar el VID y PID mediante un EEPROM externo.
- Adicionalmente tiene detección de GANG, soporta el modo MTT.
- Soporta ESD de hasta 6KV (Clase 3A)

![](https://github.com/nstrappazzonc/CH334/blob/main/img/minimal_protoboard.jpg?raw=true)

En la imagen no mostramos el resto de los puertos USB para evitar de complicar la imagen evitando la simple percepción del circuito mínimo.

Puedes conseguir los IC en la tienda oficial de [AliExpress](https://wchofficialstore.es.aliexpress.com/store/1100367542) o en [LCSC](https://www.lcsc.com).

## Componentes

Use los siguientes componentes para construir el circuito mínimo:

- Un IC CH334U.
- Oscilador de cristal de 12Mhz de 12-20pF 20ppm.
- Condensador de 0.1uF (Código: 104, Cantidad: 2).
- Condensador de 1uF (Código: 105, Cantidad: 1).
- Condensador de 10uF (Código: 106, Cantidad: 1).
- Diodo 1N4001.

## Esquema minimo del circuito

![](https://github.com/nstrappazzonc/CH334/blob/main/img/minimal_schematic.jpg?raw=true)

## Consejos

Haga uso de las siguientes consideraciones para construir y verificar el circuito mínimo con el fin de descartar cualquier problema. Algunos comentarios son de mi propia experiencia y otros son obtenidos del [foro oficial](https://www.wch.cn/bbs/search?q=CH334&page=1) que está en chino.

- Asegúrese de tener un cable USB que funcione, no solo el VCC y el GND, sino también D+ y D-.
- Para el CH334U, mida con un voltímetro los siguientes pines: 13, 17, 21, 26. Los cuatro deben tener alrededor de 3.3v.
- El oscilador de cristal de 12Mhz con las siguientes características: entre 12pF y 20pF y 20ppm.

## Proyectos relacionados

- [CH340 - USB 2.0 to Serial](https://github.com/nstrappazzonc/CH340)
- [CH552 - 8-bits MCU - 8051](https://github.com/nstrappazzonc/CH552)
- [CH9141 - Bluetooth Serial Transparent](https://github.com/nstrappazzonc/CH9141)
