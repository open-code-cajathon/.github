<div align="center">
<img src="https://img.shields.io/badge/CAJATHON-2026-1a1a2e?style=for-the-badge&labelColor=0d0d1a" alt="Cajathon 2026"/>
<img src="https://img.shields.io/badge/Eje%203-RIE--01-c0392b?style=for-the-badge&labelColor=0d0d1a" alt="RIE-01"/>
<img src="https://img.shields.io/badge/Fase-Solution%20Concept%20v6-e0a829?style=for-the-badge&labelColor=0d0d1a" alt="Versión 6"/>
<br><br>
 
# ✕ SPECTRA — E
 
**Alerta temprana de deterioro de pago**
 
Copiloto de riesgo para analistas y asesores de Caja Trujillo
 
<br>
<img src="https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square&logo=lightgbm&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-black?style=flat-square&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white"/>
<br><br>
 
Equipo: Jorge · Grasiani · Gerard · Julio &nbsp;|&nbsp; Versión 6 &nbsp;|&nbsp; 27 / 11 / 2026
 
</div>
<br>
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,8,12&height=90&section=header" width="100%"/>
<br>
## Índice
 
<table width="100%">
<tr><td>1. Resumen ejecutivo</td><td>7. Tecnología preexistente</td></tr>
<tr><td>2. Modelo conceptual: cuatro pilares</td><td>8. Enfoque de ciberseguridad</td></tr>
<tr><td>3. Problema abordado</td><td>9. Funcionalidad crítica y guion de demo</td></tr>
<tr><td>4. Marco de evidencia visual</td><td>10. Alcance priorizado (MoSCoW)</td></tr>
<tr><td>5. Experiencia del asesor</td><td>11. Cronograma y roles</td></tr>
<tr><td>6. Concepto de solución (6 etapas)</td><td>12. Riesgos y mitigaciones</td></tr>
<tr><td>13. Impacto esperado y KPIs</td><td>14. Repositorios y stack técnico</td></tr>
<tr><td>15. Reglas de colaboración</td><td>16. Cumplimiento con las bases</td></tr>
<tr><td>17. Limitaciones declaradas</td><td>18. Definición de terminado</td></tr>
</table>
<br>
---
 
<br>
**1. Resumen ejecutivo**
 
XSpectra-e proporciona al asesor las herramientas necesarias para anticipar el deterioro crediticio, comprender sus causas y actuar preventivamente antes de la mora.
 
Es un copiloto de alerta temprana para analistas y asesores de Caja Trujillo: detecta cuándo el comportamiento de un microempresario se aparta de forma persistente de su propio patrón habitual (descontando la estacionalidad normal de su rubro), explica por qué, y ayuda a decidir a quién conviene contactar primero y con qué acción preventiva, según la capacidad real del equipo.
 
> El sistema **nunca** aprueba, rechaza ni modifica un crédito: prioriza, explica y sugiere. **Decide una persona.**
 
<table width="100%">
<tr>
<th align="left" width="50%">No es</th>
<th align="left" width="50%">Es</th>
</tr>
<tr>
<td>Un modelo que reemplaza al asesor</td>
<td>Un sistema que organiza información dispersa</td>
</tr>
<tr>
<td>Un sistema automático que rechaza clientes</td>
<td>Un sistema que detecta señales tempranas de deterioro</td>
</tr>
<tr>
<td>Un dashboard tradicional de mora</td>
<td>Un sistema que explica las causas con evidencia y prioriza acciones donde generan mayor impacto</td>
</tr>
</table>
<br>
*Tres ideas lo diferencian de un semáforo de mora o de un scoring estático:*
 
<table width="100%">
<tr><td align="center" width="40"><b>1</b></td><td><b>Línea base propia.</b> Cada cliente se compara con su propia historia y con su grupo de pares (rubro y zona), no con un umbral fijo igual para todos.</td></tr>
<tr><td align="center"><b>2</b></td><td><b>Filtro de evidencia en tres niveles</b> (desviación relevante, persistencia, corroboración) que separa el deterioro real de la fluctuación normal, con estados explícitos de «observación» e «información insuficiente».</td></tr>
<tr><td align="center"><b>3</b></td><td><b>Priorización por capacidad.</b> Un optimizador asigna las intervenciones donde más pérdida evitan, dado el número de contactos que el equipo puede realizar.</td></tr>
</table>
<br>
> **La frase que debe quedar:** *XSpectra-e permite ganar tiempo antes de la mora, entregando al asesor la evidencia necesaria para actuar oportunamente.*
 
<br>
---
 
<br>
**2. Modelo conceptual: cuatro pilares integrados**
 
XSpectra-e no es un proyecto de inteligencia artificial construido por ingenieros: es una solución de negocio para Caja Trujillo en la que negocio, analítica, tecnología y seguridad trabajan juntas para que el asesor tome mejores decisiones.
 
