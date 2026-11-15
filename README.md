# IER-GATE — Documentación de diseño

Este repositorio contiene **propuestas de diseño documental** del proyecto IER-GATE (Identity, Evidence, Authorization and Recovery Gate). No contiene implementaciones, binarios ni resultados de ejecución.

> **Estado normativo: ningún documento de este repositorio es una especificación aceptada ni verificada.**
> No presentar ninguno de estos documentos como especificación IER-GATE aceptada, validada, auditada por terceros ni lista para implementación.

## Contenido congelado en estado declarado

| Documento | Estado declarado en el propio documento |
|---|---|
| `IER_GATE_PLAN.md` | **DRAFT / PARTIAL / OPEN / NOT_EXECUTED** — Plan Técnico Canónico de IER-GATE. La §1 (canon) está FROZEN. Ningún estado normativo se eleva por publicarlo. |
| `B07_FORMAL_MODEL.md` | **SPECIFICATION_ONLY / NOT_EXECUTED / DESIGN_UNVERIFIED / OPEN** — Modelo formal B-07 (R1 ACCEPTED estructuralmente; R2 `REPAIR_REQUIRED`). |
| `B07-R2-Repair-Specification.md` | **DRAFT / NOT_ACCEPTED / NOT_EXECUTED / UNVERIFIED** — Especificación de reparación R2 (v2.r2). Ningún hallazgo H-01…H-27 ni R2A-AUD-001…019 está cerrado. |

## Procedencia y hashes (publicación 2026-11-15)

| Documento | SHA-256 |
|---|---|
| `IER_GATE_PLAN.md` | `74a19ba2ab0b6dd6bc43211673a78fa82009b8b7e1f9445148866e2d631f4267` |
| `B07_FORMAL_MODEL.md` | `a7273d5896ac523a5ca725aef2840e83dbf85788721c8412cfac8d58dd6f364b` |
| `B07-R2-Repair-Specification.md` | `9c8a0aba5cf6770b12561b7734e0630c41ae44b268ce5f9ecdcf216f9c57c39e` |

## Reglas de lectura

- Estos documentos **no** son una implementación, **no** declaran `MODEL_VERIFIED`, `INDEPENDENTLY_VERIFIED`, `IMPLEMENTATION_READY` ni promoción.
- No se autoriza ejecución, integración, crash injection ni A/B.
- `MODEL_VERIFIED = NO` · `INDEPENDENCE = NOT_EXECUTED` · `PROMOTION = NOT_READY`.
- Ninguna revisión por terceros se ha ejecutado sobre estos documentos.
- Su distribución no autoriza el uso de su contenido como contrato normativo operativo.

## Directorios

- `IER_GATE_BACKUP/` — archivo documental crudo (inventario interno incluido). Los documentos conservan íntegros sus estados declarados; algunos son borradores internos preservados tal cual. No constituye una versión normativa distribuida ni modifica el estado de ninguno de sus contenidos.
- Archivos del raíz (este nivel): copias exactas de los tres documentos principales, publicadas el 2026-11-15.

## Contacto / preguntas de auditoría

Los documentos describen un proceso de diseño iterativo (auditorías adversariales internas y externas al proyecto). Las discrepancias entre documentos son historia de ese proceso: el árbol y los hashes prevalecen sobre cualquier interpretación.
