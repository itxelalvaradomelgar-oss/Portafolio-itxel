# Portafolio de Itxel Alvarado

Portafolio digital con identidad propia (azul marino y dorado) que reúne mis proyectos de IA y desarrollo web del programa ¡Supérate!.

**Portafolio desplegado:** _pega aquí tu URL de Vercel_

![Captura del portafolio](public/images/captura.png)

## Tecnologías
Next.js 15, React 19, TypeScript, Tailwind CSS 4, Vercel.

## Instalación y ejecución
```bash
npm install
cp .env.example .env.local   # variables de entorno (nunca se suben a GitHub)
npm run dev                  # http://localhost:3000
```

## Estructura
- `app/`: páginas, incluida `proyectos/[slug]` y la API `api/contact`
- `components/`: formulario de contacto y laberinto jugable
- `lib/data.ts`: textos y datos de los proyectos
- `public/images/`: imágenes

## API
`POST /api/contact` recibe `{ nombre, correo, mensaje }`, valida y responde JSON.

## Lo que aprendí
_Escríbelo con tus palabras: qué fue lo más difícil y qué te gustó más._

## Créditos de imágenes
_Indica de dónde salieron las fotos de decoración y lectura._
