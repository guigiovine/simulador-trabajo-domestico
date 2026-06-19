# Simulador de trabajo doméstico — Informal vs. Formal (Uruguay)

Herramienta web de un solo archivo para comparar lo que cuesta pagar a una persona
de trabajo doméstico **en la mano** (informal) frente al costo real de **formalizarla**
con todos los aportes ante BPS (Grupo 21).

Sirve igual sea él o ella. Es completamente **autocontenida**: un único `index.html`
sin dependencias externas (ni librerías, ni fuentes remotas). Se abre en cualquier
navegador, también sin internet.

## Qué calcula

- Sueldo nominal vs. líquido, aportes personales y patronales, y costo total para el empleador.
- Tres modos al formalizar: **mantener el líquido**, **equilibrar** (deslizador ajustable) o **tomar el valor como nominal**.
- Cargas anuales (aguinaldo, licencia, salario vacacional, presentismo) ubicadas en su mes real.
- Prima por antigüedad, nocturnidad, horas extra y día del trabajador doméstico.
- Gráfico de evolución del gasto acumulado en el tiempo, con ajustes salariales semestrales.
- Costo de regularizar atrasos (retroactivo), "qué gana la persona" y calculadora inversa.
- Paneles de normativa con enlaces oficiales, glosario y checklist del trámite.

## Cómo usarla

Abrí `index.html` con doble clic, o publicala con GitHub Pages (ver abajo) para tener un enlace.

## Aviso

Estimación orientativa con valores del laudo del Grupo 21 vigentes desde enero de 2026.
No reemplaza el cálculo oficial ni asesoramiento profesional. Para montos exactos,
usá el Simulador de aportes de BPS o llamá al 0800 2001 (opción 2).

## Publicar como sitio (GitHub Pages)

1. En el repo: **Settings → Pages**.
2. En "Build and deployment", Source: **Deploy from a branch**.
3. Branch: `main` y carpeta `/ (root)`. Guardar.
4. En un minuto queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Licencia

MIT — ver [LICENSE](LICENSE).
