# FIR Panamá 3D

Visor web en 3D del espacio aéreo de Panamá (FIR MPZL) para estudiar las rutas ATS de forma visual: rutas, puntos significativos, radioayudas y límites del FIR sobre el relieve real del país.

**Autor:** Delta Charlie · [github.com/Bugaryy](https://github.com/Bugaryy)
© 2026 · Todos los derechos reservados · ver [LICENSE](LICENSE)

> Material didáctico para el aprendizaje. No es una publicación oficial y no es apto para la navegación ni para la planificación operacional. Consulte siempre el AIP, los AIP SUP y los NOTAM vigentes.

---

## Cómo usarlo

Es un solo archivo, `index.html`. Se puede abrir desde la página de GitHub Pages del repositorio, o descargándolo y abriéndolo en el navegador de la computadora, el celular o la tableta. No hay que instalar nada.

La primera vez aparece un aviso para ver el **tutorial guiado**. También se abre en cualquier momento con el botón **?**.

## Funciones

### Espacio aéreo
- **Cuatro vistas:** Superiores, Inferiores, Nacionales y Todas. Cada una muestra solo sus rutas; "Todas" las reúne.
- **Rutas ATS** en sus colores por familia (Alpha, Golf, Lima, Mike, November, Papa…).
- **Elementos del mapa:**
  - Puntos significativos con simbología OACI: notificación obligatoria, a petición, ATS/MET y RNAV.
  - Radioayudas VOR, DME y VOR/DME.
  - Límite del FIR Panamá y FIR adyacentes: Centroamericana, Kingston, Barranquilla y Bogotá.
  - Relieve 3D del terreno y del fondo marino.

### Modos de vista
- **Plano único:** todas las rutas en un mismo nivel, como en la carta.
- **Capas:** cada familia de rutas en su propia capa.
- **Altitud FL:** cada ruta a la altura de su nivel de vuelo.
- La cámara se puede girar, acercar y desplazar, y tiene botones de vista desde arriba, vista lateral y reinicio.

### Rutas y puntos
- **Lista de rutas** con buscador, filtros por familia y casillas para mostrar u ocultar cada ruta.
- **Al seleccionar una ruta:** la cámara se acerca y aparece su ficha.
  - **Resumen:** niveles, MEA, distancia total, número de tramos, clase, navegación, dependencia ATS y frecuencias.
  - **Tabla de tramos:** rumbo magnético de ida y vuelta y distancia de cada tramo, con el total.
  - **Pestañas** de puntos y tramos, información y avisos.
- **Ficha de cada punto o radioayuda:** coordenadas, tipo, frecuencia y canal.
- **Nombres de los puntos movibles:** con una ruta seleccionada se pueden arrastrar para que no se tapen. Las posiciones se mantienen solo mientras la pestaña esté abierta.

### Ejercicios
- **Nombrar los puntos:** escribir el nombre de cada punto numerado de una ruta.
- **Construir la ruta:** tocar los puntos en orden, incluidos los FIR BDRY.
- Botón **Practicar esta ruta** directamente desde la ficha.

### Radar
- Tráfico **simulado** sobre las rutas, con bloque de datos: distintivo de llamada, modelo, nivel y velocidad.
- Número de aviones y velocidad ajustables. Los bloques se acomodan solos para no taparse, y se pueden arrastrar después de tocar el avión.

### Interfaz
- **Dos interfaces:** **Grafito** (por defecto) y **Clásica**, a elegir en Ajustes.
- **Tema oscuro y tema claro.**
- **Calidad gráfica** Baja, Media o Alta, para equipos más o menos potentes.
- **En computadora:** barra lateral, lista de rutas fija y ficha de la ruta abajo.
- **En celular y tableta:** barra de pestañas inferior (Mapa, Rutas, Ejercicios, Radar, Más) y menú para cambiar de espacio aéreo.
- **Archivo descargado en el celular:** el cambio de vista funciona sin recargar la página, incluso abierto desde WhatsApp o desde el gestor de archivos.
- **Tutorial paso a paso:** recorre cada sección y deja la pantalla preparada en cada paso, con botones para avanzar y retroceder.

## Fuentes de los datos

- **AIP Panamá:** ENR 3.1, 3.2, 3.3, 3.5, 4.1, 4.4, 6.1A y 6.1B.
- **AIP Colombia:** ENR 2.1, para los límites con los FIR Barranquilla y Bogotá.
- Los datos que no se pudieron verificar se marcan dentro del visor como **"pendiente de verificar"**, en el menú **Fuentes / Acerca de**, donde también están las páginas usadas y la fecha AIRAC de referencia.
- Costas y fronteras: Natural Earth, solo como referencia visual.
- Relieve: Terrain Tiles (formato Terrarium) de AWS Open Data / Tilezen.

## Licencia

Todos los derechos reservados. No se permite copiar, modificar, redistribuir ni usar comercialmente este proyecto sin autorización escrita del autor. Ver [LICENSE](LICENSE).
