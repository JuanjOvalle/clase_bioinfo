# clase_bioinfo
## Pasos a seguir 

1. Trabajar un ambiente del cluster que contenga los programas que necesitamos.
2. Lo primero es inferir las ortologías de los genomas que se van a trabajar.
3. Filtrar las secuencias por calidad en base a las generadas por la inferencia de ortologías.
4. Realizar un alineamiento múltiple para hacer el análisis base a base de las secuencias.
5. Recortar las partes que no encajan con el correcto alineamiento de las secuencias.
6. Concatenar las secuencias alineadas y cortadas.
7. Hacer los árboles de máxima verosimilitud.
8. Hacer el árbole de coalescencia.


## Árboles
[Árbol particionado](https://www.dropbox.com/s/alf1xfc0c9d8z84/y5KI3tULz0UG5fa4SG9w-Q.pdf?dl=0)

Se observa un árbol que asocia primero peces de aletas carnosas (Sarcopterigios) en la parte más basal del árbol, que luego se va dividiendo en
peces actinopterigios, luego reptiles, aves, llegando a mamíferos, con bootstrap generalmente altos (Por encima de 85), exceptuando el caso de *Anolis carolinensis* (Reptil) con un clado de aves galliformes.

[Árbol no particionado](https://www.dropbox.com/s/26l9gtb9ogrh38h/wVZZr-V9a3i4sbcsdtSVDw.pdf?dl=0)

Se observa un árbol que tiene relaciones idénticas al particionado, sin embargo con bootstrap generalmente menores al particionado, debido a la manera en la que no se construye el arbol usando fragmentos de ADN.

[Árbol de  coalescencia](https://www.dropbox.com/s/ylk1ddccjdqayjt/Nijl5HunwzX5u53ulm76ew.pdf?dl=0)

El árbol es parecido a los dos anteriores desde el punto de vista que 'desciende' de los grupos más 'basales' a los más 'derivados', sin embargo las relaciones no se dan por los cambios en el genoma desde el ancestro, sino desde las similitudes de los genomas más 'recientes' hasta el más 'ancestral'.


