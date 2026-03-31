# Ejercicios GitHub Actions - Frontend

Este repositorio cumple con los dos ejercicios obligatorios solicitados para `hangman-front`.

## 1) Workflow CI - OBLIGATORIO

Archivo: `.github/workflows/ci-front.yml`

Configuracion implementada:

- Se dispara en `pull_request`.
- Solo se ejecuta si hay cambios en `hangman-front/**`.
- Ejecuta build del frontend.
- Ejecuta unit tests del frontend.

En resumen, el workflow cumple la condicion pedida: PR + cambios en `hangman-front/**`.

## 2) Workflow CD - OBLIGATORIO

Archivo: `.github/workflows/cd-front.yml`

Configuracion implementada:

- Se dispara manualmente con `workflow_dispatch`.
- Construye una nueva imagen Docker del frontend.
- Publica la imagen en GitHub Container Registry (GHCR).

## Evidencia (capturas)

Capturas del flujo y resultado:

![Paso 1](image.png)

![Paso 2](image-1.png)

![Paso 3](image-2.png)

![Paso 4](image-3.png)

![Paso 5](image-4.png)

## Referencias rapidas

- CI: `.github/workflows/ci-front.yml`
- CD: `.github/workflows/cd-front.yml`
- Proyecto frontend: `hangman-front/`