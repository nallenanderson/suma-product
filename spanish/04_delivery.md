# Proceso de Delivery
*Ship For Impact - Delete, Simplify, Launch - Make Excellent Products!*

---

## Input Requerido
**Del Development:** 
- Producto funcional que coincide con prototipo validado
- 3 clientes beta ya usándolo diariamente
- Precios validados confirmados durante development ($[X]/período)
- Data de uso probando coincidencia producto-prototipo
- Feedback del cliente confirmando que resuelve su problema Y vale el precio

**Si los clientes beta no están usando el producto funcional diariamente Y confirmando valor del precio, no lo lances.**

---

## El Proceso de Launch de 3 Días

### Día 1: Decisión de Launch (Precios Ya Definidos)
**Confirmación del Modelo de Precios (De la Fase Definition):**
- Modelo de precios validado del Definition: $[X]/[período] como [Add-on/Inclusión en plan/Basado en uso]
- Validación de clientes beta: [Y]/3 clientes confirmaron que este modelo funciona para ellos
- Sistema de facturación listo: [Confirmado con equipo de Finanzas/Ops]
- **No se necesitan decisiones de modelo de precios** - el modelo fue validado con prototipo y sistema de facturación preparado

**Decisión de Launch:** 
- Pregunta: ¿Los 3 clientes beta están usando esto diariamente Y aún confirman que el modelo de precios funciona para ellos?
- **Sí:** Lanzar a todos los clientes inmediatamente con modelo de precios validado
- **No:** No lanzar - arreglar problema de producto o modelo de precios primero

### Día 2: Prenderlo (Ejecutar Modelo de Precios Validado)
**Mañana:** Producto + modelo de precios validado live para 100% de clientes
**Comunicación de Precios:** 
- **Si Add-on:** "Nuevo add-on [nombre del feature] - $[precio]/[período] - [beneficio]"
- **Si Inclusión en plan:** "[Nombre del feature] ahora incluido en tu [Nombre del Plan] - [beneficio]" 
- **Si Basado en uso:** "Nuevo [nombre del feature] - $[precio] por [unidad] - [beneficio]"
**Tarde:** Monitorear uso y cualquier confusión del modelo de precios
**Noche:** Revisar métricas de adopción y ingresos/uso inicial

### Día 3: Medir Éxito
**Uso:** [X]% de clientes lo probaron
**Conversión:** [Y]% de quienes probaron se volvieron clientes pagantes
**Ingresos:** $[Z] real vs $[Esperado] proyectado
**Problemas:** Arreglar cualquier problema de precios o producto inmediatamente

---

## El Único Plan de Launch Que Importa

### Antes del Launch (1 hora)
**Decirles a clientes:** "Nuevo feature está live ahora - esto es lo que hace"
**Decirles a soporte:** "Así es como funciona el feature + cómo ayudar a clientes"
**Decirles a ingeniería:** "Vigilar estas 3 cosas que podrían romperse"

### Día de Launch (Solo Monitorear)
**Hora 1:** ¿Los clientes lo están usando?
**Hora 4:** ¿Algún issue crítico?
**Fin del día:** Decisión de éxito o rollback

### Después del Launch (1 semana)
**Diario:** Arreglar cualquier problema del cliente inmediatamente
**Semanal:** Medir tasa de adopción
**Mensual:** Medir impacto de negocio

---

## Métricas de Éxito (Las Únicas 4 Que Importan)

### 1. Adopción del Cliente
**Target:** [X]% de clientes elegibles prueban feature dentro de 7 días
**Medición:** Tasa de activación del feature
**Acción:** Si <50% adopción después de semana 1, arreglar producto o messaging

### 2. Conversión de Ingresos  
**Target:** [Y]% de quienes prueban se vuelven clientes pagantes dentro de 14 días
**Medición:** Tasa de conversión trial-a-pagante
**Acción:** Si <[esperado]% conversión (basado en validación beta), investigar desconexión

**Nota:** Target de tasa de conversión basado en tasa de validación de clientes beta de fase Definition

### 3. Problemas del Cliente
**Target:** <5 tickets de soporte por 100 usuarios activos
**Medición:** Volumen de tickets de soporte (producto + preguntas de precios)
**Acción:** Arreglar cualquier problema que afecte >10 clientes inmediatamente

### 4. Achievement del Target de Ingresos
**Target:** $[X] ingresos mensuales incrementales (del Discovery, validado en Definition)
**Medición:** Ingresos recurrentes reales del feature
**Acción:** Si <80% del target después de 30 días, investigar (precios fueron pre-validados, así que probablemente issue de adopción)

