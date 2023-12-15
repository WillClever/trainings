# Presentacion 

Bueno, me presento, mi nombre es Trainer, soy de X Pais.

Actualmente trabajo para cleverte. Tengo 10 años de experiencia trabajando en software.

Como devops podría hacerse antes, no se llamaba Thevops, pero bueno, digo por 
acá se empezó a llamar el rol devops.

presentacion de clever y experiencias

Vamos a vamos A hablar sobre Git  y Git Hub.
El temario básicamente es conocer a nivel general 
cómo funciona github, cómo cómo funciona github específicamente 
y una repasada pequeña y cómo funciona github. Vamos a tener una 
serie de capacitaciones donde vamos a ir abordando diferentes temas
 específicos con con lo con lo que es la herramienta github en este en este proyecto.

Vamos a dar test de lo más básico, que es un cómo arrancar con git.
 Al final vamos a dar ya temas más avanzados con con github.
  En esta sesión vamos a hablar sobre.

# temario de este curso
Voy a contar acá la siguiente diapositiva.
El temario del curso.
Vamos a hablar sobre.
Que es un control de versiones que es git específicamente.

Instalación y configuración de git.
¿Cuáles son los 3 Estados en los cuales nosotros empezamos a trabajar con github?
Los comandos básicos que se usan en github. Entonces vamos a verlos desde la terminal. ¿Cómo se usan estos comandos? ¿Cómo cómo se interactúan con la consola, cómo se interactúa con con con un proyecto específico de estos? Vamos a ver cómo se inicia un proyecto, cómo se clona un proyecto, cómo se adiciona 111 trabajo AA nuestro estallado, vamos a hablar sobre estallan área sobre working directory sobre repository.
También vamos a ver.
¿Para qué no sirve el comando quite saturos, 
git Love, git checkout, reset, get branch y git stage?
Trabajaremos un poco con con el archivo Git editor.
vamos a hablar de Git, que es github. Vamos a crear un proyecto, 
vamos AA hacer un PULL. Vamos a hacer un pulso de este proyecto y vamos a hacer un merch.

# Diapositiva 3
Que es un sistema de control de versiones.
Un sistema de control de versiones es.O su nombre lo indica un sistema, 
valga la redundancia, que registra los cambios realizados. 
Que yo voy a tener en un archivo o en un conjunto de archivos 
en un periodo de tiempo a largo tiempo en un corto tiempo.
Eso me permite en ciertas partes poder recuperar versiones 
específicas más adelante, por ejemplo, yo hago una modificación de un archivo.
O lo hice hace dos meses, yo pueda de alguna manera volver a esa versión. 
Entonces el sistema de control de la versión es lo que me permite es.
Tener versiones específicas de mis archivos puedes hacerte un archivo  de 10 archivos de 1000 archivos. Es indeterminado.Diferentes sistemas de control de versiones, los cuales.
Perdón, hay diferentes sistemas de controles de versiones, en este caso yo tengo sistemas de versiones centralizados, sistemas de versiones distribuidos. Tengo sistemas de versiones locales, 
anteriormente nosotros veníamos trabajando hace unos años, trabajábamos ahora el el el tema de git se ha. Se ha abordado mucho más, pero anteriormente nosotros teníamos una versión local en esa versión local, nosotros lo que hacíamos era hacer una modificación y vamos nombrando el archivo.
Y vamos nombrando el archivo con la versión dos con versión 1 y vamos colocando la versión dos, versión 3 versión cuatro. Esto lo trabajamos en nuestro sistema local, después pasamos a una era donde teníamos los repositorios de diferente manera, teníamos unas herramientas que nos permitían hacer, digamos, este control de versiones.
Ya empezamos a conocer realmente un poco más robustas, como como Git, aunque llevan un montón de tiempo en el marcador.

No llegó a todos de forma de forma rápida. Sí, 1 se nos encontró en diferentes momentos y dependiendo de las necesidades que íbamos teniendo.

Como fuimos abordando temas ya de de de empezar a automatizar todo, de empezar a encontrar nuevas formas, de hacer nuestras automatizaciones, encontramos que git era una herramienta que nos podía ayudar. Sí, propiamente que.

Que que quites un sistema de control de versiones que me permite trabajar descentralizadamente.

Mi control de versiones en diferentes equipos o puede ser en un proyecto en diferentes proyectos, sí.

# Dispositiva 4
Git es un es un sistema de control, lo repito.
Es Open Source, fue creado por Linus Torbax por allá en el 2004.
Y lo dejó como software libre. Cualquier persona puede usar git, sí, inclusive cualquier persona puede modificar e incluso cambiar de versiones

# Diapositiva 4 
- notas (Es buena idea ir haciendos dibujos sobre las diapositivas)
Entonces para eso necesitamos conocer cuál es la diferencia. ¿Cómo funciona git? Entonces hay diferentes controles de versiones. En este caso tenemos 111, sistema de control de versiones centralizado, entonces, en este control de versiones centralizado.
Colocar acá teníamos un servidor, sí, ese servidor tenía todos los cambios que nosotros íbamos realizando sobre nuestro Código.
Y todas las personas o todo el equipo se conectaba al sistema de control de su versión centralizada.

¿Cuáles controlas con los conocemos esos version? Visual Studio visual Studio version control surval system.

Entre otros. ¿Entonces, qué era lo que pasaba? Todos estaban haciendo, tenían una copia de este mismo repositorio en su máquina y constantemente estaban haciendo validaciones.

Al repositorio central si este repositorio fallaba, nosotros íbamos a tener inconvenientes porque no podríamos validar nuestro código. No podríamos trabajar sobre nuestro código.

Además de otras de otros problemas que se podían presentar, siempre estábamos constantemente haciendo PULL y push sobre nuestro código, conflictos que se podrían generar, se borraban versiones. En algunos casos le pasaba 1, que tenía una versión y alguien estaba trabajando en el mismo repositorio o en la misma carpeta, no bloqueábamos ese archivo, entonces si esta persona, por ejemplo tomaba el archivo 1.

No también tomaba el archivo 1 y no bloqueaban el archivo 1 acá lo que iba a pasar era que cuando él él subiera, si él era el segundo, pues se borraban los cambios que había hecho el del archivo 1, entre otros inconvenientes. 

# Diapositiva 5
Entonces de esto llegó el sistema de controles destruido, que básicamente lo que me permite es tener una copia exacta del repositorio en mi local. Sí, entonces yo voy a tener la una copia de la rama a la cual estoy trabajando y voy a poder trabajar en mi local.

Entonces esto me va a permitir que cuando yo tenga ya la confirmación de mis cambios, realice, sí, cuando yo descargue la información, realice un push de mi información y yo haga validaciones hacia esto me permite ser más colaborativo, me permite trabajar Más.
Por decirlo así, con mucho más orden puedo tener diferentes versiones, puedo trabajar en diferentes versiones, puedo tener ramas, puedo tener un montón de cosas adicionales.
Que van a hacer que esto sea muchísimo más fácil trabajar con git, sí 1, segundo.
Además de otras cosas que vamos a tener con git.
Ya que es un sistema de control de versiones, pues bueno, cada miembro puede trabajar con un repositorio local.
Adicional a otras cosas que se presentaban cuando yo trabajaba con.
Creo que alguien está pudiendo ingresar a la sesión.
Bueno, aceptar por favor.

Además de otros problemas que que que se me venían presentando cuando yo trabajaba con repositorios centralizados, que si no había conexión, todos quedaron bloqueados con el distribuidor. No voy a tener ese problema si en dado caso.

Este repositorio está caído, yo puedo seguir trabajando cuando restablezca el servicio.
Lo que voy a hacer es ya confirmar los cambios.

En dado caso, por ejemplo, que esto que se cayera, por ejemplo, si git se cae de alguna manera, yo puedo buscar otra alternativas para guardar mi información, ya que tengo una copia en ese momento del repositorio, entonces puedo guardarla en otro lugar y empezar a trabajar y poner a apuntar ese a ese otro repositorio podría ser un repositorio en otra cuenta, por ejemplo en en as shout out, por ejemplo.

# Diapositiva 7
Uso de git.
¿Entonces a meter otras otras referencias a las cuales yo puedo ir haciendo?

Los locales donde yo tengo, digamos el control de versiones local, que fue como les mencioné hace un momento, tengo mi repositorio local y tengo mi control de versiones local. Es la forma, digamos, más sencilla, la que yo puedo tener. ¿El control de versiones? Sí, esto es quizás cuando yo estoy trabajando en un proyecto local donde tengo mi código fuente, almaceno mi código fuente local y lo voy versionando de manera local. ¿Qué problemas tengo? Tengo al tenerlo local, pues bueno, no puedo volver a la en el tiempo.

Tendrías que ir a la versión específica y esto pues se complica en dado caso que yo tenga muchos repositorios, yo tengo demasiados repositorios.

Perdón, tengo demasiados código fuente, demasiados archivos. Voy a tener muchísimos inconvenientes cuando quiera volver a una versión específica.

Esta versión se va, me va a traer problemas porque al final no voy a poder volver a esta versión.

Y usando git, pues me permite tener un historial completo de lo que es la la versión a la cual yo estoy trabajando.

Esa versión puedo almacenar el código de mi código fuente de un equipo de varios equipos en diferentes proyectos en diferentes repositorios. Trabajar en equipo es una de estas. ¿Puedo encontrar errores insertados en el Código? Errores encontrados en mi código, por ejemplo.
Alguien inyectó un error hace dos semanas y yo puedo encontrar quién fue la persona que inyectó no para no para buscar culpables, pero sí para poder identificar cuál fue el código que que se inyectó realizar una retroalimentación de lo que está pasando y seguir adelante.

# Diapositiva 8
Yo puedo instalar git.
¿En cualquier, por decirlo así, en cualquier sistema operativo puedo tener git en Linux, puedo tener git en en Mac? ¿Puedo tener git en en Windows?
Y voy a darle clic a esto. Entonces cuando yo vengo acá.
Yo vengo a esta línea, entonces puedo ver git Sour Culture Management. Entonces él me menciona que es git, entonces Git es es todo es local.
Está diseñado para trabajar con pequeños equipos.
Con pequeños proyectos con con proyectos muy grandes, es fácil de aprender.
Y pues básicamente lo que lo que me permite acá es como una mejora, como subversion, como CSV, como bueno, arcase y otros. Repositorios locales aquí podemos ver, digamos, las empresas que usan git y Google, Microsoft. Bueno, en general git se usa en todo El Mundo. En este momento. 

La última versión de Git. Esto está altamente actualizándose es la 2:43. H, ustedes lo pueden descargar, lo pueden instalar en su. En su máquina puede ser en Windows puede ser en Linux y en Mac en este caso como yo lo tengo yo, ya lo tengo instalado, igual lo lo lo. Les voy a mostrar cómo se instala en dado caso que por ejemplo, si yo quisiera descargarlo para Mac.

