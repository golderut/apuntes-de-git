### git tag
Lista las etiquetas en orden alfabetico.

### git tag -a nombre_etiqueta -m "mensaje de la etiqueta"
Etiqueta anotada. Se guardan en la base de datos de Git como un objetos entero. Tienen un checksum; contiene el nombre del etiquetador, correo electronico y fecha; y tienen un mensaje asociado.

´´´
git tag -l "v1.*"
´´´
Lista las etiquetas que coincidan con el patron especificado.