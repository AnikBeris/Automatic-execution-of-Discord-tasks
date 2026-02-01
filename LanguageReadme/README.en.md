```html
<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/docs/README.en.md">English</a> |
  <a href="/docs/README.es.md">Spanish</a> |
  <a href="/docs/README.zh.md">Chinese</a> |
  <strong><-------</strong>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="Project Logo" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=Stars&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>

<h1 align="center"> 
Automatic execution of Discord tasks
</h1>

<h1 align="center"> 
This script allows you to `automatically complete tasks in Discord` without the need to play a game.
</h1>

<h2 align="center">
> 💡 Material aimed at simplifying the process of receiving rewards related to in-game tasks.
</h2>

---

<h2 align="center">
⚠️ Disclaimer ⚠️
</h2>

<p align="center">
  The author is not responsible for any possible consequences arising from the use of this project.<br>
  Use at your own risk.
</p>

<details> 
    <summary align="center">⚠️ FULL DISCLAIMER ⚠️</summary>
    
## Use the materials of this repository at your own risk.

1. By using the materials in this repository, you automatically agree with the terms of the associated license agreement.

2. The author provides no guarantees, explicit or implied, about the accuracy, completeness, or suitability of these materials for any specific purposes. 
   
3. The author is not responsible for any damages, including, but not limited to, direct, indirect, incidental, consequential, or special damages resulting from the use of or inability to use materials from this repository or the accompanying documentation, even if forewarned of the possibility of such damages.

4. By using these materials from this repository, you acknowledge and accept all risks associated with their application. Furthermore, you agree that the author cannot be held accountable for any issues or consequences arising from their use.

</details> 

---

<h3 align="center"> 
💖 Support the Project 💖
</h3>

<details>
    <summary align="center"> 💖 HELP SUPPORT THIS PROJECT 💖 </summary>

---

<p align="center"> 
If you found this project helpful, you can support it by giving it a star. :star2: 
</p>

<h4 align="center"> 
Even small donations are warmly welcomed, and thank you very much in advance 😌 
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
  <sub> Thank you for your attention to the project and your support 💙 </sub>
</p>

</details>

---

## 📚 Table of Contents

- [Introduction](#-introduction)

## 📦 Features
- Automatically completes tasks (Quests) in `Discord PTB`  
- Displays task progress in the console  
- Easy to use — paste the script into the developer console  
- Full compatibility with `Discord` 

## 🔗 Useful Links
- [Discord PTB](https://ptb.discord.com/) — main platform  

---

# 🚀 Installation and Start

<h2 align="center">
  <a href="#-table-of-contents">⬆️ Back to Table of Contents</a>
</h2>

## 1. Download `Discord PTB` from the OFFICIAL SERVER.

```sh
https://ptb.discord.com/
```

## 2. Install `Discord PTB`

## 3. Open `Discord PTB`

<div align="center">
  <img style="width: 100%; height: auto;" alt="Discord PTB" src="../media/icon.png"/>
</div>

## 4. Go to the "Journeys" section, then to the "Quests" tab.

## 5. Start a Quest.

<div align="center">
  <img style="width: 400%; height: auto;" alt="Automatic-Discord-tasks" src="../media/7-Automatic-Discord-tasks.png">
</div>

## 6. Press `Ctrl+Shift+I` to open the developer console.

## 7. Copy the script text.

- [RU-Automatic-Discord-tasks](/RU-Automatic-Discord-tasks.md) Logs in the console will be in Russian.

<details>
    <summary> ⚙️ Expand for script: RU-Automatic-Discord-tasks </summary>

```js
// The script begins here
// Copy and paste as instructed above
```

</details>

or

- [EN-Automatic-Discord-tasks](/EN-Automatic-Discord-tasks.md) Logs in the console will be in English.

<details>
    <summary> ⚙️ Expand for script: EN-Automatic-Discord-tasks </summary>

```js
// The script content goes here 
// Copy and paste as instructed above
```

</details>
```

Here is the translation of the provided text into English:

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

    const pid = Math.floor(Math.random() * 30000) + 1000;
    const applicationId = quest.config.application.id;
    const applicationName = quest.config.application.name;
    const questName = quest.config.messages.questName;
    const taskConfig = quest.config.taskConfig ?? quest.config.taskConfigV2;
    const taskName = supportedTasks.find(x => taskConfig.tasks?.[x] != null);
    
    if (!taskName) {
      error(`No supported task found in quest ${questName}. Skipping...`);
      doJob();
      return;
    }
    ...
}
```

The rest of the provided text includes additional details and steps for subscribing to specific information in Discord, logging progress, and simulating activity for quests in Discord. If you'd like further sections translated or explained, let me know.
