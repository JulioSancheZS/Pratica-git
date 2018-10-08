### git log

Muestra el historial de confirmación.

`git log -n`: cambiamos la n por cualquier numero entero, por ejemplo:
`git log -2` Nos mostrara los 2 commit más recientes.

`git log --after="2017-04-07 00:00:00"`: Muestra las commit realizados despues de la fecha
especificada.

`git log --before="2017-04-07 00:00:00"`: Muestra los commit realizados antes de la fecha
especificada

Las banderas del comando `git log` se puede usar juntas segun nos convenga, por ejemplo:
`git log --after="2017-04-07 00:00:00" --before="2017-04-07 00:00:00"`

`git log --oneline`
Nos muestra en historial en una sola linea por commit
