# Axe Capital Fintech

Prototipo web responsive para explorar el flujo de solicitud y seguimiento de crédito.

## Estado actual

Este repositorio contiene una interfaz estática de demostración. No está conectada a una base de datos ni a un proveedor de autenticación. Los formularios, OTP, chat, solicitudes, aceptación y panel administrativo son simulaciones y no deben usarse para recopilar información real.

## Estructura

- `index.html`: aplicación principal y flujo de solicitud de demostración.
- `pages/registro-demo.html`: recorrido de registro simulado.
- `pages/acuerdo-demo.html`: vista ilustrativa del acuerdo.
- `admin/index.html`: panel administrativo con datos ficticios.
- `assets/`: recursos de marca.

## Ejecutar localmente

Abre `index.html` en un navegador o sirve la carpeta con un servidor estático local.

## Desplegar en Vercel

Importa este repositorio desde GitHub en Vercel. No requiere comando de build ni dependencias; deja el directorio raíz del proyecto como raíz de despliegue. Vercel publicará `index.html` y las rutas estáticas.

## Para una versión conectada

Antes de usar datos reales, hay que implementar un backend, autenticación, autorización por rol, reglas de acceso a datos y archivos, almacenamiento seguro, registros de auditoría y revisión de privacidad y términos. Nunca incluyas claves privadas ni secretos en archivos públicos del frontend.
