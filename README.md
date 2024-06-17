# apiexplorer

**apiexplorer** es una potente herramienta de desarrollo y prueba de APIs diseñada para simplificar y optimizar el trabajo de los desarrolladores. Con una interfaz intuitiva y una amplia gama de funcionalidades, **apiexplorer** permite crear, organizar y probar solicitudes API de manera eficiente. Ya sea que estés construyendo nuevas APIs o depurando las existentes, **apiexplorer** ofrece todo lo que necesitas para mejorar tu flujo de trabajo.

## Características destacadas:

- **Interfaz amigable**: Navega y gestiona tus APIs con facilidad gracias a un diseño limpio y una experiencia de usuario intuitiva.
- **Pruebas avanzadas**: Realiza pruebas detalladas de tus endpoints, incluyendo autenticación, gestión de variables y scripts personalizados.
- **Documentación integrada**: Mantén tu equipo informado con documentación clara y accesible directamente desde la aplicación.
- **Automatización de flujos de trabajo**: Crea y ejecuta conjuntos de pruebas automatizadas para asegurar la estabilidad de tus APIs.
- **Soporte para múltiples protocolos**: Trabaja con APIs REST, SOAP y GraphQL en un solo lugar.
- **Colaboración en equipo**: Comparte tus proyectos y resultados de pruebas con tu equipo para una colaboración eficiente.

**apiexplorer** es tu aliado perfecto para el desarrollo de APIs, proporcionando las herramientas necesarias para un desarrollo ágil y una entrega de alta calidad. Mejora tu productividad y garantiza el éxito de tus proyectos con **apiexplorer**.

## Personalizar configuración

Consulta la [Referencia de Configuración de Vite](https://vitejs.dev/config/).

## Configuración del Proyecto

```sh
npm install
```

### Compilar y Recargar en Caliente para Desarrollo

```sh
npm run dev
```

### Compilar y Minificar para Producción

```sh
npm run build
```

### Ejecutar Pruebas Unitarias con [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Ejecutar Pruebas de Extremo a Extremo con [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

Esto ejecuta las pruebas de extremo a extremo contra el servidor de desarrollo de Vite. Es mucho más rápido que la compilación de producción.

Sin embargo, todavía se recomienda probar la compilación de producción con `test:e2e` antes de desplegar (por ejemplo, en entornos de CI):

```sh
npm run build
npm run test:e2e
```

### Lint con [ESLint](https://eslint.org/)

```sh
npm run lint
```