**Todo lo demás son métricas de vanidad.**

---

## Comunicación al Cliente (Mínimo Viable)

### Mensaje de Launch (Enviar Una Vez)
**Subject varía por modelo de precios:**

**Si Add-on:** "[Nombre del Feature] add-on ahora disponible - $[precio]/[período]"
**Si Inclusión en plan:** "[Nombre del Feature] ahora incluido en tu [Nombre del Plan]"  
**Si Basado en uso:** "[Nombre del Feature] disponible - paga mientras usas ($[precio]/[unidad])"

**Template de contenido:**
- Qué: [Una oración de lo que hace]
- Por qué: [Una oración del problema que resuelve + valor entregado]
- Precios: [Explicación de precios específica del modelo]
- Cómo: [Un click para empezar - varía por modelo]

**Enviar a:** [Targeted por modelo de precios - todos los clientes, clientes de plan específico, etc.]

### Training de Soporte (15 minutos)
**Decirle al equipo de soporte:**
- Qué hace el feature
- Modelo de precios: $[precio]/[período] como [Add-on/Inclusión en plan/Basado en uso] - por qué este modelo
- Cómo funciona la facturación: [Proceso de facturación para este modelo]
- 3 preguntas más probables del cliente (producto + modelo de precios)
- A quién escalar issues complejos

**Respuestas de modelo de precios pre-validadas:**
- **Preguntas Add-on:** "¿Por qué cargo separado?" → "Clientes beta prefirieron flexibilidad de agregar solo si es necesario"
- **Preguntas Inclusión en plan:** "¿Por qué no disponible en Básico?" → "Clientes Pro validaron que esto encaja en su workflow"  
- **Preguntas Basado en uso:** "¿Cómo se calcula el uso?" → [Definición específica de uso de la validación]
- **Preguntas de facturación:** [Proceso para su modelo específico - mensual, anual, por-uso, etc.]

---

## Resolución de Problemas

### Issues Críticos (Arreglar Inmediatamente)
**Crítico = Cualquiera de estos:**
- Feature no funciona para >10% de usuarios
- Feature rompe funcionalidad existente
- Corrupción de data o issue de seguridad
- >20 emails de clientes enojados

**Respuesta:** Arreglar en 4 horas o rollback del feature

### Issues No-Críticos (Arreglar Esta Semana)
**No-Crítico = Todo lo demás**
**Respuesta:** Agregar a prioridades de development de la próxima semana

### Feature Rollback (Opción Nuclear)
**Trigger:** Issue crítico no se puede arreglar en 4 horas
**Proceso:** 
1. Apagar feature para todos los clientes
2. Email a clientes: "Feature temporalmente deshabilitado - regresa pronto"
3. Arreglar problema y re-lanzar cuando esté listo

---

## Patrones de Éxito del Launch

### Semana 1: Adopción + Validación de Precios
**Éxito:** >50% prueban feature, tasa de conversión coincide con validación beta
**Warning:** Buena adopción pero conversión menor que beta (investigar comunicación de precios)
**Falla:** <20% adopción (problema de product-market fit, no precios)

### Semana 2-4: Uso + Crecimiento de Ingresos
**Éxito:** Uso diario >30% de adoptadores, ingresos tracking hacia target
**Warning:** Buen uso pero ingresos bajo target (optimización de precios necesaria)
**Falla:** <10% uso diario O <10% conversión (arreglar o KILL IT)

### Mes 2+: Achievement del Target de Ingresos
**Éxito:** Hit del target de ingresos del Discovery ($[X]/mes)
**Warning:** 60-80% del target de ingresos (optimizar conversión o precios)
**Falla:** <60% del target de ingresos (iteración mayor o sunset)

---

## Anti-Patrones a Delete

❌ **Rollouts graduales y A/B tests** - Ship a todos inmediatamente
❌ **Reuniones de planning de launch** - Solo prenderlo
❌ **Programas de training de clientes** - Hacer features auto-explicativos
❌ **Documentación detallada de launch** - Escribir un email
❌ **Eventos de celebración de éxito** - Celebrar impacto de ingresos en su lugar
❌ **Retrospectivas post-launch** - Arreglar problemas inmediatamente en su lugar
❌ **Manejo de feature flags** - Ship features funcionales, no rotos
❌ **Campañas de comunicación de launch** - Un email, luego dejar que el uso hable

---

## El Loop de Customer Success

