+ Pasos:
	+ Ir a su pagina web oficial de Arduino 
	+ Ir sotware y escojer el sistema operativo
	+ Extrar el archivo comprimido descargado
	+ Ejecutar el script de instalacion:
		+ Pasos:
			+ Abrir una terminal en una jaeraquira anteorior a la capeta descomprimida
			+ `sudo chmod -R 777 arduino-1.8.19`
			+ `cd arduino-1.8.19/`
			+ Esto va agregar nuestro usuario a los grupos necesarios paa usar arduino correctamente
			+ añade nuestro usuario a los puertos que usan los USB para controlar arduino d manera mas eficiente
				+ `./arduino-linux-setup.sh $USER`
				+ Luego reiniciar el sistema para que se realicen los cambios satisfactoriamente
			+ `sudo ./install.sh`
+ Observaciones:
	+ Cuando salga una nueva cersión de arduino, debemos de desisntalar la versión actual e instalar la nueva versión
+ [[Errores en Arduino]]

