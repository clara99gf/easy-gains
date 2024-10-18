# Milestones del Proyecto

## Milestone 0: Implementación Inicial del Sistema

### Descripción
Este milestone entrega la estructura básica del sistema, con la implementación de las clases principales que serán la base para el desarrollo futuro del proyecto.

### Producto Mínimamente Viable (PMV)
El producto será un **esqueleto inicial del sistema**, que incluya:
- Clases principales del sistema con sus relaciones básicas.

### Requisitos de Validación

1. **Clases y Relaciones:**
   - Se validará si el código contiene las clases principales y sus relaciones correctamente definidas.

---

## Milestone 1: Recolección de Datos para Personalización de Rutinas

### Descripción
Este milestone implementará la funcionalidad necesaria para que los usuarios puedan proporcionar datos que faciliten la personalización de sus rutinas de entrenamiento en **easyGains**. Esto incluye la selección de su nivel de experiencia y la disponibilidad de días para entrenar, aspectos clave que influyen en la generación de un plan de entrenamiento ajustado a sus necesidades.

### Producto Mínimamente Viable (PMV)
Los usuarios podrán indicar su nivel de experiencia y la cantidad de días que tienen disponibles para entrenar semanalmente, proporcionando así la información necesaria para crear rutinas personalizadas.

### Requisitos de Validación
1. **Recolección de Datos**:
   - Verificar que los usuarios pueden seleccionar su nivel de experiencia (principiante, intermedio o avanzado) y la cantidad de días disponibles para entrenar.
   
2. **Persistencia de Información**:
   - Asegurar que los datos proporcionados se almacenan correctamente para su uso posterior en la generación de las rutinas de entrenamiento.

---

## Milestone 2: Generación de Rutinas de Entrenamiento Personalizadas

### Descripción
Este milestone se enfocará en la implementación de la lógica de negocio que genera rutinas de entrenamiento personalizadas basadas en los datos ingresados por los usuarios (nivel de experiencia y días disponibles). Se crearán planes de entrenamiento adaptados a las necesidades individuales de cada usuario, ajustándose si el usuario modifica estos datos en el futuro.

### Producto Mínimamente Viable (PMV)
El sistema debe ser capaz de generar rutinas de entrenamiento que se ajusten a los niveles de experiencia del usuario (principiante, intermedio o avanzado) y al número de días que tienen disponibles para entrenar.

### Requisitos de Validación
1. **Generación de Rutinas**:
   - Verificar que las rutinas generadas se adaptan al nivel de experiencia del usuario y a la cantidad de días disponibles para entrenar.
   
2. **Actualización Dinámica**:
   - Comprobar que al modificar el nivel de experiencia o la cantidad de días disponibles, el sistema ajusta automáticamente la rutina generada.

