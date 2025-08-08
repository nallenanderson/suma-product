# Discovery: Automated Medical Leave Processing
*Proceso de Discovery Completado - 48 horas*

---

## Marco de Preguntas Centrales - COMPLETADO ✅

1. **¿Qué problema mata a nuestros clientes y con qué frecuencia?**
   → Procesamiento manual de licencias médicas, 2-4 horas semanales por empresa

2. **¿Los clientes nos pagarán $X adicionales inmediatamente por resolver esto?**
   → $60/mes - validado con 5 clientes

3. **¿Podemos resolver esto 10x mejor que las alternativas?**
   → Sí - automatización completa vs. input manual de competidores

4. **¿Podemos construir esto en <12 semanas con nuestro equipo actual?**
   → Sí - 10 semanas estimadas (OCR + API integrations + cálculos)

---

## Resultados del Sprint de 48 Horas

### Día 1: Validación del Problema - COMPLETADO
**Mañana (4 horas) - Customer Interviews:**

- **María González, Contadora PYME (30 empleados):** "Cada licencia médica me toma 45 minutos. Entre verificar si es válida, calcular los descuentos correctos, y actualizar la liquidación. Lo peor es cuando COMPIN rechaza una licencia después de que ya pagué."

- **Carlos Mendoza, Administrador Retail (50 empleados):** "Tengo empleados que se enferman seguido, especialmente en invierno. Pierdo 3 horas por semana solo en licencias. Me da terror calcular mal y que inspección del trabajo me multe."

- **Ana Rodríguez, RRHH Constructora (80 empleados):** "Pagaría $100/mes fácil por no tener que lidiar con esto. Es mi trabajo más odiado del mes."

- **Pedro Martínez, Contador Restaurant (25 empleados):** "Las licencias me llegan siempre a última hora. Tengo que correr a procesarlas antes del cierre de liquidación. Muy estresante."

- **Carmen Silva, Administradora Clínica (60 empleados):** "Ironía que trabajando en salud, las licencias médicas sean mi mayor dolor de cabeza. Necesito algo automático urgente."

**Tarde (4 horas) - Análisis Support Tickets:**
- 127 tickets relacionados con licencias médicas (últimos 90 días)
- Promedio 1.4 tickets por día
- Temas principales: cálculos incorrectos (40%), confusión legal (35%), problemas de tiempo (25%)

### Día 2: Reality Check & Validación - COMPLETADO
**Mañana (2 horas) - Competitive Analysis:**
- **Buk:** Módulo manual, requiere input de todos los datos
- **Rankmi:** No tiene funcionalidad de licencias médicas
- **Nubox:** Cálculo básico, sin integración APIs externas
- **Oportunidad:** Ninguno tiene automatización completa ni integración COMPIN/ISAPRE

**Tarde (2 horas) - Solution Validation:**
- **Problema:** Las PYMEs chilenas pierden 2-4 horas semanales procesando licencias médicas manualmente y temen cálculos incorrectos
- **Solución:** Sistema OCR + integración APIs + cálculos automáticos que reduce proceso a 2 clicks
- **Beta commitments:** 3 clientes confirmados (María, Carlos, Ana)

---

## Matriz de Decisión Go/No-Go - RESULTADO: GO ✅

**GO - TODO verdadero:**
- [✅] 47 clientes experimentan este problema semanalmente (de base de 150 PYMEs)
- [✅] Les cuesta $1,200+ anuales (3 horas/semana × $10/hora × 52 semanas = $1,560)
- [✅] 3 clientes beta comprometidos (María, Carlos, Ana)
- [✅] Ningún competidor lo resuelve completamente - opportunity clara
- [✅] Ingeniería estima 10 semanas para MVP
- [✅] Ruta clara a $600K+ ARR (1,000 PYMEs × $60/mes × 80% penetration)

---

## Output: El Traspaso de Discovery

### El Problema Validado
Las PYMEs chilenas pierden 2-4 horas semanales procesando licencias médicas manualmente, validando con COMPIN/ISAPRE y calculando descuentos complejos. Afecta principalmente a contadores y administradores de empresas con 30-100 empleados que manejan 5-15 licencias mensuales. Les cuesta aproximadamente $1,560 anuales en tiempo perdido por empresa, más riesgo de multas por cálculos incorrectos.

