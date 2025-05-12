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

# Apunte Detallado: Arquitectura Von Neumann y Componentes Clave
# 1. Arquitectura Von Neumann
Concepto: Modelo de computación propuesto por John von Neumann donde datos e instrucciones comparten el mismo espacio de memoria.

Elementos principales:

Memoria (almacena datos e instrucciones).

CPU (procesa y controla la ejecución).

Dispositivos de Entrada/Salida (E/S).

Buses (canales de datos, direcciones y control).

# 2. Registros del Procesador
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

# 4. Interrupciones
Definición: Señales que suspenden la ejecución normal para atender eventos (E/S, errores, reloj).

Tipos:

Hardware: Pulsadores, temporizadores, controladores de E/S.

Software: Llamadas al sistema, excepciones.

Mecanismo:

Guarda contexto (registros, PC).

Salta a rutina de servicio de interrupción (ISR).

Atiende el evento.

Restaura contexto y reanuda la ejecución.

# 5. CPU (Unidad Central de Procesamiento)
5.1 Definición
Dispositivo encargado de interpretar y ejecutar las instrucciones de los programas, coordinando el funcionamiento del sistema.

# 5.2 Unidad de Control
Interpreta las instrucciones extraídas de la memoria.

Genera señales de control para direccionar el flujo de datos.

Coordina operaciones entre ALU, registros y E/S.

# 5.3 Unidad Aritmético-Lógica (ALU)
Operaciones aritméticas: suma, resta, multiplicación, división.

Operaciones lógicas: AND, OR, NOT, comparaciones.

Responde a las órdenes de la Unidad de Control.

6. Programas e Instrucciones
Programa: Secuencia de instrucciones que resuelven una tarea.

Instrucción: Operación elemental (leer, escribir, calcular, saltar).

Formato: Código de operación (opcode) + operandos.

Ciclo de vida: Compilación/ensamblado → carga en memoria → ejecución.

# 7. Memoria
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


# 1. ¿Qué es una computadora?
Una computadora es un dispositivo electrónico que recibe datos, los procesa y entrega resultados. Ejecuta instrucciones mediante programas y realiza tareas de manera automática y precisa.

