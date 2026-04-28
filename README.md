##Trabajo Individual

Juan Jhonatan Rodriguez

## Clase1
 
## Que es Git?

Sistema de control de versiones distrubuido(VCS) open source, creado por 
linus Torvalds en 2005.

Nos permite guardar archivos y las versiones de estos a lo largo del tiempo 
de manera local.
Podemos volver atras si algo fall, trabajo en equipo sin perjudicar a ningun
integrante del respositorio, mantener diferentes versiones de un mismo 
proyecto.

## Como nacio Git?

La creacion de Git sucedio por varias razones de un mismo problema, porque 
en ese entonces BITKEEPER dejo der ser gratuito y Linus Torvalds no queria 
pagar por una licencia por linux es open source, asi que dicidio crear su 
propio sistema de control de versiones al que llamo git, motivado tambien 
por que estaba cansado de depender de heramientas propietarios que no podia
controlar, termina creando una de las herramientas mas importantes para los
desarrolladores en todo el mundo.

## Como instalar Git?

Yo lo instale desde la esta misma terminal practicamente, usando los 
comandos como:

primer comando: 
	sudo apt update
segundo comando:
	sudo apt install git
tercer comando:
	git ~~version
Esos son suficientes para descargar y poder tener git en y ver la version 
como el paquete de git que tenemos.
Git es multiprogramacion, funciona de igual manera en diferentes de sistemas
operativos, lo unico que cambia es la forma de instalarlo.
		EL motivo por lo que presente tarde es porque mi maquina virtual
		elimian mi avance, no puedo hacer apagar, sino solo suspender,
		Por favor considereme por favor pepepepe.

## Clase 2

## STATES Y COMMITS

Resumen breve de estos dos conceptos seria states(estados en GIT), son las
etapas por las que pasa un archivo de un git, "Directoirio de Trabajo":
la carpeta local, donde estamos trabajando pero git aun no lo tiene
registrado, "Stage Area": El area de espera donde todo esta listo para
guardarse, "Repositorio local": archivo guardado en el historial del
repositorio.

commi(buenas practicas) seria  un modo convecional para escribir mensajes
de commit claros, estructurados y consistente, de modo que el hsitorial
del proyecto sea facil de entender y automatizar.


## Directorio de Trabajo 

## STATES Y COMMITS

Resumen breve de estos dos conceptos seria states(estados en GIT), son las
etapas por las que pasa un archivo de un git, "Directoirio de Trabajo":
la carpeta local, donde estamos trabajando pero git aun no lo tiene
registrado, "Stage Area": El area de espera donde todo esta listo para
guardarse, "Repositorio local": archivo guardado en el historial del
repositorio.

commi(buenas practicas) seria  un modo convecional para escribir mensajes
de commit claros, estructurados y consistente, de modo que el hsitorial
del proyecto sea facil de entender y automatizar.


## Directorio de Trabajo 
al repositorio, no se vera todo lo que este en el .gitignore, no se ver nada 
de lo que contenga en el gitignore en plataformas como git hub.

@@ -94,6 +128,23 @@
Es la ultima fase donde le decimos al repositorio de que cree el punto 
de guardado para que todos los cambios que estan en staged pasen a ser parte 
del historial.

## STATES Y COMMITS

Resumen breve de estos dos conceptos seria states(estados en GIT), son las
etapas por las que pasa un archivo de un git, "Directoirio de Trabajo":
la carpeta local, donde estamos trabajando pero git aun no lo tiene
registrado, "Stage Area": El area de espera donde todo esta listo para
guardarse, "Repositorio local": archivo guardado en el historial del
repositorio.

commi(buenas practicas) seria  un modo convecional para escribir mensajes
de commit claros, estructurados y consistente, de modo que el hsitorial
del proyecto sea facil de entender y automatizar.


## Directorio de Trabajo 

