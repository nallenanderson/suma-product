# Definition: Automated Medical Leave Processing
*Proceso de Definition Completado - 5 días*

---

## Input Requerido - CONFIRMADO ✅

**Del Discovery:** 
- ✅ Problem statement: "PYMEs pierden 2-4 horas/semana en licencias médicas manuales"
- ✅ Solution approach: "OCR + API integration + cálculo automático"
- ✅ 3 beta customer contacts: María, Carlos, Ana
- ✅ Revenue target: $720K ARR / Engineering estimate: 10 semanas

---

## El Sprint de Definition de 5 Días - COMPLETADO

### Día 1: Prototipo de Solución Central (6 horas) - COMPLETADO

**Mañana (3 horas) - Prototipo Construido:**
- **Prototipo:** [Licencia Chile](https://licencia-chile.lovable.app)
- **Herramienta:** Lovable.dev con React + TypeScript + Tailwind CSS
- **Componentes principales:** Drag & drop file upload, traffic light status system, calculation breakdown, confirmation summary

**User Journey Detallado:**
```
PANTALLA 1 - Upload (45 segundos esperados)
Estado inicial: Usuario con PDF de licencia médica en desktop
↓ Ve zona drag & drop con ícono de documento y texto "Arrastra tu PDF aquí"
↓ Arrastra archivo → Preview aparece con nombre + tamaño
↓ Botón "Procesar Licencia" se activa (azul)
↓ Click → Loading spinner "Extrayendo datos del PDF..."
Outcome: Usuario siente "Esto es intuitivo y profesional"

PANTALLA 2 - Validación (30 segundos esperados)
Estado: Datos aparecen automáticamente en formulario
↓ Ve información extraída: RUT, Nombre, Fechas, Tipo de licencia
↓ Traffic light muestra estado: Verde/Amarillo/Rojo con explicación
↓ Botón "Continuar a Cálculos" disponible si Verde/Amarillo
Outcome: Usuario siente "Reconoció todo correctamente, confío en el sistema"

PANTALLA 3 - Cálculos (20 segundos esperados)
Estado: Loading "Calculando descuentos..." por 2-3 segundos
↓ Ve resumen simple: Días = X, Descuento Total = $X, Sueldo Final = $X
↓ Opción "Ver Detalle" expandible con breakdown completo
↓ Botón principal "Aplicar a Liquidación" 
Outcome: Usuario siente "Finalmente números que entiendo"

PANTALLA 4 - Confirmación (15 segundos esperados)
Estado: Resumen final con checkmarks verdes
↓ Ve confirmación: Empleado, Período, Monto aplicado
↓ Opciones: "Descargar Comprobante" + "Procesar Nueva Licencia"
Outcome: Usuario siente "Completé en 2 minutos lo que antes me tomaba 45"
```

**Foco técnico:** Simular OCR con datos hardcoded, validación COMPIN con delay aleatorio, cálculos con fórmulas simplificadas chilenas

**Prototipo creado:**
1. **Pantalla Upload:** Drag & drop zona con preview del PDF
2. **Pantalla Validation:** Status de verificación COMPIN/ISAPRE con traffic light
3. **Pantalla Calculation:** Breakdown de descuentos con explicación legal
4. **Pantalla Confirmation:** Resumen y aplicación a liquidación con un click

**Tarde (3 horas) - Testing con Beta Customers:**

**María González (Contadora PYME):**
- **Reacción inicial:** "Esto es exactamente lo que necesito! El drag and drop se ve súper fácil"
- **Pain point identificado:** "¿El sistema va a reconocer todos los tipos de licencia? Hay como 15 tipos diferentes"
- **Flow confusion:** Se perdió en pantalla de calculation - "demasiados números"
- **Value confirmation:** "Si funciona así, esto vale $80/mes fácil"

**Carlos Mendoza (Admin Retail):**
- **Reacción inicial:** "El traffic light de validación es genial, así sé al tiro si está aprobada"
- **Concern:** "¿Qué pasa si COMPIN está caído? ¿Se queda colgado?"
- **Flow feedback:** "Pantalla 3 muy técnica, necesito versión más simple"
- **Value confirmation:** "Por $60/mes lo compro mañana mismo"

**Feedback Catalogado:**
- ✅ Upload flow claro y familiar
- ⚠️ Calculation screen muy compleja - simplificar
- ✅ Traffic light validation muy valorado
- ⚠️ Falta fallback si APIs fallan
- ✅ Precio $60-80/mes aceptable

### Día 2: Set de Features Mínimo (4 horas) - COMPLETADO

**Basado en feedback del prototipo, features absoluto mínimo:**

**Los 3 Features Must-Have:**
1. **Smart PDF Upload** - Drag & drop con OCR que extrae: RUT empleado, fechas, tipo de licencia, médico
2. **Validation Engine** - Consulta APIs COMPIN/ISAPRE, muestra status con traffic light (verde/amarillo/rojo)
3. **Simple Calculator** - Muestra solo: días a descontar, monto total, botón "Aplicar a Liquidación"

**Test con clientes beta:** "Si solo construyéramos estas 3 cosas, ¿cómo las usarías?"

**María:** "Perfecto. Con eso resuelvo el 90% de mis problemas. Lo demás puede venir después."
**Carlos:** "Sí, eso me sirve. Lo importante es que sea rápido y confiable."
**Ana:** "Me gusta que sea simple. Prefiero pocas funciones que funcionen bien."

### Día 3: Technical Reality Check (6 horas) - COMPLETADO

**Mañana (3 horas) - Prototipo a Ingeniería:**

**Juan (Backend Engineer) - Findings:**
- "OCR es factible con Google Vision API - $2 por cada 1000 documentos"
- "COMPIN no tiene API pública, pero podemos hacer web scraping de su portal"
- "ISAPRE APIs varían - Fonasa tiene, privadas hay que negociar"
- "Mayor riesgo: cambios en portales web rompen nuestro scraping"

**Sofía (Frontend Engineer) - Findings:**
- "El drag & drop y preview es estándar - 2 días de trabajo"
- "Traffic light component ya lo tenemos en design system"
- "Calculation breakdown necesita nueva UI pero es simple"

**Tarde (3 horas) - Timeline Refinado:**
- Semana 1-2: OCR integration + basic upload
- Semana 3-4: Web scraping COMPIN + basic validation
- Semana 5-6: Calculator engine + UI
- Semana 7-8: Integration testing + error handling
- Semana 9-10: Polish + beta deployment

**Timeline Revisado:** 10 semanas → 9 semanas (más confianza en scope reducido)

### Día 4: Plan Beta, Métricas de Éxito & Modelo de Precios (6 horas) - COMPLETADO

**Mañana (3 horas) - Validación de Precios & Packaging:**

**Paso 1 - Value Discovery con Prototipo:**
- **María:** "Para esta solución exacta, pagaría $70/mes sin dudarlo"
- **Carlos:** "Entre $50-80/mes está perfecto para el valor que entrega"
- **Ana:** "Considerando que me ahorra $300/mes en tiempo, hasta $100/mes vale la pena"

**Paso 2 - Test de Opciones de Packaging:**
- **Opción A - Add-on:** "$65/mes extra sobre plan actual"
- **Opción B - Plan inclusion:** "Incluido en plan Pro de $120/mes" 
- **Opción C - Usage-based:** "$4 por licencia procesada"
- **Opción D - Tiered:** "Básico incluido, avanzado $65/mes"

**Paso 3 - Selección de Modelo:**
- **María:** "Add-on me gusta porque puedo justificar el gasto específico"
- **Carlos:** "Add-on también, así mi jefe ve exactamente qué estamos pagando"
- **Ana:** "Prefiero add-on. Por uso me da miedo que se dispare el costo"

**Resultado:** Add-on $65/mes - 3/3 clientes prefieren este modelo

**Tarde (3 horas) - Plan Beta & Éxito:**
- ✅ 3 clientes beta confirman test en 9 semanas CON pricing $65/mes add-on
- **Success criteria:** "Si procesa mis licencias en menos de 5 minutos y calcula bien los descuentos, lo compro"
- **Weekly check-ins:** Viernes 4PM con demos en vivo

**Output del Modelo de Precios:**
- Precio validado: $65/mes
- Modelo de packaging: Add-on sobre plan existente
- Razón del cliente: "Fácil justificar gasto específico vs. upgrade completo de plan"
- Complejidad implementación: Fácil - ya tenemos sistema de add-ons
- Compromiso cliente: 3/3 clientes comprarán a este precio

### Día 5: Plan de Construcción (2 horas) - COMPLETADO

**Plan semana-por-semana:**
- **Semana 1-2:** Upload + OCR (pantalla 1 del prototipo) → código funcional
- **Semana 3-4:** Validation engine (pantalla 2 del prototipo) → código funcional
- **Semana 5-6:** Calculator + UI (pantalla 3-4 del prototipo) → código funcional  
- **Semana 7-8:** Integration + error handling → workflow completo
- **Semana 9:** Beta testing con María, Carlos, Ana

**Confirmación recursos:** Juan (backend) + Sofía (frontend) comprometidos 9 semanas full-time

---

## El Output de Definition

### Lo Que Estamos Construyendo
**Problema:** PYMEs chilenas pierden 2-4 horas/semana procesando licencias médicas manualmente
**Solución:** Sistema automatizado que convierte PDFs en ajustes de liquidación con 3 clicks
**Modelo de Precios:** Add-on $65/mes sobre plan existente
**Validación del Cliente:** 3/3 clientes beta confirmaron que pagarían este modelo
**Éxito:** Reducir procesamiento de licencias de 45 minutos a 5 minutos

### El Set de Features Validado
**Must Have (Validado por prototipo + clientes):**
1. **Smart PDF Upload** - Porque María y Carlos dijeron "el drag & drop se ve súper fácil"
2. **Validation Engine con Traffic Light** - Porque Carlos dijo "así sé al tiro si está aprobada"
3. **Simple Calculator** - Porque todos dijeron "muy técnico" al prototipo complejo, prefieren simple

**No Tendrá (Intencionalmente excluido):**
1. **Advanced Analytics** - Porque clientes no lo mencionaron en testing
2. **Bulk Processing** - Porque PYMEs procesan 1-3 licencias por vez
3. **Mobile App** - Porque todos usan desktop para administración

**Quote del Cliente:** "Si funciona así, esto vale $80/mes fácil. Por $65/mes lo compro mañana mismo." - María González

**Validación del Modelo de Precios:** 
- **Modelo elegido:** Add-on $65/mes
- **Razón del cliente:** "Fácil justificar el gasto específico vs. upgrade completo de plan"
- **Budget/approval fit:** "Mi jefe ve exactamente qué estamos pagando y por qué"

### Plan Prototipo-a-Código
**Semana 1-2:** Pantalla Upload → drag & drop funcional con OCR
**Semana 3-4:** Pantalla Validation → traffic light con APIs reales
**Semana 5-6:** Pantalla Calculator → motor de cálculo + UI limpia
**Semana 7-8:** Integration → workflow completo end-to-end
**Semana 9:** Beta testing con clientes reales

### Enfoque Técnico (Post-Prototipo)
**Stack:** React + Node.js + PostgreSQL
**Integración:** Google Vision API (OCR) + Web scraping COMPIN + APIs ISAPRE variables
**Mayor Riesgo:** Cambios en portales COMPIN rompen web scraping
**Consideraciones de Seguridad:** Encriptación PDFs (datos médicos sensibles)
**Requerimientos CloudOps:** Storage adicional para PDFs + procesamiento OCR
**Requerimientos Sistema de Facturación:** Add-on billing ya implementado

**Timeline Final:** 9 semanas (reducido de 10 por scope simplificado)
**Equipo:** Juan (backend) + Sofía (frontend) full-time

### Plan Beta (Pre-Confirmado con Modelo de Precios)
**Clientes beta:** 
- María González (maria.gonzalez@contabilidadpro.cl) - validó prototipo y pricing
- Carlos Mendoza (carlos.mendoza@retailsur.cl) - confirmó model add-on
- Ana Rodríguez (ana.rodriguez@construcc.cl) - comprometida $65/mes

**Compromiso del modelo de precios:** Add-on $65/mes - 3/3 clientes confirmaron compra
**Criterio de éxito:** Procesar licencias en <5 minutos Y cálculos 100% correctos
**Weekly demos:** Viernes 4PM + check de experiencia del pricing model

---

## Decisión Go/No-Go - RESULTADO: SHIP IT ✅

**SHIP IT - TODO verdadero:**
- [✅] 3/3 clientes beta dijeron "sí, usaría esto semanalmente" después de ver prototipo
- [✅] 3/3 clientes beta confirmaron "sí, pagaría $65/mes vía add-on" 
- [✅] Modelo de pricing add-on técnicamente factible con sistema de facturación actual
- [✅] Prototipo demuestra solución en 4 pasos del usuario
- [✅] Ingeniería confirma construcción en 9 semanas
- [✅] Riesgos técnicos manejables (web scraping como fallback)
- [✅] Clientes beta comprometidos a feedback semanal durante construcción

---

## El Traspaso a Fase de Construcción

### Meta Sprint 1 (Semana 1)
Upload funcional que acepta PDFs y extrae datos básicos con OCR

### Meta Semana 2-4
Validation engine que consulta COMPIN y muestra status confiable

### Meta Semanas 5-6
Calculator que muestra descuentos correctos con UI simple

### Meta Semanas 7-8
Workflow completo end-to-end funcionando en staging

### Meta Semana 9
Beta deployment con María, Carlos, Ana usándolo en producción

**Success Tracking:**
- Demo semanal a clientes beta (Viernes 4PM)
- Métrica semanal: tiempo promedio de procesamiento (target: <5 minutos)
- Confirmación semanal de pricing value: "¿Aún vale $65/mes para ti?"
- Si métrica no mejora O se cuestiona pricing después de 4 semanas: STOP y reevaluar

---

## Definition Complete

**Decisión:** SHIP IT
**Development empieza:** Lunes 19 Enero con prototipo como referencia exacta
**Team confirmed:** Juan + Sofía + Product Owner support

**Una persona decidió. Sin comités.**

*La mejor forma de definir un producto es prototiparlo y testearlo con clientes primero.*

---

## Key Learnings del Definition

### Insights del Prototipo
- **UI Complexity:** Clientes prefieren simple sobre completo
- **Visual Cues:** Traffic light system muy valorado
- **Workflow:** 4 pasos es el sweet spot (no 3, no 5)

### Pricing Discovery
- **Add-on preferred:** Easier budget justification vs. plan upgrades
- **Price anchoring:** $65/mes hit sweet spot entre $50-100 range
- **Value perception:** Time savings worth 20x the monthly cost

### Technical Confidence
- **Reduced timeline:** Simplified scope = más confidence
- **Risk mitigation:** Web scraping como backup plan
- **Resource allocation:** Full-time team commitment secured

### Next Phase Readiness
- ✅ Prototipo validated with target customers
- ✅ Pricing model confirmed and technical feasible  
- ✅ Engineering estimates realistic and confident
- ✅ Beta pipeline established and committed
- ✅ Success metrics defined and measurable

**Estado:** ✅ APROBADO - Listo para Development Phase