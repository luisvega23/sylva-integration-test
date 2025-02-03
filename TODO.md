#TODO:
Revisar el `base` de environment values:
-> Ahí está el helmrelease que necesitas
Utilizar el comando kustomize sobre ese para generar el helmrelease apuntando a mi repo
Minetras tanto, en mi repo:
-> Recortar los values del chart de sylva units
-> Si es posible, romper todo excepto el workload cluster operator
-> Revisar si de esta manera se inyectan los values/se aplica el patch con la imagen.
Si lo anterior se cumple -> Podríamos editar/patchear para poder apuntar a un registry offline.
Repetir proceso anterior con el SWO. Idealmente hacer esto el día lunes 