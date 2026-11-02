# Landing Page — Masterclass Presencial "Remates Judiciales Desde Cero"

Landing page estática para promocionar la masterclass presencial de 3 horas de Julissa Márquez.

- **Fecha:** sábado 5 de diciembre de 2026
- **Horario:** 5:00 p. m. a 8:00 p. m.
- **Lugar:** San Isidro, Lima
- **Inversión:** S/ 59
- **Reservas:** WhatsApp +51 994 613 551

## Estructura

```
landing-remates-judiciales-desde-cero/
├── index.html   # Página completa (HTML + Tailwind CDN + estilos)
├── img/
│   ├── julissa-marquez.jpg      # Foto original (alta resolución)
│   ├── julissa-marquez-web.jpg  # Foto optimizada usada por la página
│   ├── logo-julissa.jpeg        # Marca personal
│   └── logo-trova.jpeg          # Trova Inversiones
└── README.md
```

No hay framework ni build: es un único `index.html` que usa Tailwind CSS vía CDN. Se puede abrir directamente en el navegador o publicar en cualquier hosting estático.

## Ver la página en local

1. Abre el Explorador de archivos.
2. Ve a esta carpeta.
3. Haz doble clic en `index.html`.

También puedes usar VS Code + Live Server para recargar automáticamente al editar.

## Publicación

El proyecto está desplegado en Vercel:

https://remates-judiciales-desde-cero.vercel.app/

El repositorio de GitHub es:

https://github.com/bluzweii-crypto/remates-judiciales-desde-cero

Si Vercel está conectado al repositorio, cada push a `main` genera un despliegue de producción. Para revisar cambios sin publicarlos, usa una rama distinta o un deploy de preview.

## Datos que puedes editar en `index.html`

| Dato | Buscar |
| --- | --- |
| Número de WhatsApp | `51994613551` |
| Precio | `S/ 59` |
| Fecha y horario | `5 de diciembre de 2026`, `5:00 p. m.` |
| Lugar | `San Isidro, Lima` |
| Foto de Julissa | `img/julissa-marquez-web.jpg` |
| Logos | `img/logo-julissa.jpeg`, `img/logo-trova.jpeg` |
| Colores de marca | `:root` en el `<style>` (`--navy`, `--gold`, `--gray`, `--wa`) |

## Identidad visual

- Azul marino `#10243B`
- Dorado `#D5B36A`
- Blanco `#FFFFFF`
- Gris claro `#F1F2F4`
- Verde WhatsApp `#16845B`

Tipografías: Cormorant Garamond (títulos) e Inter (texto).

## Notas de contenido

- La página no incluye módulos, lecciones, clases grabadas ni formularios.
- Toda la conversión se hace por WhatsApp.
- No se incluyen testimonios ni resultados inventados.