### La Solución Propuesta
Automatizaremos completamente el proceso con OCR para extraer datos de PDFs, integración directa con APIs de COMPIN/ISAPRE para validación, y motor de cálculo automático que genera ajustes de liquidación listos. Ganaremos porque somos los únicos con automatización end-to-end mientras competidores requieren input manual completo.

### La Evidencia
- Clientes afectados: 47 de 150 PYMEs en base actual
- Frecuencia del problema: Semanal (peak en marzo-julio por licencias invierno)
- Costo por cliente anualmente: $1,560 o 3 horas/semana
- Clientes beta comprometidos: María González, Carlos Mendoza, Ana Rodríguez
- Estimación de ingeniería: 10 semanas
- Soluciones competitivas: 0 (Buk/Nubox tienen input manual)

### La Oportunidad
- Ingresos en 18 meses: $720K ARR (1,000 PYMEs × $60/mes)
- Estimación de costo de desarrollo: $120K (2 developers × 10 semanas × $6K/semana)
- Período de retorno: 4 meses
- Nivel de confianza: Alto - problema validado, solución técnicamente viable, mercado sin competencia directa

### Listo para Fase de Definition
- [✅] Problema validado con clientes (5 interviews + 127 support tickets)
- [✅] Enfoque de solución identificado (OCR + API + auto-calc)
- [✅] Clientes beta comprometidos (3 names + contacts)
- [✅] Oportunidad de ingresos calculada ($720K ARR potential)

### La Decisión
**SHIP IT** - Alto dolor del cliente, oportunidad de ingresos clara, ventaja competitiva defendible, y factibilidad técnica confirmada en 10 semanas.

---

## Proceso de Aprobación

**Decisor:** Product Lead  
**Decisión:** SHIP IT - aprobado 15 Enero 2025  
**Comenzar Definition:** 16 Enero 2025 con:
- Enunciado del problema: "PYMEs pierden 2-4 horas/semana en licencias médicas manuales"
- Enfoque de solución: "OCR + API integration + cálculo automático" 
- 3 contactos beta: 
  - María González (+56 9 1234-5678) - maria.gonzalez@contabilidadpro.cl
  - Carlos Mendoza (+56 9 2345-6789) - carlos.mendoza@retailsur.cl
  - Ana Rodríguez (+56 9 3456-7890) - ana.rodriguez@construcc.cl
- Estimación ingeniería: 10 semanas con Juan (backend) + Sofía (frontend)

---

## Próximos Pasos Inmediatos
1. **Kickoff Definition** - 16 Enero 9AM con Juan y Sofía
2. **Customer contact** - Agendar sesiones de prototipo con María, Carlos, Ana para 17-18 Enero
3. **Technical research** - Investigar APIs disponibles COMPIN/ISAPRE (Juan)
4. **Revenue tracking** - Setup métrica: ingresos de esta solución en 3 meses

---

## Insights Adicionales del Discovery

### Patrones de Uso Identificados
- **Estacionalidad:** Peak de licencias en meses fríos (mayo-agosto)
- **Tipos de empresa más afectados:** Retail, construcción, servicios
- **Tiempo promedio por licencia:** 45 minutos (rango: 30-90 minutos)
- **Frecuencia:** 3-8 licencias por mes por PYME

### Riesgos Técnicos Identificados
- **API availability:** COMPIN/ISAPRE pueden no tener APIs públicas
- **OCR accuracy:** PDFs de licencias tienen formatos variables
- **Legal complexity:** Regulaciones cambian frecuentemente

### Oportunidades Adicionales
- **Integration:** Conectar con mutuales (ACHS, Mutual, etc.)
- **Compliance:** Generar reportes automáticos para inspección del trabajo
- **Analytics:** Dashboard de tendencias de licencias por empresa

---

*Métrica de Éxito: $60K MRR incremental de este feature en Abril 2025*

**Estado:** ✅ APROBADO - Listo para Definition Phase