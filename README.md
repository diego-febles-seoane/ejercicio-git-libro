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

