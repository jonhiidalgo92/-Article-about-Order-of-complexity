

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


1. Taking into account the declaration of the integer (i) we can say that the order of complexity is (1), for the comparisons used it is (n + 1), and the increase in the variable that I feel is (n). The total of the sum of the complexity in this algorithm is said to be linear, since adding everything would give us 2n + 2 and by simplifying using arithmetic of the large O notation we would have a linear order (n).

2. The comparisons have a constant order of (1).

3. It would have a constant Order of (1).

4. It would have a constant order of (1).


The Summary to the sum of all constants and also adding the linear order of the cycle (for) is concluded at the end after using arithmetic that the order of complexity is O (n).


#### Complementary image to the understanding of the order of complexity as well as the number of iterations that it entails.
[Ordenes de Complejidad](https://www.campusmvp.es/recursos/image.axd?picture=Complejidad-Algoritmica.png)
