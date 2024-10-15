# ejercicio-git-libro

## Se clona el fichero

```code

git clone https://github.com/diego-febles-seoane/ejercicio-git-libro
Clonando en 'ejercicio-git-libro'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo.

```

## Se crea la capeta 

```code

git log
commit 83c1440110bb870659b981c1100967c4c82bb6fc (HEAD -> main, origin/main, origin/HEAD)
Author: Diego Febles Seoane <diegofebless@gmail.com>
Date:   Tue Oct 15 16:28:07 2024 +0100

    Initial commit

mkdir capitulos

```

## Se crea el fichero carpeta 1 y se modifica

```code

cat > capitulos/capitulo1.txt
Git es un sistema de control de versiones ideado por Linus Torvalds.

```

## Se añade al repositorio

```code

git add .

```

## Se realiza el commit 

```code

git commit -m "Añadido capítulo 1."
[main be39c32] Añadido capítulo 1.
 1 file changed, 1 insertion(+)
 create mode 100644 capitulos/capitulo1.txt

```

## Se actualiza en le repositorio

```code

git push
Username for 'https://github.com': diego-febles-seoane
Password for 'https://diego-febles-seoane@github.com': 
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (4/4), 409 bytes | 409.00 KiB/s, listo.
Total 4 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/diego-febles-seoane/ejercicio-git-libro
   83c1440..be39c32  main -> main

```

## Se crea el fichero carpeta 1 y se modifica

```code

cat > capitulos/capitulo2.txt
El flujo de trabajo básico con Git consiste en:
 1- Hacer cambios en el repositorio.
 2- Añadir los cambios a la zona de intercambio temporal.
 3- Hacer un commit de los cambios.

```

## Se añade al repositorio

```code

git add .

```

## Se realiza el commit 

```code

git commit -m "Añadido capítulo 2."
[main 6c3aecf] Añadido capítulo 2.
 2 files changed, 80 insertions(+), 1 deletion(-)
 rewrite README.md (100%)
 create mode 100644 capitulos/capitulo2.txt

```

## Se actualiza en le repositorio

```code

git push
Enumerando objetos: 8, listo.
Contando objetos: 100% (8/8), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (5/5), listo.
Escribiendo objetos: 100% (5/5), 1.20 KiB | 1.20 MiB/s, listo.
Total 5 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/diego-febles-seoane/ejercicio-git-libro
   be39c32..6c3aecf  main -> main

```