git commit -m "mesanje"
git reset --soft HEAD~` : si quieres deshacer el ultimo commit
@@ -109,6 +160,23 @@
proyecto en estado funcional.

### Escribe buenos commtis

## STATES Y COMMITS

Resumen breve de estos dos conceptos seria states(estados en GIT), son las
etapas por las que pasa un archivo de un git, "Directoirio de Trabajo":
la carpeta local, donde estamos trabajando pero git aun no lo tiene
registrado, "Stage Area": El area de espera donde todo esta listo para
guardarse, "Repositorio local": archivo guardado en el historial del
repositorio.

commi(buenas practicas) seria  un modo convecional para escribir mensajes
de commit claros, estructurados y consistente, de modo que el hsitorial
del proyecto sea facil de entender y automatizar.


## Directorio de Trabajo 

Un commit debe describir lo que hace en pocas palabras y de manera simple
Fix: "Significa" 
pero efectivo:
add : "Significa que se agrefa un nuevo archivo"

change : "Significa que se modifica un archivo existente"


		EL motivo por lo que presente tarde es porque mi maquina virtual
                elimian mi avance, no puedo hacer apagar, sino solo suspender, 
                Por favor considereme por favor pepepepe.


##Clase 3 

### GIT

##Clase 3 

### GITHUB Y SSH

### Que es GitHub?

Es una plataforma en la nube y red social para desarrollarse que permite 
alojar, gestionar, y colaborar en proyectos de software utilizando Git, 
basicamente Git es el respositorio local y GitHub es el respositorio remoto.

### Para que sirve?

Sirve para subir proyectos de progrmacion, colaborar, con otras personas, 
revisar cambios hechos por diferentes usuarios, hacer copias de seguridad
del codigo, mostrar proyecto(portafolios).

### SSH VS HTTPS

### HTTPS

Cuando clonamos y queremos usar un repositorio con HTTPS, este nos pedira
autenticacion cada vez, hasta pidiendo un token. Lo cual hace que sea 
cansancio y molesto.

### SSH

Configuramos en nuestra PC/laptop ssh para comunicarnos con github, mediante 
una key la cual al ponerla en github no necetira pedirnos autenticacion cada
vez.

Por tales inconvenientes con HTTPS es mas recomdado usar SHH key.

## Conectar un repositorio local de Git existente con uno en Github

git remote add origin

Remote es la URL que apunta al servidor externo es decir a tu repositorio  externo creado en Github
y Origin es simplemente el apodo, que git le da por defecto a esa URL

Primero debes inicializar tu repositorio local y tener un commmit inicial al menor

##Clonar un repositorio de Git

Para la clonacion de un repositorio de git debemos seguir una secuencia de pasos para tener 
corrextamente lo que queremos de el, los comandos pueden camiar de puntero de github y no te pida
auntenticacion cada vez, tambien podemos usar cuando queremos cambiar el remooto al cual esta conectada el repositorio.

		EL motivo por lo que presente tarde es porque mi maquina virtual
                elimian mi avance, no puedo hacer apagar, sino solo suspender, 
                Por favor considereme por favor pepepepe.


## Clase 4

## Git Remote(respositorio remoto)

git remote permite coectar tu repositrio local con uno remoto, indicando de donde traer o donde 
enviar.
 git remote ~v 
 mustra la url del repositorio remoto
 git remote add (nombre) 
 vincula el repo local con remoto
 git remote set~url
 cambia el url del remoto
En resumen sirve para gestionar conexiones entre tu pc y la nube.

## Multiples SSH(cuentas GitHub)

Cuando tienes mas de un cuenta en github, necesitas diferentes llaves SSH para cada una.

Cada cuenta tiene su propia "llave", como una puerta diferente.

## Configuracion de multiples SSH

# Paso 1: Crear la nueva llave

# Paso 2: Configurar el  archivo

# Paso 3: Verificar conexion 

# Configuracion local en GIT

Las configuraciones locales son solo para un repositorio y tienen prioridad sobre las globales.
	git config user.name "Name"
	git config user.email "correo"
No llevan ~~global .
Se usan cuando trabajas con distintas cuentas en diferentes proyectos.
## Clonar con el host correcto

Cuando usaas multiples cuentas, debes clonar asi:

	git clone git@github-miname:usuario/repositorio.git

Si usas mal el host, usaras la cuenta equivocada.

## Git Checkout

Permite ver los commit.
Recuperar archivos.
Cambiar de rama.
Probar cambios sin efectar a la rama principal.

## Detached HEAD(estado desacoplado)

Sucede cuando el HEad apunta a un commit y no a una rama.

Estas viendo el pasado.
Puedes hacer cambios, pero no estan guardados en una rama.
Si sale, puedes perderlos para siempre.
Es cmo ser un visitante en el historal.

## Como moverse entre los commit

	git checkout <hash>

Volver a una rama: 

	git checkout main

Si hiciste cambios en Detached HEAD:

	git checkout -b nueva_rama

Esto guarda tus cambios en una nueva rama.

## Buenas practicas con Checkout

Haz commit antes de moverte.
No trabajes de mucho en Deadched HEAD.
Crea una rama si haras cambios importantes.
Manten limpio tu direccitorio.
Usa checkout para aprender viendo el historial.

EL git remote permite conectar repositorios locales con remotos para manejar multiples cuentas de github se
usan varias llaves SSH configuradas en un archivo confif. Las configuraciones locales se aplican por 
respoditorio. El comando git checkput permite moverse entre commits y ramas, pudiendo entrar en estado
"Detached HEAD", donde los cambios pueden perderse si no se crea una rama, Es importante seguir buenas
practicas como hacer commit antes de cambiar de estado y no trabajar mucho tiempo en ese modo.

		EL motivo por lo que presente tarde es porque mi maquina virtual
                elimian mi avance, no puedo hacer apagar, sino solo suspender, 
                Por favor considereme por favor pepepepe.


