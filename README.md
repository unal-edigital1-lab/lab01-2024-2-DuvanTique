# lab01- sumador 
### Nombre: Duvan Stiven Tique Osorio

## informe de laboratorio 
### sumador 
#### modulo sum1bcc vs modulo sum1bcc_primitive
En ambos modulos de implementa un sumador implementadon varias puertas lógicas, la principal diferencia es que en el modulo **sum1bcc_primitive** se crean las compuertas lógicas una por una y se interconectan para generar la función de suma por medio del codigo, mientras que en el modulo **sum1bcc** se realiza la operacion utilizando algebra booleana (st  = 	A+B+Ci) y se guarda el resultado en la variable st la cual puede almacenar dos bits de información.
### simulación:
Como se puede observar en los siguientes archivos la salida **S** es la misma ya que se implemento la misma función de dos formas diferentes.
#### modulo sum1bcc:
[sum1bcc_simulacion.pdf](https://github.com/user-attachments/files/17997608/sum1bcc_simulacion.pdf)
#### modulo sum1bcc_primitive:
[sum1bcc_primitive_simulacion.pdf](https://github.com/user-attachments/files/17997626/sum1bcc_primitive_simulacion.pdf)

### Implementación
Utilizando 3 interruptores para controlar las entradas(A,B,Ci) se realiza la operación de suma dandonos las siguientes posibilidades
| A | B | Cin | S | Cout |
|---|---|-----|---|------|
| 0 | 0 |  0  | 0 |  0   |
| 0 | 0 |  1  | 1 |  0   |
| 0 | 1 |  0  | 1 |  0   |
| 0 | 1 |  1  | 0 |  1   |
| 1 | 0 |  0  | 1 |  0   |
| 1 | 0 |  1  | 0 |  1   |
| 1 | 1 |  0  | 0 |  1   |
| 1 | 1 |  1  | 1 |  1   |

Entonces se le asigna un led a la salida **S** y uno a la salida **Cout**, si este esta apagado su valor es **0** y si esta encendido su valor sera de **1**.

https://github.com/user-attachments/assets/f437c955-92f8-4cf8-a903-cc769d3f5670

