# Instrucciones del proyecto (Informe + Exposición)

## Informe del proyecto (entrega en PDF)

- **Formato obligatorio:** PDF generado con **LaTeX**.  
- **Fecha límite:** la del **examen**.

### Contenido mínimo requerido en la memoria

1. **Introducción** (introducción del proyecto, objetivos, alcance, etc.)  
   - **Mínimo: 2 páginas**

2. **Estado del arte de los entrenadores quirúrgicos**  
   - No solo centrado en la técnica de **palpado**, sino también en **otros tipos de intervenciones oftalmológicas**.  
   - Se valorará el **número de citas** y el **formato**.  
   - **Mínimo: 5 páginas**

3. **Metodología**  
   - Incorporar los capítulos necesarios para explicar **todos los desarrollos** realizados.  
   - Especial atención a:
     - **Simulación multifísica** (con todos los detalles necesarios)
     - **Integración de la interfaz háptica**
   - **Mínimo: 5 páginas**

4. **Resultados**  
   - Capítulo con los principales resultados del proyecto, incluyendo:
     - Capturas
     - Mapas de tensiones
     - Mapas de deformaciones
     - Etc.
   - **Mínimo: 3 páginas**

5. **Conclusiones**  
   - Principales hallazgos del proyecto  
   - Líneas de acción futuras

6. **Referencias**  
   - **Mínimo: 20 referencias** de contribuciones científicas  
   - Las referencias de **páginas web** se valorarán como **0.2** del valor de una contribución científica

### Requisitos específicos por área

#### Parte de simulación (Elementos Finitos)
Debéis proporcionar todos los detalles necesarios para comprender la metodología empleada. En concreto:
- Geometría
- Malla
- Tipo de elemento
- Materiales
- Condiciones de contorno

#### Parte de interfaces hápticas
Debéis añadir secciones donde se expongan:
- Necesidades del software de simulación
- Diagramas UML (en caso de uso de clases)
- Diagramas que expliquen los posibles usos del software por parte del usuario

Además, se explicará:
- Cómo se han integrado los distintos software necesarios para la creación del simulador

---

## Exposición del trabajo (PowerPoint)

- **Duración máxima:** **40 minutos**
- Debéis cubrir al menos los siguientes aspectos:

1. **Introducción y contexto del proyecto**
2. **Contexto médico**
   - Estado del arte de los entrenadores quirúrgicos
   - Qué se pretende lograr con el proyecto
   - Información sobre los aspectos médicos y quirúrgicos de lo que se pretende simular
3. **Simulación biomédica: detalles de la simulación**
   1. Geometría de la córnea (parámetros, gráficos, etc.)
   2. Estructura interna de la córnea: materiales, propiedades del material, etc.
   3. Mallado
   4. Fuerzas y condiciones de contorno
   5. Resultados (varias capturas con tensiones, desplazamientos, etc.)
4. **Reducción de modelo**
   1. Estrategia utilizada para reducir el orden del modelo (superficie de respuesta, regresión, ...)
   2. Resultados
5. **Integración en la interfaz**
   - Todo el trabajo realizado para integrar lo anterior en el entorno de simulación e interfaz háptica
6. **Conclusiones**
7. **Demostración**
   - Vídeos explicativos