<table width="100%">
<tr>
<th align="left">Área</th>
<th align="left">Pregunta que responde</th>
</tr>
<tr><td><b>Negocios</b></td><td>¿Por qué importa?</td></tr>
<tr><td><b>Datos / IA</b></td><td>¿Cómo detectamos?</td></tr>
<tr><td><b>Tecnología</b></td><td>¿Cómo funciona?</td></tr>
<tr><td><b>Seguridad</b></td><td>¿Cómo confiamos?</td></tr>
<tr><td><b>Diseño</b></td><td>¿Cómo lo usa el asesor?</td></tr>
</table>
*Seguridad opera como base transversal de los otros tres pilares (negocio, analítica, tecnología) que sostienen la decisión del asesor.*
 
<br>
---
 
<br>
**3. Problema abordado**
 
La situación de un microempresario suele deteriorarse de forma gradual antes del primer atraso: bajan los depósitos, aumenta el uso de la línea, se alargan los días entre abonos, el pago se posterga hacia el último día. Hoy esa señal se detecta tarde o con umbrales fijos que mezclan dos cosas distintas:
 
<table width="100%">
<tr><td width="50%" valign="top"><b>Fluctuación normal</b><br>Campañas, cosechas, feriados, semanas de poca venta que el negocio absorbe sin problema.</td>
<td width="50%" valign="top"><b>Deterioro real</b><br>Un cambio sostenido y respaldado por varias señales independientes.</td></tr>
</table>
El resultado de confundir ambas cosas es triple: **alertas tardías**, **alertas ruidosas** (falsos positivos que saturan al analista) y **ninguna forma de priorizar** cuando hay más casos que capacidad de contacto.
 
El reto, por tanto, no es «predecir mora» sino responder tres preguntas que el asesor realmente se hace:
 
1. ¿Quién se está deteriorando de verdad?
2. ¿Con cuánta certeza y por qué?
3. ¿A quién conviene contactar primero y con qué acción preventiva?
*Restricciones respetadas desde el inicio del diseño:* protección de datos personales, evitar sesgos, considerar la incertidumbre, sustentar cada alerta en evidencia, minimizar falsos positivos, facilitar la revisión humana y no generar decisiones crediticias automáticas.
 
<br>
---
 
<br>
**4. Marco de evidencia visual**
 
Cada pantalla responde a una pregunta concreta del asesor, no a una funcionalidad técnica.
 
<table width="100%">
<tr><th align="left" width="90">Punto</th><th align="left">Objetivo</th><th align="left">Mensaje clave</th></tr>
<tr><td align="center"><b>A</b></td><td>Línea base personalizada: evolución histórica del cliente con tendencia esperada (ajustada por estacionalidad) y desviaciones</td><td><i>«No comparamos clientes entre sí; identificamos cuándo un cliente cambia respecto a su propio comportamiento.»</i></td></tr>
<tr><td align="center"><b>B</b></td><td>Filtro de evidencia de tres niveles: Cambio detectado → Persistencia y corroboración → Observación / Seguimiento / Intervención</td><td><i>«La IA reduce el ruido y prioriza únicamente señales relevantes.»</i></td></tr>
<tr><td align="center"><b>C</b></td><td>Explicabilidad del riesgo: disminución de ventas, mayor uso de crédito, cambios en frecuencia de pago, variaciones del flujo</td><td><i>«La IA predice, pero también explica.»</i></td></tr>
<tr><td align="center"><b>D</b></td><td>Priorización inteligente: cola con conteos (ej. de 500 clientes: 15 alta prioridad, 60 seguimiento, 425 estables)</td><td><i>«El asesor concentra sus esfuerzos donde puede generar mayor impacto.»</i></td></tr>
<tr><td align="center"><b>E</b></td><td colspan="2">Tres vistas del tablero, cada una respondiendo la pregunta de su propio usuario — no un dashboard genérico</td></tr>
</table>
<table width="100%">
<tr><th align="left">Vista</th><th align="left">Pregunta</th><th align="left">Qué muestra</th></tr>
<tr><td>Gerencia</td><td>¿Cómo está la cartera?</td><td>Clientes en riesgo, tendencias, zonas críticas, evolución agregada</td></tr>
<tr><td>Asesor</td><td>¿A quién debo atender?</td><td>Cola priorizada, razones, acción sugerida</td></tr>
<tr><td>Ficha del cliente</td><td>¿Por qué aparece esta alerta?</td><td>Línea base, cambios detectados, evidencia, recomendación</td></tr>
</table>
<table width="100%">
<tr><th align="left" width="50%">Antes</th><th align="left" width="50%">Después</th></tr>
<tr>
<td><i>"Tenemos modelos de machine learning, SHAP, optimización y arquitectura avanzada."</i></td>
<td><i>"Ayudamos al asesor a detectar qué clientes están cambiando, entender por qué y actuar antes de que aparezca la mora."</i></td>
</tr>
</table>
*La tecnología aparece como habilitador, nunca como protagonista del relato; el detalle técnico queda disponible para quien lo pida, pero no abre la presentación.*
 
