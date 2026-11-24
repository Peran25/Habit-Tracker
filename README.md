# Mi tracker de hábitos

Aplicación web en un único archivo HTML con estética de libreta mensual cuadriculada para registrar hábitos diarios, escribir una nota por día, visualizar tu progreso y reflexionar al final de cada mes.

## Características

* **Libreta mensual interactiva:** Cambia entre meses con los botones `‹` y `›`, con resalte para fines de semana y para el día actual.
* **Diario diario:** Una línea por cada día del mes para apuntar lo que pasó o lo que te pareció interesante.
* **Seguimiento de hábitos:** Añade, renombra o elimina hábitos (con confirmación en dos pasos `×` → `¿?`), márcalos día a día (`✕`) y consulta el porcentaje de cumplimiento de cada uno (destacando en rojo el de menor porcentaje cuando hay más de un hábito).
* **Gráfica diaria (`¿Cómo ha ido?`):** Gráfica SVG que muestra cuántos hábitos cumpliste cada día y el porcentaje medio del mes.
* **Reflexión mensual:** Tres preguntas al final de cada mes, con una sugerencia automática basada en el hábito con menor porcentaje de cumplimiento.
* **Modo claro y oscuro:** Se adapta automáticamente a la preferencia del sistema (`prefers-color-scheme`) y también admite `data-theme="light"` o `data-theme="dark"` en `:root`.
* **Guardado local y copias de seguridad:**
  * Guarda automáticamente en `localStorage`.
  * En navegadores compatibles con File System Access API (como Chrome o Edge), permite crear o vincular un archivo `.json` en tu ordenador para guardado automático en disco.
  * Incluye **Exportar copia** e **Importar copia** en formato JSON.

## Cómo usarlo

1. Clona el repositorio en tu equipo:
   ```bash
   git clone [https://github.com/Peran25/Habit-Tracker.git](https://github.com/Peran25/Habit-Tracker.git)