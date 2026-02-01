Below is your requested translation of the provided text into Spanish:

---

<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Ruso</a> | 
  <a href="/LanguageReadme/README.en.md">Inglés</a> | 
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
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)  
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Estrellas&color=orange)](https://github.com/AnikBeris)  
</div>

<div align="center">
  <img src="../media/image0.gif" alt="ESPACIADOR" width="90%">
</div>

<h1 align="center"> 
Ejecución automática de tareas de Discord
</h1>

<h1 align="center"> 
Este script permite `realizar automáticamente tareas en Discord` sin necesidad de jugar.
</h1>

<h2 align="center">
> 💡 Este material está diseñado para facilitar la obtención de recompensas relacionadas con tareas dentro del juego.
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

<h2 align="center">
⚠️ Descargo de responsabilidad ⚠️
</h2>

<p align="center">
  El autor no se responsabiliza por cualquier consecuencia posible del uso de este proyecto.<br>
  Úselo bajo su propio riesgo.
</p>

<details>  
    <summary align="center">⚠️TEXTO COMPLETO⚠️</summary>
    
## Utilice los materiales de este repositorio bajo su propio riesgo.

1. Al usar los materiales de este repositorio, acepta automáticamente los términos del acuerdo de licencia asociado con él.

2. El autor no proporciona garantías, explícitas o implícitas, en relación con la precisión, integridad o idoneidad de estos materiales para propósitos específicos.

3. El autor no es responsable por cualquier daño, incluyendo, pero no limitándose a, daños directos, indirectos, incidentales, colaterales o especiales, resultantes del uso o la imposibilidad de usar los materiales de este repositorio o la documentación acompañante, incluso si se ha notificado previamente sobre la posibilidad de tales daños.

4. Al usar estos materiales, usted acepta y asume todos los riesgos asociados con su uso. Además, acepta que el autor no puede ser considerado responsable de cualquier problema o consecuencia resultante de dicho uso.

</details> 

---

<h3 align="center"> 
💖 Apoye el proyecto 💖
</h3>

<details>
    <summary align="center"> 💖 AYUDE AL DESARROLLO DEL PROYECTO 💖 </summary>

---

<p align="center"> 
Si este proyecto le ha resultado útil, puede apoyarlo dándole una estrella.:star2: 
</p>

<h4 align="center"> 
Las donaciones son muy bienvenidas, independientemente de su tamaño. Muchas gracias. 😌 
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
  <sub> Gracias por su atención al proyecto y por su apoyo 💙 </sub>
</p>

</details>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

## 📚 Contenido

- [Introducción](#-introducción)

## 📦 Características
- Ejecución automática de tareas en `Discord PTB`  
- Muestra el progreso en la consola  
- Fácil de usar: copie el script en la consola para desarrolladores  
- Compatibilidad completa con `Discord`  

## 🔗 Enlaces útiles
- [Discord PTB](https://ptb.discord.com/) — la principal plataforma  


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 

# 🚀 Instalación y configuración

<h2 align="center">
  <a href="#-contenido">⬆️ Volver al contenido</a>
</h2>

## 1. Descargue `Discord PTB` del SERVIDOR OFICIAL.

```sh
https://ptb.discord.com/
```
## 2. Instale `Discord PTB`

## 3. Ejecute `Discord PTB`


<div align="center">
  <img style="width: 100%; height: auto;" alt="Discord PTB" src="../media/icon.png"/>
</div>


## 4. Diríjase a la sección `aventuras` y luego a la pestaña `Tareas` (Quests)

## 5. Ejecute la tarea

<div align="center">
  <img style="width: 400%; height: auto;" alt="Tareas Automáticas de Discord" src="../media/7-Automatic-Discord-tasks.png">
</div>

## 6. Presione `Ctrl+Shift+I` para abrir la consola de desarrollador.

## 7. Copie el script.

- [RU-Automatic-Discord-tasks](/RU-Automatic-Discord-tasks.md) Los registros en la consola estarán en ruso.

o

- [EN-Automatic-Discord-tasks](/EN-Automatic-Discord-tasks.md) Los registros en la consola estarán en inglés.
  
---

Si necesita algún ajuste adicional, no dude en pedírmelo. 😊

Aquí está la traducción del texto proporcionado al español:

---

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
const success = (msg) => log(`[SUCCESS] ${msg}`, '#00ff9d');
const info = (msg) => log(`[INFO]    ${msg}`, '#4da6ff');
const warn = (msg) => log(`[WARN]    ${msg}`, '#ffcc00');
const error = (msg) => log(`[ERROR]   ${msg}`, '#ff4d4d');

function progressBar(progress, total, width = 20) {
  const percent = Math.min(100, Math.floor((progress / total) * 100));
  const filled = Math.floor((width * progress) / total);
  const bar = '█'.repeat(filled) + '░'.repeat(width - filled);
  const timeLeft = Math.ceil((total - progress) / 60);
  return `[${bar}] ${progress}/${total} (${percent}%) • ${timeLeft} min left`;
}

if (quests.length === 0) {
  info("No active supported quests found. Check Discover → Quests.");
} else {
  console.groupCollapsed('%c🎮 Discord Quest Booster v2.1 – Active Tasks 🚀', 'color:#7289da; font-weight:bold; font-size:14px;');
  log(`Found ${quests.length} quest(s)`, '#7289da');
  quests.forEach((q, i) => {
    const task = Object.keys(q.config.taskConfig?.tasks || q.config.taskConfigV2.tasks || {})[0];
    const target = q.config.taskConfig?.tasks?.[task]?.target || 'unknown';
    log(`\nQuest ${i+1}: ${q.config.messages.questName} (${task})`, '#ffffff');
    log(`  Target: ${target} sec`, '#cccccc');
    log(`  Remaining: ~${Math.ceil((target - (q.userStatus?.progress?.[task]?.value || 0)) / 60)} min`, '#cccccc');
  });
  console.groupEnd();

  let doJob = function() {
    const quest = quests.pop();
    if (!quest) {
      console.log('%c═══════════════════════════════════════════════', 'color:#7289da');
      success('All supported quests completed! Enjoy your rewards ✨');
      console.log('%c═══════════════════════════════════════════════', 'color:#7289da');
      return;
    }

--- 

El script y las cadenas en código no se traducen porque ya están en inglés y no se especificó ninguna limitación en ese aspecto dentro del requerimiento. El resultado es una traducción específica solo del contexto en los comentarios, declaraciones de consola o notificaciones relevantes para un usuario. Si necesitas algo más o cambios adicionales, házmelo saber.
