# LUMEN — Examen parcial I (modalidad individual)

Proyecto base: abrir `index.html` en un navegador; no instalar dependencias. Lea el enunciado del examen antes de modificar archivos. Conserve el proyecto inicial en el primer commit.

## Identificación

Estudiante: **\_\_\_\_** | Grupo: **\_\_\_\_** | Repositorio público: **\_\_\_\_**

## Diagnóstico de incidencias

Documente por separado las incidencias A–E. Para cada una: comportamiento anterior, archivo y selector/elemento exacto, causa técnica, corrección, prueba (1280/375 px según aplique), evidencia antes/después cuando sea visual y autor.

### Incidencia A

- Antes:
  ![alt text](image-10.png)
- Ubicación y causa: la causa es flex-direction: column;
  ![alt text](image-3.png)
- Corrección:
  ![alt text](image-4.png)
- Prueba:
- Capturas:
  ![alt text](image-5.png)
  ![alt text](image-6.png)
  ![alt text](image-7.png)

### Incidencia B

- Antes:
  ![alt text](image.png)
  ![alt text](image-1.png)
  ![alt text](image-2.png)
- Ubicación y causa: En galery.html y talleres.html era solo agregar el header, y en index.html era cambiar href="pages/galery.html" por href="pages/talleres.html"
  ![alt text](image.png)
  ![alt text](image-1.png)
  ![alt text](image-2.png)
- Corrección:
  ![alt text](image100.png)
  ![alt text](image-8.png)
  ![alt text](image-9.png)
- Prueba:
  ![alt text](image-11.png)
- Capturas:

### Incidencia C

- Antes:
  ![alt text](image-13.png)
- Ubicación y causa: El boton tenia href # habia que cambiarlo a href pages/talleres.html
  ![alt text](image-14.png)
- Corrección:
  ![alt text](image-12.png)
- Prueba:

### Incidencia D

- Antes:
  ![alt text](image-16.png)
- Ubicación y causa: se ubica en styles.css y la causa es porque el boton tiene un id y una clase pero en styles se usan los dos pero como id tiene mas peso que la clase entonces se aplica primero el #hero-action
  ![alt text](image-15.png)
- Corrección: Eliminar esas lineas de codigo (el #hero-action)
- Prueba:
  ![alt text](image-17.png)
- Capturas:

### Incidencia E

- Antes:
  ![alt text](image-19.png)
- Ubicación y causa: La causa se debe a que hay otro querry que choca con lo pedido en el incidente E
  ![alt text](image-18.png)
- Corrección: Eliminar la querry extra
- Prueba:
  ![alt text](image-21.png)
- Capturas:
  ![alt text](image-20.png)

## Funcionalidad individual

Describa la página creada, estructura, navegación interna, diseño CSS, controles y pruebas de responsividad.

## Evidencias Git / GitHub

- URL repositorio:
- Commits significativos y ramas:
- PR ramabugs → develop (enlace):
- PR ramaf1 → develop (enlace):
- Auto-revisión de cada PR (comentarios, lista de pruebas y correcciones antes del merge):
- PR develop → main (enlace):
- Resultado de cada merge; conflictos reales y resolución, o indicar integración sin conflictos:

## Pruebas y entrega

Registrar navegación, imágenes, 1280 px, 375 px, procedimiento para abrir, URL de repo y nombre del ZIP.
