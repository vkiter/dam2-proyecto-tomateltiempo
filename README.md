# 🍅 Tomateltiempo (TMT)

**Aplicación Android de productividad basada en la técnica Pomodoro, con gamificación, descansos activos, música ambiental, estadísticas y retos entre amigos.**

> Proyecto Intermodular · 2º DAM · Curso 2026/2027

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white)


---

## 🎥 Vídeo de presentación

👉 **[Ver vídeo de presentación](https://drive.google.com/file/d/1Iii9gtBN8PdwyBuH-SSVXIB5zT1C_xce/view?usp=sharing)**

---

## 📌 Descripción

Muchas apps de productividad se quedan en un simple temporizador Pomodoro y ofrecen pocos incentivos para mantener la constancia. Además, los descansos suelen acabar siendo una distracción más con el móvil.

**Tomateltiempo** cubre el ciclo completo: **concentración → descanso activo → recompensa → progresión**.

- ⏱️ Sesiones Pomodoro configurables (foco, descanso, ciclos) con modo estándar y modo estricto.
- 🏃 Descansos activos con rutinas guiadas de ejercicio, movilidad y estiramientos.
- 🎮 Gamificación: XP, niveles, rachas y logros.
- 🎵 Música y sonidos ambientales durante las sesiones.
- 📊 Estadísticas personales con gráficas de evolución.
- 👥 Retos y grupos con amigos, con ranking básico.

---

## 👥 Equipo

| Integrante | Rol |
|---|---|
| Francisco Javier Torregrosa López | Product Owner / Desarrollador |
| Nerea Sánchez Tendero | Scrum Master / Desarrolladora |
| Iván Asensi Torrecillas | Desarrollador / QA |
| Valeriy Khokhlov Kudriavykh | Desarrollador / QA |
| Ricardo Andretta Hurtado | Desarrollador / QA |

---

## 🛠️ Stack tecnológico

| Capa | Tecnologías |
|---|---|
| App móvil (PMDM / DI) | Kotlin · Android Studio · Jetpack Compose · Material 3 |
| Arquitectura | MVVM · ViewModel · Navigation Compose |
| Persistencia local (AD) | Room · SQLite |
| Servidor y datos (PSP / AD) | API REST · PostgreSQL |
| Multimedia | Android Media3 / ExoPlayer |
| Gestión | Git · GitHub · GitHub Projects · Figma |

---

## 🌿 Flujo de ramas

- `main` → código estable. Protegida: solo se actualiza mediante Pull Request aprobada.
- `develop` → rama de integración.
- `feature/<nombre-tarea>` → una rama por issue, se fusiona en `develop` mediante Pull Request.

Los commits siguen **Conventional Commits** (`feat:`, `fix:`, `docs:`, `chore:`, `test:`, `refactor:`).

---

## 📋 Gestión del proyecto

- **Tablero Kanban:** [Tablero de Desarrollo - Tomateltiempo](https://github.com/users/vkiter/projects/2)
- **Issues:** redactadas como historias de usuario con criterios de aceptación.
