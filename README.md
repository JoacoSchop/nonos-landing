# NONOS Landing

Landing pública de NONOS.

```sh
npm install
cp .env.example .env.local
npm run dev
```

La landing se sirve en `http://localhost:5174`. Por defecto, los botones **Ingresar** llevan a `https://nonos-app.vercel.app/ingresar`. Para desarrollar con la app local en `http://localhost:5173`, copiá `.env.example` a `.env.local`. `VITE_APP_URL` permite cambiar el origen de la app sin modificar el código.
