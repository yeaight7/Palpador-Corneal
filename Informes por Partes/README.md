# Informes por Partes

Este directorio contiene la documentación técnica detallada de cada componente del proyecto, organizada por secciones.

## Contenido

### Ansys/
Documentación completa de la simulación por elementos finitos (FEM) de la córnea usando ANSYS Workbench/Mechanical.

**Incluye:**
- `InformeANSYS.tex` y `InformeANSYS.pdf`: Memoria técnica con:
  - Geometría del modelo (radios de curvatura, espesores, capas)
  - Definición de materiales (estroma, capa de Bowman)
  - Mallado y tipo de elementos
  - Condiciones de contorno y cargas aplicadas
  - Configuración del solver
  - Resultados: tensiones, deformaciones, relaciones fuerza-desplazamiento
- `figures/`: Capturas y gráficos de los resultados de la simulación

## Otras Secciones (Futuras)

Según la estructura del proyecto, aquí se incorporarán informes de:
- **Unity/SOFA**: Integración del simulador interactivo
- **Interfaces Hápticas**: Configuración y calibración del dispositivo háptico
- **Reducción de Modelo**: Métodos de superficie de respuesta para tiempo real
- **Validación**: Comparación con datos experimentales

## Formato

Todos los informes están en **LaTeX** (.tex) con sus correspondientes PDFs generados. Las figuras y recursos auxiliares se encuentran en subcarpetas específicas de cada sección.
