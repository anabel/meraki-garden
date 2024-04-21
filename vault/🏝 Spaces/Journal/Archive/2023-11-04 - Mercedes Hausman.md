---
tags:
  - my/journal
  - my/inspiration/dev
  - my/inspiration/photography
  - my/inspiration/design
  - sources/course
date: 2023-11-04
---

# 2023-11-04

Workshop con **[Mercedes Hausmann](https://basquedokfestival.com/blog/team-member/mercedes-hausmann/)**.

Midjourney 
La herramienta más completa para imágenes con una pretensión realista

La interfaz es conversacional.

/blend 
/imagine
...


# Cómo configurar midjourney

/settings

![[Captura de Pantalla 2023-11-04 a las 18.11.05.png]]
--s 1000 calidad
--v versión:
--chaos 100 
--w 1000 weird (rollo tim burton)
--ar 4:3. 3:4
5.1: más fotográfica, libre, creativa - 
5.2: más comercial
Manzana: estética manga
Niji: estética manga

raw mode: marcado -- negativo digital
stylize: marcado very high -- calidad fotográfica de la imagen
Remix mode: marcado -- te deja la opción de ir iterando sobre el prompt que has hecho.
High variation mode: marcado --  aporta gran variación entre las propuestas que te hace.

Los parámetros deben ir al final de prompt (añadir --s 1000 al final para forzar la calidad)

Orden de las imágenes:

1 2
3 4

In the style of -- Añadido al prompt. Poner un autor conocido, una película, estilo fotográfico

¿? Meterle al prompt que sea fotográfico o fotorealista --> añadir _"realistic, photography."

/imagine [DESCRIPCION] [--s] {-- s}  { --chaos 100 (max) }  { --w}

/imagine an old woman, realistic, photography

Si introducimos poca información él rellena el resto. Los prompts/descripciones deben añadir información y construirse con una jerarquía:
1) Quien Descripción de un sujeto
2) Que Un sujeto realizando una acción
3) ", realistic, photography"
4) Donde Un sujeto realizando una acción en un lugar
5) Cuando Un sujeto realizando una acción en un lugar en una época
	1) In the 1980s
	2) 1980s fashion
	3) 
6) Como (paleta de color, tipo de cámara, carrete)
7) Momento del día, tipo de luz...
8) punto de vista más de retrato (hay códigos que se pueden ir metiendo; meter distancias focales, punto de vista) f/1.4

Los datos deben introducir lo que queremos de forma genérica pero sin llegar a ser muy especifico (que exista cierta abundancia de imágenes) 

Después se puede cambiar el formato de la foto, quitar marcos, podemos panear, ampliar el plano hacia los lados y hacía arriba y hacia abajo

Cuando seleccionas una variación te salen las flechas, que son las opciones para panear:

![[Captura de Pantalla 2023-11-04 a las 19.36.13.png]]


Al panear hay que quitar el sujeto y describir que quieres que aparezca

![[Captura de Pantalla 2023-11-04 a las 19.40.07.png]]

El zoom out vuelve a poner el formato cuadrado, de modo que primero hay que hacer zoom out y luego panear![[Captura de Pantalla 2023-11-04 a las 19.50.16.png]]
Vary region:
Puedes eliminar un elemento de la foto

![[Captura de Pantalla 2023-11-04 a las 20.05.35.png]]
También se puede quitar algo que hayas metido en el prompt y poner en su lugar blank

Una vez que hemos puesto el parametro --ar podemos usar el vary region, panear... etc

por defecto el tamaño de imagen es 1024 pero se puede ampliar

minimalism
expresionismo abstracto
surrealismo
siniestro
terror
divertido
una vanguardia artistica
pictorialismo
retrofuturista
hiperrealista
que se vea la textura
que tenga pecas (obliga a  midjourney a poner textura)

-- los adjetivos ayudan a definir

/blend { adjuntar fotos }
mezcla 1..5 fotografías
si son fotos de fondo blanco va a mezclar los motivos
depende de la forma del color y de la imagen que adjuntemos, si son motivos reconocibles(una mano y una manzana, pone la manzana en la mano)

/imagine {url image} flying in the clouds

mezcla imagen y texto

/describe {archivo}

subes el archivo y te saca 4 prompts que necesitaría para mostrar esa imagen, con referencias y enlaces de búsqueda de lo que usaría como base

puedes sacar todos los prompts como imagenes y analizar lo que saca.  Según las imagenes que te gustan puedes ir coleccionando prompts y formándote un diccionario de cosas que te gustan.

midjourney tiene una resolución 1024x1024
upscale 2x 
upscale 4x

# Referencias

Términos cinematográficos - how to read a film
https://tagg.org/teaching/mmi/filmtrms.html



