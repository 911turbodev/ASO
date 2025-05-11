# ASO

## 📘 ¿Qué es una computadora según Von Neumann?  
John von Neumann definió una computadora como una máquina electrónica de propósito general, capaz de almacenar y ejecutar programas que manipulan datos.

## 🧠 Principios clave de su arquitectura:  

### Memoria única:  
- Almacena datos e instrucciones en el mismo lugar.  
- Permite modificar programas sin cambiar físicamente la máquina.  

### Unidad de procesamiento (CPU):  
- Formada por:  
  - **Unidad de Control**: Interpreta y dirige la ejecución de instrucciones.  
  - **Unidad Aritmético-Lógica (ALU)**: Realiza operaciones matemáticas y lógicas.  

### Ejecución secuencial:  
- Las instrucciones se ejecutan una por una, en orden, a menos que se indique lo contrario (como con bucles o saltos).  

### Dispositivos de Entrada/Salida:  
- Permiten la interacción con el mundo exterior (teclado, pantalla, impresora, etc.).  

## 🧩 Importancia del modelo:  
- Base del diseño de casi todas las computadoras modernas.  
- Introdujo el concepto de programa almacenado, esencial para la programación flexible.

![image](https://github.com/user-attachments/assets/697814af-8d1d-49eb-86d4-4ad33c2a5bed)


![image](https://github.com/user-attachments/assets/d6861f86-32ee-4d85-83d1-9646cd97d4aa)

# Componentes internos de la CPU

La CPU (Unidad Central de Procesamiento) es el "cerebro" del computador. Sus componentes internos principales son:

## Unidad de Control
- Se encarga de interpretar y secuenciar las instrucciones almacenadas en memoria.
- Dirige el flujo de datos y señales de control hacia los demás componentes (ALU, registros, E/S).

## Unidad Aritmético-Lógica (ALU)
- Realiza todas las operaciones de procesamiento de datos:
  - **Aritméticas**: suma, resta, multiplicación, división.
  - **Lógicas**: comparaciones, operaciones booleanas (AND, OR, NOT, XOR).
- Responde a las órdenes de la Unidad de Control.

## Registros
- Pequeñas celdas de memoria ultra-rápida dentro de la CPU.
- Almacenan temporalmente:
  - Datos en proceso de cálculo.
  - Direcciones de memoria.
  - Resultados intermedios.
- Mejoran la velocidad de ejecución al evitar accesos constantes a la memoria principal.

## Interconexiones (Bus interno)
- Conjunto de líneas eléctricas que comunican:
  - Unidad de Control ↔ ALU
  - ALU ↔ Registros
  - Registros ↔ Unidad de Control
- Permiten el transporte de datos, direcciones y señales de control de forma coordinada.

![image](https://github.com/user-attachments/assets/869acf07-a09e-4609-a350-8688b63d1c1a)

Apunte Detallado: Arquitectura Von Neumann y Componentes Clave
1. Arquitectura Von Neumann
Concepto: Modelo de computación propuesto por John von Neumann donde datos e instrucciones comparten el mismo espacio de memoria.

Elementos principales:

Memoria (almacena datos e instrucciones).

CPU (procesa y controla la ejecución).

Dispositivos de Entrada/Salida (E/S).

Buses (canales de datos, direcciones y control).

2. Registros del Procesador
Definición: Pequeñas celdas de memoria ultra-rápida dentro de la CPU.

Tipos comunes:

Registro de instrucción (IR): Guarda la instrucción en ejecución.

Contador de programa (PC): Señala la dirección de la próxima instrucción.

Registro de estado (FLAGS): Indica condiciones (cero, acarreo, signo).

Registros generales: Operandos, resultados intermedios.

3. Ejecución de Instrucciones
Fetch (búsqueda)

La CPU lee la instrucción apuntada por el PC desde memoria.

Decode (decodificación)

La Unidad de Control interpreta la operación y sus operandos.

Execute (ejecución)

La ALU realiza la operación aritmético-lógica.

Write-back (escritura)

El resultado se escribe en un registro o en memoria.

Actualización de PC

El contador avanza a la siguiente instrucción o se modifica en saltos.

4. Interrupciones
Definición: Señales que suspenden la ejecución normal para atender eventos (E/S, errores, reloj).

Tipos:

Hardware: Pulsadores, temporizadores, controladores de E/S.

Software: Llamadas al sistema, excepciones.

Mecanismo:

Guarda contexto (registros, PC).

Salta a rutina de servicio de interrupción (ISR).

Atiende el evento.

Restaura contexto y reanuda la ejecución.

5. CPU (Unidad Central de Procesamiento)
5.1 Definición
Dispositivo encargado de interpretar y ejecutar las instrucciones de los programas, coordinando el funcionamiento del sistema.

5.2 Unidad de Control
Interpreta las instrucciones extraídas de la memoria.

Genera señales de control para direccionar el flujo de datos.

Coordina operaciones entre ALU, registros y E/S.

5.3 Unidad Aritmético-Lógica (ALU)
Operaciones aritméticas: suma, resta, multiplicación, división.

Operaciones lógicas: AND, OR, NOT, comparaciones.

Responde a las órdenes de la Unidad de Control.

6. Programas e Instrucciones
Programa: Secuencia de instrucciones que resuelven una tarea.

Instrucción: Operación elemental (leer, escribir, calcular, saltar).

Formato: Código de operación (opcode) + operandos.

Ciclo de vida: Compilación/ensamblado → carga en memoria → ejecución.

7. Memoria
7.1 Jerarquías de Memoria
Registros (más rápido, capacidad reducida)

Caché (L1, L2, L3)

Memoria principal (RAM)

Memorias secundarias (discos duros, SSD)

Almacenamiento fuera de línea (CD/DVD, cintas)

Dispositivos extraíbles (USB, tarjetas SD)

7.2 Memoria Principal (RAM)
Volátil: pierde datos al apagar.

Acceso aleatorio: lectura y escritura a igual velocidad.

Funciones: aloja programas e instrucciones en ejecución.

7.3 Memorias Secundarias
Discos duros (HDD): magnético, buena capacidad, menor velocidad.

Unidades de estado sólido (SSD): memoria flash, alta velocidad, coste mayor.

7.4 Almacenamiento Fuera de Línea
CD/DVD/Blu-Ray: óptico, uso para copias de respaldo o distribución.

Cintas magnéticas: alto volumen, lento acceso, archivado a largo plazo.

7.5 Dispositivos Extraíbles
USB flash drives: portátiles, pequeño tamaño, capacidad variable.

Tarjetas de memoria: SD, microSD; usadas en cámaras, móviles.

![image](https://github.com/user-attachments/assets/3595036b-0f29-4b56-bae0-13674b088c0e)