¿Vengo acá, hay diferentes alternativas, en dado caso puedo instalarlo con 1,1 manejador de paquetes que se llama Bribu lo puedo instalar en mi máquina? ¿Puedo usar madporse puedo usar scot o puedo instalar directamente el binario? ¿Entonces descargarme el binario?
Descargarlo e instalarlo en mi máquina.
Para para este efecto, pues yo ya lo yo ya lo tengo instalado, pero pues sí, si fuera por ejemplo, para. para Windows.
Entonces pues aquí tengo el el Windows ya tiene un manejador de paquetes como Win Get que yo puedo instalar este este este git o instalarlo para 32 bytes o para 64 bytes. Bueno, en general, exactamente sí para Linux o para Linux. Para las diferentes versiones, para debium, para feedora, para gentuo para H, Linux. Bueno, en general tiene una cobertura bastante bastante grande.

Y seguimos acá, entonces como yo ya tengo instalado git, entonces sí, yo les muestro mi terminal.
Entonces yo vengo acá y le doy bit, sí, si yo lo quisiera, si yo no lo tuviera instalado, pues lo que hago es breve install.
Como me mostraba.No me mostraba la página. Yo voy a Mac.
Ese breve stalgate yo lo le doy a instalar. En este caso no lo voy a instalar porque ya lo tengo instalado.
- (Aqui se puede realizar una demostracion en consola para mostrar de que manera puedo empezar a usar git, descargar, instalar, ver version etc)

Pero git si solo con el comando acá les recomiendo en en en si lo instalan en Windows que usen bash bash forgit la terminal o el semver no digamos, aunque se puede usar, no, no digamos no es tan potencial si no es tan óptimo para para el uso de git.
Mis días anteriores cuando yo usaba Windows tenía algunos inconvenientes. Hay que hacer unas configuraciones específicas para que el Lo tome diferente, dado que en Windows, digamos, es un carácter diferente y cuando estamos trabajando con diferentes personas, por ejemplo, si yo.
estoy trabajando con Windows, hay otras personas que trabajan con Linux o Mac van a tener inconvenientes por este Que genera Windows. Igual se hace una configuración.
Tengo, digamos mi git dentro de Git tengo dentro de mi paquete, pues tengo los diferentes comandos y cada que hace cada comando el git clon cuando yo quiero iniciar un área de trabajo.

Cuando quiero trabajar un proyecto específico, un proyecto vacío.

Cuando quiero adicionar un nuevo proyecto, cuando puedo digamos renombrar un archivo, restaurarlo, eliminarlo. Bueno, en general tengo una serie de comandos que vamos a ir viendo en este momento. De momento voy a mostrarles que cuál es la versión que tengo en este momento. Tengo la versión 2.36. Si yo hiciera una Update me dejaría la versión que le que está acá en este en este lugar.
Para efectos no voy a actualizar nada, voy a dejar todo como está con esta versión puedo trabajar.

¿Libremente, qué pasa con esto? Las versiones de git son, digamos como son, reto compatibles, entonces, en general, funciona para para todas las las versiones, hay algunas que digamos no tienen compatibilidad cuando, pues cuando cambia el mayor, cuando pasa de 1 AA dos pasa mucho tiempo, pero en general las versiones que están dentro de la misma dentro del mismo mínimo ya están de dentro del 363445 funcionan. Entonces acá lo que voy a hacer es.
 - (configuracion del git-config se puede mostrar)
Mostrales, si yo hiciera, por ejemplo, un githconfic, lo primero que tengo que hacer es configurar.

Mi usuario en este caso, pues es el usuario con el que yo tengo o el que yo quiero trabajar. El nombre de la persona.

¿El email, entonces yo puedo hacer Kit config?
Luego guion, guión global.

Y acá le voy a colocar User.
Sur name.
En ese caso, lo coloco en doble comilla.

Voy a colocar mi nombre x lo guardo.
Como yo veo que esa configuración quedó quedó correcta, entonces voy a darle git conflict.
En los menos global.
Y le voy a dar e.

Se acaban, yo ya tenía previamente configurado mi correo electrónico y la rama, entonces acá tenía quedó mi nombre Wilman Spinner, salgo de acá.

La quiero configurar mi correo electrónico, entonces voy a cambiar el correo electrónico que tenía allá por otro correo electrónico, voy a colocarle X


 acá lo que voy a cambiar es el mail.
```
git confit --global -e
git config --global core.editor "code --wait"
```
Lo vengo acá se lo modifiqué, eliminé lo que había en insertado, vale, lo puedo modificar ese nietz es el default branch, en el cual los repositorios que yo voy a crear desde acá se van a se van a se van a crear, entonces siempre se van a crear con el nombre mail. Esto cambió, previamente se usaba era el nombre Master, pero por temas de inclusión fue cambiado a main.

Después de hacer la configuración, entonces yo puedo hacer otra configuración que la voy a probar acá doble busco.

Donde lo que voy a hacer es configurar mi editor, yo no quiero que se vea a la salida de lo que hago en en en el la terminal, sino quiero verlo, por ejemplo, en visual Studio Code. Entonces lo que hago es un ejecutar un programa que se llama Git Config.
No es menos global.

Y aquí le voy a dar Core. para abrir con el Editor.

Dentro de comillas, le voy a decir que voy a abrir con Code, le voy a decir que Espere, o sea que que hasta que yo no cierre la pantalla.Que yo no cierraigamos lo que estoy ya trabajando en no, no, no siga la térmica, entonces voy a darle acá. Entonces vuelvo a ejecutar el comando que yo tenía aquí.
Global y que abra en mi visual Studio Code.

Entonces aquí vino y me abrió un visual Studio Code, me abrí el archivo acá.

Entonces me abrió, ahora me agregó una Se llama CORE y el editor, pues con esta línea lo que voy a poder hacer es que lo que yo haga internamente en visual Studio o lo que yo haga en la terminal, o sea, en esta terminal, se me abra directamente. Aquí vemos que dice que está esperando por el editor para cerrar el archivo. Si yo cierro el archivo acá sí.

Lo que va a pasar es que acá me va a seguir.

31:16
Vale.

31:18
Bueno, nuevamente.

31:20
El comando que yo les mencionaba, entonces esto esto se debe configurar en Windows para, digamos, en un un se llama CR el el el, el Entonces para que los dos trabajen, trabajen bien. O sea, si trabajas en Mac o trabajas en Linux, entonces lo que vamos a hacer es configurar git config.


# Diapositiva 10
Entonces git tiene 3 Estados, git. Cuando yo tengo un proyecto Git.
Tiene 3 Estados, el Estado.

El primer Estado es cuando estoy en networking interruptory es cuando tengo digamos archivos, estoy haciendo cambios. Los archivos pueden estar en confirmado que es comité modificado y preparado.
Cuando yo estoy trabajando en mi primer Estado, pues lo que hago es tener un git, lo que me permite es pues inicializar un proyecto git trabajo en mi working directory en este puedo, pues adicionar eliminar esas modificaciones sobre los archivos sobre 1 o varios archivos, dependiendo de la necesidad cuando yo ejecuto el girat que lo vamos a ver más adelante y agrego el archivo lo estoy colocando en un área que en el segundo en el segundo Estado que es un string área, digamos son los los archivos que están listos para. Ser confirmados en este caso ser comitéados que digamos esto no es una palabra que se usa, pero nosotros en la jerga se usa ya comitio el archivo, pero realmente ya ahí se comete del archivo o de los el conjunto de cambios que estoy realizando cuando hago commit lo que ya lo dejo es en el repositorio. ¿Ustedes recuerdan? Yo tengo un repositorio local donde yo puedo trabajar y hacer todo esto, pero después de tenerlo en ya mi repositorio local, yo puedo sincronizarme con el repositorio en el servidor, entonces es donde donde yo descargue el cambio, si no tengo cambios, lo que puedo hacer es agregar un nuevo repositorio.


En ese caso voy a ir a una carpeta que yo estaba, digamos que yo preparo previamente esto donde pues no tengo nada, tengo un espacio de trabajo que se llama training. ¿Lo volverá a esto? Puedo crear varias carpetas dentro de mi este caso bash.

Entonces sigo con la diapositiva, es como las volver al recapitulo bueno, tengo el el área, el área de working director, donde yo voy a estar trabajando, pues con los archivos y adicionando nuevos archivos, eliminando, haciendo modificaciones el estar, ya ya voy, pues voy a estar ya agregando los archivos porque puedo ser que estoy trabajando diferentes archivos, pero solo quiero agregar un archivo.
Y bueno, solo es que voy a tener listo para poder digamos, confirmar estos cambios y agregarlos al repositorio, en este caso local.
Y bueno, el repositorio local son los archivos que yo tengo guardados que posteriormente voy a sincronizar con el repositorio Con el repositorio en el que está en el servidor.

# Diapositiva 11
- (se puede hacer un workshop en cada una de los comando basicos)
Entonces sigo acá, entonces para esto tenemos unos unos comandos básicos, en este caso para poder inicializar tengo dos alternativas, 1 es inicializar un repositorio nuevo. Sí podemos iniciar un proyecto nuevo usando pues git y need realizar la iniciatización de este repositorio puede ser en una carpeta o en un proyecto. Yo vamos a un espacio configurado y preparado, o lo que puedo hacer es un git clon y descargarme una copia de ese repositorio existente.

En nuestro computador personal, en este caso lo que vamos a hacer para para esto lo que vamos a hacer es es usar Git Init, entonces voy a crear una carpeta, en este caso voy a dar MKDIR en en el caso de los que usan Windows es DIR y voy a crear una carpeta que se llama web.

Voy al LS para robar los archivos, tengo mi carpeta creada, ahora voy a ir a esa carpeta CD Web App.
Con TAP lo que puedo hacer es en en Mac lo que puedo hacer es es que me tome, digamos el el el campo, o sea me me autocomplete acá vuelvo a revisar, no tengo nada, entonces si yo ejecuto el comando Git Init.

Lo que va a hacer es inicializarme el proyecto, entonces yo doy un LS no voy a dar nada porque lo que me hizo fue crear una carpeta. Git los archivos. Git son archivos ocultos. Entonces lo que voy a hacer un es un LS -a

En ese caso, pues tengo la raíz donde estoy si quiero volver atrás con CD: puntos y el archivo. Git.

Eso lo podemos hacer desde pues desde desde el desde, pues antes de visual Studio o lo podemos hacerlo terminal desde desde donde estamos en este momento. Entonces voy, ya no tengo nada si vuelvo a estar LS menos LA los voy a ver mi archivo.

Ahora quiero ingresar a ese archivo, entonces le doy CD .Git.

Internamente dentro de git.
Dentro de Github tengo cuando inicializo de buena vez se inicializa las configuraciones que tengo este repositorio, una descripción, los hooks, digamos carpetas que están acá referencias, digamos esto, esto siempre van a ser carpetas que va a tener git para poder digamos hacer una una comparación local dentro del del del código de lo que estoy, de lo que estoy trabajando en este momento, lo que estoy trabajando es en mi, en mi working area, en este espacio que tengo acá no tengo ningún archivo, la idea es poder hacer la inicialización de un archivo.

Y para esto lo que voy a hacer es crearme un archivo en este ya inicialice mi proyecto, entonces voy a volver otra vez atrás. CD dos punto punto acá. Bueno, no veo nada, si doy le dije sí.

