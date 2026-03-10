---

# Proyecto 1: SPA Simple (React desde 0)

Este repositorio contiene una **Single Page Application (SPA)** muy sencilla, creada como práctica inicial siguiendo el primer video del curso *"React JS desde 0"* de **midudev** en YouTube.

El objetivo principal es afianzar los conceptos fundamentales de React mediante una aplicación pequeña que implementa estado, eventos y renderizado condicional.

---

## 🚀 Funcionalidades

### 1. Avatar: Conectar / Desconectar

Se muestra un avatar que simula un estado de conexión del usuario.

* **Interacción:** Al hacer clic sobre el avatar, el estado conmuta.
* **Lógica:** * `Conectado` $\rightarrow$ se desconecta.
* `Desconectado` $\rightarrow$ se conecta.


* **Propósito:** Practicar el manejo de eventos y el renderizado condicional.

### 2. Contador (`useState`)

Un contador clásico para entender la reactividad en React.

* **Controles:** Incluye dos botones para **Incrementar** y **Decrementar**.
* **Implementación:** El estado se gestiona usando el hook básico:
> `const [state, setState] = useState(...)`



---

## 📝 Notas sobre el código

En el archivo principal encontrarás comentarios detallados que explican:

* **El proceso evolutivo:** Los pasos seguidos para llegar a la solución final.
* **React "Puro":** Una aproximación de cómo se escribiría el código sin usar JSX (utilizando `React.createElement`).
* **Versión Final:** La implementación moderna utilizando **React + JSX**.

---

## 🎓 Objetivos de Aprendizaje

* [x] Creación de **Componentes**.
* [x] Uso de **JSX** para definir la interfaz.
* [x] Gestión de estado con **`useState`**.
* [x] Manejo de **Eventos** (`onClick`).
* [x] Aplicación de **Renderizado condicional**.

---
