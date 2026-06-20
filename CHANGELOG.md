# Registro de cambios

Formato basado en [Keep a Changelog](https://keepachangelog.com/es-ES/).
Versionado siguiendo [SemVer](https://semver.org/lang/es/).

## [1.3.3] — 2026-06-20
### Agregado
- Presets de valor hora ($180 a $400) con un clic.
### Cambiado
- Valor hora por defecto al cargar la página: $200.

## [1.3.2] — 2026-06-20
### Cambiado
- Nombre del sitio: "En Regla", con bajada "Calculá el costo real de formalizar trabajo doméstico en Uruguay" (encabezado, título de pestaña, OpenGraph, impresión y resumen).

## [1.3.1] — 2026-06-20
### Quitado
- Paneles "Hogar: varias personas", "Costo de regularizar atrasos (retroactivo)" y "Calculadora inversa".

## [1.3.0] — 2026-06-20
### Agregado
- Presets de frecuencia (1 a 4 días/semana, medio horario, jornada, máximo) que fijan las horas con un clic.
- Panel "Beneficios de formalizar" reforzado, en dos columnas (trabajador/a y empleador/a), con montos dinámicos de aportes jubilatorios, aguinaldo y licencia.
### Cambiado
- El panel "Lo que dejás de arriesgar" se integra al nuevo panel de beneficios.

## [1.2.1] — 2026-06-20
### Cambiado
- Scroll simplificado: un único scroll de página (se quitaron las dos columnas con scroll propio); el resumen sigue fijo arriba.
- Encabezado más compacto (título, marca y márgenes reducidos).
- "Normativa y fuentes", "Pasos para dar el alta" y "Glosario" se reorganizan en un pie de página único junto con la nota legal.

## [1.2.0] — 2026-06-20
### Agregado
- **Modo oscuro** con toggle (recuerda la preferencia).
- **Resumen fijo (sticky)** con informal/formal/diferencia y selector **mensual/anual**.
- **Animación de cifras** (count-up) en los números principales, respetando `prefers-reduced-motion`.
- **Tooltips con fuente** en términos técnicos (FONASA, antigüedad, presentismo, día del trabajador) enlazando a la norma.
- **Favicon** propio, **OpenGraph** para previsualización al compartir, y mejoras de **accesibilidad** (foco visible, aria-labels).
- **Aportes sobre el aguinaldo** (y demás cargas) para un costo formal más exacto.
- **IRPF estimado** por franjas en BPC (se descuenta del líquido si aplica).
- **Selector de categoría** I/II/III.
- **Hogar: varias personas**, con totales del hogar.
- **Indicadores**: tasa efectiva de aportes y costo efectivo por hora.
- **Validaciones** (horas > 44, valores inválidos, nominal bajo el mínimo).
- **Sello de vigencia** y BPC editable en un solo lugar.
- **Copiar resumen en texto** y **exportar CSV** (desglose + proyección).
### Mejorado
- Impresión/PDF con encabezado y fecha; se ocultan controles e interactivos.

## [1.1.1] — 2026-06-19
### Corregido
- Scroll independiente para cada columna en escritorio: la columna de ajustes y la de resultados ahora se desplazan por separado dentro de la altura de la ventana, en lugar de compartir el scroll de la página.

## [1.1.0] — 2026-06-19
### Cambiado
- Rediseño visual completo: estética **minimalista monocromática** con paleta basada en el azul institucional de BPS.
- Nueva tipografía editorial: serif para títulos y cifras, monoespaciada para etiquetas y datos (sin fuentes genéricas y sin dependencias externas).
- Superficies planas, líneas finas y sin sombras; gráfico y componentes recoloreados a la paleta azul.

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
