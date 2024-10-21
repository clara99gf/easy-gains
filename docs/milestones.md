# Milestones del Proyecto

## Milestone 0: Configuración Inicial del Sistema

### Producto Mínimamente Viable (PMV)
El sistema debe estar configurado correctamente, con todas las dependencias operativas (bases de datos, librerías, servicios, etc.) y listo para arrancar sin errores. Esta fase se enfoca en preparar el entorno técnico, sin interacción con usuarios ni generación de rutinas, pero asegurando que todo está listo para los siguientes hitos.

Se seguirán buenas prácticas de desarrollo, como la correcta gestión de dependencias, la organización modular del código y la implementación de mecanismos de control de errores para asegurar una base estable y escalable.

Se debe establecer la base técnica necesaria para abordar la [historia de usuario HU001](https://github.com/clara99gf/easy-gains/issues/2), en la que Carlos, un usuario principiante, podrá recibir una rutina personalizada basada en su nivel de experiencia y días disponibles. Para ello, el sistema debe estar correctamente configurado y listo para recolectar y almacenar los datos requeridos en los próximos hitos.

### Requisitos de Validación

1. **Inicialización del Sistema**:
   - Verificar que el sistema arranca correctamente en el entorno de desarrollo y producción.
   - Confirmar que las dependencias necesarias (bases de datos, librerías) están instaladas y funcionando correctamente, siguiendo las mejores prácticas de instalación y configuración.

2. **Disponibilidad de Módulos**:
   - Validar que los módulos para recolección de datos de usuario estarán listos para activarse en el próximo milestone.
   - Asegurar que la base de datos está preparada para almacenar información, siguiendo buenas prácticas de diseño de bases de datos y asegurando integridad y consistencia, aunque no se recolecte ni persista información en esta fase.
   
---

## Milestone 1: Recolección de Datos para Personalización de Rutinas

### Producto Mínimamente Viable (PMV)
Los usuarios podrán indicar su nivel de experiencia y la cantidad de días que tienen disponibles para entrenar semanalmente, proporcionando así la información necesaria para crear rutinas personalizadas.

### Requisitos de Validación
1. **Recolección de Datos**:
   - Verificar que los usuarios pueden seleccionar su nivel de experiencia (principiante, intermedio o avanzado) y la cantidad de días disponibles para entrenar.
   
2. **Persistencia de Información**:
   - Asegurar que los datos proporcionados se almacenan correctamente para su uso posterior en la generación de las rutinas de entrenamiento.

---

## Milestone 2: Generación de Rutinas de Entrenamiento Personalizadas

### Producto Mínimamente Viable (PMV)
El sistema debe ser capaz de generar rutinas de entrenamiento que se ajusten a los niveles de experiencia del usuario (principiante, intermedio o avanzado) y al número de días que tienen disponibles para entrenar.

### Requisitos de Validación
1. **Generación de Rutinas**:
   - Verificar que las rutinas generadas se adaptan al nivel de experiencia del usuario y a la cantidad de días disponibles para entrenar.
   
2. **Actualización Dinámica**:
   - Comprobar que al modificar el nivel de experiencia o la cantidad de días disponibles, el sistema ajusta automáticamente la rutina generada.

