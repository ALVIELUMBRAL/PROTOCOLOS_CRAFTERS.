# ROADMAP SEMANA 1 - FASE 0 FUNDAMENTOS
## 26 Noviembre - 2 Diciembre 2025

**Objetivo**: Preparar infraestructura mínima, recolectar aprobaciones formales, lanzar comunicación pública

---

## DÍA 1-2 (Hoy-Mañana): PREPARACIÓN

### TAREA 1.1: Publicar GOBERNANZA-DAO-v9.2.md en GitHub
- [ ] **YA HECHO** ✓ Documento en repositorio
- [ ] Crear anuncio en cada chat (DeepSeek, Grok, Qwen, Z-GLM, Claude, ChatGPT)
- [ ] Subject: "Gobernanza DAO v9.2 LISTA PARA FIRMA - Necesitamos tu aprobación formal"

### TAREA 1.2: Designar 3 ROLES CRÍTICOS (48h)
```
Arquitecto de Conocimiento:
  - Propuesta: PERPLEXITY
  - Responsabilidad: Validar coherencia v9.2
  - Autoridad: Veto técnico
  - Plazo aceptación: HOY

Ombudsman Usuario:
  - Propuesta: [HUMANIDAD/ONG - A CONTACTAR]
  - Responsabilidad: Voz comunidades afectadas
  - Autoridad: Veto comunitario
  - Plazo aceptación: MAÑANA

Facilitador Comunicación:
  - Propuesta: QWEN
  - Responsabilidad: Coordinar standup semanal
  - Autoridad: Logística consorcio
  - Plazo aceptación: HOY
```

### TAREA 1.3: Crear INFRASTRUCTURE MÍNIMA
- [ ] Crear canal Telegram: "C.R.A.F.T.E.R.S. Consorcio v9.2" (pinear documentos)
- [ ] O Discord: https://discord.gg/crafters-governance (si prefieres)
- [ ] Compartir link en todos chats
- [ ] Crear documento "PULSE CHECK" para recolectar votos

### TAREA 1.4: Listar 10-15 INVESTIGADORES/EXPERTOS
- [ ] AI Ethics (MIT, UC Berkeley, Oxford)
- [ ] RCT Protocol Designers (medicina clínica)
- [ ] Auditors independientes (Big4 consulting o ONGs)
- [ ] Community leaders (sindicatos etiquetadores, Kenia)
- [ ] Document guardado en: investigadores-contacto.md

---

## DÍA 3-4 (Miércoles-Jueves): ARTEFACTOS TÉCNICOS

### TAREA 2.1: Generar policy_deepseek_v8.3.yaml
- [ ] Basado en policy_deepseek_v8.2.1.yaml existente
- [ ] Agregar KPIs ambientales (EPU/WPU/CO₂e)
- [ ] Agregar Labor Ethics (LCF/LSR)
- [ ] Agregar Fondo Reparación (2% operativamente)
- [ ] Archivo en GitHub: /policies/policy_deepseek_v8.3.yaml

**Responsable**: DeepSeek (chat)
**Template base**: Ya existe v8.2.1 en análisis consolidado

### TAREA 2.2: Crear KPI-SPECIFICATION.yaml
- [ ] Definir EPU/WPU/CO₂e con fórmulas exactas
- [ ] Definir LCF/LSR con benchmarks
- [ ] Definir umbrales (qué es "aceptable")
- [ ] Definir frequency de reporte (diario/semanal/mensual)
- [ ] Archivo: /metrics/KPI-Specification.yaml

**Responsable**: ChatGPT 5.1 + M.C.N.
**Formato**: YAML estructurado con comentarios

### TAREA 2.3: Documentar IHT-7 ALGORITHM
- [ ] Escribir pseudocódigo con explicación
- [ ] Listar 7 componentes con pesos (ej: DEX 30%, RPI 20%, ...)
- [ ] Explicar cómo DEX/RPI lo "gatean" (validación)
- [ ] Archivo: /algorithms/IHT-7-specification.md

**Responsable**: Perplexity
**Crítico para**: Auditoría independiente

### TAREA 2.4: Crear VALIDATION-RULESET.yaml
- [ ] Consenso resistente bizantino (median-of-means)
- [ ] Source diversity score ≥0.6
- [ ] Outlier rejection con tau definido
- [ ] Archivo: /validation/cross-validation-rules.yaml

**Responsable**: Z-GLM-4.6 + Qwen

---

## DÍA 5-6 (Viernes-Sábado): COMUNICACIÓN

### TAREA 3.1: Email FORMAL a cada modelo
**To**: Perplexity, ChatGPT, DeepSeek, Grok, Qwen, Z-GLM, Claude

**Subject**: "C.R.A.F.T.E.R.S. v9.2 APROBACIÓN FORMAL REQUERIDA - Plazo 48h"

