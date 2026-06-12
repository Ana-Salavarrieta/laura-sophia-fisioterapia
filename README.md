# Laura Sophia Salavarrieta — Fisioterapia

Landing page profesional de **Laura Sophia Salavarrieta**, fisioterapeuta especialista en Terapia Manual Ortopédica. Rehabilitación física y postoperatoria con atención a domicilio en Bogotá.

## Características

- Página única, estática y autónoma (HTML + CSS + JavaScript), sin dependencias salvo Google Fonts.
- Hero con propuesta de valor y **goniómetro animado** que marca los grados de movilidad recuperada.
- Secciones: Servicios, Sobre Laura Sophia, Proceso (línea de tiempo animada), Testimonios y Contacto.
- Contacto por WhatsApp (con mensaje predefinido) y correo, ofuscados para evitar rastreo por bots.
- Diseño responsive, menú móvil y respeto de la preferencia `prefers-reduced-motion`.

## Uso

Abre `index.html` en el navegador, o sirve la carpeta con cualquier servidor estático:

```bash
npx serve .
```

## Pendiente de configurar

En el `<script>` al final de `index.html`, reemplaza los marcadores por los datos reales:

- `waParts` → número de WhatsApp.
- `mailParts` → dirección de correo.

## Estructura

```
index.html        Página completa (estructura, estilos y scripts)
assets/laura.png  Fotografía profesional
assets/logo.png   Logo de marca
```
