# KARIO Media - Panel de Indicadores

Este es un proyecto web para gestionar indicadores de proyectos. Básicamente es un panel donde puedes ver, añadir y eliminar indicadores con toda su info: fechas, categorías, progreso, etc. Basandonos en las ideas ilustrativas del cliente: https://www.figma.com/proto/0NKvCyMaX4G4iGAPhfosvk/KARIO?node-id=61-3&p=f&t=KvWlqGM3AA7O0r7b-1&scaling=contain&content-scaling=fixed&page-id=0%3A1

## Qué hace esto?

Es una página web para KARIO Media que te deja:
- Ver todos los indicadores de tus proyectos en una tabla
- Añadir nuevos indicadores
- Eliminar los que ya no necesitas
- Ver el progreso de cada uno
- Reportar bugs si algo no funciona
- Acceder a una sección de ayuda

## Con qué está hecho?

- HTML y CSS (nada más, sin JavaScript ni frameworks)
- Algunas fuentes de Google Fonts para que se vea bien
- Iconos en SVG

## Cómo está organizado

```
Proyecto_Html_Css/
│
├── index.html          # Página donde te logueas
│
├── css/                # Todos los estilos
│   ├── index.css
│   ├── principal.css
│   └── ...más archivos de estilos
│
├── pages/              # Las demás páginas
│   ├── Principal.html  # Panel principal con la tabla
│   ├── Anadir.html     # Para añadir indicadores
│   ├── Eliminar.html   # Para borrar indicadores
│   └── ...más páginas
│
└── media/              # Imágenes, iconos y logos
```

## Cómo usarlo

1. Descarga o clona el repo:
```bash
git clone https://github.com/Arturo1302/Proyecto_Html_Css.git
```

2. Abre el archivo `index.html` con tu navegador (doble clic o clic derecho → abrir con Chrome/Firefox/etc)

Eso es todo. No hay que instalar nada más.

**Tip:** Si usas VS Code, instala Live Server y dale clic derecho al index.html → "Open with Live Server" para verlo en vivo mientras editas.

## Las páginas

- **index.html** - Login para entrar al sistema
- **Principal.html** - Aquí ves todos los indicadores en una tabla grande con toda la info
- **Anadir.html** - Formulario para meter nuevos indicadores
- **Eliminar.html** - Para borrar indicadores que ya no quieres
- **Reportes.html** - Si algo no funciona, repórtalo aquí
- **Ayuda.html** - Documentación y FAQs
- **perfil.html** - Tu perfil de usuario

## Notas

- Todo está hecho con HTML y CSS puro, sin frameworks ni librerías raras
- Los indicadores se organizan por áreas: Marketing, Diseño, Developers, Gerencia, Producción
- Hay 3 prioridades: Baja, Media, Alta

## Contribuir

Si quieres aportar algo:
1. Haz fork del repo
2. Crea tu rama (`git checkout -b mi-feature`)
3. Haz commit de tus cambios
4. Sube tu rama (`git push origin mi-feature`)
5. Abre un Pull Request

## Autores

Hecho por Arturo - [@Arturo1302][@Damico707](https://github.com/Arturo1302)
