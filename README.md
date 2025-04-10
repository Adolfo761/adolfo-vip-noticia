# adolfo-vip-noticia
Portal de noticias dominicanas con análisis de IA en tiempo real
[build]
  command = "npm install -g pnpm && pnpm install && pnpm build"
  publish = ".next"

[build.environment]
  NODE_VERSION = "18"
  NPM_FLAGS = "--no-optional"
  NEXT_TELEMETRY_DISABLED = "1"

[[plugins]]
  package = "@netlify/plugin-nextjs"
