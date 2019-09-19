

## ORDEN DE COMPLEJIDAD EN LOS ALGORITMOS:
In each of the different orders varies according to the number of cycles, sentences and given the arithmetic that can be given when making some kind of algorithm. There are currently several types of competitions where people from different parts of the world are given a type of problem and are based on both the numerical ability understood as logical-mathematical as well as the factor of the number of iterations that the algorithm does See the platform [HackerEarth](https://www.hackerearth.com/challenges/).



#### The following algorithm is made in c ++ which has a linear order:
[Code of Algorithm](https://github.com/jonhiidalgo92/-Algorithm/)


void MenorArreglo(int m[], int n)
{
		 int actual = m[0];
			for(int i = 1; i < n-1 ; i++) (#1 )
			{
					if(actual > m[i]) (#2 )
			{
			actual = m[i];  (#3 )
			}
	}
cout<<actual<<endl;  (#4 )
}


1. Tomando en cuenta la declaracion del entero (i) podemos decir que el orden de complejidad es (1), para las comparaciones utilizadas es (n+1), y el aumento de la variable que viene siento (n). El total de la suma de la complejidad en este algoritmo se dice que es lineal, ya que sumando todo nos daría 2n+2 y al simplificar utilizando aritmética de la notación O grande nos quedaría que tiene un orden lineal (n).

2. Las comparaciones tiene un orden constante de (1).

3. Tendría un Orden constante de (1)

4. Tendría un orden constante de (1)


El Resumen a la suma de todas las constantes y sumando también el orden lineal del ciclo (for) se tiene como conclusión al final después de emplear aritmética que el orden de complejidad es de O(n).

Imagen Complementaria al entendimiento del orden de complejidad como también el numero de iteraciones que conlleva.

[Mas Informacion Acerca de los diferentes Ordenes de Complejidad](https://www.campusmvp.es/recursos/image.axd?picture=Complejidad-Algoritmica.png)
