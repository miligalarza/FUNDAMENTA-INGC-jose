# FUNDAMENTA-INGC
Repositorio de fundamenta donde guardo archivos y comentarios utiles

# CRITERIOS CYPE

## DATOS GENERALES

Usar archivos bases de cype segun corresponda ver josemek098f@gmail.com Cliente 


## COLUMNAS

#### COLUMNAS DE H°A°
- Columnas 0.70 de empotramiento. Se puede asignar a varias columnas desde entrada de columnas -copiar- grupo inicial y final-coeficiente de empotramiento-asignar -seleccionamos las columnas-terminar con click derecho terminar  
- Cuantia minima de 1.00 a 2.00  

#### COLUMNAS METALICAS
- Columnas Metalicas 0.10 de empotramiento
- Destildar opcion de dimensionar elementos metálicos
- Un perfil comun que remplaza las vigas de 20x20 de HA son las columnas 2UPN120
- Fustes de 25x25 minimo para columnas metalicas
  
## VIGAS

#### VIGAS APEO
- Articular las vigas de encadenado (en el nivel de apeo), donde haya carga utilizar vigas comunes y armar
- En el nivel de Apeos las columnas se unen con vigas que pueden estar inclinadas segun la longitud mas corta que las una

#### VIGAS DE H°A°
- Usar barras longitudinales que sean multiplos de 120cm para llegar a 1200cm sin desperdicios
- Usar numeros redondos 
- Longitud de empalme de 60 veces el diametro
- Densificar en L/5 o 2H segun el menor de estos valores desde las columnas:  
   Si la 150<L<250 usamos estribos cada 15  
   Si la L<150 usamos estribos cada 10. fi6c/20 Tramo, fi6c/10 Apoyo.  
- Longitudes tipicas: 100 120 150 170 200 240 300 340 360 400 450 480 600 720 750 800 850 900 960 1000 1050 1080 1200

- Cuantia minima superior e inferior 0,0026xAREA[cm] = As Minima a cubrir independientemente de lo q pida, DONDE EL DIAGRAMA DE MOMENTOS LO PIDA
- fi8 arriba fi10 abajo ( 1 refuerzo)
- para los refuerzos de las vigas MIRAR las envolventes y la posicion de los esfuerzos maximos!
- Vigas chiquitas(20x30 v 20x20) no pueden terner fi16 pensar en agrandar las vigas o en otra solucion
- Ref centrales en apoyos minimo 240
- Ref laterales en apoyos minimo 120
- Ref tramo minimo 300
- Ganchos: abajo +15 | arriba el maximo posible (+20)
- Saltos de armadura para refuerzos maximo 2 saltos

- EN CASAS: la armadura de piel es de fi6 v fi8 c/15
  
#### VIGAS METALICAS
- Existe una planilla donde se puede determinar si verifican las vigas metalicas de las cubiertas
- Se colocan como cargas puntales en el CYPE

## CARGAS

### CARGAS DE CUBIERTA
- Para cubiertas usar carga de 70kg/m2 o 0.07t/m2
- Distribuir correas cada 0.80-1.00 de distancia empezando a 0.10 del borde
### CARGAS DE MURO  
- Se determinan como PesoespecificoxHmuroxEspesor (cargalineal)

 ## BASES

 Ploteamos-Cargas de fundacion en CYPE (Arranques momentos y cortes) -> Obtenemos carga de bases con planilla de Carga de Fundaciones  

 
 
 ### BASES AISLADAS  
 - Usamos la planilla de bases aisladas verificamos la tension de contacto
 - se agrupan bases con cargas similares
 - EN CASAS: las bases de menos de 4 toneladas se hacen como bloques


