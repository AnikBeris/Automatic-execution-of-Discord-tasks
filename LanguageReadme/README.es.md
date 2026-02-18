```html
<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/LanguageReadme/README.en.md">English</a> |
  <a href="/LanguageReadme/README.es.md">Español</a> |
  <a href="/LanguageReadme/README.zh.md">Chino</a> |
  <strong><-------</strong>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="Logotipo del proyecto" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![Licencia](https://img.shields.io/badge/Licencia-purple?style=flat&logo=github)](/LICENSE.md)
[![Estrellas GitHub](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Estrellas&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="ESPACIADOR" width="90%">
</div>

<h1 align="center"> 
Ejecutar automáticamente tareas de Discord
</h1>

<h1 align="center"> 
Este script permite `realizar tareas automáticamente en Discord` sin necesidad de jugar el juego.
</h1>

<h2 align="center">
> 💡 Este material está orientado para facilitar la obtención de recompensas relacionadas con tareas de juego.
</h2>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ Descargo de responsabilidad ⚠️
</h2>

<p align="center">
  El autor no se hace responsable de ninguna posible consecuencia derivada del uso de este proyecto.<br>
  Úsalo bajo tu propio riesgo.
</p>

<details> 
    <summary align="center">⚠️TEXTO COMPLETO⚠️</summary>
    
## Usa los materiales de este repositorio bajo tu propio riesgo.

1. Al utilizar los materiales de este repositorio, aceptas automáticamente los términos del acuerdo de licencia asociado.

2. El autor no otorga ninguna garantía explícita o implícita con respecto a la precisión, integridad o idoneidad de estos materiales para ningún propósito específico.
   
3. El autor no será responsable de ninguna pérdida, incluidas, entre otras, pérdidas directas, indirectas, incidentales, consecuenciales o especiales derivadas del uso o la incapacidad de usar los materiales de este repositorio o su documentación asociada, incluso si se advierte sobre la posibilidad de dichas situaciones previamente.

4. Al usar estos materiales, reconoces y aceptas asumir todos los riesgos relacionados con su aplicación. Además, aceptas que el autor no puede ser considerado responsable de ningún problema o consecuencia derivada de su uso.

</details> 

---

<h3 align="center"> 
💖 Apoya el proyecto 💖
</h3>

<details>
    <summary align="center"> 💖 APOYA EL DESARROLLO DEL PROYECTO 💖 </summary>

---

<p align="center"> 
Si este proyecto te resulta útil, puedes apreciarlo dándole una estrella.:star2:
</p>

<h4 align="center"> 
Las donaciones son bienvenidas, sin importar cuán pequeñas sean, ¡muchas gracias! 😌 
</h1>

<div align="center">

|  |  |
|-------------:|:-------------|
| **Tether USDT (BEP20)** |`0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Bitcoin (BTC)** |`1Dbwq9EP8YpF3SrLgag2EQwGASMSGLADbh`|
| **Ethereum (ERC20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Binance Smart Chain (BEP20)** | `0x22258ea591966e830199d27dea7c542f31ed5dc5`|
| **Solana (SOL)** | `yYYXsiVTzsvfvsMnBxfxSZEWTGytjAViE2ojf3hbLeF`|

</div>

---

<p align="center">
  <sub> Gracias por tu atención al proyecto y por tu apoyo 💙 </sub>
</p>

</details>

* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 Contenido

- [Introducción](#-introducción)

## 📦 Funcionalidades

- Realización automática de tareas (Quests) en `Discord PTB`  
- Visualización del progreso en la consola  
- Fácil de usar: simplemente copia el script en la consola de desarrollador  
- Total compatibilidad con `Discord`  

## 🔗 Enlaces útiles

- [Discord PTB](https://ptb.discord.com/) — La plataforma principal  

---

# 🚀 Instalación y ejecución

<h2 align="center">
  <a href="#-contenido">⬆️ Volver al contenido</a>
</h2>

## 1. Descarga `Discord PTB` desde EL SERVIDOR OFICIAL.

```sh
https://ptb.discord.com/
```

## 2. Instala `Discord PTB`

## 3. Inicia `Discord PTB`

<div align="center">
  <img style="width: 20%; height: auto;" alt="Discord PTB" src="../media/icon.png"/>
</div>

## 4. Ve a la sección de `viajes` y después a la pestaña de `Tareas` (Quests)

## 5. Inicia la tarea

<div align="center">
  <img style="width: 50%; height: auto;" alt="Automatic-Discord-tasks" src="../media/7-Automatic-Discord-tasks.png">
</div>

## 6. Presiona `Ctrl+Shift+I` para abrir la consola de desarrollador

## 7. Copia el texto del script

- [RU-Automatic-Discord-tasks](/RU-Automatic-Discord-tasks.md) Los logs de la consola estarán en ruso.

<details>
    <summary> ⚙️ Expande el script: RU-Automatic-Discord-tasks </summary>

```js
// Contenido del script (ver original)
```

</details>

o

- [EN-Automatic-Discord-tasks](/EN-Automatic-Discord-tasks.md) Los logs de la consola estarán en inglés.

<details>
    <summary> ⚙️ Expande el script: EN-Automatic-Discord-tasks </summary>

```js
// Contenido del script (ver original)
```

</details>
```

Aquí tienes la traducción al español del texto:

```javascript
let ApplicationStreamingStore = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.getStreamerActiveStreamMetadata)?.exports?.Z;
let RunningGameStore, QuestsStore, ChannelStore, GuildChannelStore, FluxDispatcher, api;
if (!ApplicationStreamingStore) {
    ApplicationStreamingStore = Object.values(wpRequire.c).find(x => x?.exports?.A?.__proto__?.getStreamerActiveStreamMetadata).exports.A;
    RunningGameStore = Object.values(wpRequire.c).find(x => x?.exports?.Ay?.getRunningGames).exports.Ay;
    QuestsStore = Object.values(wpRequire.c).find(x => x?.exports?.A?.__proto__?.getQuest).exports.A;
    ChannelStore = Object.values(wpRequire.c).find(x => x?.exports?.A?.__proto__?.getAllThreadsForParent).exports.A;
    GuildChannelStore = Object.values(wpRequire.c).find(x => x?.exports?.Ay?.getSFWDefaultChannel).exports.Ay;
    FluxDispatcher = Object.values(wpRequire.c).find(x => x?.exports?.h?.__proto__?.flushWaitQueue).exports.h;
    api = Object.values(wpRequire.c).find(x => x?.exports?.Bo?.get).exports.Bo;
} else {
    RunningGameStore = Object.values(wpRequire.c).find(x => x?.exports?.ZP?.getRunningGames).exports.ZP;
    QuestsStore = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.getQuest).exports.Z;
    ChannelStore = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.getAllThreadsForParent).exports.Z;
    GuildChannelStore = Object.values(wpRequire.c).find(x => x?.exports?.ZP?.getSFWDefaultChannel).exports.ZP;
    FluxDispatcher = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.flushWaitQueue).exports.Z;
    api = Object.values(wpRequire.c).find(x => x?.exports?.tn?.get).exports.tn;
}

