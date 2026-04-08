# Proyecto Git y GitHub Actions

Este repositorio lo hice como parte de mi evaluación de la asignatura de Ingeniería DevOps.

## Objetivo

La idea de este proyecto es aprender a usar Git, trabajar con ramas y automatizar procesos con GitHub Actions.

## Modelo de ramas

Para este proyecto usé un modelo simple basado en GitFlow.

- main: aquí va la versión final o estable del proyecto.
- develop: aquí voy integrando todos los cambios en desarrollo.

También trabajé con otros tipos de ramas:

- feature/nombre: para agregar nuevas cosas o mejoras.
- hotfix/nombre: para corregir errores importantes.

## ¿Por qué usé este modelo?

Porque me permite trabajar de forma ordenada, sin afectar la versión principal, y así puedo probar cambios antes de dejarlos en producción.

## Forma de trabajo

- No trabajo directamente en main.
- Creo ramas para cada cambio.
- Hago commits con mensajes claros.
- Uso pull request para unir los cambios.

## Ejemplos de ramas usadas

- feature/readme
- feature/docs
- hotfix/arreglo-readme

## Automatización

Se agregó un workflow en GitHub Actions que revisa que los archivos markdown estén bien escritos.

## Estado del proyecto

Este repositorio se encuentra en preparación para automatización con GitHub Actions.

## Validación

Se agregó workflow para revisar archivos markdown.

