7# Iván Quirós Chavarría
# B55626
# Laboratorio 5

# sistemas M/M/1
## Según la información dada en el problema de ejemplo, Se procedió al cálculo de del parametro v, utilizamos como referencía a valores P = 1 y una tasa de arribo de 2.
## Lo que nos da un valor de v = 20/9, aproximadamente 2.22222.
## Se varió en el código el parámetro nu o parámetro de servicio, (20/9)/60.
## cambio de frecuencias por ocurrencias

## La asignación mencionaba que la administración del servicio desea un servidor no vacío por más del 10% del tiempo, pero análizando un poco se puede entender cel 10 no vacío como ## 90% o más atendiendo, por lo que en el código se cambia la condición de que "fraccion <= 0.01" por "fraccion >= 0.9". 
