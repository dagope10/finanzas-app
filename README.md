# Aplicación de Finanzas

Este proyecto implementa una aplicación de finanzas utilizando una arquitectura moderna y prácticas DevOps.

## Estructura del Proyecto

```
.
├── infrastructure/           # Código de infraestructura
│   ├── terraform/           # Configuraciones de Terraform
│   └── jenkins/            # Configuraciones de Jenkins
├── frontend/               # Aplicación Next.js
└── backend/               # Aplicación Go
```

## Requisitos de Desarrollo

- Docker
- Docker Compose
- Git
- Node.js (para desarrollo local del frontend)
- Go (para desarrollo local del backend)

## Configuración del Entorno

### macOS

1. Instalar Docker Desktop desde https://www.docker.com/products/docker-desktop
2. Instalar Git: `brew install git`

### Debian

1. Instalar Docker:
   ```bash
   sudo apt-get update
   sudo apt-get install docker.io
   sudo systemctl start docker
   sudo systemctl enable docker
   ```
2. Instalar Docker Compose:
   ```bash
   sudo apt-get install docker-compose
   ```
3. Instalar Git:
   ```bash
   sudo apt-get install git
   ```

## Inicio Rápido

(Esta sección se actualizará conforme el proyecto evolucione)
