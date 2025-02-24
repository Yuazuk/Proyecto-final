# Proyecto-final
Proyecto final puntos extras, realizado por la estudiante Yuli Azucena Callejas Barrientos con número de carnet 25003031.

El programa es un cotizador automático que calcula el precio de una cotización de seguro basado en los factores, que se detallan a continuación.  

Definición de Variables Iniciales:

Precio base: Se establece el precio base de la cotización, en este caso, Q.2000.

Valores de los recargos: Se definen los porcentajes de recargo basados en la edad del asegurado, la edad del cónyuge, la cantidad de hijos, la cantidad de propiedades y los ingresos mensuales.

Recopilación de Datos del Usuario:

Se solicitan al posible cliente los siguientes datos personales, para poder aplicar los recargos a la cotización. 

Nombre: Se solicita al usuario o asegurado que ingrese su nombre.

Edad: Se pregunta al usuario cuántos años tiene y se convierte esa entrada en un número entero, la edad debe de ser mayor a 18 años.

Estado civil: Se pregunta si el usuario está casado.

Edad del cónyuge: Si el usuario está casado, se solicita la edad del cónyuge y se convierte en un número entero.

Hijos: Se pregunta si el usuario tiene hijos y, si es así, se solicita la cantidad de hijos y se convierte en un número entero.

Propiedades: Se pregunta cuántas propiedades posee el usuario o asegurado. 

Ingresos: Se solicita al usuario que ingrese la cantidad de sus ingresos mensuales en quetzales y se convierte en un número decimal.

Realización del cálculo de recargos:

Recargo por edad del asegurado y si en dado caso tiene cónyuge, basado en las edades, se calcula un recargo y se suma al total de recargos.

	18 a 24 años: Recargo del 10% del precio base.
	25 a 49 años: Recargo del 20% del precio base.
	50 años o más: Recargo del 30% del precio base.
	Los recargos se aplican tanto al asegurado como al cónyuge por separado.

Recargo por cantidad de hijos: Se calcula un recargo del 20% sobre el precio base  basado en la cantidad de hijos,  y se suma al total de recargos.

Recargo por propiedades: Se calcula un recargo del 35% de la cotización, basado en la cantidad de propiedades y se suma al total de recargos.

Recargo por ingresos: Se calcula un recargo del 5% sobre el salario del asegurado, basado en los ingresos mensuales del usuario y se suma al total de recargos.



Cálculo del Precio Final:

Se suma el total de recargos al precio base para obtener el precio final de la cotización.

Resultados:

Se muestran tres alertas al usuario:

El nombre del asegurado.

El recargo total en quetzales.


¿Qué se podría mejorar sobre el programa?


Se podría hacer una validación del ingreso de información del usuario que sean válidas y dentro de los rangos esperados,  que las edades sean ingresadas con números  positivos y que la cantidad de propiedades y los ingresos también sean valores válidos.

Con el propósito de poder implementar un manejo de errores adecuado para capturar y manejar posibles excepciones o entradas inválidas.

Se puede dividir el código en funciones más pequeñas y manejables. Por ejemplo, crear funciones específicas para calcular recargos por edad, cónyuge, hijos, propiedades e ingresos.

Optimización del Cálculo de Recargos: Usar estructuras de datos más eficientes para manejar los recargos y evitar duplicación de código.

Dar mensajes informativos, proveyendo al usuario de mensajes informativos y visuales mientras ingresan los datos, para que tengan claro qué información se requiere.