Pues ya va en la carpeta, ahora lo que voy a hacer es inicializar un archivo, entonces voy a crear un archivo en este caso.
Pues se va a llamar archivo. vim prueba.txt
y le doy LS entonces ya tengo mi archivo y si ustedes se dan cuenta inmediatamente desde que inicialicé, dado que yo tengo digamos una terminal y uso unas configuraciones específicas, me apareció la rama en la cual estoy trabajando, si ustedes vieron, yo tenía configurado por acá en mi git config, no sé cuestiones ese comondo.


Yo tenía configurado que mi mi, mi branch por defecto es made, entonces si vemos acá ya me aparece la Roma main y me aparece un* Quiere decir que yo ya hice cambios esto porque tengo configurado una extensión que me permite visualizar esto.
En dado caso que yo no tenga, digamos.

Yo no tenga un una forma, digamos, no tenga 1111 librería que me permita ver esto. Yo lo que puedo hacer es git status, que lo vamos a ver acá, git status.

Ahora ya tengo mi archivo si yo ejecuto git status siguita estatus me permite revisar cómo está actualmente el estado del de, digamos, del repositorio. En este caso mi estado del repositorio es lo que dice que tengo archivos me parece en rojo lo que quiere decir es que está en mi work en área, no está en esta llenaria entonces acá yo no he confirmado ningún archivo, yo no lo único que tengo es un archivo que he creado nada más dentro de esto, lo que voy a hacer es modificar.


Rellenar acá eso se puede hacer en visual Studio o se puede hacer en en en directamente desde la terminal lo voy a hacer desde la desde visual Studio. Entonces lo que voy a hacer es Code.

41:04


41:07
Voy a abrir todos mis repositorios de visual Studio, entonces voy AA abrir un un code.

41:12
Acá ya tengo mi mi visual Studio, tengo mi archivo en mi archivo no tengo nada, entonces lo que voy a hacer es es este es el a modificar el archivo archivo 1 de la capacitación.

41:36
Lo que hago es almacenar merch si yo vuelvo a la terminal nuevamente acá le voy a dar un zoom para que ustedes puedan ver mejor.

# Diapositiva 12
Ya es una modificación sobre el archivo, inclusive agregando el archivo ya es una modificación porque partió un repositorio en en cero, lo que quiero hacer seguimos en la en la es adicionar este este este archivo amishta generary estoy trabajando en el working director y ahora quiero adicionar este archivo. Hay diferentes comandos que yo puedo usar, puedo agregar 1 o varios archivos, en este caso voy a agregar 1. También puede usar gitat punto o gitat gov que es otro comando.

No es digamos, no es una muy buena práctica darle equidad junto porque a menos de que yo esté seguro de lo que he modificado, está correcto, pero se me pueden adicionar archivos que yo no voy a tener en cuenta cuando le doy gida punto porque lo que va a hacer es tomar todo lo que está pendiente, lo que está en el working directory va a pasar al al, al staging Area.

42:45
Entonces lo que hago es.

42:49
Agregar este archivo voy para acá, entonces voy a decirle git at.

42:55
Y voy a archivo.

43:01
Entonces vuelvo y reviso cómo está mi Estado. Entonces git status recuerda que git status lo permite es identificar el estado de los archivos.

43:12
Entonces él me dice, cambió el Estado, ahora me dice, me aparece aquí me aparecían rojito. Ahora aquí me aparece en verde. Eso quiere decir que mi archivo está en mi stationalia es un archivo que está.

Está agregado y que si yo uso otro comando, lo lo lo que voy a hacer es confirmar este comando, mi ruedo repositorio, si yo agrego un nuevo archivo, entonces voy a ir a visual Studio y le voy a dar agregar un nuevo archivo. Este archivo se va a llamar archivo guión dos.
Y me aparece un archivo en extraordinaria y un el archivo dos en mi working directory. Quiere decir es que si yo confirmara en este momento los cambios, solo este.

Listo ahora lo que voy a hacer es agregar git up, agregar el archivo dos a mi.
Qué ocurre si hacemos una una modificación, dime, disculpa, y ahí, en ese sentido, con el el otro que aparecía el git a punto que lo que hace lo agrega igual que el anterior.

45:14
Sí, lo que pasa es que va a tomar todos los archivos que estén en mi working director. Ejemplo, si yo tuviera, por ejemplo, acá un archivo, por ejemplo, no sé una imagen que pensaba un giga si yo le doy gilat lo que va a hacer es agregar también esa imagen, agrega. Todo lo que está dentro del archivo, también agregar todo lo que está en mi working directo. Recuerda que es un control de versiones en no determina qué tipo de archivo es lo que hace, únicamente es si yo lo digat. Carga todo y no es una muy buena práctica.

45:47
Lo que lo que puedo hacer es tomar un archivo o tomar varios archivos, tomar un folder específico para esto.

45:54
Igual ahorita Ahorita ejecutamos el comando git up.

45:58
Ahora voy a hacer una modificación, por ejemplo, sobre.

46:02
El archivo dos entonces este es el archivo dos lo que voy a agregar es una Entonces ahora voy a agregar agregando.

46:11


46:13
 

46:16
A mi.

46:19
Archivo.

46:21
Lo guardo.

46:23
Hoy nuevamente al terminal y le doy click estatus.

46:29
¿Entonces, qué es lo que pasó acá acá? Me parece que el archivo también está acá.

46:33
Sí, el archivo dos está acá y el archivo también está en mi working directory.

46:38
Sacar lo que me está diciendo es que este archivo.

46:41


46:44
Tiene un contenido distinto, lo que yo adicione tiene el contenido con una sola línea.

46:50
Sí, o sea, este archivo tiene esta sola línea, o sea, el que está aquí, pero yo realicé una modificación, entonces ya no va a ser un nuevo archivo, sino va a ser una modificación que hice dentro de mi working directory. ¿Sí, pues, como dice esta modificación, él va a tomar, digamos, la diferencia que tengo él me va a decir, Mire usted hizo una modificación después de haber agregado ese archivo al esté llenaria, entonces lo que va a hacer o qué va, qué va a hacer con esto si lo va a descartar? Puede usar 1 de estos comandos o si lo va a agregar, puede usar git up si yo ejecuto, por ejemplo, Getafe.

47:21
Es lo que me estabas preguntando, él toma en ese caso todo lo que haya en el en el directorio. Recuerde que el **** es la raíz donde yo estoy en este momento, si yo doy git status.

47:33
¿Me van a parecer que los dos archivos fueron agregados, ya no me aparece que el archivo ha sido está en Networking directory en en este momento, vale?

47:43


47:46
Y bueno, básicamente porque hemos agregado modificaciones a nuestro archivo.

47:50


47:53
Y pues pasamos estas modificaciones, ahora sí, a nuestro escenario quiere decir que este archivo dos tiene las dos modificaciones que hemos realizado.

48:03
Igual si usan una extensión les voy a mostrar, digamos, las nuevas modificaciones.

48:07
Seguido a esto, ya digamos, pasamos del working directory al streaming area de un archivo. Ahora lo que vamos a hacer es ver el Estado, ya lo hemos trabajado. El estatus me permite ver, pero pues yo puedo verlo, por ejemplo, Git status.

48:24
No sé si, por ejemplo.

48:27
Me muestra, digamos, mucho más corto esa información y me muestra acá una. ¿Este caso es que adicionó, hay otros Estados como lo veíamos en en en en en la en la anterior, que puede ser al comité, ha modificado? Sí, hay diferentes Estados. En ese caso, me parece una que es que fue agregada.

48:47
Sigo acá, si ahora lo que quiero pasar este mis Station Area ya agregué.

48:55
Mis archivos al statement area ahora quiero pasarlos a mi repositorio local. Yo creo un repositorio local cuando dice guitinit, entonces lo que puedo hacer es usar este comando que se llama Git Commit, el menos MS que voy a agregar un mensaje sobre este sobre este, sobre este, sobre este commit que voy a hacer, o sea sobre esta confirmación que voy a realizar, en este caso voy a confirmar los dos archivos, archivo 1 y archivo dos.

49:18
Esa Convención, pues tienen unos estándares, debe ir entre comillas, deben inscribirse en el presente, deben ser breves.

49:27
Menos de 50 caracteres.

49:35
Deben ser menos de 50 caracteres y hay otros estándares, como el conventional commit, que ya son estándares de la industria donde se van agregando nuevas etiquetas. Smart commits, por ejemplo, agregar la tarea a la cual yo estoy trabajando en este momento y.

49:50
Y bueno, ahí hay otros, pero en ese caso vamos a usar un githcomit con el un commit simple para nuestro, para nuestro, para nuestro taller.

50:00
Entonces el kit estatus bueno me muestra, entonces vuelve a limpiar la la la la terminal. Voy a elegir estatus nuevamente tengo estos dos. Ahora quiero confirmar mis cambios. O sea, quiero confirmar estos dos y pasarlos a mi repositorio. Les doy git.

50:14
Twitter.

50:16
Menos M.

50:19
Y aquí le voy a decir confirmación.

50:25
Confirmación inicial.

50:28
Para.

50:30
El archivo.

50:34
Y.

50:36


50:38
Ejecut, entonces él me dice que insertó dos cambios, tiene 3 Inserciones y creó, digamos, entonces, si yo hoy git status.

50:49
No me aparece ya lado porque no tengo nada en el en el working directory y no tengo nada en el escenario. Quiere decir es que ya confirmé mis cambios en mi repositorio local.

50:59
Listo, ahora yo quiero hacer nuevamente una modificación entonces, pero quiero conocer las diferencias que tengo con respecto a lo que yo modifiqué a los cambios que tengo desde mi último commit con el archivo que estoy modificando. Entonces voy a ir a mi visual Studio, voy a cerrar el archivo dos, voy a ir a este y voy a agregar agregando una 

51:30
A mi archivo.

51:36
Voy a guardar, voy a ir a mi terminal.

51:40
Y voy a darle git estatus menos.

51:46
Solo corto recibían que anteriormente aparecía a digamos at agregué un nuevo archivo a mi repositorio. Aquí me están mostrando que hice una modificación si yo le doy el corto, entonces me dice que hice una modificación al archivo 1, ahora quiero quiero revisar.

52:04
¿Qué cambios fue los que yo realicé? Entonces le doy git bebif e archivo.

52:12
Lo puedo hacer con branch, lo puedo hacer con commits. En este caso lo voy a hacer desde mi mismo repositorio. Entonces aquí me muestra.

52:19
Los cambios que yo realicé.

52:21
Me dice que acá eliminó esto.

52:24
¿Y yo YYY por qué lo eliminó? Y aquí lo vuelve a agregar dos veces. Lo que pasa es que en mi archivo yo agregué a esta parte, hice un O sea, le di Enter esto como es un carácter git lo toma que hubo un cambio en esta línea, entonces lo que hace es agregarla, YYY, eliminarla y agregarla, entonces por eso me aparece este cambio, este cambio acá sí, entonces voy a darle salir a la tecla Q.

52:53
Sí.

