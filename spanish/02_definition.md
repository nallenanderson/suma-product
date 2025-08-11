# Proceso de Definition
**Quickly Define What Customers Need - Eliminar, Simplificar, Optimizar - Make Excellent Products!** [Example Document](./ejemplos/02_definition_licencias.md)

---

## Input Requerido
**Del Discovery:** 
- Enunciado del problema + Enfoque de solución
- 3 contactos de clientes beta + Meta de ingresos
- Estimación de tiempo de ingeniería

**Si no tienes estas 4 cosas, regresa al Discovery.**

---

## El Sprint de Definition de 5 Días

### Día 1: Prototipo de Solución Central (6 horas)
**Mañana (3 horas):**
Comenzar con el enfoque de solución del Discovery y construir un prototipo clickeable:
- Bosquejar el journey del usuario de 3-5 pantallas
- Construir prototipo funcional (**[Figma Make](https://www.figma.com/make/), [Lovable](https://lovable.dev/), [AI Studio](https://aistudio.google.com/app/apps), [v0](https://v0.dev/), [Bolt](https://bolt.new/), [Replit](https://replit.com/)**, hasta PowerPoint puede ser 🤯)
- Enfocarse en la acción central del usuario, ignorar el pulido

**Tarde (3 horas):**
Probar prototipo con 1-2 clientes beta:
- "Te voy a mostrar algo - dime qué piensas que hace"
- "Camíname a través de lo que esperarías que pasara paso a paso"
- Registrar qué los confunde vs. qué les hace click
- Preguntar: "¿Esto resolvería tu problema si funcionara exactamente así?"
- Preguntar: "¿Qué funcionó bien para ti? ¿Dónde sentiste que te perdiste o necesitabas más ayuda?"
- Recordar: Siempre profundizar más. Por qué, por qué, por qué...
- Catalogar hallazgos y feedback para preparar segunda iteración

### Día 2: Set de Features Mínimo (4 horas)
**Basado en feedback del prototipo, definir el mínimo absoluto:**

**Los 3 Features Must-Have:**
1. [Feature que habilita la acción central del usuario del prototipo]
2. [Feature que hace posible #1]  
3. [Feature que hace posible #2]

**Probar con clientes beta:** "Si solo construyéramos estas 3 cosas, ¿cómo las usarías y qué problemas resolvería?"

### Día 3: Technical Reality Check (6 horas)
**Mañana (3 horas):**
Mostrar prototipo a ingeniería:
- "¿Cuál es la forma más rápida de hacer que esto realmente funcione?"
- ¿Podemos hackear sistemas existentes juntos?
- ¿Cuál es el mayor riesgo técnico?

**Tarde (3 horas):**
Refinar timeline con la realidad de ingeniería:
- Estimación original del Discovery: [X] semanas
- Revisada después de ver prototipo: [Y] semanas
- Si >12 semanas: Cortar features o KILL IT

### Día 4: Plan Beta, Métricas de Éxito & Modelo de Precios (6 horas)
**Mañana (3 horas) - Validación de Precios & Packaging:**
Probar precios Y packaging con clientes beta usando prototipo refinado:

**Paso 1 - Descubrimiento de Valor:**
- Mostrar prototipo final: "¿Para esta solución exacta, qué esperarías pagar?"
- Referenciar datos del Discovery: "Dijiste que este problema te cuesta $[X]/mes"

**Paso 2 - Test de Opciones de Packaging:**
- **Opción A - Add-on:** "$[X]/mes extra sobre tu plan actual"
- **Opción B - Inclusión en plan:** "Incluido en nuestro plan Pro de $[Y]/mes" 
- **Opción C - Basado en uso:** "$[Z] por [transacción/usuario/GB procesado]"
- **Opción D - Por niveles:** "Versión básica incluida, features avanzados $[W]/mes"

**Paso 3 - Selección de Modelo:**
- Preguntar: "¿Cuál de estos se siente más justo por el valor que obtienes?"
- Preguntar: "¿Cuál haría más fácil conseguir aprobación de presupuesto?"
- Preguntar: "¿Cuál coincide con cómo piensas sobre este tipo de solución?"

**Tarde (3 horas) - Plan Beta & Éxito:**
- Confirmar que 3 clientes beta probarán en [Y] semanas CON el modelo de precios validado
- Definir éxito: "¿Qué necesita funcionar para que pagues $[Z] vía [modelo de precios] y uses esto [frecuencia]?"
- Programar check-ins semanales durante fase de construcción

**Output del Modelo de Precios:**
- Precio validado: $[X]/[período de facturación]
- Modelo de packaging: [Add-on/Inclusión en plan/Basado en uso/Por niveles]
- Razón de preferencia del cliente: "[Por qué los clientes prefieren este modelo]"
- Complejidad de implementación: [Fácil/Media/Difícil implementar este modelo]
- Compromiso del cliente: [Y]/3 clientes pagarán este precio vía este modelo

### Día 5: Plan de Construcción (2 horas)
**Plan de construcción semana por semana:**
- Semana 1-2: [Feature específico del prototipo se convierte en código funcional]
- Semana 3-4: [Siguiente feature del prototipo se convierte en código funcional]  
- Semana 5+: [Integración y testing beta]

**Confirmación de recursos:** [Y] ingenieros comprometidos por timeline

---

## El Output de Definition

### Lo Que Estamos Construyendo
**Problema:** [Copiar del Discovery]
**Solución:** [Refinada del testing del prototipo]
**Modelo de Precios:** [Add-on/Inclusión en plan/Basado en uso] a $[X]/[período]
**Validación del Cliente:** [Y]/3 clientes beta confirmaron que este modelo funciona para ellos
**Éxito:** [Métrica primaria + compromiso del cliente beta de pagar vía este modelo]

### El Set de Features Validado
**Must Have (Validado por prototipo + clientes):**
1. [Feature] - Porque [los clientes dijeron que esto era esencial en el test del prototipo]
2. [Feature] - Porque [habilita que #1 funcione]
3. [Feature] - Porque [habilita que #2 funcione]

**No Tendrá (Intencionalmente excluido):**
1. [Feature] - Porque [los clientes no lo mencionaron O complejidad de ingeniería muy alta]
2. [Feature] - Porque [nice-to-have pero no esencial para el problema central]
3. [Feature] - Porque [se puede agregar más tarde si los clientes beta lo piden]

**Quote del Cliente:** "[Mejor quote del testing del prototipo mostrando que lo quieren Y pagarán por ello]"

**Validación del Modelo de Precios:** 
- **Modelo elegido:** [Add-on/Inclusión en plan/Basado en uso o volumen/Por niveles]
- **Razón del cliente:** "[Por qué los clientes prefieren este modelo - ej., 'Add-on tiene sentido porque solo lo necesitamos ocasionalmente']"
- **Ajuste presupuesto/aprobación:** "[Cómo esto se ajusta a su procurement - ej., 'Basado en uso funciona porque podemos empezar pequeño y escalar']"

### Plan Prototipo-a-Código
**Semana 1-2:** [Pantalla 1 del prototipo] se convierte en feature funcional
**Semana 3-4:** [Pantalla 2 del prototipo] se convierte en feature funcional
**Semana 5-6:** [Integración] - features funcionan juntos
**Semana 7+:** Testing beta con clientes reales

### Enfoque Técnico (Post-Prototipo)
**Stack:** [Tech frontend] + [Tech backend] + [Base de datos]
**Integración:** [Sistemas externos necesarios]
**Mayor Riesgo:** [Desafío técnico identificado durante revisión del prototipo]
**Consideraciones de Seguridad:** [Específicamente revisado con Equipo de Seguridad]
**Requerimientos CloudOps:** [Específicamente revisado/aprobado con Equipo CloudOps]
**Requerimientos Sistema de Facturación:** [Cambios necesarios para soportar modelo de precios elegido - revisado con Finanzas/Ops]

**Timeline Final:** [Y] semanas (revisado de la estimación del Discovery)
**Equipo:** [Y] ingenieros comprometidos

### Plan Beta (Pre-Confirmado con Modelo de Precios)
**Clientes beta:** [3 nombres que vieron prototipo y se comprometieron al modelo de precios validado]
**Compromiso del modelo de precios:** $[X]/[período] como [Add-on/Inclusión en plan/Basado en uso] - [Y]/3 clientes confirmaron que este modelo funciona
**Criterio de éxito:** 2/3 clientes usan [frecuencia] Y confirman valor del modelo de precios
**Demos semanales:** Cada viernes durante construcción + check de experiencia del modelo de precios

---

## Decisión Go/No-Go
**SHIP IT si TODO es verdadero:**
- [ ] 2/3 clientes beta dijeron "sí, usaría esto [frecuencia]" después de ver prototipo
- [ ] 2/3 clientes beta confirmaron "sí, pagaría $[X] vía [modelo de precios]" 
- [ ] El modelo de precios elegido es técnicamente factible con nuestro sistema de facturación
- [ ] El prototipo demuestra que la solución cabe en <5 pasos del usuario
- [ ] Ingeniería confirma que puede construir en timeline revisado (<12 semanas)
- [ ] Los riesgos técnicos son manejables
- [ ] Los clientes beta se comprometieron a feedback semanal durante construcción

**KILL IT si CUALQUIERA es verdadero:**
- [ ] Los clientes beta no se convencieron con el prototipo O modelo de precios
- [ ] <2/3 clientes pagarán vía modelo de precios validado
- [ ] El modelo de precios requiere cambios mayores al sistema de facturación (>4 semanas dev time)
- [ ] Aún toma >12 semanas después de ver lo que realmente estamos construyendo
- [ ] Riesgos técnicos mayores descubiertos durante revisión del prototipo

---

## El Traspaso a Fase de Construcción

### Meta Sprint 1 (Semana 1)
[Un resultado específico, demostrable]

### Meta Semana 2-4
[Un resultado específico, demostrable]

### Meta Semanas 5-8
[Un resultado específico, demostrable]

### Meta Semanas 9-12
[Solución funcional en beta]

**Tracking de Éxito:**
- Demo semanal a clientes beta
- Check semanal de métrica: [Métrica primaria]
- Confirmación semanal de valor de precios: "¿Aún vale $[X] para ti?"
- Si la métrica no mejora O se cuestiona el valor del precio después de 4 semanas: STOP y reevaluar

---

## Anti-Patrones a Delete

❌ **User stories detalladas con criterios de aceptación** - Construir y testear en su lugar
❌ **Diagramas de arquitectura técnica** - Empezar a codificar y refactorizar después
❌ **Matrices de riesgo y planes de mitigación** - Ship rápido y arreglar problemas
❌ **Múltiples user personas** - Enfocarse en el problema de una persona
❌ **Planificación de Fase 2 y Fase 3** - Ship Fase 1 primero

---

## Definition Complete

**Decisión:** SHIP IT o KILL IT
**Si SHIP IT:** Development comienza el lunes con prototipo como referencia
**Si KILL IT:** Archivar prototipo y elegir siguiente problema del Discovery

**Una persona decide. Sin comités.**

*La mejor forma de definir un producto es prototiparlo y testearlo con clientes primero.*