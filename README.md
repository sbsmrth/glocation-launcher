# 🚀 Aplicación Launcher - GLocation

Este repositorio contiene **tanto el Frontend como el Backend** para la prueba de **GLocation**.  
Incluye la configuración necesaria para clonar y levantar el proyecto correctamente.

---

## 📂 Estructura del Proyecto

- **Frontend** → Aplicación React con Tailwind y Shadcn UI.  
- **Backend** → API construida en NestJS con Prisma.

---

## 🛠️ Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (versión recomendada: >=18)
- [npm](https://www.npmjs.com/) o [pnpm](https://pnpm.io/)
- [Docker](https://www.docker.com/) (opcional, para levantar servicios rápidamente)

---

## 🚀 Instalación y Configuración

1. **Clonar el repositorio**

```bash
git clone https://github.com/sbsmrth/glocation-launcher.git
```

2. **Moverse al directorio del proyecto**

```bash
cd glocation-launcher
```

3. **Inicializar submódulos (Frontend y Backend)**

```bash
git submodule update --init --recursive
```

---

## ▶️ Ejecución del Proyecto

1. **Backend**

```bash
cd glocation-be
npm install
npx prisma migrate dev
docker compose up -d
npm run start:dev
```

2. **Frontend**

```bash
cd glocation-fe
npm install
npm run dev
```

## Sobre la elección de Nest JS

Se eligió NestJS porque proporciona una arquitectura modular y organizada que facilita la escalabilidad y el mantenimiento del proyecto. Mientras que con Node.js puro es necesario estructurar controladores, servicios y validaciones. NestJS ofrece un marco basado en TypeScript, inyección de dependencias y principios de arquitectura limpia, lo que acelera el desarrollo y reduce la complejidad en aplicaciones empresariales.