52:55
Y lo que voy a hacer ahora es agregar ese cambio.

52:59
A mi repositorio, entonces voy a darle, voy a agregarlo al al Stationary. Estoy trabajando en el working director en este momento porque tengo un archivo que fue modificado. Entonces él me dice, acá, mire para, digamos, para restaurar, para agregar YYYYY, realizar un commit o para descartar los cambios en mi working Electric. Entonces voy a ligar lo que voy a hacer es agregar ese este cambio a archivo dos.

53:23
Un archivo 1 PXC.

53:30
Archivo 1, Tx. Ahora le doy git status.

53:38
Y pasó el working director y al al Excellenia le voy a dar git commit.

53:44
En un CM.

53:46
Y aquí lo que voy a decir es, se agregan.

53:50
Modificaciones.

53:54
Para el archivo.

54:02
Solamente tiene que.

54:04
Y vuelvo a Arquitectatus.

54:07
Yo no tengo nada.

54:10
Pero ahora quiero ver cuántos commits yo tengo en mi repositorio, recuerde que acá estoy trabajando local acá no estoy trabajando con github, estoy trabajando con otra herramienta, con un servidor. Solo estoy trabajando en local.

54:21
Entonces vuelvo acá.

54:24
Aquello sí, ya me parece, digamos en este caso, visual Studio identifica que tengo modificaciones. Entonces ahora lo que quiero es, después de hacer la validación, lo que quiero es revisar el nuestro historial de nuestro proyecto, en este caso nuestro repositorio. Quiero ver cuántos cuántos commits se ha realizado, dónde está quedando lo que yo he confirmado entonces con el comando Gitlock voy a darle, voy a limpiar mi área, voy a Lake Git Lock.

54:50
Entonces acá puedo ver varias cosas, 1 puede ver.

54:56
Dice commit y dice ID github, perdón, kit sorry it adiciona un ID para el commit que yo he realizado y me muestra la rama, o sea la cabeza la rama en este momento. ¿Cuál es la rama principal que es main? Sí, el autor que hizo el commit sí.

55:19
El la fecha, en este caso me dice que lo hicimos en diciembre cuatro a las 7:51 H y el mensaje que yo envié el mensaje, este mensaje inclusive puede ser un poco más robusto, no puede ser tan básico como esta, está acá y me muestra.

55:32
Los comits, o sea, las confirmaciones que yo he realizado entonces a las 7:47 H realizamos otra confirmación que fue cuando agregamos el archivo I dos y a las 7:51 H Agregamos modificaciones al archivo 1.

55:47
Yo salgo de acá.

55:49
Digamos, ya digamos, pude ver los logs. Ahora lo que quiero hacer es seguir trabajando con mi repositorio. Ahora, digamos, por ejemplo, quiero renombrar el archivo. Quiero cambiarle el archivo de nombre, entonces voy a ir acá.

56:02
Digamos si yo lo hiciera desde la terminal, sería algo así sería MB.

56:09
Archivo bueno, por ejemplo, quiero cambiar el nombre, entonces lo voy a archivo.

56:15
¿O no?

56:16
. TXT.

56:20
Entonces voy a cambiarlo, voy a leer estatus siempre que hago un cambio es el comando más usado, git status. Aquí me aparecen dos cosas, 1. ¿Me dice que cambios que conoce, o sea que en algún momento fueron creados, entonces me está diciendo que voy a eliminar, por qué voy a eliminar? Porque le cambié el nombre y me dice que voy a agregar un nuevo archivo. Entonces, como cambió el nombre, le identifica que se hizo la eliminación y se y se agregó un nuevo archivo. Él no identifica que hubo un digamos, 1111 remake, digamos de esta manera, como lo estoy haciendo.

56:54
Entonces lo que voy a hacer, en este caso voy a decirle git at, entonces tengo que agregar los dos archivos archivo, en este caso el que eliminé.

57:04
Que es el mismo, pero digamos git lo toma de esta manera y archivo.

57:09
1, que es, digamos, como se llama lo agrego, si yo le doy nuevamente quite estatus.

57:16
Sí me aparece aquí, me identifica que fue renombrado, o sea, que archivo 1 pasó a ser archivo 1, pero con el el número 1 yo le git status menos ese que es digamos el corto, me parece que fue renombrado. Sí, entonces van cambiando los Estados.

57:37
Y yo lo puedo confirmar, en este caso, Git tiene un comando específico. Sí, para hacer esto, entonces yo puedo darle git RM.

57:47
Recuerde que ya están, este archivo está en mi stajing directory. Sí, en mi stainario perdón, estoy trabajando en mi working directo. Entonces yo le doy git RM.

57:57
Sí.

58:00
Perdón, git, estoy renombrándolo.

58:03
Esto nos quita, realmente estoy renombrándole a ARGE MBRM es para borrar git MB.

58:11
Y voy a decirle.

58:14
Cuál va a ser el archivo que voy a modificar, que básicamente es el mismo comando que tengo acá, pero lo voy a hacer al revés, entonces voy a copiar esto, acá voy a decir archivo 1.

58:24
Y aquí va a ser archivo_ 1. TXT.

58:34
Este comando me permite.

58:37
No pasó ni siquiera por mi, por mi working directo, sino paso al stay área de una base. Yo le doy git status.

58:48
¿No pasó nada, por qué no pasó nada? Porque yo no había confirmado mis cambios. Entonces se le identificó que el archivo no ha sufrido cambios. Si yo vuelvo y le ejecuto, en este caso cambio el orden.

59:01
Y le doy.

59:03
Cambié el nombre.

59:10
Cambié el nombre punto Exe.

59:14
Me voy a caer, le doy quit status automáticamente, ni siquiera paso por el work directory, sino.

59:20
De una vez.

59:23
De una vez me cambió, me me me pasó este archivo al al al Este llenario voy a confirmar este este cambio, te lo doy git commit.

59:33
Commit menos M.

59:37
Y le voy a dar cambiando el nombre.

59:43
Archivo.

59:46
Listo, entonces voy a dar arquitectato.

59:50
Y si yo le doy gitlock.

59:53
Pero ahora quiero utilizar este que se llama One Line, me va a aparecer en una sola línea que es mucho más eficiente los commits que yo he realizado con un ID corto no es ID grande. Entonces cambiando el nombre, se agregaron modificaciones al archivo y confirmación inicial. He hecho 3 commits, sí.

1:00:10
Pero ahora lo que quiero hacer es, digamos, le doy git statustatus, ya no tengo nada. Ahora lo que quiero hacer es eliminar este archivo.

1:00:18
Sí, si yo le diera ese, identificamos que el nombre cambió, si yo me voy aquí a mi repositorio, él me dice que este archivo ya no existe, que lo eliminé, pero se llama. ¿Cambió el nombre? Sí, entonces voy a renombrarlo nuevamente voy a darle bit.

1:00:34
Perdón, git MB.

1:00:40
Entonces se llama cambio.

1:00:43
Archivo.

1:00:45
¿O no?

1:00:47
. TXC.

1:00:50
El kit estatus.

1:00:58
Con leledit estatus me dice que lo renombre voy a confirmando github me menos M revolviendo nombre.

1:01:16
El kitestatus.

1:01:19
Git Lock.

1:01:22
Menos One line.

1:01:24
Y bueno también se devolvieron nombre, cambiando si yo vuelvo otra vez acá él me dice que este fue eliminado, pero cambió el nombre se fue renombrada listo entonces ahora lo que quiero hacer es eliminar un archivo. Si yo, por ejemplo, lo lo tomara acá.

1:01:41
Y en este caso y le diera eliminar, doy delete.

1:01:46
Elimino el archivo dos.

1:01:50
Sí, y vuelvo aquí, doy git status.

1:01:54
Él me dice que este archivo fue eliminado si yo quisiera.

1:01:58
En este caso seguimos acá eliminando Gui Resort y Tmb y acá.

1:02:06
Entonces.

1:02:09
Dame 1 segundo.

1:02:11
Entonces acá lo eliminé, entonces yo yo yo puedo eliminarlo de esta manera. O puedo usar git. RM, si yo doy git status, vemos que está eliminado. Si yo le doy git up, estoy diciendo es que archivo dos, estoy agregando mi esta llenaria el kit estatus.

1:02:34
Él me dice que han sido eliminados y yo le doy este comando, git status S.

1:02:39
Me dice, me cambio, ahora ha eliminado, ya no es modificado. Vimos más arriba que estaba como adicionado, modificado, renombrado y eliminado. Si yo le doy git commit.

1:02:52
M.

1:02:53


1:03:06
Digamos, yo no quiero, yo no quiero en.

1:03:10
¿Este caso, yo no quiero eliminarlo, sí, entonces qué tengo que hacer? Entonces quiero que tome aquí un poquito más adelante.

1:03:20
Vamos a ver.

1:03:21
¿Entonces qué tengo que hacer? Este archivo está en MySpace, en MySpace, en MySpace Station área cierto, entonces primero tengo que sacarlo de MySpace área, entonces para no quiero eliminarlo, me equivoqué, entonces voy a decirle git acá, me dice el comando. Entonces le doy restore.

1:03:40
Sí, pero quiero sacarlo de mi stage área, entonces voy a decirle Git Stage.

1:03:45


1:03:48
Y es el archivo dos.

1:03:53
Perfecto, entonces como tengo primero que sacarlo de mi, de mi.

1:03:59
De mí, de mis tesis área, pues lo de git status.

1:04:04
Entonces él me dice, Mira.

1:04:07
Ya sale mi stage sharia.

1:04:09
Pero igual lo tengo en mi working director eliminado, entonces no lo quiero eliminar. Entonces él me dice para para descartar los cambios, lo que tienes que ejecutar es git Rev histore.

1:04:21
Y.

1:04:22
El restor y el nombre del archivo, que es archivo.

1:04:28
Archivo dos.

1:04:35
Id.

1:04:38
Uy, LS.

1:04:40
El archivo está ahí, no los mostré antes, pero pero esto lo hace más fácil. Git entonces yo le doy git RM.

1:04:48
El archivo dos.

1:04:53
Solo con este comando, él inmediatamente me elimina si yo le doy, LS acá elimino el archivo, si yo voy aquí a visual Studio lo eliminó.

1:05:01
Y Sorry.

1:05:04
Y si yo le doy git status.

1:05:08
Me dice que lo eliminó si lo XS, que es mucho más corto, me dice que aparece con delete.

1:05:15
Imprimir si quiero eliminarlo ya no lo quiero restaurar. Vuelvo otra vez git status para ver ese es el comando más usado, el Script Commit menos M.

1:05:26
Aquí, Eli.

1:05:30
Nashro.

1:05:34
Sigo.

1:05:38
El quinto estatus.

1:05:42
Y ya no tengo nada en mi celular, ahora le doy gitlock.

1:05:47
Y puedo ver que eliminé el archivo devolviendo el nombre cambiando el nombre, agregando si yo quisiera volver otra vez que lo eliminé por error, voy a volver al commit, igual lo vamos a dar rato aquí. Mover listo.

1:06:04
Por ejemplo, entonces yo.

