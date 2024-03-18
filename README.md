# Recursion_client

Parte cliente del proyecto 

El algoritmo aplicado en la función BuscarPacienteRecursivo se encarga de buscar pacientes cuyos nombres coincidan con un prefijo dado de manera eficiente en una lista ordenada de pacientes. Aquí está cómo funciona el algoritmo:

 El algoritmo utiliza un enfoque de "divide y vencerás" para buscar en la lista de pacientes. En cada iteración, divide la lista en mitades y busca en la mitad correcta basándose en el valor del nombre del paciente en el punto medio de la lista.

Recursión: La función BuscarPacienteRecursivo es recursiva. Comienza con una llamada inicial pasando la lista completa de pacientes. Luego, en cada paso recursivo, divide la lista en mitades y realiza la búsqueda solo en una de las mitades, basándose en si el nombre del paciente en el punto medio de la lista es menor o mayor que el prefijo dado.

Ordenamiento de la lista: Antes de realizar la búsqueda, la lista de pacientes se ordena alfabéticamente. Esto permite que el algoritmo realice búsquedas eficientes utilizando una técnica conocida como "búsqueda binaria".

Comparación de prefijos: En cada paso recursivo, el algoritmo compara el prefijo dado con el nombre del paciente en el punto medio de la lista. Si el nombre del paciente comienza con el prefijo dado, se agrega a la lista de resultados.

Ordenación de los resultados: Después de encontrar todas las coincidencias, la lista de resultados se ordena alfabéticamente utilizando el método Sort(). Esto garantiza que los resultados devueltos estén en orden alfabético.
