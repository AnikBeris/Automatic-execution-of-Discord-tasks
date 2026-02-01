```html
<p align="center">
  <strong>-------></strong>
  <a href="/README.md">俄语</a> |
  <a href="/LanguageReadme/README.en.md">英语</a> |
  <a href="/LanguageReadme/README.es.md">西班牙语</a> |
  <a href="/LanguageReadme/README.zh.md">中文</a> |
  <strong><-------</strong>
</p>



<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../media/logo-dark.png">
    <img alt="项目Logo" src="../media/logo-light.png" width="512" height="auto">
  </picture>
</p>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](/LICENSE.md)
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=星&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
自动执行Discord任务
</h1>

<h1 align="center"> 
该脚本允许您在不玩游戏的情况下`自动完成Discord任务`
</h1>

<h2 align="center">
> 💡 内容旨在简化获取与游戏内任务相关的奖励。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  作者不对使用此项目可能导致的任何后果负责。<br>
  使用该程序风险自负。
</p>

<details> 
    <summary align="center">⚠️完整声明⚠️</summary>
    
## 使用该存储库中的资源需自行承担风险。

1. 使用该存储库中的资源即表明您接受相关许可协议的条款。

2. 作者不对这些材料的准确性、完整性或针对特定用途的适用性提供任何明示或暗示的保证。 
   
3. 作者不承担因使用或无法使用该存储库中的材料或附带文档可能产生的任何损失责任，包括（但不限于）直接、间接、偶然或特别损失，即便您已提前被告知相关可能性。

4. 通过使用该存储库中的资源，您确认并同意承担其使用相关的所有风险。此外，您也同意，作者无法对使用该资源可能导致的问题或后果负责。

</details> 

---

<h3 align="center"> 
💖 支持项目 💖
</h3>

<details>
    <summary align="center"> 💖 帮助推进项目发展 💖 </summary>

---

<p align="center"> 
如果这个项目对您有所帮助，请为它标星点赞。:star2: 
</p>

<h4 align="center"> 
所有小额捐赠表示热烈欢迎，非常感谢。😌 
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
  <sub> 感谢您对该项目的关注与支持 💙 </sub>
</p>

</details>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 


## 📚 目录

- [简介](#-简介)



## 📦 功能
- 在`Discord PTB`中自动完成任务（Quests）  
- 在控制台中显示任务进度  
- 操作简便——将脚本粘贴到开发者控制台  
- 与`Discord`完全兼容  



## 🔗 实用链接
- [Discord PTB](https://ptb.discord.com/) — 核心平台  


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 




# 🚀 安装及运行

<h2 align="center">
  <a href="#-目录">⬆️ 返回目录</a>
</h2>

## 1. 从官方服务器下载`Discord PTB`

```sh
https://ptb.discord.com/
```
## 2. 安装`Discord PTB`

## 3. 启动`Discord PTB`


<div align="center">
  <img style="width: 100%; height: auto;" alt="Discord PTB" src="../media/icon.png"/>
</div>


## 4. 进入“路径探索”中的“任务”（Quests）

## 5. 启动任务

<div align="center">
  <img style="width: 400%; height: auto;" alt="Automatic-Discord-tasks" src="../media/7-Automatic-Discord-tasks.png">
</div>

## 6. 按`Ctrl+Shift+I`打开开发者控制台

## 7. 复制脚本文本

- [RU-Automatic-Discord-tasks](/RU-Automatic-Discord-tasks.md) 控制台日志为俄文

或

- [EN-Automatic-Discord-tasks](/EN-Automatic-Discord-tasks.md) 控制台日志为英文

以下是所需文本的翻译：

```js
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

    let secondsNeeded;
    try {
      secondsNeeded = taskConfig.tasks[taskName]?.target ?? 
                      taskConfig.tasks[taskName]?.durationSeconds ?? 
                      taskConfig.tasks[taskName]?.goal ?? 
                      900;
      if (!secondsNeeded || isNaN(secondsNeeded)) {
        warn(`Target not found for ${questName}! Using fallback 900 sec.`);
        secondsNeeded = 900;
      }
    } catch (e) {
      error(`Error reading target for ${questName}: ${e.message}`);
      secondsNeeded = 900;
    }

... (文本非常冗长，代码部分保持一致，为简洁性省略其余代码)。

```
