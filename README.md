# 🧠✨ MATCHEO

> **Donde las mentes brillantes se encuentran.**
> Una red privada para conectar emprendedores, mentes inquietas y curiosos crónicos por afinidad real — sin la presión de la imagen.

🌐 **Sitio en vivo:** [matcheo.vercel.app](https://matcheo.vercel.app)

---

## 💡 ¿Qué es MATCHEO?

MATCHEO es una plataforma web (mobile-first) pensada para conectar personas con **ganas de emprender** y **gustos afines**, sin tener que exponer públicamente lo que les apasiona.

La lógica está invertida respecto a las redes sociales actuales:

> Vos contás todo en privado, y sólo aparecen las personas con las que **realmente** coincidís.

A partir de un **70% de afinidad** se habilita el primer contacto. El resto de la identidad se va revelando por **capas**, a medida que matchean más aspectos.

---

## 🎭 Cómo funciona

| Paso | Qué pasa |
|---|---|
| **1. Perfil privado** | Completás un perfil multidimensional: gustos, hobbies, formación, valores, intereses emprendedores. Nadie lo ve. |
| **2. Matcheo algorítmico** | El algoritmo cruza compatibilidad multidimensional. A partir del **~70%** aparece un match — sin nombre ni foto. |
| **3. Revelación por capas** | Cada nuevo sub-match desbloquea una capa más: avatar, voz, texto, foto, hasta la identidad completa. |

### Las 5 capas del misterio

1. 🌫️ **Niebla afín** — Sólo el % de afinidad y un avatar abstracto
2. 💬 **Primer mensaje** — Chat con prompts inteligentes
3. 🎨 **Estilo y voz** — Profesión genérica, ciudad aproximada, tono de escritura
4. 📷 **Foto difusa** — Imagen artística, voz opcional, primer nombre
5. 👋 **Identidad plena** — Foto real, nombre completo, todos los datos

> 🛡️ El usuario siempre tiene el control: puede pausar, retroceder de capa o cerrar el match en cualquier momento.

---

## 🦄 ¿Para quién es?

- **Emprendedores** — founders, soloists, indie hackers buscando co-founders, mentores o aliados
- **Mentes inquietas** — personas que piensan distinto y buscan pares con quienes pensar en voz alta
- **Curiosos crónicos** — polímatas, autodidactas, gente que devora podcasts, papers y libros random
- **Quienes buscan vínculo profundo** — amistad, mentoría, compañía intelectual o pareja basada en compatibilidad real

---

## 🧬 Dimensiones del perfil (12+)

Formación · Espíritu emprendedor · Lecturas · Arte y estética · Hobbies y deportes · Estilo cognitivo · Valores · Filosofía de vida · Idiomas y cultura · Objetivos · Curiosidades · Tipo de vínculo buscado.

Cada usuario asigna **pesos personalizables** a cada dimensión (imprescindible / deseable / indistinta) — el algoritmo respeta esas prioridades.

---

## 🛠️ Stack técnico

Este repo contiene la **landing page** del proyecto. Es un sitio estático single-file:

- **HTML5** semántico, mobile-first
- **Tailwind CSS** vía CDN (sin build step)
- **Google Fonts** — Space Grotesk + Plus Jakarta Sans
- **SVG inline** para todos los gráficos y animaciones
- **Vanilla JS** para reveal-on-scroll y menú mobile
- **0 dependencias externas** (más allá de los CDNs)
- Respeta `prefers-reduced-motion`

---

## 🚀 Correr el sitio localmente

No requiere instalación. Tres opciones:

```bash
# Opción 1: doble click
# Abrí index.html con cualquier navegador

# Opción 2: server local con Python
python -m http.server 8000

# Opción 3: server local con Node
npx serve .
```

Después abrí http://localhost:8000

---

## 📦 Deploy

El sitio está en **Vercel** con auto-deploy desde este repo. Cada push a `main` republica el sitio en https://matcheo.vercel.app en ~30 segundos.

---

## 🗺️ Roadmap

- [x] Landing page presentable
- [ ] Formulario de waitlist conectado
- [ ] PWA instalable
- [ ] App de matcheo (signup + perfil + algoritmo)
- [ ] Modo co-founder
- [ ] Comunidades temáticas
- [ ] Apps nativas iOS / Android

---

## 📝 Licencia

Pendiente de definir. Por ahora, todos los derechos reservados.

---

## 📬 Contacto

¿Sos socio, inversor o curioso/a interesado/a en sumarse? Escribinos.

---

<sub>Hecho con 💜 para mentes inquietas.</sub>
