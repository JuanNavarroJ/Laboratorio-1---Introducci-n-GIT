# Laboratorio1-Introduccion-GIT
## Información personal 
*Mi nombre es **Johan Sebastian Arias Amador***
tengo 19 años y soy de Bogotá, 
actualmente estoy en séptimo semestre de Ingenería de Sistemas en la Escuela Colombiana de Ingeneria Julio Garavito.

## Gustos e intereses
Me gustan demasiado los deportes en especial el fútbol, entrené durante varios años pero debido a cuestiones económicas y de tiempo 
no pude seguir practicando para jugar futbol profesional. 

Por otra parte, me gustan los e-sports y he alcanzado algunos premios en el juego de la categoria
fps llamado Counter Strike Global-Offensive
gracias a la escena competitiva que se está consolidando actualmente. Con respecto a mis intereses en los 
enfoques de la carrera este sería mi top **hasta el momento**:
1. Seguridad / Infraestructura computacional.
1. Ingenería de software.
1. Sistemas y organizaciones.
1. Gerencia de proyectos.


En este [enlace](https://tycho.escuelaing.edu.co/contenido/asignaturas-pregrado/3-ing-sistemas.pdf) podrá encontrar las diferentes electivas técnicas relacionadas con los enfoques mencionados.

En el semestre actual estoy cursando 5 asignaturas las cuales son:
- Redes de computadores.
- Ciclos de vida del desarrollo de software.
- Colombia: Realidad, instituciones políticas y paz.
- Probabilidad y estadística.
- Fundamentos contables y financieros.

![image][1]

[1]: http://4everstatic.com/imagenes/850xX/diversion/payaso,-explosion-215114.jpg "Clown"

Algoritmos dfs y bfs **Python**:

```
from collections import deque
def bfs(i,n):
	isvisited=[False]*n
	d=deque([i])
	isvisited[i]=True
	while len(d):
		print(d)
		i=d.pop()
		for j in lady[i]:
			if isvisited[j]==False:
				d.append(j)
				print(d)
				isvisited[j]=True
	return isvisited
def dfs(i):
    global isvisited,lady
    isvisited[i]=True
    for j in lady[i]:
        if isvisited[j]==False:
            dfs(j)
    return
def main():
    global isvisited,lady
    lady=[[1,2],[2],[3],[4],[0]]
    isvisited=[False]*len(lady)
    dfs(0)
    print(isvisited)
main() 
```
![image][2]

[2]: https://i.ibb.co/YcMtdvF/lab-1-parte-1-primera-mitad.png "parte 1 primera mitad"

![image][3]

[3]: https://i.ibb.co/JHHDmQ2/lab-1-parte-1-2da-mitad.png "parte 1 segunda mitad"

![image][4]

[4]: https://i.ibb.co/khFxcPC/lab1-parte-2.png "parte 2"


