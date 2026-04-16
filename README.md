# taller-1-lp
## Descripción

Este programa desarrollado en *Racket* permite al usuario ingresar texto por consola y devuelve un mensaje con la entrada procesada.

El sistema valida que la entrada contenga **solo letras**.  
Si el usuario ingresa números, se lanza una **excepción personalizada** sin detener la ejecución del programa.

El programa se ejecuta en un ciclo continuo hasta que el usuario escribe `"xao"` o se detecta fin de archivo.

---

## Funcionalidades

- Lectura de texto desde consola  
- Validación de entrada (solo letras)  
- Manejo de excepciones personalizadas  
- Manejo de errores generales  
- Ejecución en bucle hasta salida del usuario  

---

## Estructura del Proyecto

- `main.rkt`: Contiene la lógica principal del programa  
- `excepcion.rkt`: Define la validación y la excepción personalizada  

---

## Requisitos

- Tener instalado **Racket**
- Editor recomendado: **DrRacket**

---

## Ejecución

1. Abrir el archivo `main.rkt`
2. Ejecutar el programa
3. Ingresar texto cuando se solicite

---

## Uso del Programa

Al iniciar, se mostrarán instrucciones:
"Holaaa, diremos lo que escribiste pero solo letras
Si escribes numeros el programa tirara una excepcion personalizada
Si quieres terminar el codigo, escribe 'xao'"

Ejemplo de uso:
Ingresa un texto: hola
Resultado: aloo tu escribiste: hola

### Error general
Cualquier otro error es capturado para evitar que el programa se cierre inesperadamente.



---

##  Conceptos Aplicados

- Programación funcional  
- Manejo de excepciones en Racket  
- Recursividad (bucle con `let loop`)  
- Validación de entrada  
- Modularidad del código  

---

## Posibles mejoras

- Permitir más tipos de validación (símbolos, espacios, etc.)  
- Interfaz gráfica  
- Historial de entradas del usuario  
- Tests automatizados  
