# PROMEDIO EDAD DE GESTACION

Equipo E4· Análisis de Datos Intermedio · Estud-IA (Capa 2)

## Brief v1

| Campo | Respuesta |
|---|---|
| Usuario y decisión | SECRETARIA DE SALUD, SE ACTUALIZA CADA TRES MESES |
| Pregunta | ¿Cuales es el rango de edad  de las mujeres en estado de gestación del municipio de envigado? |
| Fuente con API |https://www.datos.gov.co/resource/udqu-ifxr.json?$limit=5.  
https://www.datos.gov.co/resource/4zs6-n5cw.json?$limit=5    |
| Qué representa una fila | Los datos reales ingresados, ejemplo: la edad de las mujeres. |
| Campo que la identifica | edad_madre |
| Cada cuánto se actualiza | cada tres meses |
| Dato a confirmar |  |
| Tres indicadores | 1.Numero de madres gestante. 
2. Rango de edad |
| Terminó bien si… | Arroja el resultado por rangos edad y da el total de mujeres en estado de gestación. |
| No vamos a construir | |

## Contrato de datos

- Una fila es: la casilla que guarda los datos reales
- La identifica: el id principal 
- Si llega una fila repetida: se limpia
- Si falta un campo: hay un error en la recolección de la información.

## Bitácora de decisiones

| Fecha | Decisión | Por qué |
|---|---|---|
| | | |

## Reglas del repositorio

- Es público: nada de datos personales, contraseñas, tokens ni llaves.
- Las credenciales van en un archivo `.env`, que Git ignora (ver `.gitignore`). `.env.example` muestra qué variables hacen falta, sin valores.
- Cada commit explica en su mensaje qué se decidió y por qué.
