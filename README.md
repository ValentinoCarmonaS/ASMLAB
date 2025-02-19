# 🃏 Estructuras de Datos y Juego de Cartas en C y ASM  

Este proyecto implementa estructuras de datos avanzadas en **C** y funciones de manipulación en **ensamblador** para la base de un juego tipo solitario. Se desarrollaron listas doblemente enlazadas y arreglos dinámicos, optimizando el uso de memoria y el rendimiento.  

## 🚀 Características  
- **Estructuras Implementadas:**  
  - Listas doblemente enlazadas (`list_t`)  
  - Arreglos dinámicos (`array_t`)  
  - Modelo de cartas (`card_t`)  
- **Funciones clave en C y ASM:**  
  - Operaciones sobre `int`, `string`, `card`, `list` y `array`  
  - Manipulación eficiente de memoria  
  - Implementación de comparación, clonación e impresión de datos  
- **Juego tipo solitario:**  
  - Mecánica de apilamiento de cartas  
  - Uso de listas y arreglos como mazo de juego  
  - Determinación de victoria/derrota  

## 🛠️ Herramientas utilizadas  
- **Lenguajes:** C y Ensamblador (x86 NASM)  
- **Compilación y testing:** `gcc`, `make`, `valgrind`, `nasm`  
- **Validación automática:** Pruebas unitarias e intensivas  

## 📦 Instalación y Ejecución  
1. Instalar dependencias:  
   ```sh  
   sudo apt install build-essential gdb valgrind nasm  
   ```  
2. Compilar el código:  
   ```sh  
   make main  
   ```  
3. Ejecutar pruebas básicas:  
   ```sh  
   ./runMain.sh  
   ```  
4. Ejecutar pruebas unitarias e intensivas:  
   ```sh  
   ./runUnitTests.sh   
   ./runIntensiveTests.sh  
   ```  
5. Ejecutar el juego:  
   ```sh  
   ./runGame.sh  
   ```  

## 📌 Notas  
- Toda la memoria dinámica reservada se libera correctamente con `free`.  
- Se aplican restricciones en el uso de funciones estándar (`strlen`, `strcmp`, etc.) para reforzar el aprendizaje.  
- Se sigue una estructura modular y reutilizable en el código.  

📖 **Trabajo práctico de la materia "Organización del Computador" - Segundo Cuatrimestre 2024**.
