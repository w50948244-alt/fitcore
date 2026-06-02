# Ficha de Idea de Producto

## Nombre tentativo de la app
**FitCore** — Tu entrenador personal en el bolsillo

---

## Problema que resuelve
La mayoría de las personas que van al gimnasio no tienen acceso a un entrenador personal, no llevan un registro organizado de su progreso (peso, medidas, cargas) y abandonan la rutina por falta de estructura y seguimiento. Las apps existentes son demasiado genéricas o demasiado complejas para el usuario promedio.

---

## Usuario objetivo (perfil)
- **Nombre:** Carlos, 27 años
- **Contexto:** Trabaja 8 horas al día, va al gym 3–4 veces por semana, lleva 6 meses entrenando de forma irregular
- **Frustraciones:** No sabe si está progresando, olvida los ejercicios de la rutina, pierde tiempo buscando videos en YouTube
- **Motivación:** Quiere ganar músculo y llevar un control de su transformación física

---

## Jobs-to-be-done
1. **Cuando llego al gym**, quiero saber exactamente qué ejercicios hacer y con qué peso, para no perder tiempo ni improvisar.
2. **Cuando termino un entrenamiento**, quiero registrar mi progreso (series, repeticiones, peso levantado), para ver si estoy mejorando semana a semana.
3. **Cuando me pesan en casa**, quiero registrar mi peso y medidas corporales, para visualizar mi evolución física a lo largo del tiempo.

---

## Propuesta de valor en 1 oración
FitCore permite a cualquier persona que va al gym crear, seguir y medir sus rutinas de ejercicio con seguimiento de peso y medidas corporales, sin necesidad de un entrenador personal.

---

## Tipo de app
**Negocio** (modelo freemium: funciones básicas gratis, rutinas premium y análisis avanzado de pago)

---

# Backlog Inicial

> **Prompt utilizado para generar y refinar este backlog:**
> "Actúa como un product manager senior con experiencia en apps de fitness. Tengo una app móvil llamada FitCore para registro de rutinas de gym, peso y medidas corporales. Por favor: (1) genera un backlog inicial de al menos 10 historias de usuario en formato 'Como [usuario], quiero [acción]', (2) clasifícalas por prioridad alta, media y baja, (3) identifica cuáles son esenciales para el MVP v1."

---

## 🔴 Prioridad Alta (MVP v1)

| # | Historia de Usuario | Criterio de aceptación |
|---|---|---|
| 1 | Como usuario, quiero registrarme con email y contraseña para tener una cuenta personal en la app. | El usuario puede crear cuenta, iniciar sesión y cerrar sesión correctamente. |
| 2 | Como usuario, quiero ingresar mis datos físicos (peso, altura, edad, género) para que la app personalice mi experiencia. | Los datos se guardan en el perfil y se pueden editar en cualquier momento. |
| 3 | Como usuario, quiero crear una rutina de ejercicios con nombre, días de la semana y lista de ejercicios, para organizar mi entrenamiento semanal. | Puedo crear, editar y eliminar rutinas. Cada rutina puede tener múltiples ejercicios. |
| 4 | Como usuario, quiero registrar series, repeticiones y peso de cada ejercicio durante el entrenamiento, para tener un historial de mis sesiones. | El log se guarda con fecha y hora; puedo verlo posteriormente. |
| 5 | Como usuario, quiero registrar mi peso corporal diariamente, para hacer seguimiento de mi evolución con el tiempo. | El registro muestra fecha, peso y una gráfica de líneas de los últimos 30 días. |
| 6 | Como usuario, quiero ver un historial de mis entrenamientos anteriores, para comparar mi rendimiento semana a semana. | La pantalla de historial lista sesiones con fecha, rutina usada y volumen total. |

---

## 🟡 Prioridad Media (Post-MVP)

| # | Historia de Usuario | Criterio de aceptación |
|---|---|---|
| 7 | Como usuario, quiero registrar mis medidas corporales (pecho, cintura, cadera, brazos, piernas), para visualizar cambios en mi composición física. | Puedo agregar medidas por fecha y ver gráficas de evolución por zona. |
| 8 | Como usuario, quiero explorar una biblioteca de ejercicios con instrucciones y músculo trabajado, para seleccionarlos fácilmente al armar mis rutinas. | La biblioteca tiene al menos 50 ejercicios con imagen, descripción y músculos principales. |
| 9 | Como usuario, quiero recibir una notificación a la hora que programe mi entrenamiento, para no olvidarme de ir al gym. | El usuario puede configurar días y hora; la notificación aparece aunque la app esté cerrada. |
| 10 | Como usuario, quiero ver estadísticas de mi volumen de entrenamiento semanal (kg levantados, sets totales), para entender mi carga de trabajo. | El dashboard muestra resumen semanal con comparativa respecto a la semana anterior. |

---

## 🟢 Prioridad Baja (Versión futura)

| # | Historia de Usuario | Criterio de aceptación |
|---|---|---|
| 11 | Como usuario, quiero compartir mi progreso (foto + stats) en redes sociales, para mostrar mi transformación. | El usuario puede generar una tarjeta visual exportable desde la app. |
| 12 | Como usuario, quiero recibir sugerencias de rutinas generadas por IA según mi objetivo (fuerza, volumen, pérdida de grasa), para no tener que diseñarlas desde cero. | La IA genera una rutina de 4–6 ejercicios ajustada al objetivo y nivel del usuario. |
| 13 | Como usuario premium, quiero acceder a planes de nutrición básicos vinculados a mi objetivo, para complementar mi entrenamiento. | Los planes incluyen distribución de macronutrientes y ejemplos de comidas por día. |

---

*Documento generado como entregable de Semana 1. Commit inicial sugerido antes del inicio de la Semana 2.*
*Ruta sugerida en repositorio: `docs/product-idea.md`*
