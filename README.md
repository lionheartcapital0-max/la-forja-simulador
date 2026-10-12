# La Forja — Simulador y Evaluador Diario

Herramienta de formación de **La Forja**: simulador de escenarios operativos con evaluación asistida por IA.

## Qué hace

- **Evaluador Diario** (`index.html`): 22 escenarios, días 1–90, temporizador y envío a evaluación con un clic.
- **Biblioteca de Pruebas** (`pruebas.html`): 14 pruebas de formato para práctica diaria.

## Cómo funciona

1. El alumno responde un escenario en la página (100% estática, sin servidor).
2. Al pulsar **ENVIAR PARA EVALUACIÓN**, la respuesta viaja al backend.
3. Gemini evalúa: veredicto (APROBADO / NO APROBADO), fallo observado, consejos y orden de mejora.
4. El resultado se guarda en una hoja de cálculo y el alumno ve su evaluación al instante.

## Arquitectura

- **Frontend:** HTML/CSS/JS estático → GitHub Pages (carga sin VPN).
- **Backend:** Google Apps Script + Gemini API + Google Sheets.
- Sin dependencias, sin build, sin servidor que mantener.

## Uso

Abrir https://lionheartcapital0-max.github.io/la-forja-simulador/ — no requiere instalación.

---

Parte del programa **La Forja** — formación de operadores. El operador convierte problemas en capacidad.
