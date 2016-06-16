x3g Cura plugin para Tecnoart II
==


Despues de trabajar mucho tiempo con el Cura y solo en windows, decidi arreglarlo para que funcione en mi Mac.

En el proceso aprendi cosas interesantes e incluso escribi mi propio plugin picando cosas de aca y alla.

La cuestion mas importante es que el unico plugin que funcionaba hasta ahora, era muy incomodo de usar: en el caso de windows tenias que abrir Cura en modo administrador y eso te generaba, despues del postprocessing, un archivo Output.x3g en el raiz de tu disco C (por eso habia que ejecutarlo en modo administrador). En el caso de Mac, directamente no andaba, o la unica documentacion disponible, estaba espantosamente incompleta

Esta nueva version genera un archivo con extension .x3g en el mismo directorio de donde cargaste el archivo .stl original, con lo cual no necesitas ejecutarlo como administrador

## Instalacion

* Tomar el contenido de la carpeta plugin y volcarlo en la carpeta homonima dentro de la instalacion local de Cura. En el caso de windows es X:/CuraFolder/Resources/plugins. En el caso de Max es /Applications/Cura/Cura.app/Contents/Resources/plugins/
* Ya en Cura, agregar el plugin GPX al final de la lista de plugins a usar. Como se ve en la imagen:


![alt mac](https://github.com/diegoram/x3gTecnoArtPlugin/blob/master/img/1.png)

Aca la parte mas importante es el archivo param.ini que es el que contiene todos los parametros seteados especialmente para la impresora Tecnoart II de Far (la cual es una replica de la MakerBot).
Tener en cuenta que en el parametro de "Tipo de Maquina" se debe indicar que es una "r1d" (MakerBot dual extruder)


