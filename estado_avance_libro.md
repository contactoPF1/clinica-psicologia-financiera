# Estado de avance — Clínica de Psicología Financiera

Este archivo lo usa la rutina automática diaria para saber qué sección redactar y si debe esperar aprobación. No borrar la estructura de campos.

## Estado actual

- **Última actualización:** 2026-08-16
- **Manuscrito de trabajo:** `Manuscrito de trabajo - Clínica de Psicología Financiera.md` (misma carpeta)
- **Sección en curso:** 1.5 Importancia de la psicología financiera en el mundo moderno
- **Estado de la sección en curso:** `pendiente_de_redactar` — es un borrador de dos párrafos, el segundo termina a mitad de palabra ("bienesta..."), hay que completarla.
- **Modo de avance:** espera aprobación explícita del usuario entre secciones. No redactar la siguiente sección hasta que el estado de la actual sea `aprobado`.

## Valores posibles del campo "Estado de la sección en curso"

- `pendiente_de_redactar`: nadie ha escrito el borrador todavía. La rutina debe escribirlo hoy.
- `borrador_listo_para_revision`: la rutina ya escribió el borrador y está esperando que Billy lo lea y responda.
- `aprobado`: Billy confirmó el borrador (o pidió cambios menores ya aplicados). La próxima corrida debe avanzar a la siguiente sección de la hoja de ruta y marcarla `pendiente_de_redactar`.
- `cambios_solicitados`: Billy pidió ajustes puntuales. La rutina debe aplicar los ajustes y volver a `borrador_listo_para_revision`, no avanzar a la siguiente sección.

## Hoja de ruta (orden a seguir, según memoria del proyecto)

1. 1.5 Importancia de la psicología financiera en el mundo moderno — **siguiente**
2. Cierre reflexivo del Capítulo 1
3. Revisión integral del Capítulo 1 completo (progresión, repeticiones, sustento de afirmaciones científicas, presencia de México/Latam, equilibrio psicología/finanzas, momento de aparición de AFC, voz del autor)
4. Bibliografía consolidada y verificada del Capítulo 1
5. Capítulo 2 (Sección 2: Pilares de una vida financiera consciente) — Producción de ingresos
6. Administración del dinero
7. Cómo vives con tus deudas
8. Tu actitud frente al ahorro
9. Inversión y sus frutos
10. Integración de los pilares financieros
11. (continuar según el índice completo en la memoria del proyecto: `project_libro_clinica_estructura.md`)

## Reglas para la rutina diaria (resumen, ver memoria completa)

- Seguir el estilo y las reglas de `feedback_libro_clinica_estilo_y_reglas.md` (memoria del proyecto): académico-divulgativo, sin moralizar, ejemplos de México/Latam, no inventar estadísticas, no presentar AFC como validada científicamente, verificar fuentes citadas.
- Escribir SIEMPRE en `Manuscrito de trabajo - Clínica de Psicología Financiera.md`, nunca sobrescribir directamente `Libro Psicología Financiera.docx` (ese archivo es el respaldo original).
- Al terminar un borrador, actualizar este archivo (`estado_avance_libro.md`) a `borrador_listo_para_revision` y notificar a Billy con un resumen breve de lo escrito.
- Si el estado sigue en `borrador_listo_para_revision` cuando corre la rutina, NO escribir nada nuevo: solo enviar un recordatorio breve de que hay una sección esperando revisión.
