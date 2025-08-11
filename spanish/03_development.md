# Proceso de Development
*Ship Working Code Daily - Eliminar, Simplificar, Optimizar - Make Excellent Products!* [Example Document](./ejemplos/03_development_licencias.md)

---

## Input Requerido
**Del Definition:** 
- Prototipo testeado + validación del cliente
- 3 features must-have (confirmados por cliente)
- 3 clientes beta comprometidos a testing semanal
- Plan de construcción semana por semana

**Si no tienes estas 4 cosas, regresa al Definition.**

---

## El Ciclo de Construcción Semanal

### Lunes: Meta Semanal + Referencia del Prototipo
**Resultado de Esta Semana:** [Una pantalla/feature del prototipo se convierte en código funcional]

**Test de Éxito:** "¿Pueden los clientes beta completar [tarea específica del prototipo] sin que se rompa?"

**Referencia del Prototipo:** Usar prototipo del Definition como especificación - construir exactamente lo que los clientes ya validaron

### Martes-Jueves: Construir Contra el Prototipo
**Pregunta Diaria:** "¿Esto funciona como el prototipo que los clientes aprobaron?"

**Regla Diaria:** Cada ingeniero commitea código funcional que coincida con el comportamiento del prototipo

**Demo Diario:** Mostrar el progreso de ayer comparado con el prototipo (máximo 5 minutos)

### Viernes: Demo a Cliente & Feedback
**Demo:** Mostrar el feature funcional de esta semana a clientes beta (los mismos que testearon el prototipo)
**Preguntar:** "¿Esto funciona como esperabas del prototipo?"
**Registrar:** Diferencias entre prototipo y código funcional que importan a los clientes
**Decidir:** Seguir construyendo siguiente pantalla del prototipo O arreglar el trabajo de esta semana

---

## El Único Tracking Que Importa

### Progreso Semanal
**Prototipo vs. Realidad:** [Qué pantalla del prototipo ahora es código funcional]
**Feedback del Cliente:** [Lo que los clientes beta dijeron sobre el trabajo de esta semana]
**Siguiente Feature del Prototipo:** [Qué pantalla del prototipo construimos la próxima semana]

**Eso es todo. No story points, no burn-down charts, no velocity tracking.**

### Quality Gates (Delete Todo Lo Demás)
**Los 3 Gates:**
1. **¿Funciona?** [El usuario puede completar la acción central]
2. **¿Es seguro?** [Data financiera encriptada, no exploits obvios]
3. **¿Es rápido?** [<3 segundos de tiempo de respuesta]

**Si los 3 = Sí:** Ship it
**Si cualquiera = No:** Arréglalo

---

## Resolución de Problemas

### Issues Diarios
**Problema:** [Qué se rompió hoy]
**Owner:** [Una persona arregla esto]
**Arreglar para:** [Fin del día/mañana/esta semana]

**No sistemas de tracking de issues. No prioridades de tickets. Una persona lo posee, lo arregla rápido.**

### Retrospectiva Semanal (5 minutos)
**¿Qué nos frenó esta semana?** [Una cosa]
**¿Cómo lo eliminamos la próxima semana?** [Una acción]
**¿Quién posee el arreglo?** [Una persona]

---

## Estándares de Código (Mínimo Viable)

### Definición de Funcional
- [ ] Feature funciona end-to-end para usuario objetivo
- [ ] Otro ingeniero lo ha testeado
- [ ] El código no rompe features existentes
- [ ] Los cálculos financieros son correctos (para ERP/Payroll)

**No reuniones de code review. No architecture reviews. Solo código funcional.**

### Mínimos de Seguridad (No-Negociables)
- [ ] Data de usuario encriptada en reposo y en tránsito
- [ ] Data financiera usa encriptación AES-256
- [ ] Endpoints de API requieren autenticación
- [ ] Validación de input previene SQL injection

### Mínimos de Performance
- [ ] Respuestas de API <3 segundos
- [ ] Carga de páginas <5 segundos
- [ ] Queries de base de datos optimizadas para 1000+ usuarios

---

## El Loop Build-Ship (Driven por Prototipo)

### Semana 1-2: Primera Pantalla del Prototipo → Código Funcional
**Construir:** Pantalla/workflow más importante del prototipo
**Testear:** Con los mismos 3 clientes beta que validaron el prototipo
**Comparar:** "¿La versión funcional coincide con lo que esperabas del prototipo?"
**Resultado:** Pantalla funciona como prototipo O arreglamos las diferencias

