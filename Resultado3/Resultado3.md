#Hallazgo 3

#Personas que padecerán de enfermedades respiratorias base-linea (crónicas)

Proceso: Para elaborar el proceso se ha importado los datos del dataset respiratory.csv
y se ha desarrollado lo siguiente:

1. Retrieve respiratorias, la base de datos.
2. Numerical to Binomial, para convertir los datos enteros a binomial (true or false).
3. Set Role, con las siguientes propiedades attribute name = baseline y target role = label.
4. Validation, para obtener las predicciones a su vez se divide en subprocesos:

	* 4.1 Logistic, Creación del modelo
	* 4.2 Apply Model, aplicación del modelo
	* 4.3 Performance, Evalución del modelo

#Conclusiones

El último resultado nos muestra una estadística predictiva del 64,20 % de presición; indicando que se incrementara el número de personas que padeceran alguna enfermedad respiratoria crónica dentro de un rango de 7.04 % a 8.54 %.
