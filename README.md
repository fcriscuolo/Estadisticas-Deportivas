# Estadísticas Deportivas

## Descripción

Se proveen dos archivos de texto plano que contienen, por línea, la información de la anotación de los partidos y de los equipos con el siguiente formato:

**partido.log**
```
JUGADOR(APELLIDO),TIPO DE ANOTACIÓN
```

**equipo-X.txt**
```
NOMBRE APELLIDO
```

## Objetivo

Realizar un programa tipo script en NodeJS que muestre:
* el resultado final del partido, teniendo en cuenta las reglas de anotación de puntos del deporte; 
* el nombre completo del jugador que haya hecho la mayor cantidad de puntos;
* la distribución de puntos por tipo de anotación.

**NOTA**: se considera un _bonus_ si la información es presentada en un formato serializable.

## Reglas de anotación de puntos

* BASKET: `DOBLE` = 2 puntos; `TRIPLE` = 3 puntos;
* RUGBY: `TRY`= 5 puntos; `CONVERSION` = 2 puntos
