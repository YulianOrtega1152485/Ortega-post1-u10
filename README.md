# Laboratorio Unidad 10 - Jerarquía de Caché

## Descripción
Implementación de un benchmark en C para medir la latencia de acceso a memoria utilizando arreglos de diferentes tamaños, observando el efecto de la jerarquía de caché (L1, L2, L3 y RAM).

## Estructura del proyecto
- src/ → código fuente en C
- capturas/ → evidencias de ejecución
- README.md → documentación y análisis

## Herramientas
- Ubuntu/Linux
- GCC
- perf
- time

## Archivos
- cache_bench.c → benchmark de caché

## Checkpoint 1: Detección de caché

Se consultó la jerarquía de caché del procesador mediante los archivos del sistema Linux ubicados en:

/sys/devices/system/cpu/cpu0/cache/

### Resultados

- L1 Datos: 48K
- L1 Instrucciones: 32K
- L2: 1280K
- L3: 24576K

![Checkpoint 1](capturas/checkpoint1.png)