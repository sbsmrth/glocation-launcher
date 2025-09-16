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
npm run start:dev
```

2. **Frontend**

```bash
cd glocation-fe
npm install
npm run dev
```
