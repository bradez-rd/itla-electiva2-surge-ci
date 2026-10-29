# Integración continua con Surge

1. Cree un dominio único, por ejemplo `brailin-itla-c3.surge.sh`.
2. En una terminal autenticada ejecute `npx surge@latest tokens add --domain brailin-itla-c3.surge.sh -m "github actions"`.
3. Guarde el valor como secreto de GitHub `SURGE_TOKEN`.
4. Cree la variable de repositorio `SURGE_DOMAIN` con el dominio.
5. Haga push a `main`; el workflow publica el sitio automáticamente.

El token se mantiene fuera del repositorio y queda restringido a un solo dominio.
