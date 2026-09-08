# Estado de avance — Clínica de Psicología Financiera

Este archivo lo usa la rutina automática diaria para saber qué sección redactar y si debe esperar aprobación. No borrar la estructura de campos.

## Estado actual

- **Última actualización:** 2026-09-07
- **Manuscrito de trabajo:** `manuscrito.md` (este repositorio)
- **Sección en curso:** Revisión integral del Capítulo 2 completo
- **Estado de la sección en curso:** `pendiente_de_redactar` — **El Capítulo 2 está terminado y aprobado por Billy, en vivo, sección por sección.** Contiene 2.1 La ilusión del autocontrol (de Zwaan et al., 2017), 2.2 Por qué evitamos mirar (efecto avestruz, Karlsson, Loewenstein y Seppi, 2009), 2.3 Cómo se cambian los hábitos financieros sin romperlo todo de golpe (Clear, kaizen, dos minutos, papel-vs-digital, socio corresponsable), 2.4 Cuando la crisis rompe hasta la confianza en tus propios números (indefensión aprendida, Seligman y Maier, 1967), 2.5 El sistema completo: de la observación al hábito (síntesis + Lally et al., 2010, sobre los 66 días para formar un hábito), y el Cierre reflexivo del Capítulo 2 (tres desplazamientos, tres advertencias, observación personal con la frase de Tim Maurer verificada, herramienta de la línea base, reflexión y puente al Capítulo 3). Falta, igual que se hizo con el Capítulo 1, la revisión integral formal (progresión, repeticiones, sustento científico, presencia México/Latam, voz del autor) antes de dar por cerrado el capítulo y pasar al 3. La rutina automática puede retomar su función normal para el Capítulo 3 en adelante; ya no hay riesgo de colisión con esta sesión sobre el Capítulo 2.
- **Modo de avance:** espera aprobación explícita del usuario entre secciones. No redactar la siguiente sección hasta que el estado de la actual sea `aprobado`.

## Valores posibles del campo "Estado de la sección en curso"

- `pendiente_de_redactar`: nadie ha escrito el borrador todavía. La rutina debe escribirlo hoy.
- `borrador_listo_para_revision`: la rutina ya escribió el borrador y está esperando que Billy lo lea y responda.
- `aprobado`: Billy confirmó el borrador (o pidió cambios menores ya aplicados). La próxima corrida debe avanzar a la siguiente sección de la hoja de ruta y marcarla `pendiente_de_redactar`.
- `cambios_solicitados`: Billy pidió ajustes puntuales. La rutina debe aplicar los ajustes y volver a `borrador_listo_para_revision`, no avanzar a la siguiente sección.

## Hoja de ruta (orden a seguir, según memoria del proyecto)

1. 1.5 Importancia de la psicología financiera en el mundo moderno — *aprobada por Billy, punto por punto (1.5.1-1.5.12), el 2026-09-01*
2. Cierre reflexivo del Capítulo 1 — *aprobado por Billy el 2026-09-01*
3. Revisión integral del Capítulo 1 completo — *hecha el 2026-09-01, hallazgos corregidos (ver arriba)*
4. Bibliografía consolidada y verificada del Capítulo 1 — *hecha el 2026-09-05*
5. Capítulo 2 (Sección 1: Fundamentos) — Consciencia y hábitos: confrontando tu realidad financiera — *aprobado por Billy en vivo, sección por sección, el 2026-09-07 (2.1-2.5 y Cierre reflexivo)* *(material flotante del capítulo ya integrado; nota: el índice completo tiene 25 capítulos en 6 secciones; el Capítulo 2 real es este, no "Producción de ingresos" — ver corrección abajo)*
6. Revisión integral del Capítulo 2 completo — **siguiente paso, aún no hecho**
7. Bibliografía consolidada y verificada del Capítulo 2 (ya casi completa; revisar que no falten fichas)
8. Capítulo 3 — Ikigai y vida financiera con propósito
9. Capítulo 4 — Pensamientos, creencias y realidad financiera
10. Capítulo 5 — Emociones y dinero
11. Capítulo 6 — Inteligencia emocional y desempeño financiero
12. Capítulo 7 — Producción de ingresos (inicio de la Sección 2: Pilares de una vida financiera consciente)
13. (continuar según el índice completo de 25 capítulos en la memoria del proyecto: `project_libro_clinica_estructura.md`)

**Corrección importante (2026-09-01):** una versión anterior de este archivo saltaba directo de "Capítulo 1" a "Producción de ingresos" como si fuera el Capítulo 2. Eso era un error: según el índice real de 25 capítulos (Sección 1: Fundamentos = capítulos 1-6), el verdadero Capítulo 2 es "Consciencia y hábitos: confrontando tu realidad financiera", y "Producción de ingresos" es el Capítulo 7, al inicio de la Sección 2. No saltarse los capítulos 2-6 de la Sección 1.

## Material flotante (casos de sesión ya desarrollados, pendientes de integrar)

Existe `material_flotante.md` en este repositorio: contiene pasajes ya redactados (voz del autor) a partir de casos reales de sesión, cada uno etiquetado con el capítulo del índice al que pertenece (2, 8, 9, 10, 15, 16, 19, 21). Ninguno de esos capítulos se ha escrito todavía en `manuscrito.md`. **Antes de redactar cualquiera de esos capítulos, revisar primero `material_flotante.md` e integrar el material correspondiente** (con los ajustes de tono/transición necesarios), en vez de partir de cero. Al integrar un bloque, borrarlo de `material_flotante.md` para no duplicar contenido. Si surge material nuevo de sesiones antes de llegar a su capítulo, agregarlo ahí con el mismo formato.

## Reglas para la rutina diaria (resumen, ver memoria completa)

- Seguir el estilo y las reglas de `feedback_libro_clinica_estilo_y_reglas.md` (memoria del proyecto): académico-divulgativo, sin moralizar, ejemplos de México/Latam, no inventar estadísticas, no presentar AFC como validada científicamente, verificar fuentes citadas.
- Escribir SIEMPRE en `manuscrito.md` de este repositorio, nunca sobrescribir directamente `Libro Psicología Financiera.docx` (ese archivo es el respaldo original y vive fuera del repo).
- Al terminar un borrador, actualizar este archivo (`estado_avance_libro.md`) a `borrador_listo_para_revision` y notificar a Billy con un resumen breve de lo escrito.
- Si el estado sigue en `borrador_listo_para_revision` cuando corre la rutina, NO escribir nada nuevo: solo enviar un recordatorio breve de que hay una sección esperando revisión.
