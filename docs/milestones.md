# Milestones del Proyecto

## Milestone 0: Estructura Inicial del Proyecto

### Descripción
El objetivo de este milestone es definir la estructura conceptual del proyecto, identificando los principales componentes del sistema a partir de las historias de usuario. Se seguirán buenas prácticas de diseño, como la separación de responsabilidades, para asegurar que el proyecto sea escalable y fácil de mantener.

### Producto Mínimamente Viable (PMV)
El PMV consistirá en un esquema organizado que represente los principales componentes del sistema, sirviendo como base para el desarrollo futuro.

### Requisitos de Validación

1. **Identificación de Componentes:**
   - Analizar las historias de usuario para determinar los componentes y áreas funcionales clave del sistema.

2. **Estructura Modular:**
   - Definir una estructura organizada que separe claramente las responsabilidades del sistema y permita su crecimiento sin grandes cambios estructurales.

### Historias de Usuario Relevantes

- **HU001**: Rutina Personalizada
- **HU002**: Rutina Flexible
- **HU003**: Ajustar Nivel de Entrenamiento

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

### Historias de Usuario Relevantes
- **HU001**: Rutina Personalizada
- **HU002**: Rutina Flexible
- **HU003**: Ajustar Nivel Entrenamiento

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

### Historias de Usuario Relevantes
- **HU001**: Rutina Personalizada
- **HU002**: Rutina Flexible
- **HU003**: Ajustar Nivel de Entrenamiento