<br>
---
 
<br>
**5. Experiencia del asesor**
 
La interfaz lleva al asesor de "ver datos" a "entender la situación y actuar". Toma como referencia de estilo —no de contenido ni de marca— la simplicidad visual de apps financieras modernas; el dashboard final lleva identidad propia de XSpectra-e, **sin logos ni marcas de terceros**.
 
<table width="100%">
<tr><td width="25%" valign="top"><b>Vista general de cartera</b></td><td>Pantalla inicial: clientes estables, en seguimiento y en atención prioritaria, más las acciones recomendadas del día. Es la versión operativa del punto D.</td></tr>
<tr><td valign="top"><b>Ficha inteligente del cliente</b></td><td>Historial de pagos y saldos, línea base propia (punto A) con la desviación actual en cifras, y ficha de evidencia (punto C): qué cambió, por qué importa, qué tan confiable es la alerta.</td></tr>
<tr><td valign="top"><b>Copiloto conversacional</b></td><td>Interfaz de preguntas y respuestas sobre la evidencia ya calculada por el motor — no decide, solo explica. Es el "agente explicador LLM con guardrails" previsto como <i>Should</i>.</td></tr>
<tr><td valign="top"><b>Cierre de cada alerta</b></td><td>Situación detectada, evidencia que la respalda (lista de verificación) y recomendación del catálogo de acciones — nunca solo una etiqueta de "cliente riesgoso".</td></tr>
</table>
<br>
 
---
 
<br>
**6. Concepto de solución — seis etapas**
 
Cada etapa sostiene una de las cuatro piezas del marco de evidencia: entender al cliente, filtrar el ruido, explicar el riesgo y priorizar la acción.
 
<table width="100%">
<tr><td align="center" width="90"><b>Etapa 1</b><br><sub>/automation + /security</sub></td><td><b>Ingesta segura.</b> Carga desde CSV/API. Validación estricta de esquema (Pydantic), neutralización de fórmulas (<code>= + - @</code>), rechazo de archivos con macros, tokenización de PII con HMAC-SHA256 con clave fuera del código. El analista y cualquier LLM ven solo tokens.</td></tr>
<tr><td align="center"><b>Etapa 2</b><br><sub>/data</sub></td><td><b>Línea base propia y señales.</b> Patrón habitual por ventana móvil, ajustado por estacionalidad y comparado con pares de rubro y zona, en cuatro familias: flujo, endeudamiento, comportamiento de pago, carga de la cuota.</td></tr>
<tr><td align="center"><b>Etapa 3</b><br><sub>/data</sub></td><td><b>Filtro de evidencia en tres niveles.</b> Ver tabla técnica abajo. Una variación que no supera los tres niveles se registra como fluctuación normal y no genera alerta.</td></tr>
<tr><td align="center"><b>Etapa 4</b><br><sub>/data</sub></td><td><b>Modelo calibrado con incertidumbre.</b> Gradient boosting (LightGBM/XGBoost) estima probabilidad de primer atraso a 30 días; calibración por regresión isotónica + intervalo conformal. Estados: Estable, Observación, Alerta preventiva, Información insuficiente. Explicación vía SHAP + comparación contra línea base.</td></tr>
<tr><td align="center"><b>Etapa 5</b><br><sub>/automation + /data</sub></td><td><b>Priorización y acción preventiva.</b> Optimizador que maximiza pérdida esperada evitada, sujeto a capacidad diaria de contacto. Catálogo de acciones: contacto preventivo, visita, orientación financiera, evaluación de reprogramación. Ninguna se ejecuta sin confirmación humana.</td></tr>
<tr><td align="center"><b>Etapa 6</b><br><sub>/security + /gen-ai</sub></td><td><b>Revisión humana, equidad y aprendizaje.</b> Asesor valida/descarta, supervisor aprueba, se registra el resultado. Log de auditoría append-only. Panel de equidad por grupo. Los descartes alimentan el reajuste futuro.</td></tr>
</table>
*Módulo opcional (Should): contagio relacional — un grafo (NetworkX) eleva la prioridad de un cliente cuando varios de sus vinculados (avales, mercado, proveedor) entran en alerta.*
 
<br>
**6.1 Filtro de evidencia — detalle técnico**
 
<table width="100%">
<tr><th align="left">Nivel</th><th align="left">Pregunta</th><th align="left">Técnica</th></tr>
<tr><td><b>N1 · Desviación relevante</b></td><td>¿Se aparta más de lo que explican su estacionalidad y sus pares?</td><td>Z-score robusto (mediana/MAD) contra línea base estacional</td></tr>
<tr><td><b>N2 · Persistencia</b></td><td>¿El cambio es sostenido o un pico aislado?</td><td>CUSUM / detección de punto de cambio</td></tr>
<tr><td><b>N3 · Corroboración</b></td><td>¿Lo confirman al menos dos familias de señales independientes?</td><td>Regla de corroboración sobre las cuatro familias</td></tr>
</table>
> **Por qué no es un chatbot, un dashboard ni una automatización básica:** el valor está en el motor analítico — línea base propia, detección de cambios sostenidos, probabilidad calibrada con incertidumbre y optimización de la intervención. La interfaz y el LLM solo presentan y explican lo que el motor calculó.
 
