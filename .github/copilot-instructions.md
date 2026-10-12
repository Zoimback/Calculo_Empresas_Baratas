Este proyecto trata de identificar empresas a traves de yfinance cuya valoracion actual a dia de hoy este relativamente barata basandode en calculos matemáticos.

Se trata de poder vencer al índice y obtener el mayor rendimiento posible para el usuario y su cartera.


# Desarrollo

## GIT
Antes de realizar cualquier tipo de accion tienes que comprobar en que rama estas. Si estás en main deberas generar una rama llamada feature/{featurename}.X.Y donde X es la version actual del programa e Y es el numero de cambios realizados en esa versión. 

Cuando se termine el desarrollo subiras el código y generaras una PR hacia main describiendo los cambios a traves del mcp de github y usando unicamente las herramientas delimitadas para ello. El commit deberá llevar {featurename}-X.Y 

## PYTHON
El script estará completamente desarrollado en python. 

Librerias permitidas:
  - Pandas
  - yfinance
  - PyTest
  - Numpy

Para desarrollar en python deberas consultar las instrucciones:
 - Desarrollo general: `.github\instructions\python.instruction.md`
 - Desarrollo test: `.github\instructions\python_test.instruction.md`

Para los test, deben tener una cobertura mínima del 0,80.


