---
slug: es-es/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** pone GitHub Copilot en tu terminal como asistente de programación con agentes. Explora bases de código, genera código, ejecuta comandos y se conecta a herramientas externas, todo desde la línea de comandos para que puedas mantener el flujo sin cambiar a un editor gráfico.

El taller sigue un flujo de trabajo continuo en Tailspin Toys: prepara el proyecto en GitHub Codespaces, añade valoraciones con estrellas y combina el primer pull request (PR), y después implementa el filtrado con instrucciones, habilidades, herramientas MCP, un agente de QA y Agent Merge. Terminarás explorando los comandos de barra y revisando formas de reutilizar lo aprendido.

## Ejercicios

| Ejercicio | Tema | Descripción |
|----------|-------|-------------|
| [0. Requisitos previos][ex0] | Configuración | Prepara el proyecto y tu Codespace |
| [1. Instala Copilot CLI][ex1] | Instalación | Instala Copilot CLI, inicia sesión y familiarízate con la herramienta |
| [2. Añade valoraciones con estrellas][ex2] | Primer cambio | Muestra las valoraciones existentes y combina tu primer PR |
| [3. Modos de agente: Plan y Autopilot][ex3] | Modos de agente | Planifica la funcionalidad desde su incidencia, impleméntala con Autopilot y revísala en Interactive |
| [4. Guía a Copilot con instrucciones personalizadas][ex4] | Contexto | Actualiza las instrucciones y aplícalas al filtrado |
| [5. Personaliza y usa una habilidad quality-checks][ex5] | Comprobaciones repetibles | Actualiza el formato del informe de la habilidad y ejecuta las comprobaciones |
| [6. Valida la funcionalidad con Playwright MCP][ex6] | Observación en el navegador | Configura MCP en CLI e inspecciona el filtrado |
| [7. Crea y usa un agente de QA][ex7] | Requisitos y cobertura | Revisa los requisitos, la cobertura y las pruebas de verificación |
| [8. Crea y combina el PR de la funcionalidad][ex8] | Revisión y combinación | Revisa el cambio completo y usa Agent Merge |
| [9. Comandos de barra en GitHub Copilot CLI][ex9] | Funciones de CLI | Explora el contexto, los modelos, el uso compartido y la delegación opcional |
| [10. Resumen y próximos pasos][ex10] | Resumen | Repasa el flujo de trabajo, las personalizaciones reutilizables y otros recursos |
| [Opcional: incorpora Foundry][foundry] | Agentes hospedados | Prepara un modelo, despliega un agente basado en catálogo y conéctalo al sitio web |

## Requisitos previos

Antes de asistir a este taller, asegúrate de tener:

- [ ] Una cuenta de GitHub con un plan activo de **Copilot Student, Pro, Pro+, Business o Enterprise**
- [ ] Permiso para crear un repositorio y un Codespace
- [ ] Conocimientos básicos de operaciones de terminal o línea de comandos

> [!TIP]
> ¿No tienes un plan de pago? Los estudiantes verificados pueden obtener GitHub Copilot gratis a través de [GitHub Education][callout-student-plan-education]. El plan **Copilot Student** incluye las funciones de agente, MCP, revisión de código y Copilot CLI que utiliza este taller, así que puedes completar con él todos los recorridos.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Si usas Copilot Business o Copilot Enterprise, asegúrate de que tu administrador haya habilitado Copilot CLI.

## Primeros pasos

**[Empieza con el ejercicio 0: Requisitos previos →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