1:06:09
Segundo.

1:06:11
Entonces yo quiero.

1:06:14
Digamos, kit tiene una serie de.

1:06:22
1 segundo y tiene una serie, digamos, de workflows o de alternativas que me permiten a mí trabajar dentro de mi repositorio local. Entonces una de estas es que yo puedo tener diferentes ramas, o sea, puedo hacer ramificaciones y puedo tener un por decirlo así, multiverso de mi proyecto. Eso suele pasar que hay en algunos proyectos, se se vuelven multiverso porque hay muchísimas ramas. La idea es que estos workflows sean workflows que se trabajan con el estándar.

1:06:52
Hay diferentes estándar que se han venido trabajando, que se han se han venido, digamos, puliendo para que digamos los diferentes desarrollados.

1:06:58
Equipos trabajen con estos estándares y para esto digamos, cuando yo quiero crear una rama.

1:07:04
O ver en la rama a la que yo estoy en este momento, digamos una rama o un branch es.

1:07:10
Es digamos, una bifurcación o una copia del lugar donde yo estoy trabajando.

1:07:16
En lugar de donde yo estoy trabajando y tengo una copia que no quiero digamos, en este caso no quiero tocar la rama main sí, mi rama principal. No quiero hacer modificaciones, amor y mi rama porque es una rama bastante sensible a la cual no quiero realizar modificaciones directamente. Quiero tener una copia y hacer cambios sin ningún problema, obviamente pues es.

1:07:38
Cambios, pues van a ser de desarrollo de software y quiero hacer esos cambios y quiero y quiero que estos cambios.

1:07:46
No vean afectada la rama principal entonces.

1:07:49
Si yo le doy kick Price en este caso.

1:07:53
Sí que este es otro comando, entonces me va a mostrar las ramas que yo tengo.

1:07:59
Yo tengo en este caso, pues solo tengo una que fue la que cree inicialmente cuando cree el repositorio, entonces voy a decirle que voy a crear una nueva rama. Entonces grit Brunch. Hay dos formas de hacerlo, yo puedo hacerlo con git Range y que puedo usar checkout. Sí, el checkout funciona para dos cosas, 1 cuando tengo una rama en un repositorio remoto, en este caso en mi servidor y quiero descargar esa rama sí o cuando quiero agregar crear una nueva rama, puedo usar el comando el git Checkout Bo puede usar git.

1:08:31
Y darle el nombre, pero igual Git Checkout va a estar presente si yo le doy git prunch, entonces voy a darle new.

1:08:39
New Rall, New Brunch.

1:08:45
Entonces vuelvo a ejecutar kitprunch, que fue el comando que teníamos acá y él me va.

1:08:50
A.

1:08:52
Crear dos ramas, en este caso me muestra un* porque estoy en la Roma main, pero sigamos, quiero pasar a la otra rama para salirme de acá. Le doy clic checkout.

1:09:05
Eso me permite, digamos, pasar entre ramas, no le voy a dar ningún menos. El menos B es para crear. Entonces voy a decirle que voy a pasar a new.

1:09:14


1:09:18
Pasar a new grunge.

1:09:22
¿Qué pasa? Yo le dije Checkout.

1:09:26
Out, ramas.

1:09:30
Me dice que pues no hay una rama en este momento, no puedo moverme entre esa rama, pero si yo le doy KID Prunch.

1:09:41
Pero de git Range me va a decir que estoy en la rama.

1:09:46
En la rama new Ranch y pasaré la rama Meade, hay otro comando que se llama es el gith, que también puedo pasar entre ramas, pero este digamos no descarga ninguna información. El check out me permite descargar información del repositorio remoto.

1:10:01
Listo, entonces con esto ya digamos, podemos ver que hemos creado una rama. Hemos haciendo un repaso, hemos.

1:10:09
Eliminado, hemos renombrado, hemos agregado.

1:10:14
Agregado archivos a nuestro de nuestro Work Interruption área de nuestro Stalin área hemos hecho confirmaciones a nuestro repositorio si yo reviso, por ejemplo, este branch.

1:10:25
Y le doy, por ejemplo, Kit estatus. Sí me dice no tengo nada, pero él me muestra la rama a la cual estoy en este momento. Ahora, si yo le doy, por ejemplo, un gitlock.

1:10:34
Sí, uf, magia, sí, él me dice que hay una nueva rama YY de una vez me va sacando la bifurcación. Me va haciendo, digamos, me muestra de dónde viene esta rama y todos los commits que yo había hecho en main van a estar acá.

1:10:50
Porque es una copia realmente de la rama Mint, o sea eliminando, devolviendo, cambiando el nombre del archivo, se agregaron y las horas y el ID si yo me salgo de acá, le doy por ejemplo, Kit lot menos One line es un comando bastante útil.

1:11:05
Me aparece en una sola línea cada 1 de los commits y el ID de cada 1 de estos. Estos los se usan bastante estos ID para hacer validaciones, entonces seguimos acá, ya hicimos el checkout, ahora queremos ver diferencias de nuestro Branch 1 o nuestro branch, dos de un de una modificación.

1:11:27
Es en casos, qué caso sería que yo haya hecho una modificación en mi archivo acá visual Studio Code también me identifica que se creó una nueva rama.

1:11:37
Puedo trabajar desde visual Studio, pero entonces voy a hacer una modificación, entonces agregando a mi archivo agregando.

1:11:45
Una segunda línea.

1:11:49
Amy archivo.

1:11:53


1:11:54
Y le voy a dar guardar.

1:11:56
Yo miro acá, entonces pues ya le quit status. Él me dice que hay una modificación de este archivo, pero ahora quiero usar el DIF mucho más poderoso. Entonces quiero decirle Gif Dif.

1:12:09
Quiero decirle Gitdef.

1:12:13
Pero necesito identificar la rama, entonces la rama ya las ya sabemos cuál es, entonces voy a decirle, voy a comprar los cambios en mi New Bryan.

1:12:26
A mí, Ramón Mein. ¿Cuál archivo? Pues el archivo 1.

1:12:30
Y Ah, no me aparece nada, porque seguramente.

1:12:40
Yo.

1:12:46
Uy, no me parece nada. ¿Por qué creen que no me aparece nada?

1:12:50
Esto pasa porque.

1:12:53
Yo tengo mis cambios.

1:12:56
En mi working directri yo no tengo ninguna confirmación de los cambios.

1:13:01
Sí, al no tener ninguna confirmación, pues él no va a identificar.

1:13:06
Que he hecho cambios, sí, solo estoy trabajando en mi directorio, en mi directorio local no tengo ningún cambio, digamos confirmado en mi repositorio. Esta nueva rama es un pues es un repositorio de una rama agregada a nuestro repositorio. Lo que yo puedo hacer es git up.

1:13:23
1 lo agrego, le doy git status.

1:13:28
Menos ese.

1:13:32
El archivo 1. Ahora le doy gitcommit.

1:13:36
Ah, digamos, quiero hacerlo otra vez. Quiero evaluar este este cambio, no me aparece nada. Estoy comparando, es el branch mas no comparando los commits, ni siquiera estoy comparando el código si yo hiciera por ejemplo, un gift.

1:13:48
Sí le lo lo lanzar así, no, no, no tengo ninguna modificación porque ya lo agregué a mi, a mi extraordinario. Entonces ahora le doy git commit menos M.

1:13:59
Y voy a decirle que esto es 1, segundo sigo acá.

1:14:07
Ta ta ta voy a decirle que se agrega.

1:14:13
Begam.

1:14:14
Una.

1:14:16
 

1:14:20
Gif status no tengo cambios y ahora sí voy a ejecutar mi comando ya le controle, acá voy a ejecutar mi comando que se llama Github, New Branch. Sí entonces ejecuto y él me dice que.

1:14:34
Tengo tengo diferencias, sí, porque tengo un montón de diferencias. Claro, lo que pasa es que estoy comparando la rama main, estoy comparando la rama main al revés, si yo lo hiciera, por ejemplo, sí quiero.

1:14:48
Main.

1:14:50
Con new.

1:14:53
Drunch.

1:14:58
Dice que adquiere Minecraft, fue por lo que inserte un nuevo Estas no las modifiqué sí no hice ninguna modificación. Entonces aparece igualita a este le agrego un Y esta es la segunda línea que yo agregué. Entonces me aparecen los dos cambios bien, y esto pues ya está confirmado, inclusive yo no puedo hacer esto con un.

1:15:20


1:15:21
Mis cambios locales, entonces voy a darle otra vez acá y voy a decirle o One line.

1:15:27
Yo quiero ver, por ejemplo, esta una Quiero comparar este commit con este commit, voy a voy a tomar estos dos commits los voy a guardar por acá, por ejemplo, en un nuevo archivito.

1:15:38
Sí.

1:15:40
Y voy a comparar estos dos comits.

1:15:44
Entonces me voy acá, voy a darle salir, entonces voy a darle git.

1:15:52
It, Dif.

1:15:55
Y voy a copiar estos dos estos dos.

1:16:00
Que lo voy a cerrar, esto no lo necesito.

1:16:04
Voy a comparar estos dos que están acá, entonces los voy a copiar y las voy a pegar acá y de archivo.

1:16:12
No.

1:16:13
Estoy comparando al revés, sí, porque los estoy eliminando. Entonces lo que voy a hacer es pararlos, comparar el más antiguo con el más nuevo.

1:16:24
Es.

1:16:31
También aparece este archivo porque estoy comprobando comets, si yo lo hiciera, por ejemplo con 1 más viejito. Ejemplo.

1:16:39
Era era gitlock.

1:16:43
Era.

1:16:44
Git.

1:16:46
OK.

1:16:49
Ahora no lo quiero comparar, pues ya le no lo quiero comparar con.

1:16:57
No lo quiero comparar con este, sino con el primero que tengo acá.

1:17:02
Sí te va a salir.

1:17:04
Pues ya compararlo con.

1:17:08
Netflix.

1:17:11
Pararlo con.

1:17:18
Con.

1:17:21
Archivo.

1:17:25
Usted me va a mostrar que al del transcurso del tiempo esta rama se eliminó porque agregaron, se agregaron 3.

1:17:33
Con con un commit muchísimo. ¿Entonces aquí me dice dónde soy git? ¿El archivo 1 ya es el mismo archivo de estos commits entre este y este me está diciendo que se hicieron?

1:17:46
Se adicionaron 3.

1:17:48
3 cambios visita ahora seguimos, ya revisamos como hacía con un commit. Ahora yo quiero descartar cambios, entonces estoy en mi rama, quiero saber en qué rama estoy hit ranch.

1:18:01
Ese es mi ramaño salgo nuevamente, entonces quiero descartar CAPS, me voy a ir aquí a mi a mi cerrar esto no lo necesito. Quiero ir a mi a mí. Entonces eliminé estas dos líneas, le voy a dar guardar. Sí, entonces voy a decirle quite estatus.

1:18:21
Pero yo cambié estas estas estas líneas, pero yo no quería hacer ese cambio. Entonces lo que yo puedo hacer es darle un comando que me permita descartar esos cambios, sí, pero en ese caso quiero descartarlos del repositorio, sí.

