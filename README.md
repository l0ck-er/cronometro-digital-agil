# ⏱️ Cronómetro Digital Web — Proyecto Ágil

Aplicación web de cronómetro digital con precisión al milisegundo (`Date.now()`), registro de vueltas parciales (*laps*), validación de estados y modo oscuro. Desarrollado bajo metodología ágil híbrida (**Scrum + Kanban**) en modalidad individual.

## 🎯 Alcance y Funcionalidades
* **Conteo exacto (`Date.now()`):** Evita desfases de tiempo incluso si se cambia de pestaña en el navegador.
* **Control de flujo:** Iniciar, pausar, reanudar y reiniciar a `00:00:00.00`.
* **Historial de Vueltas (*Laps*):** Cálculo dinámico del tiempo parcial de cada vuelta y tiempo total acumulado.
* **Prevención de errores:** Bloqueo automático de botones según el estado activo para evitar acciones inválidas o doble clic.
* **Interfaz adaptable:** Diseño responsivo con alternancia entre modo oscuro y modo claro.

## 📋 Product Backlog (36 pts | 24 hrs)

| ID | Historia de Usuario | Prioridad | Puntos | Horas |
| :--- | :--- | :---: | :---: | :---: |
| **HU01** | Estructura base e interfaz responsiva `00:00:00.00` | Muy Alta | 3 | 3 hrs |
| **HU02** | Iniciar conteo continuo con precisión (`Date.now()`) | Muy Alta | 5 | 4 hrs |
| **HU03** | Pausar y reanudar conservando tiempo acumulado | Muy Alta | 5 | 3 hrs |
| **HU04** | Reiniciar marcador a cero y limpiar historial | Alta | 3 | 2 hrs |
| **HU05** | Registro de vueltas (*laps*) con diferencia parcial | Alta | 8 | 4 hrs |
| **HU06** | Bloqueo de estados inválidos y prevención doble clic | Alta | 5 | 3 hrs |
| **HU07** | Modo oscuro de alto contraste | Media | 4 | 3 hrs |
| **HU08** | Pruebas de estrés de 60 minutos y documentación | Media | 3 | 2 hrs |

## 🚀 Cómo ejecutarlo
No requiere instalación ni dependencias externas. Solo descarga o clona el repositorio y abre `index.html` en cualquier navegador web moderno.
