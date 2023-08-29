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