1:18:36
No quiero, no quiero descartarlos porque yo podría usar un git resort y él me descartaría los cambios. En ese caso lo quiero hacer desde mi working directory. Lo quiero. Quiero descartar, digamos este entonces voy a usar este git checkout y voy a darle el archivo y checkout.

1:18:56
El checkout me funciona también para archivos y para ramas les voy a leer archivo 1 y le doy ese comando me si yo le doy quita estatus.

1:19:06
Lo que pasó es que ya no tengo el cambio modificado, reviso nuevamente acá y el cambio fue modificado.

1:19:16
Esto es cuando digamos hago cambios directamente a la rama YY no los tengo digamos almacenados, aunque puedo usar Git restor y puedo usar otros cambios. ¿Entonces ahora qué pasa cuando yo?

1:19:32
Cuando yo hago quiero eliminar un commit, o sea, quiero volver a una versión de un commit específico. Yo le doy gitlock, este ya es un comando que se va a usar bastante. Voy a darle salir acá, entonces Git lock.

1:19:47
Menos online quiero verlo más corto, pues quiero resetear mis cambios a esta versión.

1:19:55
Sí.

1:19:56
Quiero, quiero, quiero eliminar este cambio que yo había hecho acá, sino quiero volver a la versión a la versión.

1:20:05
Entonces para eso, porque ya no estoy trabajando sobre working Direct, estoy ya es quitando cambios, es uso github reset.

1:20:12
En cambio, me permite ese comando me permite resetear mediante un hash, entonces voy acá.

1:20:20
Bueno, el git checkout. Antes de eso, el Git Checkout lo puedo hacer también por un archivo, por una cantidad n de archivos o por todo el directorio G Checout menos menos punto lo haría para todo el. O sea, si yo tengo, por ejemplo 10 cambios o 10 archivos.

1:20:36
Si los elimino, ya no los puedo volver a tener, no, entonces si los si los modifiqué y no eran modificaciones que tendría que hacer y le hago un check checkup. Él va a quitar todos los cambios que yo tenía mi working directo. Ahora si yo quiero cambiar, quiero deshacer cambios, o sea, quiero retroceder en el tiempo porque hice un commit que no debía hacer porque inyectó errores o porque ese comic no se debió haber ahí porque me equivoqué.

1:20:57
Por sí, por muchas razones, entonces yo puedo usar el comando Gitwitzit puedo resetear, digamos. ¿Aquí hay diferencias a nivel de resit puedo hacer un reset hard? El Heart elimina el commit sí, o sea, lo deshace, lo lo, lo, lo lo quita y el el giresheit Hash sin el Heart lo que hace es que me devuelve a ese commit, pero me mantiene los cambios, me mantiene las modificaciones.

1:21:26
Sí, en este caso, pues para que yo no tenga, digamos, no quería eliminar, agregar males commit, dice. Bueno y se hizo y se genere conflicto sobre el repositorio. Entonces vas a hacer un reset hard, pero antes de eso necesito conocer hacia dónde quiero irme. Entonces voy a decirle Git Locke, entonces quiero devolverme a este ID, voy a salir.

1:21:48
Proshoit.

1:21:49


1:21:52
Voy a volver.

1:21:55
Ahora estás sí, tu cabecera sí está en el comando eliminando archivos. Si yo le doy gitlock.

1:22:04


1:22:08
En archivo estoy en archivos, sale otro commit se desapareció si yo voy acá.

1:22:16
La Que yo he agregado ya no existe.

1:22:20
Se puede ver también por acá.

1:22:24
El comando en Linux no gat CAT.

1:22:28
Archivo 1.

1:22:30
Ya no me aparece.

1:22:32
Ya no aparece la Que yo había agregado antes tenía 3 líneas agregadas.

1:22:39
Bueno, esto es otro comando ya los gitlock aquí quiero moverme a otra rama, entonces lo mismo, quiero moverme a una rama a un git checkout, los git checkout.

1:22:51
Hotmail.

1:22:53
Me voy a otra rama.

1:22:55
Main, le doy git ranch.

1:23:02
Estoy en la Roma Mail, pero mantengo mi nueva rama.

1:23:06
Ahora quiero, quiero cambiar, quiero crear una nueva rama, entonces voy a usar el comando a salir de acá, git check out.

1:23:17
B.

1:23:19


1:23:21


1:23:25
Roggit brunch experience con branch la diferencia de crear una rama con el Gith Ranch y el nombre de la rama y el git Checkout. Es que cuando yo creo una rama con el git checkout menos b automáticamente yo cambio a la rama a la cual fui chequeada sí cree la rama y adicionalmente hice el check out. Esto ahorra unos segundos, pero es bastante útil.

1:23:48
Ahora lo que quiero hacer es hacer una modificación, entonces archivo.

1:23:55
Quiero hacer una modificación, voy a hacer una modificación sobre mi archivo 1 entonces agregando.

1:24:03
Múltiples líneas, entonces, órale control C, Control V voy a agregar múltiples líneas mi archivo.

1:24:11
Ya le quite estatus.

1:24:14
Yo quiero, ya no quiero trabajar en esto, quiero seguir con mi trabajo, pero quiero cambiarme a la A la New Branch. No quiero hacer en otra rama.

1:24:27
Otro trabajo, quiero agregar un nuevo archivo entonces, Ah, bueno, entonces para esto voy a usar Git Checkout, sí.

1:24:37
Quiero mantener mis esos cambios que yo estaba haciendo acá en este no quiero pasarlos al otro lado, yo yo le doy it check out.

1:24:46
Menos, no, no voy a leer. N menos vale new Orange.

1:24:54
¿Él me cambió a la otra rama, pero qué pasó? Yo le dije, estatus.

1:25:00
Se movió también los cambios y yo no quería hacer eso. Yo quería que mis cambios se quedaran en la otra rama 1, pero todavía no los quería confirmar. Entonces voy a volver a la nueva rama, me di cuenta que mis cambios están acá, o sea, estoy en la rama, en la new la new Ranch, pero yo no me quería traer esos cambios para acá. Sí, esto porque no hay conflicto, si hubiera conflictos me hubiera dicho, no es que usted tiene bastantes conflictos y no puede hacerlo porque en sus repositorios remotos tienen más cambios, entonces no puedes hacer la compilación o la modificación de esto.

1:25:28
Bueno, puedes hacer ese, no puedes hacer ese cambio porque vas a generar conflictos YY esto no es no es saludable. Entonces voy a volverme a mi rama.

1:25:37
Que a mi Second branch.

1:25:43
Vuelvo y cambio, entonces estoy en Second branch. Quiero guardar esto. Entonces voy a elegir. Hay un hay un comando que se llama Git Stage. El git Stack es 1, guardado, provisional y rápido. Entonces yo le doy git stach.

1:25:57


1:25:59
Y me dice que guardó el working directring entonces guardó lo que yo estaba trabajando en el working Direct y yo le quite status.

1:26:06
Igual lo podría hacer también para si yo trabajara dentro de mi rama, entonces me doy git out.

1:26:12
Banch y voy a voy a dar arquitectatus.

1:26:17
No tengo cambios, voy aquí, tengo mis dos cambios en esta rama.

1:26:23
Ahora voy AA cambiar de rama otra vez voy a ir para git checkout.

1:26:28
Voy a limpiar un poquito el check out.

1:26:33
Con brunch.

1:26:36
Voy ahora acá y aquí le voy a dar git stage.

1:26:46
Ah, bueno.

1:26:48
Yo veo acá estoy en Second branch, sí, y no tengo esos cambios, pero quiero seguir trabajando sobre eso. Entonces quitestas.

1:26:57
Él me dice que tengo guardado un work en improcess en este momento voy a sacarlo acá y para volver mis cambios que tenía yo ahí puedo volver varios días.

1:27:07
Esto con otro con digamos, con un ID, por ejemplo, un github.

1:27:12
Para administrar cambios hay otros, por ejemplo, Gith crack en esto es digamos esto, esto se hace, es un clic. Acá lo estamos haciendo netamente desde la terminal y es donde más se usa acá. Mis múltiples cambios fueron agregados.

1:27:27
Y.

1:27:30
Digamos, pasamos al reset.

1:27:33
Tenemos un stash.

1:27:36
Ahora quiero, por ejemplo, no quiero guardar, quiero ignorar algún archivo en este caso.

1:27:43
Y tengo que ir sash. Quiero hacer ignorar, digamos algunos cambios, por ejemplo, variables de ambiente, cosas que yo tenga en mi repositorio. Entonces este git North es un archivo que está dentro de las raíz del repositorio.

1:27:58
Lo que hace este es es descartarme cambios de mi directorio que no voy posteriormente no voy a subir, o sea que no se van a ver visibles y que pues por alguna razón, cuando alguien clone no va a tener ese ese archivo porque en mi en mi remoto no va a tener digamos esa información, lo voy a descartar desde mi local. Sí, entonces para esto tengo que agregar un archivo que llama Guited Nord, entonces me voy acá.

1:28:22
Y le voy a dar punto Kit nor.

1:28:28
Ya me identifica que es un archivo. Adquisitor, en ese caso voy a agregar un un archivo que llama punto Emp. Sí, y en este archivo punto EM voy a ver si le password.

1:28:39
Voy a ser igual a.

1:28:44
Por ejemplo.

1:28:46
Pon 1139 pon y acaba, por ejemplo, el user.

1:28:51


1:28:55
Epic.

1:29:00
Voy a guardar, pero este archivo no lo puedo cargar porque tiene un password, entonces lo que hago es agregarlo a mi punto le voy a dar punto. M.

1:29:10
Y lo que va a hacer es que cuando yo sé que acá inmediatamente visual Studio identifico que este archivo.

1:29:16
No lo no lo voy a agregar, entonces voy a ir aquí a mi terminal.

1:29:20
Voy a darle git status.

1:29:24
¿Él me, él no me identifica si yo no agregara este punto, git North, Qué pasa si yo elimino este punto? Git North, voy a eliminar, no lo quiero y le voy a dar git estatus.

1:29:35
Él me identifica este, pero yo no quiero agregar ese archivo sí o no, entonces lo que hago es pues agregarme quiero ignor.

1:29:50
Le cambio el nombre.

1:29:59
Ignor.

1:30:05
El punto solo agregando el nombre y me va a identificar si estuviera dentro de una carpeta, agregó la carpeta lo agrego a la ruta, me voy acá, le doy git status.

1:30:16
No cese.

1:30:21
Entonces el este no lo no lo conoce, pero igual tengo que agregar mi archivo, sí, pero si bien vuelvo a ejecutar el kit estatus, el el largo, él no me va a mostrar el archivo que tienen mis variables. Esto porque pues este archivo no debería subirse porque es un archivo que tiene un password, los passwords, pues no puedo tener esto en un repositorio, entonces voy a agregar esto Guitar.

1:30:43
¿Gat punto punto si yo quisiera agregar todo, entonces qué pasa si yo le doy agregar todo acá?

1:30:49
¿Debería tomar los dos cambios, debería tomar cuál cambio el cambio que yo hice acá? Sí, de las nuevas líneas y el cambio acabo de agregar un múltiples líneas 3.