<br>
---
 
<br>
**7. Tecnología preexistente**
 
<table width="100%">
<tr><th align="left">Componente</th><th align="left">Titularidad</th><th align="left">Licencia / condición</th></tr>
<tr><td>Python, Pandas, NumPy, SciPy, scikit-learn, Pydantic</td><td>Terceros (open source)</td><td>BSD / MIT</td></tr>
<tr><td>LightGBM, XGBoost, SHAP, MAPIE, Fairlearn, OR-Tools</td><td>Terceros (open source)</td><td>MIT / BSD / Apache 2.0</td></tr>
<tr><td>FastAPI, Next.js, shadcn/ui, PostgreSQL, NetworkX</td><td>Terceros (open source)</td><td>MIT / BSD / PostgreSQL License</td></tr>
<tr><td>LLM vía API (opcional)</td><td>Terceros (servicio)</td><td>Sujeto a lineamientos de Caja Trujillo sobre IA externa; sin PII; plan de respaldo por plantilla</td></tr>
<tr><td><b>Función de tokenización HMAC y esqueleto del pipeline de ingesta</b></td><td>Equipo (desarrollo propio previo)</td><td>Preexistente, declarado</td></tr>
<tr><td><b>Generador sintético v0 (esquema de clientes y tokenización)</b></td><td>Equipo (desarrollo propio previo)</td><td>Preexistente, declarado</td></tr>
</table>
> **Sobre el nombre:** «XSpectra» coincide con una marca registrada de XNEXT S.P.A. en equipos de rayos X. «XSpectra-e» se usa solo como nombre de proyecto del hackathon, sin uso comercial. Antes de la entrega se confirmará por escrito la búsqueda en INDECOPI y se tendrá lista una alternativa de nombre.
 
<br>
---
 
<br>
**8. Enfoque de ciberseguridad**
 
La seguridad se trata como *seguridad desde el diseño*, no como protagonista del relato.
 
```
CSV / API (datos sintéticos)
 → [1 Ingesta segura · FastAPI]   validación, sanitización, tokenización HMAC
 → [2 Señales]                   línea base propia + ajuste estacional y de pares
 → [3 Filtro de evidencia]       desviación → persistencia (CUSUM) → corroboración
 → [4 Modelo]                    LightGBM + calibración + intervalo conformal
 → [5 Priorización]              optimización con capacidad + catálogo de acciones
 → [6 Interfaz · Next.js]        cola, ficha de evidencia, equidad; Asesor → Supervisor
 → [PostgreSQL]                  decisiones y log append-only
 
 Opcionales: agente explicador LLM con guardrails · contagio relacional (NetworkX)
```
 
<table width="100%">
<tr><th align="left">Exigencia</th><th align="left">Control en XSpectra-e</th></tr>
<tr><td>Protección de datos personales</td><td>Solo datos sintéticos; tokenización HMAC-SHA256 con clave fuera del código; bóveda de PII separada; ninguna PII en logs ni en prompts; RBAC con mínimo privilegio</td></tr>
<tr><td>Evitar sesgos</td><td>Atributos sensibles excluidos del modelo; rubro/zona solo para ajuste estacional, auditados; panel de equidad por grupo</td></tr>
<tr><td>Considerar la incertidumbre</td><td>Calibración, intervalos conformales, estados «observación» e «información insuficiente»</td></tr>
<tr><td>Evidencia y pocos falsos positivos</td><td>Filtro de tres niveles, ficha contra patrón propio, casos señuelo estacionales en validación</td></tr>
<tr><td>Revisión humana, sin decisiones automáticas</td><td>El sistema solo prioriza y sugiere; toda acción requiere confirmación y queda registrada</td></tr>
</table>
> **Nota de rigor:** un SHA-256 simple sobre un DNI es reversible por fuerza bruta (10⁸ combinaciones); por eso se usa HMAC con clave secreta. Los controles se presentan como principios aplicados en el prototipo, no como cumplimiento certificado — alineado a la Ley 29733 y la Res. SBS 504-2021, sin afirmar certificación.
 
<br>
---
 
<br>
**9. Funcionalidad crítica y guion de demo**
 
El guion gira en torno a un cliente microempresario con historial estable, un cambio progresivo, detección temprana, explicación del riesgo y recomendación de acción preventiva.
 
