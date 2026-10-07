# Calidad de software

Repositorio de la materia **Calidad de software**. Aquí se pueden reunir apuntes, ejercicios y ejemplos relacionados con la evaluación y mejora de la calidad de los productos de software.

## Conceptos básicos

- **Calidad de software:** grado en que un sistema satisface los requisitos y expectativas de sus usuarios, y mantiene características como confiabilidad, seguridad, facilidad de uso y mantenibilidad.
- **Requisito:** condición o capacidad que el sistema debe cumplir. Puede describir una función (requisito funcional) o una característica de calidad (requisito no funcional).
- **Verificación:** comprobación de que el producto se construyó correctamente y cumple las especificaciones.
- **Validación:** comprobación de que el producto resuelve las necesidades reales de sus usuarios.
- **Prueba de software:** actividad que ejecuta o evalúa el sistema para detectar defectos y aportar información sobre su calidad. Las pruebas reducen riesgos, pero no demuestran que el software esté libre de errores.

## Niveles de prueba

### Pruebas unitarias

Verifican una unidad pequeña y aislada del código, como una función o método. Suelen ser rápidas y ayudan a detectar errores cerca de su origen. Para aislar la unidad de servicios externos, se pueden usar dobles de prueba, como *mocks* o *stubs*.

### Pruebas de integración

Comprueban que dos o más componentes colaboran correctamente, por ejemplo, una aplicación y su base de datos o una API externa.

### Pruebas end-to-end (E2E)

Validan un flujo completo desde la perspectiva del usuario, recorriendo los componentes principales del sistema. Por ejemplo, pueden comprobar que una persona inicia sesión, completa una acción y recibe el resultado esperado. Son valiosas para verificar el comportamiento integrado, aunque suelen ser más lentas y sensibles a cambios que las pruebas unitarias.

## Buenas prácticas

- Escribir pruebas claras, repetibles y enfocadas en un comportamiento concreto.
- Comprobar tanto los resultados esperados como casos límite y entradas inválidas.
- Mantener las pruebas junto al código relacionado y actualizarlas cuando cambien los requisitos.
- Usar pruebas unitarias para lógica aislada, pruebas de integración para colaboraciones y pruebas E2E para los flujos críticos.
- Ejecutar las pruebas antes de integrar cambios y revisar los fallos en lugar de ignorarlos.

## Organización del repositorio

Este repositorio puede crecer con materiales, ejercicios y ejemplos de la materia. Cuando se incorporen proyectos, conviene documentar en cada uno sus requisitos, herramientas, instrucciones de ejecución y comandos para correr sus pruebas.