1:31:00
Fui a los los espacios, también los toma, voy a darle guardar piedad.

1:31:07
Le doy kit status.

1:31:11
Aquí, estatus.

1:31:14
Con el punto me agregó los dos archivos, qué pasa si, por ejemplo, yo hubiera tenido el punto hempera webgit.se me había ido ese archivo y sin sin tener que seguir en or entonces ese git, ese equidad, punto o guitarol, no es recomendable usarlo a menos de que ustedes estén seguros de que los cambios que están haciendo son son cambios que no deben, deberían ir en ese en ese en ese cómic.

1:31:40
Skidcommit.

1:31:41
No sé, me voy a agregarlo a mi repositorio y le voy a decir agregando.

1:31:47


1:31:53
Ignacio.

1:31:56
Hay algunos templates que ayudan a trabajar git no dependiendo del aplicativo, lo importante es tratar de identificar esos archivos que no deberían subirse a un repositorio, por ejemplo, archivos compilados, archivos que pesan mucho, imágenes que tienen infinidad de de gigas o megas por.

1:32:14
Por ejemplo, documentación. XLS, punto Doc. Eso no debería ir ahí. Entonces se pueden agregar acá algunos archivos propiamente de los lenguajes de programación, algunos, por ejemplo, variables de ambiente visual, estudio, género en una carpeta canva, punto ES code cuanto se está compilando.

1:32:29
Entonces esos archivos son los que se se agregan al git North, voy a agregar al git North al proyecto.

1:32:42
Ahorita.

1:32:48
Listo el kit estatus.

1:32:52
Listo, ya agregué, pues gitlock quiero ver si se cambia hasta acá, efectivamente, agregando git en or si ustedes ven en la línea que el el el branch que yo había eliminado.

1:33:02
De que le hice rushse ya desapareció, se fue. No existe más. Aquí ya visualizo, me muestra que no hay cambios disponibles.

1:33:11
Y seguimos acá con la diapositiva.

1:33:16
Entonces ya digamos, trabajamos en nuestro repositorio local, ya hicimos.

1:33:23
Las modificaciones tenemos nuestro proyecto, Agregamos nuestro repositorio, en ningún momento creamos un repositorio en github, lo creamos. Estamos trabajando desde nuestro local. Entonces hay una herramienta que me permite hacer mucho más eficiente mi trabajo, tener un trabajo colaborativo, tener un trabajo visual. Sí, porque pues trabajar solamente en en.

1:33:45
En la línea de comandos, pues obviamente es de un reto bastante alto, sí.

1:33:54
Es de un reto bastante alto y hay plataformas en este caso como github, que me ayudan AA trabajar plataformas de forma colaborativa.

1:34:05
Me ayudan a tener un control visual.

1:34:12
Github, pues es un un rapper de git que fue creado para tener y alojar proyectos en gran escala. ¿Tener ese servidor? Sí, acá estoy trabajando en local en mi máquina, pero necesito tener un servidor al cual yo voy a empujar esos cambios donde yo voy a tener todos mis cambios en mi servidor, donde yo los voy a tener relajados para que en algún caso otros desarrolladores este esto que yo hice lo puedan descargar en su en su repositorio.

1:34:37
Lo puedan traer traer su código a su máquina local y trabajar con este nuevo y lo que me permite es colaborativamente, empezar a trabajar y a crear.

1:34:48
Proyectos con diferentes lenguajes de programación, github puedes tener acceso público a muchísimos repositorios. Puedes tener acceso privado ya cuando quieres tener privado tus repositorios porque no quieres que tu know how salga a Internet por.

1:35:07
Porque son cosas que se han desarrollado para la empresa, se usan en repositorios privados.

1:35:14
Cuando quieres colaborar con múltiples equipos ya tienes que pagar una licencia, pagar una suscripción. Hay diferentes suscripciones Enterprise Team y cada una tiene diferentes características.

1:35:25
El 4 de junio del 2018, github y Github, pues era una empresa, digamos, una sociedad.

1:35:32


1:35:33
¿Que tenía un auge bastante grande, aún lo tiene, sigue teniendo el auge, pero fue comprado por Microsoft? Bueno, no, pero no fue comprado por Microsoft. Igual Microsoft le ha dado, digamos, un level adicional. Y bueno, la cantidad fue de 7000 500000000 de dólares, una cantidad bastante bastante alta.

1:35:54
Entonces vamos a revisar, entonces estuvimos trabajando todo este tiempo en nuestro local, nuestro corte Directo y nuestro studin área tuvimos nuestro reporte local, yo quiero interactuar con más desarrolladores, entonces para eso uso Guitar, para tener un repositorio remoto.

1:36:08
Cual yo pueda ya empujar esos cambios a mi remoto o pueda descargar esos cambios de otro desarrollador realizo.

1:36:14
Entonces y trabajamos equidad que agregamos de nuestro working director en Stall en área pasamos y hicimos nuestro git commit que dejamos en nuestro repositorio local. Sí, pero no hemos empujado esto a ningún lugar, no hemos empujado esto a ningún no hemos descargado ningunos cambios, no hemos hecho choco, no hemos hecho match, es para esto lo que vamos a hacer es por acá con la cuenta.

1:36:39
De Github, que es, digamos en cuenta personal de github.

1:36:44
Y si yo, bueno, yo agrego a github.

1:36:48
Github.

1:36:50
No, y aquí a get up.

1:36:52
No tengo digamos ya estoy loqueado, ya tengo mi usuario, tengo mi perfil.

1:36:56


1:36:57
Y quiero agregar un nuevo repositorio, quiero cargar lo que trabajamos en este momento, que es un archivo, un director y un y bueno, el el password que lo tengo local. Esto no debería visualizarse ya. Entonces voy a cargar en mi github. Entonces voy a crear un nuevo repositorio. Este repositorio se va a llamar bueno.

1:37:17
Y va a ser de tipo público, ustedes lo quieren descargar, ahorita lo pueden descargar, solo es para el tema de prueba, le voy a decir.

1:37:25
Crear repositorio, no voy a agregar ningún readme, no voy a agregar nada. ¿El ritmo es un archivo de lectura que lo que me permite es entender cómo se va a instalar mi proyecto es supremamente importante, es una de las cosas más importantes que 1 usa cuando cuando trabaja colaborativamente con github y con otras herramientas, poder saber cómo yo puedo es en mi manual de instalación, cómo yo puedo instalar mi aplicación, qué, qué requerimientos va a tener mi mi computadora para poder yo hacer, digamos 111 instalación de mi proyecto sin necesidad de preguntarle otro, desarrollar venga, cómo instalo esto que?

1:37:57
¿Qué versión de, por ejemplo, de punto Net debo tener o qué versión de Python debo tener? Entonces esto lo agrego dentro de mi readme y cualquiera cualquier persona que llega lee primero el readme por eso, dice Léeme.

1:38:08
Creó mi repositorio con mi repositorio está vacío, entonces él él me muestra que pues no tengo nada, no he agregado nada. Yo ya previamente ya hice unas configuraciones para poder digamos conectarme AA Github estas configuraciones, pues puede ser por HTTPS usando, digamos el el desktop de github o usando SCH. Yo tengo mis configuraciones hechas por SCH, quizás en en en más adelante vamos a ver cómo se hacen estas configuraciones. Por ahora, lo que yo quiero ver es cómo agrego mi proyecto.

1:38:39
De de de Kitty, el proyecto que yo, mi proyecto de de mis archivos porque son archivos, realmente los agregué o los quiero ver ya y que a otra persona los pueda descargar. Sí, entonces para esto vamos a usar el comando KEY Remote at origin y la URL, entonces aquí en esto me aparece lo mismo que yo hice, agrego un init acá me están diciendo que agregar un readme aquí que hicieron un commit que crearon una rama y agregar sí, digamos yo. En este caso iría en el gitbrage o iríamos nosotros en este en en este G badge, entonces ahora lo que voy a hacer es tomar esta.

1:39:17
Y lo que voy a hacer es.

1:39:19
Y mami terminal.

1:39:21
Yo y el s.

1:39:24
¿Por qué no me aparecen el Direct Nord? Porque es un archivo que lleva un punto al principio, entonces aparece, pero si yo voy y busco aparece, aparece mi gitón aquí. Si yo quiere estatus, no tengo nada, tengo todo, tengo mis seconds, pero yo quiero, me voy a ir a.

1:39:41
Y ramo principal switchbit este comando también es otro comando para hacer veo aquí no hago checkout de nada, sino solo me cambio dentro de los repositorios que tengo locales dentro de las ramas que tengo locales. Perdón.

1:39:55
Entonces voy a elegir estatus, no tengo ningún cambio.

1:39:59
Tengo, digamos, un punto en por qué creen que tengo este punto Emp aquí o este archivo de variables you git status.

1:40:07
Los cambios que yo realicé los realicé sobre la Second branch. Entonces, si yo me voy aquí, ese archivo desapareció.

1:40:15
Entonces como yo me traigo esos cambios localmente, si quiero publicarlos es para esto lo que voy a hacer es un ir meoch.

1:40:25


1:40:34
Github, esto lo estoy haciendo local, pero con github se usan algo que llama el PULL request. Realmente es una solicitud de cambio, pero detrás de eso es un March. Les voy a Second branch. Entonces aquí hizo algo, voy a elegir estatus.

1:40:50
Lo que hizo, ya no tengo ninguna diferencia, yo voy acá y reviso, se me trabo mis cambios, el merch lo que hace es unir dos ramas. Sí, hace el merch entre una rama. Yo estoy parado en rama en la rama main y lo que hice fue decirle que me mercharon, o sea que me uniera. O sea, esto es como una asociación, digamos, como un conjunto donde sí hace hace la la combinación de los cambios que hay, o sea, me trae los cambios de la Second branch a mí ramame.

1:41:20
Sí, yo el git estatus no tengo nada como lo vimos acá y ahora quiero agregar esto. Entonces el comando que yo copié es poco bueno que lo había copiado.

1:41:30
Entonces aquí voy a copiarlo nuevamente.

1:41:34
Voy a darle git Remote at origin, agrego y adicional a esto tengo que.

1:41:43
Hacer tanteo que ir acá, entonces tengo que ir a hacer un push origin main sí, entonces voy acá.

1:41:51
Es el push.

1:41:54
El PUSH es un berts, entonces el mert es vamos AA abrir aquí una escala hidro rápido.

1:42:02
No entro a este mismo.

1:42:04
¿Entonces aquí qué fue lo que hizo?

1:42:07
¿Entonces tenía yo mi email, cierto?

1:42:11
Entonces esto fue algo, digamos que me encontré esto no lo había planeado. Realmente fue así porque y yo estaba trabajando sobre el Second branch.

1:42:20


1:42:23
Entonces yo lo que quiero agregar es mi rama Second branch, lo voy a dejar acá. Yo había hecho cambios, había agregado el punto git North.

1:42:32
El git Norca, sí.

1:42:35
El equip Nord.

1:42:39
Hemos pasado el tiempo.

