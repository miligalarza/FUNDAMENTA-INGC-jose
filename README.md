# FUNDAMENTA-INGC
Repositorio de fundamenta donde guardo archivos y comentarios utiles

# CRITERIOS CYPE

## DATOS GENERALES

Usar archivos bases de cype segun corresponda ver josemek098f@gmail.com Cliente 

PARA OBRAS CON HORMIGON IN SITU USAR H13 O H17 ... en san miguel de tucuman se puede llegar a usar H21


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
- Donde pida mas q la armadura minima se puede colocar un bloque de apoyo de 60x60x60 y poner en el cype ua carga de .8 hacia arriba negativa

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
- Ref del diametro de la base o mas
- Ref centrales en apoyos minimo 240
- Ref laterales en apoyos minimo 120
- Ref tramo minimo 300
- Ganchos: abajo +15 | arriba el maximo posible (+20)
- Saltos de armadura para refuerzos maximo 2 saltos
- Vigas simetricas aprox hacer armaduras simetricas aprox 
- EN CASAS: la armadura de piel es de fi6 v fi8 c/15
- Se pueden verificar en armado de vigas la flecha activa con el simbolo de la par de As maximo se permite L/500
- En caso de vigas no estructurales puede usarse cuantia minima de 1.5XAs (As lo q pide el cype)
  
#### PLANILLA VIGAS METALICAS
- Existe una planilla donde se puede determinar si verifican las vigas metalicas de las cubiertas
- Se colocan como cargas puntales en el CYPE 
- Se usan para calcular Cerchas y vigas metalicas
- K1 , VM1, VM2, etc. (ej K1 Luz 3.14 sep 0.75 perfil N10  (C100/50/15/1.6)cant 1 posicion 1 
- LUZ agregamos la luz de calculo, la planilla calcula como una viga simplente apoyada
- SEP. agregamos la separacion o la luz de carga que absorbe cada elemento
- g p w p son carga gravitatoria uniformemente distribuida, carga viva uniformemente distribuida, de viento uniformemente distribuida y carga puntual (podemos poner g y p como solo 70 en uno de los dos para asignar lo que usamos normalmente)
- Cant. Posicion Para Vigas siempre usamos 2 y 1
- Asignamos un perfil y vamos probando, se usa mucho perfiles C dobles (como formando un rectangulo)

#### CORREAS
 - Se colocan a 30cm del borde contrario a la canaleta o a 30cm de la apretada.
 - Donde va la canaleta va una correa en coincidencia
 - Se adopta una separacion conveniente en funcion del espacio a ocuar con correas
 - Considerar en caso de continuidad entre correas el factor 0.7 de la planilla de vigas metalicas
 - Se usan normalmente correas de 10cm de alto de 1.5 o 2mm de espesor... elementos estructursles como vigas metalicas de refuerzo llevan minimo espesor de 2mm.. correas sin vigas meralicas llevan tmb 2mm
 - para el tanque se divide la carga de tanque en general 1100l o kg en 4 correas q van de bajo en posicion 2 y se verifican un valor muy normal es de 140 de alto de correa 

#### PLANILLA CALCULO DE CERCHAS

  - Editamos solo los elementos en Rojo
  - Luz: es la luz de calculo como si fuera una viga simplemente apoyada todo el elemento
  - Carga puntual la carga q va en el medio.. ej si tengo 3 vigas metalicas q llegan al coronamiento de mi cercha divido la carga total q llega a ese punto en dos ( como si analizara la mitad de la cercha)
  - Carga y ancho de carga es una carga uniformemente distrubuida que corresponde con la cercha ( como el resto de los elemenotos como corresas 70kg por el ancho de influencia)

 
    VERIFICACION DEL CORDON COMPRIMIDO  
  - Determino el brazo de palanca elastico desde el eje del centro del elemento superior hasta el eje del elemento inferior 
  - Determino la longitud del cordon comprimido como el cordon central con la longitud inclinada entre barras inclinadas
  - Introducimos un codigo de busqueda que corresponde con REF Perfiles ( usamos mucho perfiles C como por ejemplo C 80-2)
 
    
    VERIFICACION DE LA DIAGONAL  
  - Introducimos angulo
  - Longitud de la diagonal mas larga y codigo de busqueda hasta q verifique (Usamos mucho perfiles C80-2 v C80-2.5)


A la hora de elegir los perfiles debemos pensar como los elementos se van a soldar ejemplo 2 perfiles C80 tienen una soldadura mas segura q un perfil C80 y un TE 30x30
Se prefiere el uso de la cerchas  como si fuera un triangulo con la base abajo en el centro y se repiten simetricamente la armadura a la izquierda y derecha (Celosía/Cercha tipo pratt triangular)
las barras verticales se van proponiendo segun la luz ej (.80m a 1 m)
Creamos una planilla para cada cercha.  


En cerchas de cierre no importa tanto el angulo, tratamos de que sean medidas estandares para todo el tramo donde la cercha de cierre coincida con correas ponemos un montante en correspondencia con la correa o soportes



    
## CARGAS

### CARGAS DE CUBIERTA
- Para cubiertas usar carga de 70kg/m2 o 0.07t/m2
- Distribuir correas cada 0.80-1.00 de distancia empezando a 0.10 del borde
### CARGAS DE MURO  
- Se determinan como PesoespecificoxHmuroxEspesor (cargalineal)

 ## PLANILLA BASES AISLADAS

  -  Ploteamos-Cargas de fundacion en CYPE (Arranques momentos y cortes) -> Obtenemos carga de bases con planilla de Carga de Fundaciones:( ponemos en fila los cuadros de columna donde solo tiene q aparecer el axil, destildamos momento y corte, las ponemos en fila ponemos data extratct seleccionamos a lore, seleccionamos los elementos que queremos, destildamos todo menos text (destildamos line y poliline2d), next, y guardamos en un archivo, usamos la planilla de stagneto de carga de fundaciones pegamos en AB lo q obtuvimos del data extract, borramos si hay cosas mas abajo q nuestras cols, ejecutamos la macro, copiamos y pegamos lo de D a F, hacmos Ctrl+L buscamos ": Hipótesis" y apretamos remplazar todo despues a lo que queda en la tabla lo pegamos en el proximo paso y agrupamos por cargas ej cada 5t y unificamos para tener menos base.... estos valores de carga junto con con la tension admisible del suelo a la profundidad q estamos ej 9 o 12 t son los q usamos para el excel de bases aisladas
 -  Cuando tenesmos bases convinadas donde llegan 2 o mas columnas primero tenemos q calcular el baricentro de fuerzas y de ahi se calcula la dimension de la base
 -  cx cy dimensiones de la columna
 -  bx by dimensiones de la columna +2.5cm
 -  ax ay dimensiones de la base en planta
 - d0 y d son la altura de la parte rectangular y de la parte superior del cono trucnado de la base respectivamente,
 -  H es la altura d menos el recubrimiento
 -  d d0 y H tal q el agunlo del cono truncado de la base sea 23 es lo deseable
 -  Para pegar las planillas de bases aisaldas y cualquiera hacemos paste special - scale 0.07 
 - Usamos la planilla de bases aisladas verificamos la tension de contacto
 - se agrupan bases con cargas similares
 - EN CASAS: las bases de menos de 4 toneladas se hacen como bloques

 ## PLANILLA VIGAS Y COLUMNAS PARA MUNICIPAL

 - xxxxxx_Planilla municipal_VIGAS_COLUMNAS CYPE

