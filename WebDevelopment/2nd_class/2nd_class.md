# Programación Web *(2nd Class)*

## HTML
### ¿Que es?
Len1guaje de marcas de hipertexto. Invencion en los noventa para la creacion de documentos enriquecidos, requiere un editor de texto simplemente. Es un lenguaje interpretado normalmente por un navegador web.

### Elementos importante 
#### Doctype
En el código fuente de los documentos y subpáginas HTML, la etiqueta <!DOCTYPE html> debe encontrarse al principio. Gracias a DOCTYPE se puede saber a primera vista de qué tipo de documento se trata. Si el documento no tiene la etiqueta se pueden producir errores de visualización en tu web.

#### Etiquetas 
(<, >) encapsulan un determinado identificador que determina el contenido de la misma hay dos tipos, de auto cerrado (self closing) y aquellas que llevan contenido dentro que serian as:
- Comunes: ```<etiqueta></etiqueta>```
- Self closing: ```<etiqueta />```
##### Etiquetas importantes
###### Body
La etiqueta ```<body>``` define el cuerpo del documento. El elemento ```<body>``` contiene todo el contenido de un documento HTML, como títulos, párrafos, imágenes, hipervínculos, tablas, listas, etc.
###### Comments
La etiqueta comment se utiliza para insertar comentarios en el código fuente. Los comentarios no se muestran en los navegadores.
```<!--This is a comment. Comments are not displayed in the browser-->```
###### Doctype
Todos los documentos HTML deben comenzar con una declaración ```<!DOCTYPE>```.
La declaración no es una etiqueta HTML. Es una "información" al navegador sobre qué tipo de documento debe esperar.

##### Etiquetas más comunes
1. body: 
2. H[1-6]: Son textos de cabecera, que hacen como titulos. ````<h3></h3>```
3. Parrafo: etiqueta de parrafo para textos de gran longitud ```<p></p>```
4. anchor (enlace):  Anchor o hipervinculos que enlazan a una pagina externa o alguna otra ubicacion dentro de la misma pagina. ```<a></a>```
5. break: tag diseñado para salto de linea ```<br>```
6. Unordered List: Listas de items desordenados (no numerados) ```<ul></ul>```
7. Ordered List: Listas de items ordenados (numerados) ```<ol></ol>```
8. List item: Item de lista, elemento que compone una lista ya sea ordenada o desordenada ```<li></li>```
9. imagenes: Esta etiqueta se utiliza para incrustar una imagen en una página HTML. Técnicamente, las imágenes no se insertan en una página web, sino que se enlazan a páginas web. La etiqueta ```<img/>``` crea un espacio para la imagen referenciada. La etiqueta ```<img/>``` tiene dos atributos obligatorios:
	- src - Especifica la ruta a la imagen.
	- alt - Especifica un texto alternativo para la imagen, si la imagen por alguna razón no se puede mostrar
	Nota: especifique siempre la anchura y la altura de la imagen. Si no se especifican, la página podría parpadear mientras se carga la imagen.

#### Estructura basica de un documento de HTML
```
<!DOCTYPE html>
<html>
	<head>
		<title>Title of the document</title>
	</head>
	<body>
		he content of the document......
	</body>
</html> 
```



