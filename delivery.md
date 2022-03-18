Algoritmo y planteamiento
INICIO
	1. Pedir cadena al usuario
	2. Evaluar if(cadena.length <=20)
		entonces evaluamos
		else{numero maximo ingresado}
	3. Identificamos y agrupamos
		identificar numeros
		identificar OPERADORES
	4. Ordenamos la cadena por numeros y OPERADORES
		en parentesis: numeros
		fuera del parentesis: OPERADOR
	//empeczamos a operar apartir de aqui
    5. Scaamos la cadena y la convertimos en Array
	6. Recorremos el array
		recorreArray(){
			if (cadena.contains("/")){
				div = ope1(numDerecha/operador/numIzquierda);
			}
			else if (cadena.contains("*")){
				resta = ope2(numDerecha*operador*numIzquierda);
			}
			else if (cadena.contains("+")){
				suma = ope2(numDerecha-operador+numIzquierda);
			}
			else if(cadena.contains("-")){
				resta = ope2(numDerecha-operador-numIzquierda);
			}
		}
	7.creamos un metodo mostrarArray()
	