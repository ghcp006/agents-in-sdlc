---
title: "Lección 12 - Publica el sitio con GitHub Pages"
description: "Usa la aplicación GitHub Copilot para configurar un flujo de trabajo de Pages, revisar su pull request y verificar el Space Quiz publicado."
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Publica el Space Quiz para que cualquiera pueda acceder. Copilot puede preparar el flujo de trabajo y guiar el despliegue, pero tú debes revisar los cambios y confirmar que el sitio está disponible.

En esta lección:

- pedirás a Copilot que configure el despliegue con GitHub Pages;
- revisarás el flujo de trabajo y el pull request antes de combinarlo;
- seguirás el despliegue y comprobarás el sitio publicado.

## Escenario

El Space Quiz ya está en un repositorio de GitHub, pero la gente necesita una forma sencilla de probarlo. Publicar el sitio de un solo archivo con GitHub Pages lo hace accesible desde una URL pública sin añadir un servidor ni una dependencia de ejecución.

## Pide a Copilot que despliegue el sitio

En la sesión de la aplicación Copilot para `space-quiz`, envía este prompt:

```plaintext
Enable GitHub Pages for this repository. Create a GitHub Actions workflow that builds the website if needed and deploys it to GitHub Pages. Add a README describing the app and how to run it locally if one does not already exist. Create a pull request with these changes and merge it after required checks pass. Monitor the deployment until it succeeds, then report the final URL of the live website. If you lack permission to enable Pages or merge, tell me exactly what I need to approve or do; do not report success until the site is live.
```

![Diagrama de tres etapas: un pull request combinado de space-quiz; una ejecución correcta de GitHub Actions para desplegar el sitio con los pasos Build website, Upload artifact y Deploy to Pages; y el Space Quiz publicado en yourname.github.io/space-quiz/.](../../../_images/first-steps-app-pages-deploy.svg)

> [!WARNING]
> Este prompt pide al agente que cree y combine un pull request y cambie la configuración de Pages del repositorio. Revisa el diff, los permisos de despliegue y cualquier solicitud de aprobación de GitHub antes de continuar.

## Revisa el flujo de trabajo y verifica el despliegue

1. Confirma que el README solo se añade si el repositorio aún no tiene uno.
2. Revisa los cambios del pull request, incluidos los pasos de compilación y despliegue del flujo de trabajo.
3. Combínalo únicamente después de que se aprueben las comprobaciones requeridas del pull request.
4. Sigue la ejecución de despliegue de GitHub Actions hasta que finalice correctamente.
5. Abre la URL indicada y confirma que se carga el Space Quiz.

Si el agente no puede habilitar Pages o combinar el pull request, sigue las instrucciones específicas que te proporcione. No des la tarea por terminada hasta que el despliegue se complete correctamente y el sitio publicado se cargue.

## Resumen y siguientes pasos

Tu Space Quiz ya está disponible como sitio publicado y has verificado el despliegue en lugar de confiar únicamente en el informe del agente. Continúa con la [Lección 13: Repaso y próximos pasos][next-lesson].

[next-lesson]: ../13-review/
