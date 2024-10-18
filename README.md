Definir monto Como Real
	Definir pelicula Como Caracter
	Definir horario Como Caracter
	
	Escribir " ingrese el tipo de pelicula"
	Leer pelicula// a,b,c
	Escribir " ingrese el horario de la pelicula"
	Leer horario // normal reducido
	
	si ( pelicula = "a")
		si ( horario = "normal")
			monto = 1200
		SiNo
			monto = 1200 - ( 1200 * 0.20)
		FinSi
	FinSi
	
	si ( pelicula = "b" )
		si ( horario = "normal" )
			monto = 1500
		SiNo
			monto = 1500 - ( 1500 * 13.3)
		FinSi
	FinSi
	
	si ( pelicula = "c")
		monto = 1800
	FinSi
	
	Escribir " el monto de la pelicula es:", monto
	
	
FinAlgoritmo
 
