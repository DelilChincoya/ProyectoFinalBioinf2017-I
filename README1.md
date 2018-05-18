
El  proyecto de ensamblado *de novo* del genoma de cloroplasto de *Mammillaria supertexta* se encuentra organizado en los siguinetes directorios:

## 	`Data` 

#####	`Raw`
Contiene los datos crudos, tal como salieron del secuenciador.

#####	`Filtered`
Contiene las secuencias tras haber sido limpiadas con AfterQC.

#####	`Novoplasty`
Contiene la secuencia usada como semilla para el ensamblado (RuBP), los archivos output del ensamblado y el archivo de configuración utilizdo para correr el análisis (`config.txt`).

##### 	`Soap`
Contiene el archivo de configuracion `soap.config` con las instrucciones para correr SOAPdenovo, así como los archivos output de los análisis.

##	`Bin`
Contiene los scripts utilizados para correr los análisis.
`Filtrado` contiene los parametros para hacer el trmming, limpeza de adaptadores y filtrado por calidad con AfterQC.

`Ensamblado` indica cómo correr NOVOPlasty (en realidad no es un script); todos los parámetros se encuentran en el archivo de configuración en  `/Data/Novoplasty`

`Ensamblado2` indica cómo correr SOAPdenovo, el resto de los parámetros se encuentra en el archivo de configuración en `/Data/Soap`

##	`Docs`
En el se aloja un documento de excel con información sobre las muestras.


