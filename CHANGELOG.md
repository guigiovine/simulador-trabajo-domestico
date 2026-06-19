# Registro de cambios

Formato basado en [Keep a Changelog](https://keepachangelog.com/es-ES/).
Versionado siguiendo [SemVer](https://semver.org/lang/es/).

## [1.0.0] — 2026-06-19
### Agregado
- Modo intermedio **"Equilibrar"** con deslizador ajustable (0–100%) para repartir el peso de los aportes entre empleador y trabajador/a.
### Cambiado
- Proyecto **100% autocontenido**: se eliminó la dependencia de Google Fonts; ahora usa fuentes del sistema. Sin recursos externos.
### Quitado
- Funcionalidades de guardar escenario, estimador de riesgo de informalidad y comparador de escenarios.

## [0.6.1] — 2026-06-19
### Corregido
- Error `SecurityError` al actualizar la URL dentro del iframe de vista previa; el armado del enlace ahora está protegido y solo ocurre al copiar.

## [0.6.0] — 2026-06-19
### Agregado
- Cálculo fino: prima por antigüedad, presentismo, nocturnidad, horas extra y día del trabajador doméstico.
- Costo de regularizar atrasos (retroactivo), panel "qué gana la persona" y calculadora inversa.
- Proyección plurianual con ajustes salariales semestrales.
- Paneles de normativa con enlaces oficiales, glosario y checklist del trámite.
- Exportar/imprimir (PDF) y compartir escenario por enlace.

## [0.5.0] — 2026-06-19
### Corregido
- Los interruptores (toggles) de cargas anuales no respondían al clic; se corrigió usando `label`.

## [0.4.0] — 2026-06-19
### Agregado
- Los gastos extra (aguinaldo en junio/diciembre, licencia y salario vacacional en el mes de vacaciones) se reflejan en su mes real.
- Opción para que el escenario informal también incluya aguinaldo y licencia.

## [0.3.0] — 2026-06-19
### Agregado
- Gráfico de evolución del gasto acumulado en el tiempo, con tooltip mes a mes.

## [0.2.0] — 2026-06-19
### Cambiado
- Lenguaje neutro: la herramienta sirve igual para cualquier trabajador/a, sea él o ella.

## [0.1.0] — 2026-06-19
### Agregado
- Versión inicial: comparación informal vs. formal, cálculo de aportes y dos modos de formalización.