### Semana 3-4: Segunda Pantalla del Prototipo → Código Funcional
**Construir:** Siguiente pantalla/workflow del prototipo
**Testear:** Integración con trabajo de semana 1-2 + feedback de clientes beta
**Comparar:** "¿Puedes completar el workflow completo del prototipo?"
**Resultado:** Workflow funciona end-to-end O simplificamos

### Semana 5-8: Prototipo Completo → Producto Funcional
**Construir:** Pantallas restantes del prototipo + integración
**Testear:** Journey completo del usuario con clientes beta
**Comparar:** "¿Esto resuelve tu problema como mostró el prototipo?"
**Resultado:** Clientes beta usan diariamente O iteramos

### Semana 9-12: Polish Basado en Uso
**Construir:** Arreglar lo que más les cuesta a los clientes beta
**Testear:** Patrones de uso y feedback
**Resultado:** Listo para lanzamiento completo a todos los clientes

---

## Loop de Feedback del Cliente (Clientes Pre-Validados)

### Demo Semanal al Cliente (Mismos Clientes Beta del Definition)
**Mostrar:** Feature funcional de esta semana vs. versión del prototipo
**Preguntar:** "¿Esto funciona como esperabas? ¿Qué es diferente?"
**Registrar:** Gaps entre prototipo y código funcional
**Decidir:** Arreglar diferencias O seguir construyendo (si el gap no les importa a los clientes)

### Salud de Clientes Beta (Pipeline Validado)
**Saludable:** Cliente usa features funcionales diariamente (coincidiendo expectativas del prototipo)
**Warning:** Cliente confundido por diferencias del prototipo
**Crítico:** Cliente dice "esto no funciona como el prototipo me mostró"

**Si Crítico:** Parar de construir nuevos features y arreglar la desconexión

---

## Coordinación del Equipo

### Daily Standup (máximo 5 minutos)
**Ayer:** Qué feature del prototipo construí en código funcional
**Hoy:** Qué parte del prototipo estoy haciendo funcionar
**Blocker:** Gap entre prototipo y realidad técnica (o "ninguno")

**No status updates. No discusiones de planning. Solo progreso prototipo-a-código.**

### Planning Semanal (máximo 15 minutos)
**Semana pasada:** ¿La pantalla del prototipo funcionó como los clientes esperaban? [Sí/No]
**Esta semana:** Qué pantalla/workflow del prototipo estamos construyendo
**Recursos:** Quién está trabajando en qué parte del prototipo

---

## Anti-Patrones a Delete

❌ **Reuniones de sprint planning** - Planear una semana a la vez
❌ **Estimación de story points** - Constrúyelo y ve cuánto toma
❌ **Backlog grooming** - Trabajar en el feature más importante primero
❌ **Velocity tracking** - Ship features funcionales o no lo hagas
❌ **Burndown charts** - Demo a clientes en su lugar
❌ **Sistemas de manejo de issues** - Arreglar problemas inmediatamente
❌ **Ceremonias de code review** - Testear el código de otros rápidamente
❌ **Checklists de definition of done** - Ship código funcional

---

## Métricas de Éxito

### Solo Una Importa
**¿Los clientes beta están usando la versión funcional como usaron el prototipo?**

*Todo lo demás son métricas de vanidad.*

### Health Check Semanal
**Fidelidad del Prototipo:** ¿El código funcional coincide con el comportamiento del prototipo?
**Uso del Cliente:** [X]% de clientes beta usando features funcionales diariamente
**Feedback del Cliente:** [Igual que prototipo/Mejor que prototipo/Peor que prototipo]
**Salud Técnica:** [No bugs críticos/Algunos bugs/Roto]

---

## Procedimientos de Emergencia

### Issues de Producción
**Paso 1:** Una persona posee el arreglo
**Paso 2:** Arreglar en 4 horas o rollback
**Paso 3:** Post-mortem en un párrafo: Qué se rompió + Cómo lo prevenimos

### Escalaciones de Cliente
**Paso 1:** Engineering lead habla con cliente directamente
**Paso 2:** Arreglar su problema en 24 horas
**Paso 3:** Construir feature para prevenir problemas similares

---

## Development Complete

**Éxito:** Clientes beta usan el producto funcional como usaron el prototipo
**Falla:** El producto funcional no coincide con el comportamiento del prototipo que los clientes validaron

**Construir el prototipo que ya aprobaron. Todo lo demás es waste.**