# AdolFO_VIP Noticia

Portal de noticias dominicanas con análisis de IA en tiempo real

## Características

- Diseño responsivo con Tailwind CSS
- Categorización de noticias (Local, Deportes, Internacional, etc.)
- Funcionalidad de texto a voz
- Panel de administración protegido
- Actualizaciones automáticas de contenido
- Análisis de IA en tiempo real

## Tecnologías Utilizadas

- HTML5
- CSS3 con Tailwind CSS
- JavaScript (ES6+)
- Web Speech API para texto a voz
- Soporte para modo oscuro
- Optimizado para SEO

## Instalación

1. Clona este repositorio
2. Abre el archivo `index.html` en tu navegador

## Desarrollo

Para contribuir al desarrollo:

1. Haz un fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/nueva-caracteristica`)
3. Haz commit de tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Haz push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## Configuración de Netlify

```
[build]
  command = "npm install -g pnpm && pnpm install && pnpm build"
  publish = ".next"

[build.environment]
  NODE_VERSION = "18"
  NPM_FLAGS = "--no-optional"
  NEXT_TELEMETRY_DISABLED = "1"

[[plugins]]
  package = "@netlify/plugin-nextjs"
```

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE para más detalles.
