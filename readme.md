# iBlock Energy Monitor

Proyecto que permite conectar un sensor de voltaje y corriente no invasivos a un Arduino a través del conector estándar iBlock. 

Este sistema se desarrolló para experimentar con la medición de corriente, voltaje, potencia en corriente alterna, tal como se muestra en el sistema __Open Energy Monitor__.

Para mayor información de este proyecto, recomendamos visitar:

* https://learn.openenergymonitor.org/


## Periféricos y características

* Conector estándar de 10 pines IDC-10 con distribución de conector iBlock
* Conector jack tipo barril (para plug invertido) permite conectar sensor de voltaje (transformador)
* Conector tipo bornera permite conectar sensor de voltaje (transformador)
* Conector jack de 3.5 mm
* Circuitos de polarización para preparar la señal para la entrada analógica
* Se puede llevar la señal del sensor de voltaje a los pines A0 y A2
* Se puede llevar la señal del sensor de corriente a los pines A1 y A3
* Circuito impreso con tamaño estándar de 5 cm
* Se recomienda usar el sensor de corriente SCT-013-000
* Se requiere un transformador de sensado de voltaje

## Contenido del repositorio

1. __root__ - Archivos fuente de EAGLE para esta placa
2. __/documents__ - Documentación adicional, hojas de datos de componentes e instrucciones de ensamble
3. __/production__ - Histórico de gerbers enviados a producción
4. __/extras__ - Dibujos técnicos, hardware de montaje adicional y diseños de accesorios relacionados
4. __/firmware__ - Si existe el firmware de prueba o definitivo de esta placa

## Versiones del Hardware

* 1.0 - Versión inicial