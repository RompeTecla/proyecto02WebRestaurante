<center>

# :hamburger::potato:<font color="orange"><u>Rte. El Taller de la Tapa</font></u>:meat_on_bone::cheese:



## Explicación del proyecto

Es un restaurante real, al que conozco al dueño y a pesar de su calidad, no tiene pagina web propia.
Pensé que esto sería una manera divertida de aprender a utilizar bootstrap, aunque he de reconocer que al principio me ha costado bastante hacerme con las sintaxis en el html. GeeksHubs nos requiere la web de un restaurante que sea completamente "responsive".

### Cómo se hizo

En el desarrollo de la web se han necesitado: un index.HTML que hace la estructura de la página inicial o de bienvenida. Un .hmtl por cada una de las secciones de la web como son: "Reservas, Desayunos, Tapas, Postres, etc. Ha sido necesaria la integración de stylesheets de css propia para darle el formato específico a ciertos elementos. Además de los css específicos y los complementos de Bootstrap y el linkeo de javascript; Para lograr una web completamente responsive. Cada una de las páginas excetuando el index contienen una navbar con links que nos redirigen a las paginas de la carta y reservas.

<p align="center">
<img src="https://raw.githubusercontent.com/RompeTecla/proyecto02WebRestaurante/master/img/imgreadme/tecnologias.jpg"  width="" height="100"></p>


La estructura de la página se ha realizado con elementos de Bootstrap y clases afines para evitar conflictos durante la ejecución y mejorar la escalabilidad. Solo se ha aplicado clases css propias en los casos en los que era imperativo usarlo.

### Cómo funciona

Inicialmente nos encontraremos con una web en forma de "bienvenida" con un plato a modo de botón y la dirección del local en el inferior de la página. Botón que al pasar por encima el puntero hace un efecto de hover transform y al hacer click en el, te redirige a la página de "la carta"

<img src="https://raw.githubusercontent.com/RompeTecla/proyecto02WebRestaurante/master/img/imgreadme/paginaprincipal.png"  width="" height="280">
<p align="center">

En dicha carta veremos los diferentes servicios que ofrece El Taller. También a partir de esta página ya vemos una "navbar" superior que servirá para navegar a: la página de inicio (al hacer click en el logo del Rte.), a la página de "Nuestra carta" y a "Reservas".
Y por supuesto, al clickar en cada uno de los servicios accederemos a el contenido de los servicios. Ej.: Desayunos, tapas, carnes y pescados, etc.

<img src="https://raw.githubusercontent.com/RompeTecla/proyecto02WebRestaurante/master/img/imgreadme/paginacarta.png"  width="" height="280"></p>

Como extra decidí añadirle la página de reservas (aunque no se almacenen datos en ninguna base) me parecía correcto añadirle el detalle de dicha página y que esta al aceptar la reserva te redirigiera a la página de "reserva confirmada"

<img src="https://raw.githubusercontent.com/RompeTecla/proyecto02WebRestaurante/master/img/imgreadme/paginareservas.png"  width="" height="200"><img src="https://raw.githubusercontent.com/RompeTecla/proyecto02WebRestaurante/master/img/imgreadme/paginareservaconfirmada.png"  width="" height="200">


### Errores conocidos

Al crear una reserva no se envia ningun formulario ni se crea ningún archivo de registro.
No he conseguido solucionar el problema con el scroll horizontal al abrir el inspector con responsive para nexus 5. Una vez abierto el inspector, recargas página y el scroll desaparece. Navegas por todas las páginas y sigue sin haber scroll horizontal. Sospecho que pueda ser problema de la caché del navegador. (abierta la web en mi smartphone S.Galaxy Note 10+ y el scroll horizontal es inexistente)

### Agradecimientos

Grácias a mis compañeros y a mi familia por el apoyo en momentos de pantalla en blanco y mis negaciones constantes con el desarrollo.
<p align="center">
<img src="https://media1.giphy.com/media/jnQjvuFbdYObxxKADE/giphy.gif?cid=ecf05e47fdvf0f6j83ntetnpmvefdaeaqhzt0ldzmussrhpg&ep=v1_gifs_search&rid=giphy.gif&ct=g" alt="Alt Text" width="200px">
</p>
<p align="center">
<img src="https://media4.giphy.com/media/Ic5Ov5WX3O8M0/giphy.gif?cid=ecf05e47m3rzwx44amg7ieaoum16dc0vk556kjy15kapj26i&ep=v1_gifs_search&rid=giphy.gif&ct=g" alt="Alt Text" width="200px">
</p>