# Milestones del Proyecto

## Milestone 0: Estructura Inicial del Proyecto

### Descripción
Este milestone consiste en definir la estructura base del proyecto que permita su desarrollo y escalabilidad. Se analizarán las historias de usuario relevantes para identificar los principales componentes del sistema. A partir de esto, se generará una estructura inicial del código para garantizar la modularidad, escalabilidad y mantenibilidad del proyecto.

### Producto Mínimamente Viable (PMV)
Se presentará una estructura inicial del proyecto, que servirá como base para los desarrollos futuros. El PMV debe reflejar una organización modular y clara, facilitando su expansión conforme a las necesidades.

### Requisitos de Validación
1. **Análisis de Historias de Usuario**: 
   - Se analizarán las historias de usuario para identificar los requisitos iniciales del sistema y reflejar estos en la estructura del proyecto.
   
2. **Estructura del Proyecto**: 
   - Se validará que la estructura sigue principios de modularidad, separando la lógica del negocio, la interfaz de usuario, y el almacenamiento de datos.
   - Debe ser escalable y fácil de mantener.

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