🔧 Componentes fundamentales:
![image](https://github.com/user-attachments/assets/2a73a81d-76ee-49ea-a820-4645af3977be)

# 2. ¿Qué es el CPU?
El CPU (Unidad Central de Procesamiento) es el “cerebro” de la computadora. Ejecuta instrucciones y controla el funcionamiento del sistema.

# 3. ¿Qué es la memoria principal?
Es la memoria RAM (Memoria de Acceso Aleatorio), donde se cargan temporalmente los datos y programas en ejecución.

🧠 Función:
Almacena instrucciones y datos para ser rápidamente accedidos por el CPU.

📌 Ejemplo:
Al abrir un programa, este se carga en la memoria RAM para su ejecución.

# 4. ¿Qué es la memoria secundaria?
Es un tipo de almacenamiento permanente y de gran capacidad como el disco duro o SSD.

🧠 Función:
Guardar datos y programas de manera persistente, incluso cuando el equipo se apaga.

📌 Ejemplo:
Archivos guardados en un disco duro (HDD).

# 5. ¿Qué es el almacenamiento fuera de línea?
Es el almacenamiento extraíble y no conectado permanentemente, como:

CD/DVD

USB

Discos externos

Usado para copias de seguridad, transporte de datos o almacenamiento temporal.

# 6. ¿Qué es una jerarquía de memorias?
Organización de memorias en niveles según:

Velocidad

Tamaño

Costo

![image](https://github.com/user-attachments/assets/69df5329-5762-4a4a-8e26-8d68b09878cd)

# 7. ¿Qué es la memoria caché?
Es una memoria muy rápida ubicada cerca del CPU. Almacena instrucciones y datos usados con frecuencia, reduciendo el tiempo de acceso.

# 8. ¿Qué es un buffer?
Es una área de memoria temporal que almacena datos mientras se transfieren entre dispositivos con distintas velocidades.

📌 Ejemplo:
Reproducción de un video en streaming (el buffer almacena parte del video para evitar cortes).

# 9. ¿Qué es la memoria virtual?
Espacio de almacenamiento en disco que actúa como extensión de la RAM. Permite ejecutar más programas de los que la RAM podría manejar sola.

# 10. ¿Cuáles son los componentes fundamentales del CPU?
plaintext
Copiar
Editar
![image](https://github.com/user-attachments/assets/4f8a2a54-c8d5-46e0-8258-74f149231a9d)

# 11. ¿Cuál es la función de la UC?
La Unidad de Control dirige el flujo de datos y coordina la ejecución de instrucciones, interpretando las órdenes del programa.

# 12. ¿Cuál es la función de la ALU?
La Unidad Aritmético-Lógica realiza operaciones matemáticas (suma, resta) y lógicas (AND, OR, NOT).

# 13. ¿Qué elemento de la UC indica la siguiente instrucción?
El contador de programa (PC, Program Counter) contiene la dirección de la siguiente instrucción a ejecutar.

# 14. ¿Qué es el ciclo de vida de una instrucción?
Es el proceso mediante el cual el CPU ejecuta instrucciones.

🔄 Fases del ciclo:
Búsqueda (Fetch): Se obtiene la instrucción de memoria.

Decodificación (Decode): Se interpreta la instrucción.

Ejecución (Execute): Se realiza la operación.

Almacenamiento (Write back): Se guardan resultados si es necesario.

# 15. ¿Qué son las técnicas de direccionamiento?
Métodos para acceder a los operandos que necesita una instrucción.

📌 Tipos:
Directo: La dirección del operando está en la instrucción.

Indirecto: La instrucción contiene una dirección que apunta a otra dirección donde está el operando.

Inmediato: El operando está directamente en la instrucción.

Por base y desplazamiento: Se suma un desplazamiento a un registro base.

![image](https://github.com/user-attachments/assets/ba188e57-f0f5-453a-8028-6c60b5faf149)


# 16. ¿Qué son los periféricos?
Dispositivos que permiten la interacción con la computadora.

📎 Clasificación:
Entrada: Teclado, ratón

Salida: Monitor, impresora

Entrada/Salida: USB, disco externo

17. Mecanismos de E/S (Entrada/Salida)
✅ Guiado por programa:
El CPU controla todo el proceso de E/S. Es simple, pero ineficiente (CPU queda ocupada).

✅ Por interrupciones:
El dispositivo interrumpe al CPU cuando está listo, liberando al CPU mientras tanto.

✅ DMA (Acceso Directo a Memoria):
Un controlador especial transfiere datos entre la memoria y el dispositivo sin involucrar al CPU.
![image](https://github.com/user-attachments/assets/a3f998d8-176e-41c2-bf4f-ad216cafd9a0)


# -----------------------------------------------------------------------

# Esquema general de una computadora:

![image](https://github.com/user-attachments/assets/900530da-5d57-4dca-8d52-31aa2279209b)


Unidad Central de Procesamiento (CPU): Es el cerebro de la máquina.

Unidad de Control (UC): Decodifica las instrucciones y genera las señales de control para coordinar las demás partes. Es crucial para implementar los modos de direccionamiento:
Direccionamiento Directo: La UC interpreta la dirección en la instrucción y la envía directamente al Registro de Dirección de Memoria (MAR).

Direccionamiento Indirecto: La UC interpreta la dirección en la instrucción, la envía al MAR para leer otra dirección de la memoria. Luego, usa esa segunda dirección (leyéndola a través del MBR y colocándola en el MAR) para acceder al operando final.

Direccionamiento Inmediato: La UC identifica que el operando está dentro de la propia instrucción (ya en el Registro de Instrucción) y lo pasa directamente a la ALU o a un registro, sin acceder a la memoria para buscarlo.

Unidad Aritmético-Lógica (ALU): Realiza operaciones matemáticas y lógicas sobre los datos.

Registros: Pequeñas unidades de memoria de alta velocidad dentro de la CPU.

Contador de Programa (PC): Almacena la dirección de la próxima instrucción a ejecutar.

Registro de Instrucción (IR): Almacena la instrucción que se está ejecutando actualmente. Contiene el código de operación y el campo de dirección/operando.

Registro de Dirección de Memoria (MAR): Almacena la dirección de memoria a la que se va a acceder (leer o escribir).

Registro de Buffer de Memoria (MBR) / Registro de Datos de Memoria (MDR): Almacena temporalmente los datos que se leen o escriben en la memoria.

Registros de Propósito General (GPRs): Usados para almacenar operandos y resultados intermedios (pueden incluir acumuladores, registros base, etc.).

Memoria Principal (RAM): Almacena instrucciones y datos. Es una secuencia de celdas, cada una con una dirección única.

Sistema de Entrada/Salida (E/S): Permite la comunicación con dispositivos externos (teclado, monitor, disco duro, etc.). 
Incluye controladores y puertos de E/S.

Buses del Sistema: Conjunto de cables que conectan los componentes principales.

Bus de Direcciones: Transporta las direcciones de memoria desde la CPU (MAR) a la memoria o a los dispositivos de E/S.
Bus de Datos: Transporta los datos entre la CPU (MBR), la memoria y los dispositivos de E/S.
Bus de Control: Transporta las señales de control desde la UC a los demás componentes (ej. señales de lectura/escritura de memoria, peticiones de interrupción).

# 2. Teniendo en cuenta que la memoria de la máquina del punto 1 tiene una cantidad de 1.048.576 palabras
¿Cuántos bits necesita para direccionarla?

2. Bits para direccionar 1.048.576 palabras
La cantidad de ubicaciones a direccionar es N = 1.048.576.
Necesitamos encontrar la cantidad de bits 'b' tal que 2^b ≥ N.
Calculamos el logaritmo en base 2: b = log₂(N).
Sabemos que 1.048.576 es exactamente 2^20 (ya que 1 Mebi = 2^20).
Entonces: b = log₂(2^20) = 20.
Respuesta: Se necesitan 20 bits para direccionar 1.048.576 palabras.

# 3. Si tiene una memoria de 8GiB ¿Cuántos bits necesita para direccionar la memoria? 

Bits para direccionar 8 GiB de memoria
Primero, convertimos GiB (Gibibytes) a bytes, asumiendo que la memoria es direccionable a nivel de byte (lo estándar).
1 GiB = 2^30 bytes.
8 GiB = 8 × 2^30 bytes = 2^3 × 2^30 = 2^33 bytes.
La cantidad de ubicaciones (bytes) a direccionar es N = 2^33.
Calculamos los bits necesarios: b = log₂(N) = log₂(2^33) = 33.
Respuesta: Se necesitan 33 bits para direccionar 8 GiB de memoria.

# 4. Suponga que la máquina tiene una memoria de 1GB con palabras de 64bits y el registro de instrucción del
CPU tiene 32bits, con su campo de direcciones de 16bits. Responda:
a. ¿Cuánta memoria se podría direccionar con direccionamiento directo?
b. ¿Cuánta memoria se podría direccionar con direccionamiento indirecto?
c. ¿Cuánta memoria se podría direccionar con direccionamiento inmediato?
d. ¿Cuánta memoria se podría direccionar si posee direccionamiento por base y desplazamiento, con
registros base de 24bits?
e. ¿Qué tamaño debería tener el contador de programa si se quiere aprovechar toda la memoria
completa para instrucciones? 

# 4. Análisis de la Máquina Específica
Datos:

Memoria Total: 1 GB = 2^30 bytes

Tamaño de Palabra: 64 bits = 8 bytes

Registro de Instrucción (IR): 32 bits

Campo de Direcciones (en IR): 16 bits

Registro Base: 24 bits

a. ¿Cuánta memoria se podría direccionar con direccionamiento directo?
Con 16 bits en el campo de dirección, se pueden direccionar 2^16 ubicaciones distintas.
Esto equivale a 2^16 bytes = 65.536 bytes = 64 KiB.
Respuesta (a): Se pueden direccionar 64 KiB con direccionamiento directo.

b. ¿Cuánta memoria se podría direccionar con direccionamiento indirecto?
El campo de direcciones de 16 bits apunta a una ubicación de memoria que contiene una dirección de 30 bits (ya que 1 GB = 2^30 bytes).
La dirección final puede ser cualquiera dentro del rango de 2^30.
Respuesta (b): Se puede direccionar 1 GB con direccionamiento indirecto.

c. ¿Cuánta memoria se podría direccionar con direccionamiento inmediato?
El operando está dentro de la propia instrucción, no se accede a memoria para obtenerlo.
Respuesta (c): 0 bytes (o “No aplica”, ya que no direcciona memoria).

d. ¿Cuánta memoria se podría direccionar si posee direccionamiento por base y desplazamiento, con registros base de 24 bits?
El registro base de 24 bits permite apuntar hasta 2^24 bytes = 16 MiB.

El desplazamiento de 16 bits permite acceder a 2^16 bytes = 64 KiB.

Combinando ambos, se pueden generar distintas "ventanas" de 64 KiB dentro de todo el rango de 1 GB.

Cambiando el valor del registro base, es posible cubrir toda la memoria.
Respuesta (d): Se puede direccionar 1 GB con direccionamiento por base y desplazamiento.

e. ¿Qué tamaño debería tener el contador de programa si se quiere aprovechar toda la memoria completa para instrucciones?
Si las instrucciones están direccionadas a nivel de byte, se necesitan log₂(2^30) = 30 bits.

Si las instrucciones están alineadas a palabras de 64 bits (8 bytes), se direccionan 2^30 / 8 = 2^27 ubicaciones.
Entonces, log₂(2^27) = 27 bits.
Respuesta (e): El contador de programa debe tener 30 bits si direcciona a nivel de byte, o 27 bits si direcciona palabras de 8 bytes.

Ejercicio 1: Microcontrolador con Memoria Limitada

Imagina un microcontrolador simple con las siguientes características:

Memoria Total: 512 KiB (Kibibytes), direccionable a nivel de byte.
Tamaño de Palabra: 16 bits.
Registro de Instrucción (IR): 20 bits.
Campo de Direcciones (en IR): 10 bits.
Posee un conjunto de Registros de Propósito General (GPRs) de 16 bits cada uno.
Responde:

Contador de Programa (PC): ¿Cuántos bits necesita el PC para poder direccionar toda la memoria de instrucciones?
Direccionamiento Directo: ¿Cuánta memoria (en KiB) se podría direccionar utilizando el campo de 10 bits del IR para direccionamiento directo?
Direccionamiento Indirecto por Registro: Si una instrucción usa un GPR de 16 bits para contener la dirección de memoria del operando (ej. LOAD R1, (R2) donde R2 contiene la dirección), ¿cuánta memoria podría direccionar este modo?
Direccionamiento Inmediato: ¿Cuánta memoria se direcciona para obtener el operando en un modo inmediato?
Direccionamiento Indexado: Supón un modo de direccionamiento indexado donde la dirección efectiva se calcula sumando el contenido del campo de direcciones de 10 bits (considerado como un desplazamiento sin signo) al contenido de un GPR de 16 bits (registro índice). ¿Cuál es el rango máximo de memoria que podría teóricamente alcanzar este modo si el GPR puede cargarse con cualquier valor?
Ejercicio 2: Sistema con Espacio de Direccionamiento Virtual

# EJERCICIOS

Considera un sistema con las siguientes especificaciones:

Memoria Física Instalada: 16 GiB, direccionable a nivel de byte.
Tamaño de Palabra: 64 bits.
Arquitectura de Direcciones Virtuales: El sistema utiliza direcciones virtuales de 48 bits.
Registro de Instrucción (IR): 32 bits.
Campo de Direcciones (en IR): 18 bits.
Responde:

Bits para Direccionar Memoria Física: ¿Cuántos bits se necesitan para direccionar de forma única cada byte de la memoria física instalada?
Espacio de Direccionamiento Virtual: ¿Cuál es el tamaño total del espacio de direcciones virtuales que la CPU puede generar (en TiB o PiB)?
Direccionamiento Directo (en espacio virtual): Si el campo de 18 bits del IR se usa para direccionamiento directo dentro del espacio virtual, ¿cuánta memoria virtual (en KiB o MiB) puede direccionar directamente?
Direccionamiento por Base y Desplazamiento: El sistema tiene registros base de 48 bits. Si el campo de direcciones de 18 bits del IR se usa como un desplazamiento, ¿cuánta memoria virtual se podría direccionar con este modo?
Paginación: Si el sistema usa páginas de 4 KiB para mapear direcciones virtuales a físicas, ¿cuántos bits de la dirección virtual de 48 bits se usarían para el número de página virtual y cuántos para el desplazamiento dentro de la página?
Ejercicio 3: Máquina con Direccionamiento Segmentado y Palabra Ancha

Supón una arquitectura con estas características:

Memoria Total: 64 GiB, direccionable a nivel de byte.
Tamaño de Palabra: 32 bits.
Registro de Instrucción (IR): 40 bits.
Campo de Segmento (en IR): 8 bits. Este campo selecciona uno de 2 
8 registros de segmento.
Registros de Segmento: Cada registro de segmento contiene una dirección base de 30 bits.
Campo de Desplazamiento (en IR): 20 bits.
El direccionamiento principal es segmentado, donde la dirección efectiva se calcula: Dirección Efectiva = Contenido del Registro de Segmento (seleccionado por el campo de segmento) + Campo de Desplazamiento del IR.

# Responde:

# Bits del PC: ¿Cuántos bits necesitaría el PC para direccionar toda la memoria física si las instrucciones se almacenan en cualquier byte?
# Tamaño de un Segmento: ¿Cuál es el tamaño máximo de un único segmento (es decir, cuánta memoria es accesible con un valor fijo en un registro de segmento, variando solo el desplazamiento de 20 bits)? Exprésalo en MiB.
# Direccionamiento Total con Segmentación: ¿Cuál es la cantidad máxima de memoria que se podría direccionar teóricamente con este esquema de segmentación (considerando que los registros de segmento pueden apuntar a cualquier base permitida por sus 30 bits y el desplazamiento se suma)?
# Direccionamiento Relativo al PC: Supón que existe un modo de direccionamiento relativo al PC. El campo de desplazamiento de 20 bits del IR se usa como un offset con signo (complemento a dos) que se suma al PC actual. ¿Cuál es el rango de direccionamiento (hacia adelante y hacia atrás) desde la instrucción actual, en MiB?
# Direccionamiento Indirecto: Si el resultado del cálculo de la dirección segmentada (Base de Segmento + Desplazamiento) apunta a una palabra de memoria (32 bits) que a su vez contiene una dirección física completa para acceder al operando final, ¿cuántos bits necesitaría esa dirección física completa almacenada en memoria?

Solución Ejercicio 1: Microcontrolador con Memoria Limitada
Memoria Total:
512 KiB = 512 × 1024 bytes = 2^9 × 2^10 bytes = 2^19 bytes.

Campo de Direcciones IR:
10 bits.

GPRs:
16 bits.

Contador de Programa (PC):
Para direccionar 2^19 bytes únicos, se necesita un PC con log₂(2^19) = 19 bits.
Respuesta: 19 bits.

Direccionamiento Directo:
El campo de direcciones de 10 bits puede especificar 2^10 direcciones diferentes.
Asumiendo direccionamiento a nivel de byte, esto corresponde a 2^10 bytes = 1024 bytes = 1 KiB.
Respuesta: 1 KiB.

Direccionamiento Indirecto por Registro:
El GPR de 16 bits contiene la dirección.
Con 16 bits se pueden generar 2^16 direcciones únicas = 65.536 bytes = 64 KiB.
Aunque la memoria total sea mayor, este modo está limitado por el tamaño del registro.
Respuesta: 64 KiB.

Direccionamiento Inmediato:
El operando está dentro de la instrucción. No se direcciona memoria para obtenerlo.
Respuesta: 0 bytes (No se direcciona memoria para el operando).

Direccionamiento Indexado:
EA (dirección efectiva) = GPR (16 bits) + Desplazamiento (10 bits).

GPR puede tener hasta 2^16 - 1 = 65.535.

Desplazamiento puede tener hasta 2^10 - 1 = 1023.
Dirección máxima generada: 65.535 + 1023 = 66.558.
Aunque esta suma exceda los 64 KiB, el alcance real está limitado por el tamaño del GPR.
Respuesta: El modo puede alcanzar hasta 66.558, pero en la práctica solo 64 KiB son direccionables consistentemente debido a los 16 bits del GPR.

Solución Ejercicio 2: Sistema con Espacio de Direccionamiento Virtual
Memoria Física:
16 GiB = 16 × 2^30 bytes = 2^4 × 2^30 bytes = 2^34 bytes.

Dirección Virtual:
48 bits.

Campo de Direcciones IR:
18 bits.

Tamaño de Página:
4 KiB = 4 × 1024 bytes = 2^12 bytes.

Bits para Direccionar Memoria Física:
log₂(2^34) = 34 bits.
Respuesta: 34 bits.

Espacio de Direccionamiento Virtual:
Con 48 bits, el espacio es de 2^48 bytes = 256 × 2^40 bytes = 256 TiB.
Respuesta: 256 TiB.

Direccionamiento Directo (en espacio virtual):
Campo de 18 bits → 2^18 bytes = 256 × 1024 bytes = 256 KiB.
Respuesta: 256 KiB.

Direccionamiento por Base y Desplazamiento:

Registro base de 48 bits puede apuntar a cualquier dirección dentro del espacio virtual.

Desplazamiento de 18 bits se suma a la base.
Respuesta: 256 TiB (todo el espacio virtual puede ser direccionado).

Paginación:

Dirección virtual: 48 bits.

Tamaño de página: 2^12 bytes.

Bits de desplazamiento: log₂(2^12) = 12 bits.

Bits del número de página virtual: 48 - 12 = 36 bits.
Respuesta: 36 bits para el número de página virtual y 12 bits para el desplazamiento.

Solución Ejercicio 3: Máquina con Direccionamiento Segmentado y Palabra Ancha
Memoria Física:
64 GiB = 64 × 2^30 bytes = 2^6 × 2^30 = 2^36 bytes.

Registros de Segmento:
Base de 30 bits.

Campo de Desplazamiento IR:
20 bits.

Dirección Efectiva (EA):
Base de segmento (30 bits) + desplazamiento (20 bits).

Bits del PC:
Para direccionar 2^36 bytes, se necesitan log₂(2^36) = 36 bits.
Respuesta: 36 bits.

Tamaño de un Segmento:
2^20 direcciones posibles con el desplazamiento → 2^20 bytes = 1 MiB.
Respuesta: 1 MiB.

Direccionamiento Total con Segmentación:

Dirección máxima: (2^30 - 1) + (2^20 - 1) ≈ 2^30 + 2^20

Eso es aproximadamente 1 GiB + 1 MiB.

Mucho menor que los 64 GiB disponibles, por lo tanto no se puede acceder a toda la memoria física.
Respuesta: Aproximadamente 1 GiB + 1 MiB.

Direccionamiento Relativo al PC:

Desplazamiento de 20 bits con signo → rango: desde -2^19 hasta +2^19 - 1

2^19 bytes = 512 KiB

Rango efectivo: desde PC - 512 KiB hasta PC + 511.999 KiB
Respuesta: Rango relativo de 1 MiB (desde -512 KiB hasta +511.999 KiB).

Direccionamiento Indirecto:

La dirección generada por segmentación apunta a una palabra de 32 bits.

Pero para cubrir toda la memoria física de 2^36 bytes se necesitarían 36 bits.

Limitación: No caben 36 bits en una palabra de 32 bits.
Respuesta: Se necesitan 36 bits, pero no pueden almacenarse en una palabra de 32 bits — hay una limitación real en este modo.

# CUESTIONARIO ARQUITECTURA

# Cuestionario Microprocesadores

# 1- ¿Qué es la ALU y para qué sirve?
La ALU (Arithmetic Logic Unit) o Unidad Aritmético-Lógica es un circuito digital fundamental dentro de la CPU (Unidad Central de Procesamiento).
Sirve para: Realizar operaciones aritméticas (como suma, resta, multiplicación, división) y operaciones lógicas (como AND, OR, NOT, XOR, comparaciones) sobre los datos (operandos) que recibe. Es el componente que ejecuta los cálculos y las decisiones lógicas básicas de la computadora.

# 2- ¿Qué es la Unidad de Control y para qué sirve?
La Unidad de Control (UC) es otro componente esencial de la CPU. Actúa como el "director de orquesta" del procesador.
Sirve para:

Buscar (Fetch): Obtener la siguiente instrucción a ejecutar desde la memoria principal.

Decodificar (Decode): Interpretar la instrucción para saber qué operación realizar y con qué datos.

Ejecutar (Execute): Generar y enviar las señales de control necesarias a las otras partes del computador (ALU, registros, memoria, periféricos) para que ejecuten la instrucción decodificada.

Coordinar: Sincronizar todas las actividades dentro de la CPU y entre la CPU y otros componentes del sistema.

# 3- Investigue qué son las arquitecturas RISC y CISC, indique cuáles son las ventajas y desventajas principales de cada una. Dé ejemplos de procesadores (dispositivos) que utilizan estas arquitecturas.

CISC (Complex Instruction Set Computer):
Características: Conjunto amplio y variado de instrucciones, muchas complejas. Formatos de instrucciones variables. Operaciones pueden acceder directamente a memoria.
Ventajas:

Menos instrucciones para realizar tareas complejas.

Código más compacto.

Más sencillo para programar en ensamblador.
Desventajas:

Hardware más complejo.

Tiempos de ejecución variables.

Difícil implementar pipelining.

Alto consumo energético.
Ejemplos: Intel x86/x86-64 (Core i3/i5/i7/i9), AMD Ryzen/EPYC.

RISC (Reduced Instruction Set Computer):
Características: Instrucciones simples, de formato fijo. Basada en registros. Arquitectura Load/Store.
Ventajas:

Hardware más simple y rápido.

Fácil implementar pipelining y ejecución paralela.

Menor consumo energético.

Rendimiento más predecible.
Desventajas:

Se requieren más instrucciones simples.

Dependencia de compiladores eficientes.
Ejemplos: ARM (Snapdragon, Apple M1/M2), RISC-V, MIPS, PowerPC.

Cuestionario Memoria

# 1- ¿Cuáles son los tipos de memoria que existen en informática?

Memoria Principal (Primaria):

RAM: Volátil. DRAM (común), SRAM (más rápida y cara).

ROM: No volátil. PROM, EPROM, EEPROM.

Memoria Flash: EEPROM rápida. Usada en SSDs, USB.

Memoria Caché: SRAM rápida entre CPU y RAM (L1, L2, L3).

Registros: Muy rápidos, dentro de la CPU.

Memoria Secundaria:

HDD, SSD (Flash), ópticos (CD/DVD), cintas.

Memoria Virtual: Parte del disco usada como RAM por el sistema operativo.

# 2- Organice las memorias encontradas en el punto anterior de manera jerárquica e indique cómo influye la misma en el costo de los diferentes dispositivos.

Jerarquía de Memoria (de mayor a menor velocidad):

Nivel 0: Registros → Muy rápida, muy costosa, poca capacidad.

Nivel 1: Caché (L1 < L2 < L3) → Muy rápida, cara, pequeña.

Nivel 2: RAM (DRAM) → Rápida, costo medio, capacidad media.

Nivel 3: Almacenamiento (SSD, HDD) → Lento, barato, gran capacidad.

Nivel 4: Almacenamiento terciario (ópticos, cintas) → Muy lento, muy barato, muy grande.

Influencia en el costo: Cuanto más rápida la memoria, más costosa por bit. Los dispositivos caros suelen tener más memoria rápida (más RAM, SSD, caché). Esto afecta directamente el rendimiento.

# 3- ¿Indique todas las unidades (tamaños) que puede tener una memoria, de menor a mayor?

Bit (b)

Byte (B) = 8 bits

Kibibyte (KiB) = 2¹⁰ bytes = 1,024 B

Mebibyte (MiB) = 2²⁰ bytes = 1,024 KiB

Gibibyte (GiB) = 2³⁰ bytes = 1,024 MiB

Tebibyte (TiB) = 2⁴⁰ bytes

Pebibyte (PiB) = 2⁵⁰ bytes

Exbibyte (EiB) = 2⁶⁰ bytes

(Nota: En almacenamiento, también se usan prefijos decimales: 1 KB = 1,000 B, 1 MB = 1,000,000 B, etc.).

# 4- ¿Qué es la volatilidad de la memoria? ¿A qué tipo de dispositivos afecta y a cuáles no?
La volatilidad indica si una memoria pierde su contenido al apagar el dispositivo.

Volátiles:

Registros

Caché

RAM (DRAM/SRAM)

No volátiles:

ROM, EEPROM

Flash (pendrives, SSD)

HDD, discos ópticos, cintas

Cuestionario Periféricos

# 1- ¿Qué es el control de E/S por interrupciones?
Es un método para que los periféricos avisen a la CPU cuando una operación de E/S ha finalizado.
Funcionamiento:

La CPU inicia una operación y sigue trabajando.

El dispositivo envía una interrupción cuando finaliza.

La CPU ejecuta una rutina específica (ISR) para atender el evento.

Luego retoma su tarea anterior.
Ventaja: La CPU no desperdicia tiempo revisando si el periférico terminó, mejora la eficiencia.

# 2- ¿Qué es DMA? ¿Cómo funciona?
DMA (Direct Memory Access) permite que ciertos dispositivos transfieran datos entre la memoria y el periférico sin intervención directa de la CPU.

Pasos:

La CPU configura al controlador DMA.

El DMA toma control del bus para transferir datos.

Al finalizar, envía una interrupción a la CPU.
Resultado: Transferencias más rápidas y la CPU queda libre para otras tareas.

# 3- ¿Cómo beneficia al rendimiento del sistema?

Libera a la CPU de tareas repetitivas de transferencia.

Aumenta la velocidad de transferencia (acceso directo).

Permite paralelismo: CPU trabaja mientras el DMA transfiere.

Mejora la eficiencia y rendimiento general del sistema.