<table width="100%">
<tr><th align="center" width="60">#</th><th align="left">Desarrollo a demostrar de punta a punta</th></tr>
<tr><td align="center">1</td><td>Panel sintético longitudinal (24 meses) con estacionalidad por rubro, deterioros inyectados y casos señuelo</td></tr>
<tr><td align="center">2</td><td>Motor de señales y filtro de tres niveles contra línea base propia</td></tr>
<tr><td align="center">3</td><td>Modelo calibrado con incertidumbre y backtest temporal</td></tr>
<tr><td align="center">4</td><td>Optimizador de priorización por capacidad + simulador de impacto</td></tr>
<tr><td align="center">5</td><td>Ficha de evidencia y revisión humana con log de auditoría visible</td></tr>
</table>
**9.1 Guion cronometrado (5 min)**
 
<table width="100%">
<tr><th align="left">Momento</th><th align="left">Qué se demuestra</th><th align="left" width="80">Tiempo</th></tr>
<tr><td>1 · Datos y seguridad</td><td>Carga del panel sintético, tokenización visible, rechazo de carga con fórmulas maliciosas</td><td>45 s</td></tr>
<tr><td>2 · Señal contra ruido</td><td>Cliente con caída estacional (no alerta) vs. deterioro sostenido (alerta), con los 3 niveles</td><td>1 min</td></tr>
<tr><td>3 · Cola priorizada</td><td>Cola ordenada por pérdida evitable y capacidad; ficha con evidencia, intervalo y acción sugerida</td><td>1 min 15 s</td></tr>
<tr><td>4 · Revisión humana</td><td>Asesor valida, supervisor aprueba, log muestra ambos usuarios</td><td>45 s</td></tr>
<tr><td>5 · Evidencia de valor</td><td>Backtest contra el semáforo, panel de equidad y simulador de impacto</td><td>1 min</td></tr>
</table>
<br>
---
 
<br>
**10. Alcance priorizado (MoSCoW)**
 
<img src="https://img.shields.io/badge/MUST-c0392b?style=flat-square"/> &nbsp;
<img src="https://img.shields.io/badge/SHOULD-e0a829?style=flat-square"/> &nbsp;
<img src="https://img.shields.io/badge/COULD-2980b9?style=flat-square"/> &nbsp;
<img src="https://img.shields.io/badge/WON'T-7f8c8d?style=flat-square"/>
 
<table width="100%">
<tr><td align="center" width="90"><img src="https://img.shields.io/badge/MUST-c0392b?style=flat-square"/></td><td>Ingesta con tokenización · generador v1 con señuelo · señales y filtro de tres niveles · modelo con calibración y backtest · cola priorizada con optimizador · ficha de evidencia · revisión Asesor → Supervisor · log de auditoría</td></tr>
<tr><td align="center"><img src="https://img.shields.io/badge/SHOULD-e0a829?style=flat-square"/></td><td>Intervalo conformal y estado de información insuficiente · panel de equidad · simulador de impacto · explicación por LLM con guardrails · módulo de contagio relacional</td></tr>
<tr><td align="center"><img src="https://img.shields.io/badge/COULD-2980b9?style=flat-square"/></td><td>Hash chain en el log · rol Auditor con vista propia · carga de .xlsx · reentrenamiento con feedback</td></tr>
<tr><td align="center"><img src="https://img.shields.io/badge/WON'T-7f8c8d?style=flat-square"/></td><td>Integración con el core bancario, tiempo real, redes neuronales de grafos</td></tr>
</table>
*La priorización garantiza que el flujo de punta a punta funcione aunque el bloque Should o Could no llegue a tiempo.*
 
<br>
---
 
<br>
**11. Cronograma y roles**
 
<table width="100%">
<tr><th align="left">Momento</th><th align="left">Hito</th><th align="left">Responsables</th></tr>
<tr><td>Inmersión tecnológica (01.12)</td><td>Repositorio, contratos de API y esquemas, CI; sin código de funcionalidad nueva</td><td>Todo el equipo</td></tr>
<tr><td>Jornada 1 · mañana</td><td>Generador v1 con señuelo; ingesta y tokenización; señales y línea base</td><td>Jorge, Gerard</td></tr>
<tr><td>Jornada 1 · tarde</td><td>Filtro de tres niveles; modelo y backtest; esqueleto de la interfaz</td><td>Jorge, Grasiani, Julio</td></tr>
<tr><td>Jornada 2 · mañana</td><td>Calibración e incertidumbre; optimizador y acciones; ficha de evidencia; revisión y log</td><td>Gerard, Grasiani, Julio</td></tr>
<tr><td>Jornada 2 · tarde</td><td>Equidad, simulador, integración y pruebas; ensayo; video plan B; congelar versión</td><td>Todo el equipo</td></tr>
</table>
**11.1 Roles**
 
