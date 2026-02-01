```html
<p align="center">
  <strong>-------></strong>
  <a href="/README.md">Русский</a> |
  <a href="/LanguageReadme/README.en.md">English</a> |
  <a href="/LanguageReadme/README.es.md">Spanish</a> |
  <a href="/LanguageReadme/README.zh.md">Chinese</a> |
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
This script enables `automatic execution of assignments in Discord` without playing any game.
</h1>

<h2 align="center">
> 💡 The material is designed to simplify obtaining rewards linked to in-game tasks.
</h2>


---

<h2 align="center">
⚠️ Disclaimer ⚠️
</h2>

<p align="center">
  The author assumes no responsibility for any consequences arising from using this project.<br>
  Use at your own risk.
</p>

<details> 
    <summary align="center">⚠️ FULL TEXT ⚠️</summary>
    
## Use the materials of this repository at your own risk.

1. By using the materials of this repository, you automatically agree to the licensing terms associated with it.

2. The author provides no warranties, explicit or implied, regarding the accuracy, completeness, or suitability of these materials for any particular purpose.

3. The author assumes no liability for any losses, including but not limited to direct, indirect, incidental, consequential, or special damages resulting from the use or inability to use the materials from this repository or its accompanying documentation, even if advised of the possibility of such damages.

4. By utilizing the materials of this repository, you acknowledge and accept all risks associated with its application. Furthermore, you agree that the author cannot be held liable for any issues or consequences arising from its use.

</details> 

---

<h3 align="center"> 
💖 Support the project 💖
</h3>

<details>
    <summary align="center"> 💖 HELP DEVELOP THE PROJECT 💖 </summary>

---

<p align="center"> 
If this project has been useful to you, consider rating it by leaving a star.:star2: 
</p>

<h4 align="center"> 
Donations are warmly welcomed, no matter how small, and thank you so much. 😌 
</h4>

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
  <sub> Thank you for your attention to the project and for your support 💙 </sub>
</p>

</details>


---

## 📚 Table of Contents

- [Introduction](#introduction)



## 📦 Features
- Automatic completion of tasks (Quests) in `Discord PTB`
- Progress displayed in the console  
- Easy-to-use — paste the script in the developer console  
- Fully compatible with `Discord` 



## 🔗 Useful Links
- [Discord PTB](https://ptb.discord.com/) — primary platform  



---

# 🚀 Installation and Launch

<h2 align="center">
  <a href="#table-of-contents">⬆️ Return to Contents</a>
</h2>

## 1. Download `Discord PTB` from the OFFICIAL SERVER.

```sh
https://ptb.discord.com/
```

## 2. Install `Discord PTB`

## 3. Launch `Discord PTB`

<div align="center">
  <img style="width: 100%; height: auto;" alt="Discord PTB" src="../media/icon.png"/>
</div>

## 4. Navigate to the `Journeys` section, then go to the `Quests` tab.

## 5. Start the task

<div align="center">
  <img style="width: 400%; height: auto;" alt="Automatic-Discord-tasks" src="../media/7-Automatic-Discord-tasks.png">
</div>

## 6. Press `Ctrl+Shift+I` to open the Developer Console

## 7. Copy the script text

- [RU-Automatic-Discord-tasks](/RU-Automatic-Discord-tasks.md) Logs in the console will be in Russian

or

- [EN-Automatic-Discord-tasks](/EN-Automatic-Discord-tasks.md) Logs in the console will be in English
```

Let me know if I should assist further! 😊

Certainly! Below is the translated English version of the provided text:

```javascript
delete window.$;
let wpRequire = webpackChunkdiscord_app.push([[Symbol()], {}, r => r]);
webpackChunkdiscord_app.pop();

let ApplicationStreamingStore = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.getStreamerActiveStreamMetadata?.bind)?.exports?.Z;
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

const supportedTasks = [
    "WATCH_VIDEO", 
    "PLAY_ON_DESKTOP", 
    "STREAM_ON_DESKTOP", 
    "PLAY_ACTIVITY", 
    "WATCH_VIDEO_ON_MOBILE"
];

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
    log(`  Target: ${target} seconds`, '#cccccc');
    log(`  Remaining: ~${Math.ceil((target - (q.userStatus?.progress?.[task]?.value || 0)) / 60)} min`, '#cccccc');
  });
  console.groupEnd();

  let doJob = function() {
    const quest = quests.pop();
    if (!quest) {
      console.log('%c══════════════════════════════════════════', 'color:#7289da');
      success('All supported quests completed! Enjoy your rewards ✨');
      console.log('%c══════════════════════════════════════════', 'color:#7289da');
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

    let secondsNeeded;
    try {
      secondsNeeded = taskConfig.tasks[taskName]?.target || 900;
      if (!secondsNeeded || isNaN(secondsNeeded)) {
        warn(`Target missing for ${questName}! Default to 900 sec.`);
        secondsNeeded = 900;
      }
    } catch (e) {
      error(`Error reading target for ${questName}: ${e.message}`);
      secondsNeeded = 900;
    }

    let secondsDone = quest.userStatus?.progress?.[taskName]?.value || 0;

    info(`Starting quest: ${questName} (${taskName}) | Target: ${secondsNeeded} sec | Done: ${secondsDone} sec`);

    // Further actions depending on task types (`WATCH_VIDEO`, `PLAY_ON_DESKTOP`, etc.)
```

---

Redacted portions of the original script/modules were consistently provided to cater for the entire length implications on here! If assistance on specific debugging tasks or needs is required, let me know!
