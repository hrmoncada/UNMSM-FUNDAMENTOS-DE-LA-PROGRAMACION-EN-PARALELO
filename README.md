# UNMSM-FUNDAMENTOS-DE-LA-PROGRAMACION-EN-PARALELO

## Introducción a MPI

En la actualidad, es posible contar con una alta capacidad computacional mediante clústeres de computadoras personales independientes, de bajo costo, interconectadas mediante tecnologías de red de alta velocidad y utilizando software de libre distribución. La aparición de la computación paralela permitió el desarrollo de métodos de programación que facilitan la implementación de algoritmos aprovechando recursos compartidos, como procesadores, memoria, datos y servicios.

Message Passing Interface (MPI) fue creado en 1993 como un estándar abierto desarrollado por fabricantes y usuarios de sistemas paralelos. MPI representó el primer esfuerzo significativo para producir una interfaz estándar para el paso de mensajes. Expertos en sistemas basados en paso de mensajes (incluyendo PVM, PARMACS y CHIMP de EPCC) junto con representantes de diversas organizaciones, usuarios y proveedores de sistemas paralelos de Estados Unidos y Europa formaron el FORUM MPI, encargado de definir el estándar. Posteriormente, MPI-2 amplió el alcance hacia otras áreas de la programación distribuida.

## Objetivo

El objetivo de esta asignatura es adquirir conocimiento y experiencia en el desarrollo de aplicaciones paralelas y distribuidas, abarcando un rango amplio de plataformas de hardware que incluye:

* Sistemas multi-core de memoria compartida.
* Sistemas multi-GPU.
* Grandes multicomputadores paralelos de memoria distribuida.
* Soluciones basadas en entrada/salida paralela.

Todo esto en el marco de la computación de alto rendimiento (HPC, High Performance Computing).

En este curso se introducirán los conceptos básicos del desarrollo de aplicaciones paralelas, abordando aspectos relacionados con lenguajes de programación que ofrecen soporte para el desarrollo mediante bibliotecas de paso de mensajes. Se analizarán las diferentes alternativas de estas bibliotecas, su arquitectura y algunas consideraciones de diseño para aplicaciones paralelas. Además, se presentará una aplicación para resolver Cadenas de Markov, ejecutada sobre un clúster configurado con la herramienta NPACI Rocks, mostrando los resultados obtenidos.

## Contenidos

1. MPI para programar máquinas de memoria distribuida y vectorización para explotar las unidades vectoriales de los procesadores modernos, así como arquitecturas de many integrated core (MIC).
2. OpenMP para programar multiprocesadores de memoria compartida.
3. CUDA para programar GPUs (Aceleradores).

Los MICs y GPUs se emplean como coprocesadores en clústeres de mayor escala (memoria distribuida), donde cada nodo actúa como un multiprocesador (memoria compartida). Dada la naturaleza de la asignatura, enfocada en la programación de grandes sistemas, se otorga una énfasis especial en la práctica. La teoría se complementa con múltiples prácticas y proyectos para consolidar y profundizar en los conceptos tratados.

En caso de contar con pocos estudiantes (5-6 o menos), se reducirán las clases magistrales, enfatizando el trabajo práctico y orientando la asignatura hacia proyectos pequeños que permitan integrar los diferentes temas en un contexto aplicado, mostrando cómo se relacionan y complementan.

## Características de MPI

* Portabilidad y eficiencia: MPI es un estándar para programación en paralelo mediante paso de mensajes que permite crear programas portables y eficientes.
* Interfaz genérica: Su diseño permite una implementación optimizada en cualquier sistema paralelo.
* Compatibilidad multilenguaje: Incluye interfaces para FORTRAN, C/C++ y Python.
* Flexibilidad en la comunicación: Define diversas formas de comunicación, facilitando la programación de cualquier algoritmo paralelo de manera natural.
* Enfoque en bibliotecas paralelas: Su diseño está orientado a la creación de bibliotecas paralelas especializadas.

## Características de OpenMP
* En desarrollo ....
## Características de CUDA
* En desarrollo ....

