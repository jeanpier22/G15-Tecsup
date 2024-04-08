# form
## action
Para definir donde se va a guardar la informacion del formulario
es una url
## method: por defecto es get
get: sirve para listar informacion obtener 
post: publicar

text    Nombre
text    Apellido
email   Email
date    Fecha de Nacimiento
number  DNI
tel number Telefono celular
password Contrasena
radio Sexo

Pais (select options)
Ciudaad (select options)
text Direccion
checkbox Cursos
file  foto de DNI

submit 
<input type="submit" value="enviar"/>
<button type="submit">Enviar</button>

La pagina web debe verse igual en cualquier tipo de navegador, no deben ser diferentes.

number no se usa, se puede usar un text y en js se cambia a numero
La validacion de datos se hace en js.
Que es mejor mostrar los errores antes o despues?


Todo navegador tiene la opcion de dev tool (inspeccionar f12)

Cada input tiene dos atributo epecial
name = value
name es un identificador

Todo input de selección requiere un value es una regla

readonly si envía al sevidor pero disabled no envía
