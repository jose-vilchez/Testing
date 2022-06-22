
7 PRINCIPIOS DEL SOFTWARE TESTING 

PRINCIPIO1 : EJECUTAR PRUEBAS NOS MUESTRA LA PRESENCIA DE DEFECTOS, PERO NO PUEDAN PROBAR QUE NO LOS HAY. EJEMPLO SAMSUNG LANZAMIENTO EXISTENCIA DE BUGS ERRORES DE PROGRAMACIÓN.
PRINCIPIO2 : EL TESTING EXHAUSTIVO ES IMPOSIBLE.EJEMPLO PROBAR LA FUNCIÓN FUENTES DE WORD.EJEMPLO REAL -CASO WEATHER.COM, DONDE TRATA SOBRE EL CLIMA Y TODOS LOS PAISES TIENEN DIFERENTES CIUDADES. SON 500 MIL CIUDADES, IMPOSIBLE PROBAR COMO SE COMPARTA EL CLIMA EN LAS CIENTOS DE CIUDADES. ENTONCES ES  MEJOR 
HACER UN ANALISIS DE RIESGO.
PRINCIPIO3 : LA VERIFICACION DE LA CALIDAD DE UN SISTEMA DEBE EMPEZARSE LO ANTES POSIBLE. MAS TARDE DE ECUENTREN LOS DEFECTOS MAS COSTOSOS ES ARREGLARLOS.
PRINCIPIO4 : LA MAYORIA DE DEFECTOS RELEVANTES SUELEN CONCENTRARSE EN UN GRUPO MUY DETERMINADO DE MÓDULOS DE NUESTRO PRODUCTO. ES DECIR ENFOCARSE EN MODULOS MÁS IMPORTANTES
PRINCIPIO5 : LA PARADOJA DEL PESTICIDA. PARA ENCONTRAR NUEVOS DEFECTOS HAY QUE ACTUALIZAR LOS CASOS DE PRUEBA, PONER NUEVOS CASOS DE PRUEBAS,ETC. 
PRINCIPIO6 : EL TESTING ES TOTALMENTE DEPENDIENTE DEL CONTEXTO. SI ES PARA UN HOSPITAL SE TIENE QUE TENER EN CUENTA QUE SE DEBE HACER MÁS PRUEBAS PORQUE ESTÁ EN RIEGO VIDAS HUMANAS.
PRINCIPIO7 : LA FALACIA DE AUSENCIA DE ERRORES, LA MAYORIA DE DEFECTOS CRITICOS PUEDEN QUE HAYA SIDO CORREGIDOS, PERO ESTO NO ASEGURA DE QUE SEA EXITOSO O DE LA MEJOR CALIDAD.


PRUEBAS ÁGILES(AGILE TESTING)
ES UNA PRACTICA DE PRUEBAS DE SOFTWARE QUE SIGUE LOS PRINCIPIOS DEL DESARROLLO DE SOFTWARE.
SCRUM: HACER EL SOFTWARE DE MANERA AGIL EQUIPO DE DESARROLLO AGIL.
PRUEBAS ÁGILES : PERMITEN UNA ALTA CALIDAD DEL PRODUCTO YA QUE LOS ERRORES SE ELIMINAN EN UNA ETAPA INCIAL QUIERE DECIR CUANDO SE ESTÁ DESARROLLANDO EL PRODUCTO.

EJEMPLO PRUEBAS ÁGILES 
CUANDO UNA EMPRESA DE DESARROLLO SOLICITA CREAR UNA APLICACION WEB BÁSICA PARA VOTAR POR AUTOS DEPORTIVOS , QUIERE QUE SUS CLIENTES VOTEN Y DEJEN UN COMENTARIO .
ENTONCES , SI TRABAJAS EN UN EQUIPO DE 6 PERSONAS DONDE HAY 4 DESARROLLADORES, UN ANALISTA DE NEGOCIO Y UN TESTER, EL PRODUCT OWNER LLEVA ESA NECESIDAD. Y SE TRABAJA EN UN SPRINT DE 2 SEMANAS.

SPRINT #1
OBJETIVO: CREAR UN APLICACIÓN WEB BÁSICA PARA VOTAR POR AUTOS DEPORTIVOS.

SEMANA1 -SEMANA2 
-REQUISITOS WEB(HISTORIAS) / DESCRIBIEN TODA LA NECESIDAD QUE EL CLIENTE NECESITE Y SE SOCIALIZAN CON TODO EL EQUIPO. SI SE NECESITA HACER UNA PÁGINA, UNA OPCIÓN DE LOGUEO, VOTAR POR LOS AUTOS, OPCION DE REGISTRO DE USUARIOS. UNA LISTA DE REQUISITOS QUE EL CLIENTE NECESITA.
-DESARROLLO DE LA APLICACIÓN
-PRUEBA FUNCIONALES * DONDE EL TESTER CREA CASOS DE PRUEBAS, DURANTE LA SEMANA 1 
-LIBERACIÓN APLICACIÓN WEB A PRODUCCIÓN(RELEASE): EN SEMANA 02 ENVIAR AL CLIENTE.

AGILE TESTER DURANTE EL SPRINT:
![](https://i.postimg.cc/W1HxHVKZ/sprint.png)

AGILE TESTER DURANTE EL SPRINT 
-AYUDAR AL EQUIPO A LA REVISIÓN DE COMÚN ENTENDIMIENTO DE REQUISITOS.


PROYECTO " SITIO WEB Buggy Cars Rating" PLAN DE PRUEBAS LIGHT 

1.INTRODUCCIÓN

buggy cars es una aplicación web que permite a los usuarios votar por los autos deportivos más famosos del mundo y dejar una opinión para marca y modelo. El objetivo de este plan de pruebas es analizar que se va a probar, como, con que recursos y cual es el plan de riegos que hay y su mitagación.

2.ALCANCE DE LAS PRUEBAS(¿QUE VAS A PROBAR?)
Se van a probar las siguientes historias de usuario definidas en el sprint backlog

![](https://i.postimg.cc/mr3vLgSF/3.png)