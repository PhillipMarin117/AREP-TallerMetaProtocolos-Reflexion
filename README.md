# TALLER DE ARQUITECTURAS DE SERVIDORES DE APLICACIONES, META PROTOCOLOS DE OBJETOS, PATRÓN IOC, REFLEXIÓN

## Manual de usuario

Si se deseea hacer uso del programa lo primero que debe realizarse el clonar el repositorio almacenado en Github a través del siguiente comando:

```
git clone https://github.com/PhillipMarin117/AREP-TallerMetaProtocolos-Reflexion.git

```
O si desea puede descargarlo como archivo zip y luego descomprimirlo en la carpeta que desee.

Una vez hecho alguno de los dos pasos anteriores, nos dirigimos a la ruta de instalación y por medio de la consola digitamos el siguiente comando:

```
mvn package

```

Ejecutando el siguiente comando puede generar la documentacion:

```
mvn javadoc:javadoc

```

Ejecutando el siquiente comando en la consola y accediendo al siguiente link se puede visualizar una prueba.

```
java -cp target/classes edu.escuelaing.arep.nanoSpring.App edu.escuelaing.arep.nanoSpring.HelloController


```
o ingresando a través de este link desplegado en heroku:

[heroku](https://secure-reaches-84671.herokuapp.com/example.html)

![image](https://github.com/csarssj/ARSW-4-Servidor-Web/blob/master/img/prueba.png)

### Prerequisitos

Este proyecto necesita tener los siguientes progamas instalados en la máquina donde se deseea ejecutar:

```
  java version "1.8.0_251"
  Apache Maven 3.6.3
  git version 2.25.0.windows.1
  jdk1.8.0_251
```

El sistema, mas alla de facilitar el registro de las iniciativas e ideas de proyectos, es una valiosa base de conocimiento donde los diferentes actores pueden revisar si hay iniciativas, ideas o intereses similares y aunar esfuerzos para la materializacion.


## Construido en

* [Maven](https://maven.apache.org/) - Dependency Management

## Despliegue en heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://secure-reaches-84671.herokuapp.com/nspapp/pi)

*Puede acceder a las siguientes direcciones para:*

	- *Resuesta del mapeo /nspapp accediendo a los POJOS:
		* https://secure-reaches-84671.herokuapp.com/nspapp/pi
		* https://secure-reaches-84671.herokuapp.com/nspapp/hola		
	- *Resuesta de un HTML con CSS e Imagenes:* https://secure-reaches-84671.herokuapp.com/index.hmtl
	- *Resuesta de un HTML con CSS Y JavaScript:* https://secure-reaches-84671.herokuapp.com/example.hmtl
	- *Resuesta de imagenes:*
		* https://secure-reaches-84671.herokuapp.com/ca.png
		* https://secure-reaches-84671.herokuapp.com/dr.png

## Integración continua

[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/csarssj/AREP-LAB-4)

## Control de versiones 

[Github](https://github.com/) para el versionamiento.

## Authors

[Felipe Marín](https://github.com/PhillipMarin117) 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) 
