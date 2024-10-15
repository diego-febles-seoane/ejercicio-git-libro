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

## Se edita el capitulo 1

```code
diff --git a/capitulos/capitulo1.txt b/capitulos/capitulo1.txt
new file mode 100644
index 0000000..e69de29
```
## Se edita el capitulo 2

```code
diff --git a/capitulos/capitulo2.txt b/capitulos/capitulo2.txt
new file mode 100644
index 0000000..4abf557
--- /dev/null
 b/capitulos/capitulo2.txt
@@ -0,0 +1,4 @@
El flujo de trabajo básico con Git consiste en:
 1- Hacer cambios en el repositorio.
 2- Añadir los cambios a la zona de intercambio temporal.
 3- Hacer un commit de los cambios.
```

## Se edita el capitulo 3

```code
diff --git a/capitulos/capitulo3.txt b/capitulos/capitulo3.txt
new file mode 100644
index 0000000..6e501ab
--- /dev/null
+++ b/capitulos/capitulo3.txt
@@ -0,0 +1 @@
+Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultanea en ellas.
diff --git a/cat b/cat
new file mode 100644
index 0000000..e69de29

```

## Se edita la biblioteca

```code
diff --git a/bibliografia.txt b/bibliografia.txt
new file mode 100644
index 0000000..544e5fa
--- /dev/null
 b/bibliografia.txt
@@ -0,0 +1,2 @@
- Chacon, S. and Straub, B. Pro Git. Apress.
- Loeliger, J. and McCullough, M. Version control with Git. O'Reilly.
diff --git a/capitulos/capitulo1.txt b/capitulos/capitulo1.txt
new file mode 100644
index 0000000..e69de29
```

## Se edita el capitulo 2

```code
diff --git a/capitulos/capitulo2.txt b/capitulos/capitulo2.txt
new file mode 100644
index 0000000..4abf557
--- /dev/null
 b/capitulos/capitulo2.txt
@@ -0,0 +1,4 @@
El flujo de trabajo básico con Git consiste en:
 1- Hacer cambios en el repositorio.
 2- Añadir los cambios a la zona de intercambio temporal.
 3- Hacer un commit de los cambios.
```

## Se edita el capitulo 3

```code
diff --git a/capitulos/capitulo3.txt b/capitulos/capitulo3.txt
new file mode 100644
index 0000000..6e501ab
--- /dev/null
 b/capitulos/capitulo3.txt
@@ -0,0 +1 @@
Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultanea en ellas.
```
## Se edita el capitulo 4

```code

diff --git a/capitulos/capitulo4.txt b/capitulos/capitulo4.txt
new file mode 100644
index 0000000..99278d7
--- /dev/null
 b/capitulos/capitulo4.txt
@@ -0,0 +1 @@
En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto.
```
## Se edita el indice

```code
diff --git a/cat b/cat
new file mode 100644
index 0000000..e69de29
diff --git a/indice.txt b/indice.txt
```
## Se edita el indice

```code
new file mode 100644
index 0000000..2e99548
--- /dev/null
 b/indice.txt
@@ -0,0 +1 @@
Indice de los cápitulos, con conceptos avanzados de git
```