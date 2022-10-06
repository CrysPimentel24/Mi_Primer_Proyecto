*Comando de Git basicos -Guia Completa*  

5/10/2022

# GIT CHEAT SHEET
- ¿Que es Git? 
- Cheat Sheet Ofrece...
- Funcionamiento de Git
- Comandos
- Caracteristicas
- Ventajas y Desventajasgit

# .....................................................................................................................

## *¿Que es Git?*
Es un sistema de control de versiones distribuido de código abierto desarrollado por Linus Torvalds, el creador de Linux. El control de versiones distribuido permite a los desarrolladores descargar un software, realizar cambios y subir la versión que han modificado.



## *¿Que nos ofrece GIT?*
Git, que presenta una arquitectura distribuida, es un ejemplo de DVCS (sistema de control de versiones distribuido, por sus siglas en inglés). En lugar de tener un único espacio para todo el historial de versiones del software, como sucede de manera habitual en los sistemas de control de versiones antaño populares, como CVS o Subversion (también conocido como SVN), en Git, la copia de trabajo del código de cada desarrollador es también un repositorio que puede albergar el historial completo de todos los cambios.

Además de contar con una arquitectura distribuida, Git se ha diseñado teniendo en cuenta el rendimiento, la seguridad y la flexibilidad.


## *Funcionamiento*
### **Básicamente, Git funciona del siguiente modo:**

1. Crea un "repositorio" (proyecto) con una herramienta de alojamiento de Git (por ejemplo, Bitbucket).
2. Copia (o clona) el repositorio a tu máquina local
3. Añade un archivo a tu repositorio local y confirma ("commit") los cambios
4. Envía ("push") los cambios a la rama principal
5. Haz cambios en tu archivo con una herramienta de alojamiento de Git y confírmalos
6. Extrae ("pull") los cambios a tu máquina local
7. Crea una rama ("branch", versión), haz algún cambio y confírmalo
8. Abre una solicitud de incorporación de cambios ("pull request": propón cambios a la rama principal)
9. Fusiona ("merge") tu rama con la rama principal.


## *Comandos*
### **Los mas usados (en clase):**

**Cls:** Para borrar historial del console.

**Dir:** Se usa para la revisión de archivo que está en el escritorio.

**Cd:** Agrega una ruta de ubicación de archivo.

**Mkdir:** crear una carpeta nueva.

**CMD:** Abrer la consola, cuando estas dentro de console, te dice la versión y los derechos reservados.

**Rmdir:** Borra una carpeta.

## *Caracteristicas*
### **Git es una herramienta que realiza una función del control de versiones de código de forma distribuida, de la que destacamos varias características**

- Es muy potente.
- Fue diseñada por Linus Torvalds.
- No depende de un repositorio central.
- Es software libre.
- Con ella podemos mantener un historial completo de versiones.
- Podemos movernos, como si tuviéramos un puntero en el tiempo, por todas las revisiones de código y desplazarnos una manera muy ágil.
- Es muy rápida-
- Tiene un sistema de trabajo con ramas que lo hace especialmente potente.

## *Ventajas y Desventajas*

## **Ventajas:**
- **Sistema distribuido**, sin un punto central de fallo, que permite el trabajo incluso sin conexión.

- **Superrápido y ligero**, optimizado para hacer operaciones de control muy rápidas.

- **Crear ramas y mezclarlas** es rápido y poco propenso a problemas, al contrario que en otros sistemas tradicionales.

- **La integridad de la información está asegurada** gracias a su modelo de almacenamiento, que permite predecir este tipo de problemas. En sistemas tradicionales este era un problema grave.

- **Permite flujos de trabajo muy flexibles.** El concepto de área de preparación o staging permite versionar los cambios como nos convenga, no todo o nada.

## **Desventajas:**

- **Es más complejo** que los sistemas centralizados tradicionales porque entran en juego más repositorios, más operaciones y más posibilidades para trabajar en equipo, que hay que decidir.

- **La curva de aprendizaje es empinada.** Lo básico lo aprendes enseguida, pero la realidad te demuestra que no es suficiente "tocar de oído" con él. La documentación es tan compleja que muchas veces no resulta de ayuda.

- **Los comandos y algunos conceptos** que usa pueden llegar a ser confusos, al igual que algunos mensajes que muestra.

- Por defecto, **se lleva mal con archivos binarios muy grandes**, como vídeos o documentos gráficos muy pesados. Por suerte existen soluciones para ello (Git LFS).

# ...................................................................................................................