<table width="100%">
<tr><td width="25%"><b>Jorge</b><br><sub>Data Scientist y Negocio</sub></td><td>Generador, línea base, filtro, modelo, backtest, KPIs e impacto</td></tr>
<tr><td><b>Grasiani</b><br><sub>ML, UX/UI y Ciberseguridad</sub></td><td>Calibración y equidad, diseño de la ficha, PII y guardrails</td></tr>
<tr><td><b>Gerard</b><br><sub>Backend e IA</sub></td><td>FastAPI, ingesta, optimizador, auditoría, explicador opcional</td></tr>
<tr><td><b>Julio</b><br><sub>Frontend</sub></td><td>Cola, ficha, revisión y auditoría en la interfaz</td></tr>
</table>
<br>
---
 
<br>
**12. Riesgos y mitigaciones**
 
<table width="100%">
<tr><th align="left">Riesgo</th><th align="left">Mitigación</th></tr>
<tr><td>Alcance excesivo para dos jornadas</td><td>Prioridad Must; contratos de API definidos antes; plan B de interfaz en Streamlit</td></tr>
<tr><td>Datos de Caja Trujillo no disponibles</td><td>Generador sintético propio; no se depende de entregas externas</td></tr>
<tr><td>Modelo sobreajustado a datos sintéticos</td><td>Se declara como limitación; backtest temporal; señuelos estacionales</td></tr>
<tr><td>API del LLM no disponible o no permitida</td><td>Explicación por plantilla determinista con el mismo formato de evidencia</td></tr>
<tr><td>Internet lento en la sala</td><td>Demo local y video plan B</td></tr>
<tr><td>Definición del KPI distinta a la propuesta</td><td>Se confirma con el Challenge Owner; métricas recalculadas con el generador</td></tr>
<tr><td>Objeción sobre el nombre</td><td>Alternativa de nombre preparada</td></tr>
<tr><td>Exceso de tecnicismo en la presentación</td><td>Guion centrado en el caso del microempresario; detalle técnico disponible pero no protagonista</td></tr>
</table>
<br>
---
 
<br>
**13. Impacto esperado y KPIs**
 
<table width="100%">
<tr><th align="left">Enfoque convencional</th><th align="left">XSpectra-e</th></tr>
<tr><td>Semáforo por días de mora (reactivo)</td><td>Alerta antes del primer atraso</td></tr>
<tr><td>Umbral fijo igual para todos</td><td>Línea base propia y estacional por cliente</td></tr>
<tr><td>Toda variación es alerta</td><td>Filtro de tres niveles; la fluctuación normal no alerta</td></tr>
<tr><td>Un puntaje sin explicación</td><td>Probabilidad calibrada, intervalo y evidencia contra su patrón</td></tr>
<tr><td>Lista larga sin orden de acción</td><td>Cola priorizada por capacidad y pérdida evitable</td></tr>
<tr><td>Decisión implícita</td><td>Revisión humana obligatoria y trazabilidad</td></tr>
</table>
**13.1 Indicadores técnicos propuestos**
 
<table width="100%">
<tr><th align="left">Indicador</th><th align="left">Definición</th><th align="left">Meta de aceptación</th></tr>
<tr><td><b>Anticipación</b></td><td>Mediana de días entre la alerta preventiva y el primer atraso</td><td>≥ 14 días</td></tr>
<tr><td><b>Precisión en la cola</b> (precision@K)</td><td>Proporción de los K casos priorizados que luego caen en atraso</td><td>≥ 2× la línea base</td></tr>
<tr><td><b>Falsas alertas por estacionalidad</b></td><td>Clientes con caída estacional normal que terminan en alerta</td><td>≤ 10 % de casos señuelo</td></tr>
<tr><td><b>Calibración</b> (ECE)</td><td>Error de calibración esperado</td><td>≤ 0,05</td></tr>
<tr><td><b>Equidad</b></td><td>Diferencia de tasa de falsos positivos entre grupos</td><td>≤ 5 puntos porcentuales</td></tr>
</table>
**13.2 Indicadores de negocio**
 
<table width="100%">
<tr><td width="33%" valign="top"><b>Operativos</b><br>— Tiempo promedio de revisión<br>— N° clientes priorizados<br>— Casos atendidos preventivamente</td>
<td width="33%" valign="top"><b>Riesgo</b><br>— Anticipación antes de mora<br>— Precisión de alertas<br>— Reducción de falsos positivos</td>
<td valign="top"><b>Cliente</b><br>— Contactos preventivos realizados<br>— Clientes recuperados<br>— Seguimientos exitosos</td></tr>
</table>
> **Nota de rigor:** las métricas sobre datos sintéticos validan el pipeline, no el desempeño real; el siguiente paso es un piloto con datos de Caja Trujillo en entorno controlado. La efectividad de las acciones es un supuesto editable expuesto en el simulador de impacto — no se afirma una cifra de ahorro antes de medirla en un piloto.
 
<br>
---
 
<br>
**14. Repositorios y stack técnico**
 
