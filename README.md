# El_Patito
código nuevo
Algoritmo  Algoritmo_Modificado
	Escribir "Ingrese la cantidad de datos:"
	Repetir
		
		Leer n
		Si n<=0 Entonces
			Escribir "El número debe ser positivo y distinto de cero."
			Escribir "Introduzca un número válido."
		Fin Si
		
	Hasta Que n>0
	
	acum<-0
	
	Para i<-1 Hasta n Hacer
		Escribir "Ingrese el dato ",i,":"
	    leer dato
		Si dato<0 Entonces
			Escribir "El dato debe ser positivo."
			Escribir "Ingrese el dato ",i,":"
			
		Fin Si
		
		Mientras contador<0 Hacer
			
		   Leer dato
			Si dato<0 Entonces
				Escribir "El dato debe ser positivo."
				Escribir "Ingrese el dato ",i,":"
			Fin Si
		FinMientras
	
		
		acum<-acum+dato
	Fin Para
	
	prom<-acum/n
	
	Escribir "El promedio es: ",prom
	
	Escribir "Para salir pulsa enter "
	leer salir 
		
FinAlgoritmo
