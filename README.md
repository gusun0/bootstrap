#MEDIDAS DE BOOTSTRAP
xs/col ( < 575)
sm  (576 - 767)
md  (768 - 991)
lg  (992 - 1199)
xl  (1200 > )

#Colores
primary
secondary
dark
light
danger
warning
success
info 
white

#clearfix
Sirve para que cada elemento respeto su individualidad en las columnas


#mx-auto
mx-auto con sytle="width: 100px" => sirve para centrar elementos

#display
podemos usar display-1 para modificar el tamaño de los elementos, se usa del 1 -> 4 


#mark
se usa para poner un sombreado

#kbd
sirve para dar a conocer los atajos de teclado

#alienar texto
text-left, center, right;

#nowrap
text-nowrap sirve para que no haya cortes


#table
table-striped -> da color a cada fila
table-bordered ->  da borde


#img-fluid
es para que una imagen grande se adapte 

rounded es para imagenes redondeadas


#img-thumbnail
Es para que la imagen tenga un marco

#jumbotron
para resaltar contenido de texto

#alert
otra manera de resaltar texto

#data-dismiss
esto nos sirve para cerrar un alert
<p class="alert alert-success alert-dismissable">
<button type="button" class="close" data-dismiss="alert">&times;</button>


#btn-link
#btn-outline-primary
#btn-lg o #btn-sm
#btn-group-vertical




#Para hacer un Submenu
<div class="btn-group ">
<button type="button" class="btn btn-outline-success  btn-sm">Enviar</button>
<button type="button" class="btn btn-outline-success  btn-sm">Enviar</button>

<div class="btn-group">
<button type="button" class="btn btn-outline-success dropdown-toggle" data-toggle="dropdown">Sony</button>
	<div class="dropdown-menu">
		<a href="#" class="dropdown-item">Tablet</a>
		<a href="#" class="dropdown-item">Smartphone</a>
		<a href="#" class="dropdown-item">Computadora</a>
	</div>
</div>

</div>

#Usando insginas
class="badge"
badge-pill badge-primary => para que tenga esquinas redondeadas

#badge con span en un botón
<button type="button" class="btn btn-dark">Mensaje <span class="badge badge-light">4</span></button>

#progress
se usa para representar una barra de progreso

#page-item
para paginación con bootstrap

#pagination en bootstrap

<div class="pagination">
	<li class="page-item"><a class="page-link" href="#">Uno</a></li>
	<li class="page-item"><a class="page-link" href="#">Dos</a></li>
	<li class="page-item"><a class="page-link" href="#">Tres</a></li>
	<li class="page-item"><a class="page-link" href="#">Cuatro</a></li>
	<li class="page-item"><a class="page-link" href="#">Cinco</a></li>
</div>

#breadcrumb

#list-group
se usa para tener listas con list-group-item


#Para poner un menu desplegable
<div class="dropdown">
	<button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">Desplegable</button>
	<div class="dropdown-menu">
		<a href="#" class="dropdown-item">Link 1</a>
		<a href="#" class="dropdown-item">Link 2</a>
		<a href="#" class="dropdown-item">Link 3</a>
	</div>
</div>

#collapse
se usa para que el contenido aparezca/desaparezca

#data-toggle
es un pseudoelemento


#acordeon
se usa igual para mostrar/ocultar elementos

#nav-justified
nav-justified se emplea en nav para que se use todo el espacio de la pantalla


#form-control
se emplea para formularios

#carousel slide
es para mostrar imágenes
