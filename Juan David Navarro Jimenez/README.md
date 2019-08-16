
# Información personal 
Mi nombre es **Juan David Navarro Jiménez** , soy estudiante de
Ingeniería de Sistemas en la [Escuela Colombiana de Ingeniería Julio Garavito](https://www.escuelaing.edu.co/es/). 

---

Actualmente estoy cursando 5 materias que equivalen a 18 créditos.
-	*RECO*
-	*CVDS*
-	*TPRO*
-	*CNYT*
-	*ACSO*

---

## Plan de estudios
El plan de estudios es el número 14.
![Imagenes](https://github.com/JuanNavarroJ/Laboratorio1-Introduccion-GIT/blob/master/Juan%20David%20Navarro%20Jimenez/Img/PlanDeEstudios.PNG)

## Lineas de codigo
Codigo de la clase NumeroComplejo que es utilizado en una [libreria](https://github.com/JuanNavarroJ/LibreriaCNYT) propia
de operaciones de numeros complejos. 
```	
public class NumeroComplejo {
	
	//Atributos
	private double pReal;
	private double pImaginario;
	
	/**
	 * Constructor de la clase Numero complejo.
	 * @param	real	Es la parte real del numero complejo.
	 * @param	imaginario	Es la parte imaginaria del numero complejo.
	 */
	public NumeroComplejo(double pReal, double pImaginario ) {
		this.pReal = pReal;
		this.pImaginario = pImaginario;
	}
	
	//Metodos
	
	/**
	 * Metodo que permite hacer el conjugado al numero complejo.
	 * @return	Retorna El conjugado del numero complejo que es un nuevo numero complejo.
	 */
	public NumeroComplejo conjugado() {
		return new NumeroComplejo(pReal, pImaginario*-1);
	}
	
	/**
	 * Metodo que permite hacer el modulo al numero complejo.
	 * @return	Retorna el modulo del numero complejo.
	 */
	public double modulo() {
		double interno = Math.pow(pReal, 2) + Math.pow(pImaginario, 2);
		return Math.sqrt(interno);
	}
	
	/**
	 * Metodo que permite hacer la fase al numero complejo.
	 * @return	Retorna la fase del numero complejo.
	 */
	public double fase() {
		double ang = Math.toDegrees(Math.atan(pImaginario/pReal));
		return ang;
	}
}
```

## Parte III. - GIT Branching

![Imagenes](https://github.com/JuanNavarroJ/Laboratorio1-Introduccion-GIT/blob/master/Juan%20David%20Navarro%20Jimenez/Img/GitCon.PNG)

![Imagenes](https://github.com/JuanNavarroJ/Laboratorio1-Introduccion-GIT/blob/master/Juan%20David%20Navarro%20Jimenez/Img/Git1.PNG)

![Imagenes](https://github.com/JuanNavarroJ/Laboratorio1-Introduccion-GIT/blob/master/Juan%20David%20Navarro%20Jimenez/Img/Git2.PNG)

![Imagenes](https://github.com/JuanNavarroJ/Laboratorio1-Introduccion-GIT/blob/master/Juan%20David%20Navarro%20Jimenez/Img/Git3.PNG)