<table width="100%">
<tr><th align="left">Repositorio</th><th align="left">Stack</th><th align="left">Propósito</th></tr>
<tr><td><a href="https://github.com/open-code-cajathon/xspectra-e-frontend"><code>xspectra-e-frontend</code></a></td><td>Next.js · shadcn/ui · Vercel</td><td>Cola, ficha de evidencia, revisión, auditoría</td></tr>
<tr><td><a href="https://github.com/open-code-cajathon/xspectra-e-backend"><code>xspectra-e-backend</code></a></td><td>Python · FastAPI · Railway</td><td>Ingesta, señales, modelo, optimización</td></tr>
<tr><td><a href="https://github.com/open-code-cajathon">Organización</a></td><td>—</td><td>Acceso centralizado a repos y miembros</td></tr>
</table>
> Repositorios privados. Solicitar acceso a los responsables técnicos antes de la fase presencial.
 
**14.1 Capas tecnológicas**
 
<table width="100%">
<tr><th align="left">Capa</th><th align="left">Tecnología</th><th align="left">Función</th></tr>
<tr><td>Ingesta</td><td>FastAPI, Pandas, Pydantic</td><td>Validación, sanitización, tokenización</td></tr>
<tr><td>Señales y filtro</td><td>Python, NumPy, SciPy</td><td>Línea base, z-score robusto, CUSUM</td></tr>
<tr><td>Modelo</td><td>LightGBM/XGBoost, scikit-learn, SHAP, MAPIE</td><td>Probabilidad calibrada, incertidumbre, explicabilidad</td></tr>
<tr><td>Optimización</td><td>OR-Tools o SciPy</td><td>Asignación bajo capacidad</td></tr>
<tr><td>Equidad</td><td>Fairlearn</td><td>Métricas por grupo</td></tr>
<tr><td>Interfaz</td><td>Next.js, shadcn/ui (plan B: Streamlit)</td><td>Cola, ficha, revisión, auditoría</td></tr>
<tr><td>Persistencia</td><td>PostgreSQL</td><td>Decisiones y log append-only</td></tr>
<tr><td>Explicación (opcional)</td><td>LLM con guardrails</td><td>Redacta la ficha a partir de evidencia estructurada</td></tr>
</table>
<br>
---
 
<br>
**15. Reglas de colaboración**
 
<table width="100%">
<tr><td width="40">01</td><td>Trabajo asincrónico por defecto</td></tr>
<tr><td>02</td><td>Toda tarea tiene responsable, prioridad y criterio de terminado</td></tr>
<tr><td>03</td><td>Ningún cambio se integra sin revisión (PR) y pruebas ejecutadas</td></tr>
<tr><td>04</td><td>Cambios en contratos de API se coordinan entre ambos desarrolladores</td></tr>
<tr><td>05</td><td>Todo componente preexistente se declara explícitamente</td></tr>
<tr><td>06</td><td>Nada se marca como terminado sin evidencia</td></tr>
</table>
<table width="100%">
<tr><th align="left">Herramienta</th><th align="left">Uso</th></tr>
<tr><td>GitHub</td><td>Código, pull requests, pruebas y evidencia técnica</td></tr>
<tr><td>Notion</td><td>Organización de tareas y decisiones</td></tr>
<tr><td>Chat del equipo</td><td>Coordinación asincrónica</td></tr>
<tr><td>Vercel / Railway</td><td>Despliegue de frontend y backend</td></tr>
</table>
**15.1 Seguridad y confidencialidad**
 
<table width="100%">
<tr><td width="90" align="center"><b>Prohibido</b></td><td>Subir datos personales reales o información restringida sin autorización</td></tr>
<tr><td align="center"><b>Prohibido</b></td><td>Publicar secretos, claves de API o credenciales</td></tr>
<tr><td align="center"><b>Prohibido</b></td><td>Divulgar material confidencial del desafío</td></tr>
<tr><td align="center"><b>Prohibido</b></td><td>Usar IA externa con información restringida sin autorización</td></tr>
<tr><td align="center"><b>Obligatorio</b></td><td>Acceso mínimo necesario (RBAC) a cada repositorio</td></tr>
</table>
<br>
---
 
<br>
**16. Cumplimiento con las bases del Cajathon**
 
*Referencia: Bases oficiales V4, revisión 05/11/2026. Verificar actualizaciones.*
 
