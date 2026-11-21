# Instalación y actualización

## Elegir el paquete

- **Skill independiente:** carpeta `vitaefluxum` con SKILL.md, references, assets y agents. Úsala en aplicaciones que admitan importar skills con recursos locales.
- **Repositorio:** conserva el empaquetado del plugin de Codex y la documentación. No es un instalador universal para todos los asistentes.

## Pasos

1. Guarda una copia de tu versión anterior y de tus proyectos. La actualización no debe borrar imágenes o documentos de trabajo.
2. Comprueba qué mecanismo de skills admite tu aplicación y tu cuenta. En Claude, utiliza su mecanismo de skills si está disponible; en Codex o ChatGPT, utiliza el mecanismo que ofrezca el entorno. Los nombres de botones y métodos pueden cambiar.
3. Importa la carpeta completa o el ZIP cuando ese mecanismo lo admita. No subas solamente SKILL.md: necesita sus imágenes y referencias.
4. Sustituye o desactiva la versión anterior para evitar dos instrucciones contradictorias. Conserva tu copia de seguridad fuera de las skills activas.
5. Abre una conversación nueva y pide «Muéstrame qué puedes hacer» y «Enséñame los tipos de blueprint de personajes». Comprueba que se ven los ejemplos nuevos.

Si el asistente solo admite documentos, puede consultar el contenido como documentación, pero eso no equivale a instalar una skill. Generar imágenes y ejecutar Blender requieren herramientas adicionales disponibles en ese entorno. No se necesita una habilidad privada del creador.

No se ha validado este paquete mediante importación real en todas las aplicaciones. Consulta [portabilidad](plugins/vitaefluxum/skills/vitaefluxum/references/portabilidad.md) para adaptar el uso sin prometer capacidades inexistentes.
