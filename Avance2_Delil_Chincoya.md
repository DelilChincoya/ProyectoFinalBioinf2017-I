## Avance 2
###### Delil Andrea Chincoya Martínez

##### Preprocesamiento
Hasta el momento he limpiado los datos crudos (filtrado y trimming) con tres softwares: Trimmomatic, Trim Galore y AfterQC, para comparar los resultados con cada uno de ellos. He decidido quedarme con las lecturas limpiadas por AfterQC, mismas que tienen una longitud mínima de 120 pb y una calidad phred mayor a 15.

##### Ensamblado
Para el ensamblado utilizaré probablemente NOVOPlasty. NOVOPlasty es un software que permite ensamblar genomas de organelos a partir de secuencias provenientes de genoma total.
Ya corrí algunas pruebas con NOVOPlasty; utilicé como semilla una secuencia de matK de *Mammillaria supertexta* que se encuentra disponible en GenBank. Hasta el momento no he podido ensamblar más de 30,000 pb. El tamaño esperado del genoma es de unos 120,000 pb.
