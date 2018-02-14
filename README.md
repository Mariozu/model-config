# model-config
Este repositorio contiene todos los modelos y configuraciones tambien los archivos de configuracion
para light-codegen  
frameworks. 

#Ejemplo
Para Usarlo:
```
	generate.sh -f [framework] -m [input-dir] -o [output-dir] -c[config-dir]


	para los framework:
	- light-rest-4j
	- light-hybrid-4j-server
	- light-hybrid-4j-service
	- light-graphql-4j

	ejemplo.:
	./generate.sh light-rest-4j ~/networknt/model-config/rest/petstore /tmp/petstore
         java -jar [.jar] -f [framework] -o [directorio de salida] -m [modelo.json] -c [configuracion.json]


```
#Notas
Nota: Este repositorio se usa para llamar swagger solo  si es para light-rest-4j. ahora, aqui podras encontrar modelos y configuraciones para:
- light-rest-4j
- light-hybrid-4j-server
- light-hybrid-4j-service
- light-graphql-4j


