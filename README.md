# FUCKORGANIZACIONDECOMPUTADORES

🚨 GUÍA DEFINITIVA (PARA CUALQUIER EXAMEN)
🧠 1. CÓMO PENSAR (ESTO ES TODO)

TODO en este curso se resume en esto:

ENTRADA → PROCESO → SALIDA

👉 Ejemplo:

entrada: datos en RAM
proceso: CPU + ALU
salida: resultado en RAM

💥 Si no sabes → usa esto → SIEMPRE suma puntos

🧠 2. ALU (CUALQUIER EJERCICIO)
🔥 MÉTODO UNIVERSAL
1. escribe X y Y
2. aplica:
   zx → nx → zy → ny
3. aplica operación (f)
4. aplica negación (no)
5. revisa resultado

👉 Esto funciona SIEMPRE

🧠 SI TE PIDEN EXPLICAR

“Las señales de control modifican las entradas antes de la operación, permitiendo a la ALU realizar diferentes funciones.”

🖥️ 3. CPU (CUALQUIER PREGUNTA TEÓRICA)
🔥 RESPUESTA UNIVERSAL

“La CPU obtiene instrucciones desde memoria (fetch), las decodifica (decode) y las ejecuta (execute), utilizando la ALU y controlando el flujo mediante el Program Counter.”

💥 esto responde casi TODO

🔁 SI TE PIDEN EXPLICAR SUMA

Usa esto (Actividad 1 del examen):

PC manda dirección
memoria devuelve instrucción
CPU la interpreta
ALU suma
resultado se guarda

👉 EXACTO lo que pide el parcial

⚙️ 4. MEMORIA Y DFF (SIEMPRE CAE)
🔥 RESPUESTA UNIVERSAL

“El DFF permite almacenar un bit sincronizado con el reloj. Sin elementos secuenciales no es posible mantener el estado, por lo que no se puede construir memoria confiable solo con lógica combinacional.”

👉 esto responde TODA la actividad 2

⏱️ CLOCK (Actividad 3)

👉 RESPUESTA:

datos incorrectos
pérdida de información
errores

👉 SOLUCIÓN:

aumentar ciclo de reloj
optimizar circuito
🧱 5. REGISTROS (Actividad 4)

👉 RESPUESTA UNIVERSAL:

“El registro almacena el valor solo cuando load está activo y ocurre un flanco de reloj, manteniendo el valor en los DFF.”

💻 6. ENSAMBLADOR (CUALQUIER EJERCICIO)
🔥 MÉTODO UNIVERSAL

SIEMPRE haces esto:

1. cargar (@)
2. operar (D=…)
3. guardar (M=…)
📌 PATRONES QUE FUNCIONAN SIEMPRE
👉 GUARDAR
@100
M=0
👉 COPIAR
@200
D=M
@100
M=D
👉 SUMA
@0
D=M
@1
D=D+M
@2
M=D
👉 RESTA
@17
D=A
@200
D=M-D
@100
M=D

👉 esto responde actividad 5

🔥 CONDICIONALES
@100
D;JEQ

👉 if D == 0

🔥 CICLOS
(LOOP)
...
@LOOP
0;JMP
🧠 7. PROBLEMAS DIFÍCILES (CÓMO RESOLVERLOS)
🔥 VALOR ABSOLUTO
si x >= 0 → guardar
si x < 0 → cambiar signo
🔥 RAÍZ CUADRADA
probar i = 1,2,3...
hasta i*i > número

👉 esto es EXACTO lo que esperan

🔥 PANTALLA / TECLADO
leer KBD
if → dibujar
else → limpiar

👉 suficiente para ganar puntos

🚨 8. NAND2TETRIS (MUY IMPORTANTE)

👉 SIEMPRE:

cargas programa
ejecutas
revisas RAM

👉 el profe espera que sepas usarlo

💣 9. CÓMO RESPONDER (ESTO TE SUBE LA NOTA)
SI NO SABES:

👉 escribe:

qué entra
qué hace
qué sale
SI ES TEÓRICO:

👉 usa palabras:

CPU
ALU
memoria
buses
PC
SI ES CÓDIGO:

👉 sigue patrón:

cargar → operar → guardar
🔥 10. LO QUE MÁS VALE EN EL EXAMEN

Según el documento:

👉 se evalúa:

entender
explicar
aplicar

💥 NO solo memorizar

🚨 RESUMEN FINAL (LO QUE MEMORIZAS YA)
ALU = calcula
CPU = ejecuta
memoria = guarda
PC = controla
ensamblador = pasos simples
💪 ÚLTIMO MENSAJE (IMPORTANTE)

Tú no necesitas saber todo.
👉 necesitas resolver con método

Y ahora ya lo tienes.

Si quieres dejar esto en nivel “no fallo mañana”:

👉 dime: “simulacro final extremo”
y te hago:

examen completo igual al tuyo
con trampas reales
y te enseño a no caer

💥 estás listo mucho más de lo que crees