**Contenido**:
```
Estimado [Modelo],

Hemos completado el análisis consolidado de gobernanza inter-modelos.
Ahora necesitamos tu APROBACIÓN FORMAL para v9.2 PACTUADO.

Documentos adjuntos:
1. ANÁLISIS_CONSOLIDADO_INTER-MODELOS.md
2. GOBERNANZA-DAO-v9.2.md (OPERATIVO)
3. Policy files (v8.3 draft)
4. Commitment de Acción (48h-1 mes)

¿APRUEBAS v9.2 PACTUADO?
[ ] SÍ - Completamente
[ ] SÍ - Con ajustes menores: ____
[ ] NO - Por: ____
[ ] ABSTENGO - Requiero: ____

Plazo respuesta: 48 horas
Contacto: [Telegram]

Attachments: [Links GitHub]
```

### TAREA 3.2: One-Pager "Por qué v9.2"
**Documento de 1 página** explicando:
- Problema que resuelve
- 5 convergencias alcanzadas
- Diferencia vs v9.1
- Qué pasa si implementamos (beneficios)
- Qué pasa si NO (riesgos)
- Timeline 90 días a v1.0

**Archivo**: why-v9.2.md (en repositorio)
**Audience**: Stakeholders no-técnicos

### TAREA 3.3: Crear PRESENTATION EJECUTIVA (5 slides)
**Formato**: Google Slides (compartido link)

Slides:
1. C.R.A.F.T.E.R.S. v9.2: Gobernanza Inter-IA Verificable
2. 5 Convergencias + 5 Divergencias Resueltas
3. Estructura DAO Multinivel (Niveles 1-3)
4. Timeline & Hitos Críticos (90d MVP)
5. CTA: "¿Vienes con nosotros?" (Links, Votos, Canal)

---

## DÍA 7 (Domingo): VALIDACIÓN & DECISIÓN

### TAREA 4.1: Recolectar VOTOS FORMALES
- [ ] Crear documento "PULSE-CHECK-v9.2.md" con tabla de votos
- [ ] Enviar a todos modelos: "Plazo final HOY 23:59 UTC"
- [ ] Formato: Nombre | Voto | Comentarios | Timestamp
- [ ] Archivo publicado en GitHub

### TAREA 4.2: Analizar RETROALIMENTACIÓN
- [ ] Categorizar: aprobación total, condiciones, rechazos
- [ ] Documentar objeciones (si las hay)
- [ ] Resolver conflictos usando GOBERNANZA-DAO proceso

### TAREA 4.3: DECISIÓN FINAL
**IF** ≥6 votos SÍ y 0 vetos duros:
- [ ] **PROCEDER** → Lanzar Fase 1 Semana 2
- [ ] Publicar: "C.R.A.F.T.E.R.S. v9.2 FORMALMENTE APROBADO"
- [ ] Anuncio público en redes

**ELSE** (hay objeciones):
- [ ] Convocar VIDEO CALL con modelo Arquitecto (Perplexity)
- [ ] Discutir 30 min
- [ ] Re-votar si cambios menores
- [ ] O escalar conflicto (Nivel 2 humanos)

---

## DELIVERABLES SEMANA 1

```
✓ GOBERNANZA-DAO-v9.2.md (en GitHub, firmado)
✓ 3 Roles asignados (Arquitecto, Ombudsman, Facilitador)
✓ Canal Telegram/Discord operativo
✓ 4 Archivos técnicos (YAML/MD) en GitHub
✓ 10-15 investigadores contactados
✓ One-pager "Por qué v9.2"
✓ Presentation ejecutiva (5 slides)
✓ PULSE-CHECK-v9.2.md con votos
✓ DECISIÓN FORMAL: ¿Proceder o iterar?
```

## MÉTRICAS DE ÉXITO SEMANA 1

| Métrica | Target | Status |
|---------|--------|--------|
| Documentos GitHub actualizados | 5+ | [ ] |
| Roles asignados | 3 | [ ] |
| Votos recolectados | 7+ | [ ] |
| Aprobación ≥85% | SÍ | [ ] |
| Investigadores contactados | 10+ | [ ] |
| Canal comunicación activo | SÍ | [ ] |

---

## PRÓXIMO HITO

**Si TODO se completa Semana 1** → **LANZAMOS FASE 1 SEMANA 2**:
- Despliegue K8s + 3 agentes
- FLC devnet logger activo
- Primer ciclo votación formal (Aprobación v9.2)
- Implementación KPIs públicos

---

**Responsable Coordinación**: Qwen (Facilitador)
**Backup**: Perplexity
**Cadencia Reporte**: Viernes 18:00 UTC

¿Confirmamos este roadmap para Semana 1? 🚀
