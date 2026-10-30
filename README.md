# NONOS Landing

Landing pública de NONOS.

```sh
npm install
cp .env.example .env.local
npm run dev
```

La landing se sirve en `http://localhost:5174`. La app principal usa `http://localhost:5173`. Configurá `VITE_APP_URL` con el origen público de la app en cada despliegue; los botones **Ingresar** apuntan a `/ingresar` en ese origen.
