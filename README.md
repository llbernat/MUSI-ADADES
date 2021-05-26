# Propuesta de análisis

## Descripción de la serie temporal

Una única serie contenida en un fichero *csv* con estas características: 

- Magnitud: **potencia activa** acumulada en el período de muestreo
- Unidades: **VA**
- Intervalo temporal: **desde el 1 de abril de 2019 al 1 de abril de 2021** (ambos inclusive)
- Número de muestras: *2 al día*, una a las 00:00h y otra a las 12:00h UTC
- Número de campos: *3*. Descritos en el siguiente apartado

### Descripción de los campos

A continuación describimos los tres campos que componen la serie: 

- Campo 1: 
  - Nombre: 'Series'
  - Tipo: alfanumérico con el literal `Potència activa`
- Campo 2:
  - Nombre: 'Time'
  - Tipo: marca de tiempo (*timestamp*) conforme con el formato XXXX de la RFC9999
- Campo 3:
  - Nombre: 'Value'
  - Tipo: numérico entero positivo