1:42:41
Estamos bien, entonces yo he hecho cambios acá y cuando yo fui AA revisar me aparecía el punto Emp. Sí me aparecía el punto Emp aquí environment.

1:42:52
¿Por qué? Porque yo no tenía ese cambio, yo no tenía ese cambio, no los cambios que yo había hecho en esta esta rama.

1:43:01
No estaban acá y esto es solamente el local, entonces lo que yo hice fue con el merch fue tomar estos cambios lo que había acá y empujarlos acá. ¿Entonces quiere decir que main quedó con el giednor como vimos acá?

1:43:17
Quedó con el Guinness, no estoy en la rama amen y quedó con el archivo de ambiente Environment.

1:43:24
Y ahora lo que quiero hacer es con este Remote ADD ya tengo todos mis cambios acá. Ahora lo que quiero es si me voy acá estamos en este commit, quiero hacer este push, o sea, quiero empujar todos los cambios que yo tengo acá con todos los commits que he realizado.

1:43:38
Época, los a mi remoto, entonces si yo voy y ejecuto git PUSH, entonces acá me dice, tienes que crear.

1:43:48
Gitus menos u entonces, pues ya de menos u.

1:43:52
Entonces en su.

1:43:56
Y lo que hice fue tomar los cambios que tenía en mi local y empujarlos a un repositorio si hoy gith estatus.

1:44:04
No tengo nada en mente porque lo único que hice fue por los cambios. Ahora, si yo me voy acá y actualizo.

1:44:12
Esa que ya tengo mis cambios, tengo mi giridor mi archivo punto EM tengo mi archivo 1 con todos mis cambios y además yo puedo ver el historial.

1:44:23
Tengo mi rama, si ven solo tengo la rama Men, las otras ramas están en mi local y me dice que fue actualizado hace 11 minutos. ¿Bueno, fue el momento en el que yo creé el repositorio, no tengo ningún readme, puedo ver el historial de mis cambios? Sí, acá hay varios cambios.

1:44:40
Y tengo github ya aquí un poquito más de zoom.

1:44:45
Entonces tengo mi código, este es mi repositorio, tengo mi rama, tengo los 6 commits. Entonces esto es supremamente importante porque si ustedes ven hace 54 minutos hicimos nuestro primer commit. ¿Tiene un código del commit? Sí.

1:45:04
Ahora si yo voy a mi repositorio y le doy gitlock.

1:45:09
En los One line.

1:45:13
Y voy a pasar esto acá un poquito más pequeño.

1:45:19
Los comits, el ID de los Comits es el mismo.

1:45:22
Sí, porque es lo que estoy haciendo, es trabajando sobre mi repositorio local, tengo todos los comeds agregando git North, eliminando archivo dos, devolviendo el nombre, cambiando todos los commits que yo realicé, los tengo en mi repositorio.

1:45:37
En mi github, mi repositorio en mi servidor, digo la rama, las otras ramas, yo no las he empujado. O sea, yo no he hecho empujar la rama porque estoy parado dentro del del de Maine si yo quisiera empujar una nueva rama, pues lo que hago es pararme sobre la rama, entonces vengo acá.

1:45:53
Ya vale salir.

1:45:55
Sí, entonces voy a ir a git.

1:46:00
Yo quiero conocerla. Ramón.

1:46:03
Subir a esta nueva rama.

1:46:06
Voy a salir, voy a le git checkout o git switch, ustedes prefieran.

1:46:13
El check out si la rama subiera remota, por ejemplo, Ahorita lo vamos a ver checkout new Branch, entonces me cambia la nueva rama, le doy git status.

1:46:24
Tengo un cambio es porque no tengo los cambios, entonces voy a voy a irme mejor a la de Second branch para no hacer otro match acá no me quita nada, pero pero.

1:46:35
Los análisis cambian ahí.

1:46:38
Sembrunch.

1:46:42
Como los nuevos cambios, pero acá en Music con Brandch voy a agregar el archivo dos, voy a ir aquí a archivo dos.

1:46:49
Archivo_ dos.

1:46:53
Pxt.

1:46:56
Y este.

1:46:59
Es.

1:47:03
Archivo dos.

1:47:06


1:47:08
Adicional, quiero agregar mi readme.

1:47:11
Entonces voy a lea Readme.

1:47:14
MD

1:47:18
y a este es el esto funciona con markdown entonces voy a darle Web App.

1:47:30
Este es el proyecto.

1:47:35
TK.

1:47:37
A sí o del curso del curso el curso.

1:47:45
It PONES.

1:47:47


1:47:51
Dos.

1:47:53
Sí.

1:47:55
Toca.

1:47:57
Vale.

1:48:00
El proyecto.

1:48:02
Lo podéis guardar, voy otra vez a mi terminal.

1:48:08
Voy a limpiarla, voy a elegir estatus.

1:48:12
Con dos archivos voy a Agregarlos Geta.

1:48:17
Readmi.

1:48:21
Y Archi.

1:48:23
Dios.

1:48:29
Y el estatus.

1:48:31
Señor Jami, estoy juniorly, git formet.

1:48:36
Menos M.

1:48:38
Y acá le voy a decir agregando.

1:48:44
Me.

1:48:46
Y.

1:48:48
Archivo.

1:48:52
Y Touch.

1:48:54
Pero estoy en mi nueva rama, entonces si yo le doy un github.

1:48:58
Y sí que no, entonces vamos a usar github origin.

1:49:04
O ese comando.

1:49:06
Que hacemos etapas, básicamente es una laptop, es lo mismo que estoy diciendo la.

1:49:16
El git status.

1:49:19
Si yo me voy a aquí a Kit, por ejemplo, Git Checkout.

1:49:25


1:49:29
Lo avisamos acá yo tengo todos mis archivos, acá me voy a Checar Main le doy git status.

1:49:37
Estoy acá, pues estos archivos que yo tenía en esta rama no aparecen porque están en en Second branch, entonces acá ya estoy trabajando con mi repositorio, aquí ya no lo estoy solamente trabajando en local, ya estoy trabajando con 1,1 repositorio con github, entonces ahora voy a Github, voy a revisar el Código sí, entonces él me dice que ha encontrado un Second branch. Sí, entonces como yo cargué ya esta rama, acá esta rama sí tiene mi ritmo y automáticamente el ritmo es leído por por github.

1:50:07
Otro readme web up ese es el proyecto del curso de git.

1:50:11
Y bueno, ahora podríamos hacer más cosas, igual vamos a revisar temas ya más profundos de github.

1:50:21
Después de esto seguía perdón.

1:50:26
Wheelman, señor.

1:50:30
Yo pienso que no sé, podríamos pasar a la parte de preguntas para no pasarnos de la 11.

1:50:36
¿Sí, la parte, la parte de preguntas, qué preguntas tienen?

1:50:41
Con gusto las las atento las atendemos, las atienden en este momento.

1:50:46
Yo creo que tiene que haber altas dudas porque hay alta información. Sí pueden empezar a preguntarnos chicos.

1:51:06
Por lo que veo quedó bien claro, sí que.

1:51:10
Bueno, sí, me gustaría hacerles unas preguntas a ustedes, ya que no tienen preguntas.

1:51:14
¿Cuál de estos comandos debería yo usar para inicializar un proyecto de git?

1:51:18
El que quiera responderme.

1:51:24
La tercera correcto es listo.

1:51:29
Cuáles las podrían configurarse y asegurar que tengo un archivo, certificar que un archivo nunca será omitiado será confirmado a nuestro gatopositorio cuál de estas el punto git. Git in North Kidnard. TXC, git.

1:51:54
Escuché la cuatro.

1:51:58
¿Y bueno es esta un togety nor?

1:52:04
Es la número dos.

1:52:06
Hemos creado nuevos archivos llamado punto Index. HTML. ¿Cuál es de las siguientes?

1:52:15
Digamos, es 1 de los que yo puedo hacer el commit.

1:52:18
Faltan los siguientes comandos, los siguientes es 6 y los siguientes pasos, puedo realizar un commit o podemos realizar un commit de este.

1:52:28
¿Pongo la pregunta, me la puedes repetir? Por favor, hemos creado un nuevo archivo llamado interés. HTML.

1:52:37
Falta las siguientes comandos, por así decirse eso no digamos para este archivo podemos realizar un commit.

1:52:47
La última.

1:52:51


1:52:54
Segunda.

1:52:59
Realmente me permite realizar me permite realizar un commit que sale ahí. Mala pregunta, Index.

1:53:06


1:53:08
Y la siguiente es qué comando tú correrías para ver el el historial de Commits en tu repositorio.

1:53:16
The candy History with Blocks.

1:53:22
Listo, eso es todo por hoy, no sé si tengan alguna inquietud adicional.

1:53:28


1:53:29
No, pues estamos por cerrar la sesión.

1:53:32
Agradecerles a ustedes por el tiempo, por el espacio fueron 1:50 H y 50 minutos más o menos que estuvimos en esto y agradecerles por la paciencia. Es una sesión un poquito larga, pero pero bueno, hay bastante información. Posteriormente les envío a les comparto esta información y bueno, el vídeo quedará quedará almacenado.

1:53:53
Y además, una una pregunta para para los para los.

1:53:59
¿Cómo se llama para los administradores?

1:54:02
Para la próxima tenemos que tener instalado.

1:54:06
O algunas de estas herramientas.

1:54:10
Se pueden tener instalado git.

1:54:15
En este momento, kit van a tener github. Víctor me me me confirma, va a tener una un digamos acceso a github, entonces seguramente previamente a las sesiones les van a pasar el acceso.

1:54:29
Git se lo pueden instalar en en el documento yo los envío lo que vemos acá vamos a tener acá, hagamos un una guía de usuario.

1:54:38
Realmente es muy sencillo, solamente quite las máquinas instalar Windows en Linux y en Mac.

1:54:44
YY esas configuraciones que mencionabas al principio con respecto AA las diferencias, todo eso va a estar en el documento fuera de esta.

1:54:55
¿Digamos, va a estar el vídeo, que es lo que vimos acá y va a estar, digamos las las realmente todas estas ejecuciones de comando fue cómo interactuamos con git, entonces, en qué casos vamos a usarlo? Por ejemplo, cuando quiero encontrar diferencias, cuando quiero confirmar mi código.

1:55:13
¿Me me mencionaba más que nada las configuraciones que mencioné al principio con respecto de instalarlo en Windows, tenías ciertas diferencias que instalan en Linux?

1:55:23
Ese tipo de diferencia sí lo podemos en las próximas lo podemos, lo podemos ver.

1:55:30
Vale, gracias, oye Luis, si tenéis problemas ahí me ha dicho el proyecto de que es lo distinto que secreto.

1:55:38
Gracias.

1:55:41
Listo.

1:55:42
Entonces eso es todo, les agradezco. Les agradezco mucho que tengan un excelente resto de día. Gracias wildman. Gracias muchachos.

1:55:53
Un poquito. Gracias. Bueno, Chao, gracias.

1:55:58
Chao Chao.

1:56:00
Chao, gracias.

1:56:03
Muchas gracias.

1:56:05

