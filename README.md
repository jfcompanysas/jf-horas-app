# Aplicación Control de Horas Extras - JF COMPANY S.A.S.

Aplicación web instalable en celular tipo PWA para controlar asistencia, horas ordinarias, horas extras, aprobación de registros y exportación CSV.

## Cómo probarla en computador

1. Instalar Node.js.
2. Abrir esta carpeta en Visual Studio Code.
3. Ejecutar:

```bash
npm install
npm run dev
```

4. Abrir la URL que entrega Vite.

## Cómo instalarla en celular

Para que aparezca como app instalable, debe publicarse en un dominio HTTPS, por ejemplo:

- Vercel
- Netlify
- Firebase Hosting
- Hosting propio de jfcompanysas.com

Después de publicada:

- En Android/Chrome: abrir la página y tocar "Instalar app" o "Agregar a pantalla principal".
- En iPhone/Safari: compartir > "Agregar a pantalla de inicio".

## Advertencia operativa

Esta versión guarda los datos localmente en cada dispositivo. Para que varios supervisores y administración trabajen sobre la misma información, debe conectarse a Firebase, Supabase o un backend propio.
