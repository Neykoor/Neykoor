<div align="center">

# Hey, soy Neykoor 👋

**Desarrollador de librerías y bots para WhatsApp**  
*Construyendo herramientas de producción con Node.js · México 🇲🇽*

</div>

---

## 🛠️ Stack tecnológico

Las tecnologías que uso en mis proyectos:

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![ESModules](https://img.shields.io/badge/ES%20Modules-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

| Tecnología | Uso |
|---|---|
| **JavaScript (ESM)** | Lenguaje principal — todas las librerías son ES Modules nativos |
| **Node.js 18+** | Runtime — async/await, private class fields, AbortController |
| **SQLite + WAL** | Persistencia con transacciones atómicas (`BEGIN IMMEDIATE`) |
| **Baileys** | API no oficial de WhatsApp Web para bots |

---

## 📦 Librerías

### 🌸 [LidSync](https://github.com/Neykoor/lidsync)
> Resuelve LIDs de WhatsApp (`170360431460562@lid`) a JIDs reales (`521234567890@s.whatsapp.net`)

- Cache LRU con TTL configurable
- Índice invertido O(1) desde el store de Baileys
- Integración con Signal Repository interno de Baileys
- Normalización automática de JIDs (elimina sufijos `:0`, `:1`)
- Store Pro incluido con escritura atómica y graceful shutdown

[![Repo](https://img.shields.io/badge/GitHub-LidSync-181717?style=flat-square&logo=github)](https://github.com/Neykoor/lidsync)
![Language](https://img.shields.io/badge/JavaScript-ESM-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Stars](https://img.shields.io/github/stars/Neykoor/lidsync?style=flat-square)

---

### 🎲 [kamijs](https://github.com/Neykoor/kamijs)
> Motor de Gacha con economía, trades y IA de Compasión para bots de WhatsApp

- Transacciones atómicas con `BEGIN IMMEDIATE` en SQLite (modo WAL)
- Sistema de Mercy/Pity adaptativo basado en estrés del usuario
- Trades entre usuarios con expiración automática y verificación en transacción
- Imágenes dinámicas desde Yande.re por tag de booru
- Cooldowns en dos pasos: verificación → confirmación
- Moneda personalizable por instancia
- Integrado con LidSync para normalización de JIDs

[![Repo](https://img.shields.io/badge/GitHub-kamijs-181717?style=flat-square&logo=github)](https://github.com/Neykoor/kamijs)
![Language](https://img.shields.io/badge/JavaScript-ESM-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Stars](https://img.shields.io/github/stars/Neykoor/kamijs?style=flat-square)

---

## 📊 Estadísticas

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Neykoor&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Neykoor&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=Neykoor&theme=tokyonight&hide_border=true)

</div>

---

## 📍 Ubicación

<div align="center">

![México](https://img.shields.io/badge/México-Top%20Developers-006847?style=for-the-badge&logo=google-maps&logoColor=white)

</div>

---

<div align="center">

*Las librerías están diseñadas para producción — rápidas, predecibles y resistentes a fallos.*

</div>
