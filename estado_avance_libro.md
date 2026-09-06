# Estado de avance — Clínica de Psicología Financiera

Este archivo lo usa la rutina automática diaria para saber qué sección redactar y si debe esperar aprobación. No borrar la estructura de campos.

## Estado actual

- **Última actualización:** 2026-09-01
- **Manuscrito de trabajo:** `manuscrito.md` (este repositorio)
- **Sección en curso:** Revisión integral del Capítulo 1 completo
- **Estado de la sección en curso:** `pendiente_de_redactar` — Billy revisó y aprobó el Capítulo 1 completo punto por punto en sesión directa conmigo (Prólogo, 1.1, 1.2, 1.3, 1.4 con sus 8 subapartados, 1.5 con sus 12 bloques ya numerados 1.5.1-1.5.12, y el Cierre reflexivo del Capítulo 1). En el proceso se resolvieron las tres notas de verificación pendientes con fuentes reales (PwC en 1.4.3, ENIF/OCDE-INFE y CONSAR en 1.5), se agregó material nuevo verificado (Díaz-Guerrero y el dinero, terremotos/Venezuela, Akerlof, Scarcity/tunneling, Hershfield, kakeibo/Pennebaker) y se numeraron los bloques de 1.5 (decisión de mantener o quitar esa numeración sigue pendiente para el cierre del libro). Todavía NO se ha hecho la revisión integral formal (progresión, repeticiones, sustento científico, presencia México/Latam, equilibrio psicología/finanzas, momento de aparición de AFC, voz del autor) ni la bibliografía consolidada final. No avanzar a Capítulo 2 hasta completar esos dos pasos.
- **Modo de avance:** espera aprobación explícita del usuario entre secciones. No redactar la siguiente sección hasta que el estado de la actual sea `aprobado`.

## Valores posibles del campo "Estado de la sección en curso"

- `pendiente_de_redactar`: nadie ha escrito el borrador todavía. La rutina debe escribirlo hoy.
- `borrador_listo_para_revision`: la rutina ya escribió el borrador y está esperando que Billy lo lea y responda.
- `aprobado`: Billy confirmó el borrador (o pidió cambios menores ya aplicados). La próxima corrida debe avanzar a la siguiente sección de la hoja de ruta y marcarla `pendiente_de_redactar`.
- `cambios_solicitados`: Billy pidió ajustes puntuales. La rutina debe aplicar los ajustes y volver a `borrador_listo_para_revision`, no avanzar a la siguiente sección.

## Hoja de ruta (orden a seguir, según memoria del proyecto)

1. 1.5 Importancia de la psicología financiera en el mundo moderno — *aprobada por Billy, punto por punto (1.5.1-1.5.12), el 2026-09-01*
2. Cierre reflexivo del Capítulo 1 — *aprobado por Billy el 2026-09-01*
3. Revisión integral del Capítulo 1 completo — **siguiente paso, aún no hecho** (progresión, repeticiones, sustento de afirmaciones científicas, presencia de México/Latam, equilibrio psicología/finanzas, momento de aparición de AFC, voz del autor)
4. Bibliografía consolidada y verificada del Capítulo 1
5. Capítulo 2 (Sección 1: Fundamentos) — Consciencia y hábitos: confrontando tu realidad financiera *(nota: el índice completo tiene 25 capítulos en 6 secciones; el Capítulo 2 real es este, no "Producción de ingresos" — ver corrección abajo)*
6. Capítulo 3 — Ikigai y vida financiera con propósito
7. Capítulo 4 — Pensamientos, creencias y realidad financiera
8. Capítulo 5 — Emociones y dinero
9. Capítulo 6 — Inteligencia emocional y desempeño financiero
10. Capítulo 7 — Producción de ingresos (inicio de la Sección 2: Pilares de una vida financiera consciente)
11. (continuar según el índice completo de 25 capítulos en la memoria del proyecto: `project_libro_clinica_estructura.md`)

**Corrección importante (2026-09-01):** una versión anterior de este archivo saltaba directo de "Capítulo 1" a "Producción de ingresos" como si fuera el Capítulo 2. Eso era un error: según el índice real de 25 capítulos (Sección 1: Fundamentos = capítulos 1-6), el verdadero Capítulo 2 es "Consciencia y hábitos: confrontando tu realidad financiera", y "Producción de ingresos" es el Capítulo 7, al inicio de la Sección 2. No saltarse los capítulos 2-6 de la Sección 1.

## Material flotante (casos de sesión ya desarrollados, pendientes de integrar)

Existe `material_flotante.md` en este repositorio: contiene pasajes ya redactados (voz del autor) a partir de casos reales de sesión, cada uno etiquetado con el capítulo del índice al que pertenece (2, 8, 9, 10, 15, 16, 19, 21). Ninguno de esos capítulos se ha escrito todavía en `manuscrito.md`. **Antes de redactar cualquiera de esos capítulos, revisar primero `material_flotante.md` e integrar el material correspondiente** (con los ajustes de tono/transición necesarios), en vez de partir de cero. Al integrar un bloque, borrarlo de `material_flotante.md` para no duplicar contenido. Si surge material nuevo de sesiones antes de llegar a su capítulo, agregarlo ahí con el mismo formato.

## Reglas para la rutina diaria (resumen, ver memoria completa)

- Seguir el estilo y las reglas de `feedback_libro_clinica_estilo_y_reglas.md` (memoria del proyecto): académico-divulgativo, sin moralizar, ejemplos de México/Latam, no inventar estadísticas, no presentar AFC como validada científicamente, verificar fuentes citadas.
- Escribir SIEMPRE en `manuscrito.md` de este repositorio, nunca sobrescribir directamente `Libro Psicología Financiera.docx` (ese archivo es el respaldo original y vive fuera del repo).
- Al terminar un borrador, actualizar este archivo (`estado_avance_libro.md`) a `borrador_listo_para_revision` y notificar a Billy con un resumen breve de lo escrito.
- Si el estado sigue en `borrador_listo_para_revision` cuando corre la rutina, NO escribir nada nuevo: solo enviar un recordatorio breve de que hay una sección esperando revisión.