### Monitoreo Diario (5 minutos)
**Revisar:** Números de uso del cliente
**Preguntar:** ¿Algún ticket nuevo de soporte sobre este feature?
**Actuar:** Arreglar problemas el mismo día

### Health Check Semanal (15 minutos)
**Tendencia de uso:** ¿Arriba, abajo, o plano?
**Feedback del cliente:** ¿Feliz, confundido, o enojado?
**Impacto de negocio:** ¿Positivo, neutral, o negativo?

### Review de Impacto Mensual (30 minutos)
**Impacto de ingresos:** $[X] MRR incremental
**Retención de clientes:** [Y]% mejora
**Destino del feature:** Seguir construyendo, mantener, o sunset

---

## Templates de Comunicación de Launch

### Email de Launch al Cliente
```
Subject: [Feature] está live ahora

Hola [Cliente],

Acabamos de lanzar [Nombre del Feature] - [resuelve problema específico].

Pruébalo ahora: [Link directo]

¿Preguntas? Responde este email.

Gracias,
[Equipo]
```

### Briefing al Equipo de Soporte
```
Nuevo feature: [Nombre del Feature]
Qué hace: [Una oración]
Cómo lo usan clientes: [Una oración]
Preguntas comunes: [Listar 3]
Escalar a: [Nombre] para issues complejos
```

### Anuncio Interno de Launch
```
[Nombre del Feature] está live para todos los clientes.
Vigilar: [3 issues potenciales]
Target de éxito: [X]% adopción en 7 días
Preguntas a: [Product Manager]
```

---

## Framework de Decisión de Launch

### Ship It Si:
- [ ] Clientes beta lo usan diariamente
- [ ] Feature funciona end-to-end
- [ ] Resuelve problema real del cliente
- [ ] Equipo de soporte sabe cómo ayudar
- [ ] Se puede hacer rollback si es necesario

### No Ship Si:
- [ ] Clientes beta dejaron de usarlo
- [ ] Funcionalidad mayor rota
- [ ] No hay beneficio claro para el cliente
- [ ] Muy complejo para dar soporte
- [ ] No se puede medir éxito

**Una persona decide. Sin comités.**

---

## Realidad Post-Launch

### Semana 1: Fire Fighting
**Foco:** Arreglar cualquier cosa que rompa workflows del cliente
**Éxito:** No clientes enojados, feature funciona
**Decisión:** Continuar o rollback

### Mes 1: Adoption Drive
**Foco:** Ayudar a clientes a descubrir y usar feature
**Éxito:** Tasa de adopción target alcanzada
**Decisión:** Invertir más o pivot

### Mes 3: Medición de Impacto
**Foco:** Medir resultados de negocio
**Éxito:** ROI claro de la inversión de development
**Decisión:** Construir más features u optimizar existentes

---

## Integración de Precios Across Workflow

### Fase Discovery (Pricing Foundation)
**Preguntas Clave:**
- "¿Qué pagarías para nunca lidiar con este problema otra vez?"
- "¿Cuánto te cuesta este problema anualmente?"
- "¿Cuál es tu presupuesto actual para resolver esto?"

**Output de Precios:** Rango de precios basado en valor del cliente ($[X] - $[Y])

### Fase Definition (Validación & Decisión de Precios) ⭐
**Durante testing del prototipo:**
- "Para esta solución exacta [mostrar prototipo], ¿qué esperarías pagar?"
- "A $[X]/mes, ¿comprarías esto?"
- "¿Qué precio haría que esto fuera un no-brainer vs. muy caro?"

**Output de Precios:** **DECISIÓN DE PRECIO VALIDADA** - $[X]/período con compromiso del cliente

### Fase Development (Confirmación de Precios)
**Durante demos semanales:**
- "Mientras esto se vuelve real, ¿aún vale $[X] para ti?"
- "¿La versión funcional entrega el valor que esperabas por este precio?"

**Output de Precios:** Confirmación final de precio de usuarios beta activos

### Fase Delivery (Solo Ejecución de Precios)
**Launch con precios pre-validados:**
- Ejecutar estrategia de precios validada (no decisiones de precios)
- Monitorear tasas de conversión vs validación beta
- Solo optimizaciones menores si es necesario

**El insight clave:** El precio se DECIDE en Definition, se CONFIRMA en Development, se EJECUTA en Delivery.

---

## Launch Complete

**Éxito:** Clientes usan feature diariamente + impacto de negocio logrado
**Falla:** Baja adopción o no impacto de negocio

**El mercado decide si los features tienen éxito, no las métricas internas.**

*Ship fast, measure impact, fix problems immediately.*