[TAREA4_JulethFlores_netsize (1).txt](https://github.com/Julethflores/-T1_Unix_GitTarea/files/8978540/TAREA4_JulethFlores_netsize.1.txt)#! /bin/bash
echo "Filename : ../data/Saavedra2013/n1.txt" #IMPRIMIR TEXT DE UNA CARPETA
echo "Número de filas" #IMPRIME EL NÚMERO DE FILAS
cat  ../data/Saavedra2013/n1.txt | wc -l #IMPRIME ALGO QUE ESTA HECHO
echo "Número de columnas" #IMPRIME EL NÚMERO DE COLUMNAS
head - n1 ../Saavedra2013/n1.txt | tr -d " " | tr -d "\n" | wc -c #LEE LO CARACTERES DELA PRIMERA LÍNEA

$ cat netsize.sh
#! /bin/bash
echo "Filename : ../data/Saavedra2013/n1.txt" #IMPRIMIR TEXT DE UNA CARPETA
echo "Número de filas" #IMPRIME EL NÚMERO DE FILAS
cat  ../Saavedra2013/n1.txt | wc -l #IMPRIME ALGO QUE ESTA HECHO
echo "Número de columnas" #IMPRIME EL NÚMERO DE COLUMNAS
head -n1 ../Saavedra2013/n1.txt | tr -d " " | tr -d "\n" | wc -c #LEE LO CARACTERES DELA PRIMERA LÍNEA

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ cat netsize.sh
#!/bin/bash
echo "Filename : ../data/Saavedra2013/n1.txt" #IMPRIMIR TEXT DE UNA CARPETA
echo "Número de filas" #IMPRIME EL NÚMERO DE FILAS
cat  ../data/Saavedra2013/n1.txt | wc -l #IMPRIME ALGO QUE ESTA HECHO
echo "Número de columnas" #IMPRIME EL NÚMERO DE COLUMNAS
head - n1 ../Saavedra2013/n1.txt | tr -d " " | tr -d " \n " | wc -c #LEE LO CARACTERES DELA PRIMERA LÍNEA


USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ nano netsize.sh

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ bash netsize.sh
Filename : ../data/Saavedra2013/n1.txt
Número de filas
cat: ../data/Saavedra2013/n1.txt: No such file or directory
0
Número de columnas


USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ nano netsize.sh

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ touch netsize_all.sh

USER@DESKTOP-61NU5K9 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
USER@DESKTOP-61NU5K9 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ bash netsize_all.sh
Numero de filas
97
14
270
7
61
35
38
118
76
13
10
62
18
19
19
179
80
17
82
27
90
61
25
8
28
45
70
79
14
40
44
51
33
101
28
12
42
55
56
36
58
139
118
47
21
45
8
33
34
126
14
110
14
678
663
9
16
19
12
Número de columnas
81
21
92
73
18
16
12
25
32
15
17
42
8
46
37
27
29
17
41
6
20
26
37
20
26
22
21
26
9
170
14
100
26
12
19
11
9
30
10
62
18
42
50
24
8
47
16
8
14
26
51
208
12
91
131
32
26
34
23

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ nano netsize.sh

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ bash netsize.sh
Filename : ../data/Saavedra2013/n1.txt
Número de filas
cat: ../data/Saavedra2013/n1.txt: No such file or directory
0
Número de columnas
81

USER@DESKTOP-61NU5K9 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ cat netsize.sh
#! /bin/bash
echo "Filename : ../data/Saavedra2013/n1.txt" #IMPRIMIR TEXT DE UNA CARPETA
echo "Número de filas" #IMPRIME EL NÚMERO DE FILAS
cat  ../data/Saavedra2013/n1.txt | wc -l #IMPRIME ALGO QUE ESTA HECHO
echo "Número de columnas" #IMPRIME EL NÚMERO DE COLUMNAS
head -n1 ../Saavedra2013/n1.txt | tr -d " " | tr -d "\n" | wc -c #LEE LO CARACTERES DELA PRIMERA LÍNEA


USER@DESKTOP-61NU5K9 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ nano netsize.sh

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ bash netsize.sh
Filename : ../data/Saavedra2013/n1.txt
Número de filas
97
Número de columnas
81

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ ^C

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ ./netsize.sh Saavedra2013/n1.txt >>netsize.txt

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ ./netsize.sh Saavedra2013/n1.txt >>netsize_all.txt

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ ./netsize_all.sh Saavedra2013/n1.txt >>netsize.txt

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$ ./netsize_all.sh Saavedra2013/n1.txt >>netsize_all.txt

USER@DESKTOP-61NU5K9 MINGW64 ~/documents/Github/CSB/unix/data/Saavedra2013 (master)
$
[TAREA4_JulethFlores_netsize (1).txt](https://github.com/Julethflores/-T1_Unix_GitTarea/files/8978646/TAREA4_JulethFlores_netsize.1.txt)

# -T1_Unix_GitTarea
Realice el ejercicio 1.10.3 Plant-Pollinator Networks, página 52, en el texto: 2019_Allesina_Wilmes_ComputingSkills4Biologists-Toolbox.pdf. 
