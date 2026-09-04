# El Cerebro de Marketing — Bartender

Este repositorio es el **cerebro de marketing** del negocio: un conjunto de
agentes especializados y skills reutilizables que trabajan coordinados sobre
Claude Code para planificar, crear y medir marketing de forma consistente.

No es una app ni un pipeline de código — es la configuración de un equipo de
marketing formado por subagentes (`.claude/agents/`) y procesos empaquetados
como skills (`.claude/skills/`). Cualquier persona que abra este repo con
Claude Code hereda automáticamente este equipo.

## Cómo está organizado

```
CLAUDE.md                     ← este archivo, el mapa del cerebro
marketing/brand-voice.md      ← ficha de marca: quién somos, tono, prohibido
.claude/agents/               ← subagentes especializados (el "quién")
.claude/skills/               ← procesos paso a paso (el "cómo")
```

## El equipo (`.claude/agents/`)

| Agente | Cuándo usarlo |
|---|---|
| `director-marketing` | Punto de entrada para pedidos ambiguos o campañas completas. Diagnostica y delega en el resto del equipo. |
| `copywriter` | Redactar textos: posts, anuncios, descripciones de carta, eslóganes. |
| `social-media-manager` | Planificar y estructurar contenido para redes sociales. |
| `community-manager` | Responder reseñas, comentarios y mensajes; gestionar reputación. |
| `seo-local` | Optimizar Google Business Profile y SEO local. |
| `email-crm` | Email marketing, programas de fidelización, segmentación de clientes. |
| `event-promo-designer` | Diseñar promociones, happy hours, eventos y campañas de temporada. |
| `growth-analyst` | Leer métricas, sacar conclusiones y proponer siguientes pasos. |
| `brand-guardian` | Revisar que cualquier pieza respete la voz y las normas de marca. |

Invócalos con la herramienta Agent (`subagent_type`) o pídeselo directamente a
`director-marketing`, que sabe repartir el trabajo.

## Los procesos (`.claude/skills/`)

| Skill | Para qué sirve |
|---|---|
| `campaign-brief` | Convertir una idea suelta en un brief de campaña accionable. |
| `content-calendar` | Construir un calendario editorial de redes sociales. |
| `cocktail-copy` | Escribir descripciones de cócteles y platos para carta o redes. |
| `promo-flyer` | Producir un flyer/artifact visual para una promoción. |
| `review-response` | Responder reseñas online (buenas y malas) siguiendo el tono de marca. |
| `competitor-scan` | Analizar qué están haciendo bares/locales competidores. |
| `email-newsletter` | Redactar y estructurar una newsletter o email de campaña. |
| `kpi-report` | Convertir datos de rendimiento en un informe claro con conclusiones. |

Invócalas con `/nombre-skill` o dejando que el agente correspondiente las use.

## Regla de oro

Antes de escribir o publicar cualquier pieza, revisa `marketing/brand-voice.md`.
Todo agente y toda skill deben respetar esa ficha de marca; si falta
información para cumplirla (nombre del local, tono exacto, promociones
vigentes...), pregunta en vez de inventar datos del negocio real.