<table width="100%">
<tr><th align="left">Requisito</th><th align="left">Cómo se cumple</th><th align="left" width="110">Estado</th></tr>
<tr><td>3.3 Solution Concept con 8 componentes</td><td>Este documento</td><td><img src="https://img.shields.io/badge/Listo-2ecc71?style=flat-square"/></td></tr>
<tr><td>3.3 / 8.3 Tecnología preexistente identificada</td><td>Componente 5</td><td><img src="https://img.shields.io/badge/Listo-2ecc71?style=flat-square"/></td></tr>
<tr><td>8.2 Sin datos personales reales ni credenciales</td><td>Solo datos sintéticos y PII masking</td><td><img src="https://img.shields.io/badge/Listo-2ecc71?style=flat-square"/></td></tr>
<tr><td>8.2 Restricciones sobre herramientas de IA externas</td><td>LLM opcional, sin PII, plantilla de respaldo; se consultará al Caja Expert de Seguridad</td><td><img src="https://img.shields.io/badge/Por%20confirmar-e0a829?style=flat-square"/></td></tr>
<tr><td>4.2 Evidencia de desarrollo</td><td>Repositorio con ramas, commits fechados y CI</td><td><img src="https://img.shields.io/badge/Durante%20el%20hackathon-2980b9?style=flat-square"/></td></tr>
<tr><td>5.2 Funcionalidad crítica demostrable</td><td>Cinco funcionalidades con demo en vivo y plan B</td><td><img src="https://img.shields.io/badge/Durante%20el%20hackathon-2980b9?style=flat-square"/></td></tr>
<tr><td>8.1 Derechos de terceros y no plagio</td><td>Licencias declaradas; verificación del nombre</td><td><img src="https://img.shields.io/badge/Pendiente-c0392b?style=flat-square"/></td></tr>
</table>
**16.1 Alineación con la rúbrica — Fase 1**
 
- No mostrar demasiadas tecnologías sin evidencia funcional de respaldo
- No presentar un dashboard genérico; cada pantalla responde una pregunta del asesor
- No dejar la IA como caja negra: toda alerta debe explicarse
- No dejar que la ciberseguridad ocupe más espacio que la detección, explicación y priorización
- No agregar complejidad (Should/Could) que no pueda demostrarse en vivo
**16.2 Alineación con la rúbrica — Fase 2 (evaluación final)**
 
<table width="100%">
<tr><th align="left">Criterio</th><th align="left" width="70">Peso</th><th align="left">Cómo responde XSpectra-e</th></tr>
<tr><td>Alineación al desafío</td><td>25 %</td><td>Deterioro gradual, distinción señal/fluctuación, priorización preventiva</td></tr>
<tr><td>Impacto potencial</td><td>30 %</td><td>KPIs con línea base de comparación, anticipación medible, pérdida evitable con supuestos explícitos</td></tr>
<tr><td>Viabilidad técnica</td><td>25 %</td><td>Línea base, CUSUM, boosting calibrado, conformal, optimización — con límites declarados</td></tr>
<tr><td>Factibilidad de construcción</td><td>20 %</td><td>Alcance priorizado, preexistente declarado, plan por jornada, planes B</td></tr>
</table>
<table width="100%">
<tr><th align="left">Criterio</th><th align="left" width="70">Peso</th><th align="left">Evidencia prevista</th></tr>
<tr><td>Impacto potencial en el negocio</td><td>35 %</td><td>Backtest contra el semáforo, cola por pérdida evitable, simulador de impacto</td></tr>
<tr><td>Funcionalidad y validación técnica</td><td>35 %</td><td>Demo en vivo (mínimo 3/5), backtest, calibración, pruebas y repositorio</td></tr>
<tr><td>Innovación y calidad</td><td>20 %</td><td>Línea base propia, filtro de tres niveles, priorización por capacidad</td></tr>
<tr><td>Presentación y demostración</td><td>10 %</td><td>Guion de 5 minutos centrado en el caso del microempresario</td></tr>
</table>
<br>
---
 
<br>
**17. Limitaciones declaradas**
 
- Las métricas sobre datos sintéticos validan el pipeline, **no el desempeño real**; el siguiente paso es un piloto con datos de Caja Trujillo en entorno controlado.
- Las metas de aceptación y la efectividad de las acciones son **supuestos a calibrar**.
- El sistema **no toma decisiones crediticias**; cualquier cambio de condiciones corresponde a las instancias de Caja Trujillo.
<br>
---
 
<br>
**18. Definición de terminado**
 
Una funcionalidad se considera terminada únicamente cuando cumple, sin excepción, lo siguiente:
 
<table width="100%">
<tr><td width="40" align="center">☐</td><td>Cumple sus criterios de aceptación</td></tr>
<tr><td align="center">☐</td><td>Tiene pruebas ejecutadas</td></tr>
<tr><td align="center">☐</td><td>Está integrada donde corresponde</td></tr>
<tr><td align="center">☐</td><td>No introduce riesgos de seguridad sin gestionar</td></tr>
<tr><td align="center">☐</td><td>Cuenta con evidencia de funcionamiento</td></tr>
<tr><td align="center">☐</td><td>Sus limitaciones están documentadas</td></tr>
</table>
<br>
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,8,12&height=90&section=footer" width="100%"/>
<div align="center">
**Cumplimiento + impacto medible + funcionalidad verificada + ejecución disciplinada**
 
<sub>Documento vivo — se actualiza conforme avanza el proyecto · Basado en Solution Concept v6</sub>
 
</div>
 
