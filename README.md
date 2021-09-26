# nvim-notes

## Menú

- [moverse entre palabras](#moverse-entre-palabras)
- [insertar](#insertar)
- [eliminar texto](#eliminar-texto)
- [guardar](#guardar)
- [salir](#salir)
- [moverse entre archivos](#moverse-entre-archivos)
- [historial](#historial)
- [pegar](#pegar)
- [reemplazar y cambiar](#reemplazar-y-cambiar)
- [saltos de linea y busqueda](#saltos-de-linea-y-busqueda)
- [cambio de parentesis](#cambio-de-parentesis)
- [abrir linea, reemplazar](#abrir-linea-reemplazar)
- [copiar y pegar](#copiar-y-pegar)

---

> modo normal

### moverse entre palabras

* `w` adelantar palabras
* `<numero>w` adelantar una cantidad de palabras
* `b` regresar palabras
* `<numero>b` regresar una cantidad de palabras
* `e` final de la palabra
* `h` izquierda
* `l` derecha
* `j` abajo
* `k` arriba

---

### insertar

* `i` insertar texto antes
* `a` insertar texto despues
* `A` final de la línea

---

### eliminar texto

* `x` eliminar caracter por caracter
* `dww` eliminar palabra por palabra
* `dd` eliminar toda una línea (guarda la línea en el clipboard)
* `db` eliminar hacia atras
* `d$` eliminar hacia adelante del cursor
* `de` eliminar hasta el final de una palabra
* `d<numero>w` eliminar una cantidad de caracteres dados

---

### guardar

* `:w` guardar sin salir
* `:wq` guardar y salir

---

### salir

* `:q` salir sin guardar
* `:q!` salir forzado

---

### moverse entre archivos

* `gd` navegar entre definiciones locales
* `gf` navegar entre directorios alguna definición
* `ctrl o` ver referencia
* `ctrl i` devolver referencia

---

### historial

* `u` deshacer
* `ctrl r` rehacer

---

### pegar

* `p` pegar abajo
* `P` pegar arriba

---

### reemplazar y cambiar

* `r` reemplazar, despues tipear el cambio
* `cw` cambiar una palabra desde donde esta el cursor
* `ciw` cambia toda la palabra

---

### saltos de linea y busqueda

* `gg` inicio del archivo
* `G` final del archivo
* `<numero>G` ir al numero de la linea
* `/<nombre>` busca a partir del cursor
* `?<nombre>` busca en todo el documento (`<Enter> + n o N` para cambiar entre coincidencias)

---

### cambio de parentesis

* `%` ir al parentesis correspondiente
* `:s/<nombre>/<nuevonombre>` cambia la primera ocurrencia de una linea
* `:s/<nombre>/<nuevonombre>/g`cambia todas las ocurrencias de una linea
* `:%s/<nombre>/<nuevonombre>/g` cambia todas las ocurrencias del archivo (sin preguntar)
* `:%s/<nombre>/<nuevonombre>/gc` cambia todas las ocurrencias del archivo (preguntando)

---

### abrir linea, reemplazar

* `o` nueva linea abajo
* `O` nueva linea arriba
* `R` reemplazar y el cursor avanza

---

### copiar y pegar

> modo visual `v`

* `x` cortar
* `y` copiar
* `p` pegar
