# Traductor i18n con Ionic

## Descripción

Este proyecto consiste en una aplicación móvil desarrollada con **Ionic Framework 8** y **Angular** que implementa la internacionalización (i18n) utilizando la librería **@ngx-translate**. La aplicación permite cambiar el idioma entre español e inglés en tiempo real mediante un selector de idioma.

## Tecnologías utilizadas

- Ionic Framework 8
- Angular 20
- TypeScript
- @ngx-translate/core
- @ngx-translate/http-loader

## Requisitos

Antes de ejecutar el proyecto es necesario tener instalado:

- Node.js
- npm
- Ionic CLI

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/NohemiMimi/i18n.git
```

Entrar a la carpeta del proyecto:

```bash
cd TraductorI18n
```

Instalar las dependencias:

```bash
npm install
```

## Ejecución

Iniciar la aplicación en modo desarrollo:

```bash
ionic serve
```

La aplicación se abrirá automáticamente en el navegador.

## Funcionalidades

- Cambio dinámico entre español e inglés.
- Traducciones almacenadas en archivos JSON.
- Interfaz desarrollada con componentes Standalone.
- Uso de la nueva sintaxis de control de flujo de Angular (`@for`).

## Estructura de traducciones

```text
src/
└── assets/
    └── i18n/
        ├── es.json
        └── en.json
```

## Autor

Nohemí García Velasco
