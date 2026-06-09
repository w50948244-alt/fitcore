# FitCore 🏋️

App móvil de seguimiento de rutinas de gym, peso y medidas corporales.  
Entregable Semana 2 — MVP inicial con React Native + Expo.

---

## Stack tecnológico

| Capa | Tecnología |
|---|---|
| Framework | React Native + Expo SDK 51 |
| Lenguaje | TypeScript |
| Navegación | React Navigation (Bottom Tabs + Stack) |
| Estado global | Zustand |
| Gráficas | react-native-chart-kit |
| Fechas | date-fns |
| Almacenamiento | AsyncStorage (listo para persistencia) |

---

## Estructura del proyecto

```
fitcore/
├── App.tsx                      # Entry point
├── app.json                     # Configuración Expo
├── package.json
├── tsconfig.json
└── src/
    ├── navigation/
    │   └── MainNavigator.tsx    # Tab navigator principal
    ├── screens/
    │   ├── HomeScreen.tsx       # Dashboard principal
    │   ├── RoutinesScreen.tsx   # CRUD de rutinas
    │   ├── WorkoutScreen.tsx    # Sesión activa con timer
    │   ├── ProgressScreen.tsx   # Gráficas y registro de peso
    │   └── ProfileScreen.tsx   # Perfil del usuario
    ├── store/
    │   └── fitcoreStore.ts      # Estado global (Zustand)
    └── theme/
        └── index.ts             # Colores, tipografía, espaciado
```

---

## Pantallas implementadas (MVP v1)

### ⚡ Home — Dashboard
- Saludo personalizado con fecha
- Banner de rutina del día (detecta el día actual)
- Stats: peso actual, sesiones esta semana, volumen total
- Accesos rápidos

### 📋 Rutinas
- Listado de rutinas con expansión
- Ver ejercicios de cada rutina (series × reps × kg)
- Crear nueva rutina: nombre, días, ejercicios
- Eliminar rutina

### 🏋️ Workout — Sesión activa
- Selección de rutina para comenzar
- Timer en tiempo real
- Edición de series, reps y peso por ejercicio
- Cálculo de volumen por ejercicio
- Finalizar y guardar log automático

### 📈 Progreso
- Gráfica de evolución de peso (LineChart)
- Registro de peso del día
- Registro de medidas corporales (pecho, cintura, cadera, brazos, piernas)
- Historial de registros

### 👤 Perfil
- Vista de estadísticas generales
- Edición: nombre, edad, altura, objetivo, nivel
- Card de transformación (peso inicial vs actual)

---

## Cómo correr el proyecto

### 1. Instalar dependencias
```bash
cd fitcore
npm install
```

### 2. Iniciar el servidor de desarrollo
```bash
npx expo start
```

### 3. Ver en tu teléfono
1. Descarga la app **Expo Go** desde App Store o Google Play
2. Escanea el QR que aparece en la terminal

### 4. Ver en simulador (opcional)
```bash
# iOS (solo Mac con Xcode)
npx expo start --ios

# Android (con Android Studio)
npx expo start --android
```

---

## Historias de usuario cubiertas en esta entrega

| Historia | Estado |
|---|---|
| Registrar datos físicos (peso, altura, edad) | ✅ ProfileScreen |
| Crear rutina con ejercicios y días | ✅ RoutinesScreen |
| Registrar sets/reps/peso durante el workout | ✅ WorkoutScreen |
| Registrar peso corporal diariamente | ✅ ProgressScreen |
| Ver historial de entrenamientos | ✅ HomeScreen |
| Ver evolución del peso con gráfica | ✅ ProgressScreen |
| Registrar medidas corporales | ✅ ProgressScreen |

---

## Próximos pasos (Semana 3)

- [ ] Persistencia real con AsyncStorage
- [ ] Autenticación con email/contraseña (Supabase o Firebase)
- [ ] Biblioteca de ejercicios con imágenes
- [ ] Notificaciones push para recordatorios
- [ ] Estadísticas de volumen semanal avanzadas

---

*Prompt de Discovery utilizado:*  
> "Actúa como un product manager senior. Tengo una app llamada FitCore para gym. Identifica 3 supuestos no validados, sugiere 2 segmentos alternativos, lista los 5 mayores riesgos de ejecución."
