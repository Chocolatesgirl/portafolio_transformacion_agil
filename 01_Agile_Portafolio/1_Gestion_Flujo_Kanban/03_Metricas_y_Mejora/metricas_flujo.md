# 📊 Métricas de Flujo — Gestión Basada en Datos

## 🎯 Objetivo

Definir y utilizar métricas de flujo para:

* Evaluar el desempeño del sistema Kanban
* Identificar cuellos de botella
* Tomar decisiones basadas en datos
* Mejorar la predictibilidad de entrega

---

## 🧩 Contexto del caso

Equipo desarrollando una:

👉 **Aplicación de aprendizaje de inglés para niños de 3 a 8 años**

### Problema inicial

* Alta variabilidad en tiempos de entrega
* Acumulación de trabajo en Testing
* Baja visibilidad del flujo

👉 Resultado:

* Lead Time elevado
* Cycle Time inestable
* Baja capacidad de planificación

---

## 📏 Métricas clave del sistema

---

### ⏱️ 1. Lead Time

Tiempo total desde que una tarea es solicitada hasta que se entrega en producción.

👉 Mide la experiencia del cliente

---

### 🔄 2. Cycle Time

Tiempo desde que el equipo comienza a trabajar en una tarea hasta que la finaliza.

👉 Mide la eficiencia del equipo

---

### 📦 3. Throughput

Cantidad de tareas completadas por unidad de tiempo.

👉 Mide capacidad de entrega

---

### 📊 4. Work In Progress (WIP)

Cantidad de tareas en curso en un momento dado.

👉 Mide carga del sistema

---

## 📊 Análisis del sistema (estado inicial)

### Observaciones

* Lead Time alto y disperso
* Cycle Time variable
* WIP elevado en Development y Testing
* Throughput bajo

---

### 🔍 Diagnóstico

* Sistema sobrecargado
* Cuello de botella en Testing
* Exceso de multitarea

---

## 🛠️ Decisiones basadas en métricas

### 1. Reducción de WIP

* Implementación de límites por etapa

---

### 2. Priorización de tareas en progreso

* Enfoque en finalización

---

### 3. Redistribución de capacidad

* Apoyo del equipo en Testing

---

### 4. Gestión de bloqueos

* Identificación y resolución temprana

---

## 📈 Resultado después de ajustes

| Métrica    | Antes    | Después      |
| ---------- | -------- | ------------ |
| Lead Time  | Alto     | Reducido     |
| Cycle Time | Variable | Estable      |
| WIP        | Alto     | Controlado   |
| Throughput | Bajo     | Incrementado |

---

## 📉 Análisis de distribución

### Lead Time

<p align="center">
  <img src="03_Metricas_y_Mejora/lead_time_distribution.png" width="600">
</p>

---

### 🔍 Interpretación

* Alta dispersión → sistema inestable
* Valores extremos → bloqueos
* Distribución concentrada → flujo estable

---

## 📊 Cumulative Flow Diagram (CFD)

<p align="center">
  <img src="03_Metricas_y_Mejora/cumulative_flow_diagram.png" width="700">
</p>

---

### 🔍 Qué permite identificar

* Evolución del WIP
* Velocidad del sistema
* Cuellos de botella
* Estabilidad del flujo

---

### 🚨 Hallazgos en el caso

* Acumulación en Testing
* Bandas irregulares → flujo inestable
* Crecimiento inconsistente de “Done”

---

## 📉 Evolución del sistema

<p align="center">
  <img src="03_Metricas_y_Mejora/flujo_before_after.png" width="700">
</p>

---

### 📊 Comparación

| Métrica   | Antes         | Después     |
| --------- | ------------- | ----------- |
| Flujo     | Inestable     | Continuo    |
| Entrega   | Impredecible  | Predecible  |
| Capacidad | Desbalanceada | Equilibrada |

---

## 🔗 Conexión con el sistema Kanban

Las métricas permiten validar:

* 🧱 `diseno_tablero_kanban.md` → estructura del flujo
* 🔄 `simulacion_flujo_trabajo_jira.md` → operación real
* 🛠️ `politicas_wip.md` → control del sistema

👉 Sin métricas, no hay mejora continua.

---

## 💼 Enfoque profesional

Las métricas no son solo indicadores.

Son herramientas para:

* Tomar decisiones
* Ajustar el sistema
* Mejorar resultados

👉 El foco está en el sistema, no en las personas.

---

## 🔥 Insight clave

> No puedes mejorar lo que no puedes medir…
> pero medir sin interpretar tampoco genera valor.

---

## ✅ Conclusión

El uso de métricas permite:

* Entender el comportamiento del sistema
* Detectar problemas reales
* Implementar mejoras efectivas

👉 Kanban se convierte en un sistema de mejora continua basado en datos.