const supportedTasks = ["WATCH_VIDEO", "PLAY_ON_DESKTOP", "STREAM_ON_DESKTOP", "PLAY_ACTIVITY", "WATCH_VIDEO_ON_MOBILE"];
let quests = [...QuestsStore.quests.values()].filter(x => 
    x.userStatus?.enrolledAt && 
    !x.userStatus?.completedAt && 
    new Date(x.config.expiresAt).getTime() > Date.now() && 
    supportedTasks.find(y => Object.keys((x.config.taskConfig ?? x.config.taskConfigV2).tasks || {}).includes(y))
);
let isApp = typeof DiscordNative !== "undefined";

const log = (msg, color = '#fff') => console.log(`%c${msg}`, `color: ${color}; font-family: Consolas, monospace;`);
const success = (msg) => log(`[ÉXITO] ${msg}`, '#00ff9d');
const info = (msg) => log(`[INFO]    ${msg}`, '#4da6ff');
const warn = (msg) => log(`[ADVERTENCIA]    ${msg}`, '#ffcc00');
const error = (msg) => log(`[ERROR]   ${msg}`, '#ff4d4d');

function progressBar(progress, total, width = 20) {
  const percent = Math.min(100, Math.floor((progress / total) * 100));
  const filled = Math.floor((width * progress) / total);
  const bar = '█'.repeat(filled) + '░'.repeat(width - filled);
  const timeLeft = Math.ceil((total - progress) / 60);
  return `[${bar}] ${progress}/${total} (${percent}%) • ${timeLeft} min restantes`;
}

if (quests.length === 0) {
  info("No se encontraron misiones activas compatibles. Verifica en Descubrir → Misiones.");
} else {
  console.groupCollapsed('%c🎮 Discord Quest Booster v2.1 – Tareas Activas 🚀', 'color:#7289da; font-weight:bold; font-size:14px;');
  log(`Se encontraron ${quests.length} misión(es)`, '#7289da');
  quests.forEach((q, i) => {
    const task = Object.keys(q.config.taskConfig?.tasks || q.config.taskConfigV2.tasks || {})[0];
    const target = q.config.taskConfig?.tasks?.[task]?.target || 'desconocido';
    log(`\nMisión ${i+1}: ${q.config.messages.questName} (${task})`, '#ffffff');
    log(`  Objetivo: ${target} seg`, '#cccccc');
    log(`  Restante: ~${Math.ceil((target - (q.userStatus?.progress?.[task]?.value || 0)) / 60)} min`, '#cccccc');
  });
  console.groupEnd();

  let doJob = function() {
    const quest = quests.pop();
    if (!quest) {
      console.log('%c═══════════════════════════════════════════════', 'color:#7289da');
      success('¡Todas las misiones compatibles fueron completadas! Disfruta tus recompensas ✨');
      console.log('%c═══════════════════════════════════════════════', 'color:#7289da');
      return;
    }

    const pid = Math.floor...(continuación en el script anterior)
``` 

Espero que esta traducción te sea útil. Si necesitas otros segmentos, documentos traducidos o alguna asistencia, no dudes en mencionarlo.
