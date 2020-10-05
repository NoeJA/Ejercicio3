# Pseudocódigo ciclos for
#Ejercicio 1
Input
M= arreglo con n elementos
Output
Multiplicación de todos los elementos entre si

m=0
For cada elemento en M:
  m=m*M[i]
  
  return m
  
  ** Por el for, y despreciando los demás componentes, es de longitud, n, y por tener que ejecutar el ciclo completo, la complejidad queda de theta(n) **

 #Ejercicio 2
 
 Input:
 A= arreglo de tamaño n
 
 Output:
 Promedio de M
 
 Suma=0
 For numero in M:
  Suma=Suma+M[i]
 mean Suma/n
 return mean
 
 ** Por el for, y despreciando los demás componentes, es de longitud, n, y por tener que ejecutar el ciclo completo, la complejidad queda de theta(n) **
 
 #Ejercicio 3
 
  Input:
  M= arreglo tamaño n
  Output:
  Elemento mas pequeño
  
  menor= none
  For i in rango=(0,longitud(M)):
    For j in (M-M[i]): 
      If M[i]<M[j]:
        menor=elemento[i]
        break
    return menor
  ** Complejidad: Es de n^2, y por el break, sería de O(n2) ** 
    
    #Ejercicio 4
    
    Input:
  M= arreglo tamaño n
  Output:
  Elemento mas pequeño
  
  mayor= none
  For i in rango=(0,longitud(M)):
    For j in (M-M[i]): 
      If M[i]<M[j]:
        menor=elemento[i]
    return mayor
    
  ** Es de n^2, y por el break, sería de O(n2) **
  
 #Ejercicio 5
 Input
 n= número
 Output:
 True/False
 
 For i en rango=(2,n)
    If módulo(n/[i])==0
    return False
  return True
  
 ** Sería de tamaño n, y al tener que ejecutarse todo el ciclo, complejidad=theta(n) **
    
  
