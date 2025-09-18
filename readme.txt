# Prueba de Carga con Apache JMeter - FakeStoreAPI

## Descripción
Plan de prueba en Apache JMeter para evaluar el endpoint de autenticación de FakeStoreAPI.
Datos de usuario parametrizados desde CSV.

## Datos de Entrada
Archivo: usuarios.csv
Formato:
user,passwd
donero,ewedon
kevinryan,kev02937@
johnd,m38rmF$
derek,jklg*_56
mor_2314,83r5^_

## Configuración del Escenario
- Herramienta: Apache JMeter 5.6.3
- Carga objetivo: 20 TPS
- Tiempo de respuesta máximo: 1.5 s
- Tasa de error aceptable: < 3%