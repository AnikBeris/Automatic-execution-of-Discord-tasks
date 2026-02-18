以下是翻译的内容：

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
[![GitHub Stars](https://img.shields.io/github/stars/AnikBeris?style=flat&logo=github&label=星标&color=orange)](https://github.com/AnikBeris)

</div>

<div align="center">
  <img src="../media/image0.gif" alt="SPACER" width="90%">
</div>


<h1 align="center"> 
Discord任务的自动执行
</h1>

<h1 align="center"> 
该脚本允许`自动执行Discord中的任务`，无需参与游戏。
</h1>

<h2 align="center">
> 💡 该材料的目的是更轻松地获取与游戏任务相关的奖励。
</h2>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



<h2 align="center">
⚠️ 免责声明 ⚠️
</h2>

<p align="center">
  开发者不对使用本项目可能造成的任何后果承担责任。<br>
  后果自负。
</p>

<details> 
    <summary align="center">⚠️ 完整免责声明 ⚠️</summary>
    
## 使用本仓库内容的后果自负。

1. 使用本仓库内容时，您自动同意与其相关的许可协议条款。

2. 开发者对材料的准确性、完整性或适用性未作任何明示或暗示的担保，且不对特定用途适用性负责。
   
3. 开发者不对任何损失负责，包括但不限于因使用或无法使用本仓库内容或伴随文档而直接、间接、附带或特殊的赔偿，即使已被告知可能导致此类损失。

4. 使用本仓库内容时，您承担所有相关风险。此外，用户同意开发者不对使用导致的任何问题或后果承担责任。

</details> 

---

<h3 align="center"> 
💖 支持项目 💖
</h3>

<details>
    <summary align="center"> 💖 助力项目发展 💖 </summary>

---

<p align="center"> 
如果这个项目对您有用，欢迎点个星星评价：star2: 
</p>

<h4 align="center"> 
再小的捐赠都非常欢迎，非常感谢。😌 
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
  <sub> 感谢您对本项目的关注与支持 💙 </sub>
</p>

</details>


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 



## 📚 目录

- [简介](#简介)



## 📦 功能
- 自动完成`Discord PTB`中的任务 (Quests)  
- 控制台显示进度信息  
- 简单易用——将脚本粘贴到开发者工具  
- 完全兼容`Discord` 



## 🔗 有用链接
- [Discord PTB](https://ptb.discord.com/) — 主平台  

  


* * * * * * * * * * * * * * * * * * 
* * * * * * * * * * * * * * * * * * 






# 🚀 安装与运行

<h2 align="center">
  <a href="#目录">⬆️ 返回目录</a>
</h2>

## 1. 从官方服务器下载`Discord PTB`。

```sh
https://ptb.discord.com/
```
## 2. 安装`Discord PTB`

## 3. 启动`Discord PTB`


<div align="center">
  <img style="width: 20%; height: auto;" alt="Discord PTB" src="../media/icon.png"/>
</div>


## 4. 转到“探索”部分，然后进入任务选项卡 (Quests)

## 5. 开始任务

<div align="center">
  <img style="width: 50%; height: auto;" alt="Automatic-Discord-tasks" src="../media/7-Automatic-Discord-tasks.png">
</div>

## 6. 按下`Ctrl+Shift+I` 打开开发者控制台

## 7. 复制脚本内容

- [RU-Automatic-Discord-tasks](/RU-Automatic-Discord-tasks.md) 控制台日志将显示为俄语

或

- [EN-Automatic-Discord-tasks](/EN-Automatic-Discord-tasks.md) 控制台日志将显示为英语

```

以下是您提供的JavaScript代码的中文翻译：

```javascript
删除窗口.$;
let wpRequire = webpackChunkdiscord_app.push([[Symbol()], {}, r => r]);
webpackChunkdiscord_app.pop();

let ApplicationStreamingStore = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.getStreamerActiveStreamMetadata).exports.Z;
let RunningGameStore = Object.values(wpRequire.c).find(x => x?.exports?.ZP?.getRunningGames).exports.ZP;
let QuestsStore = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.getQuest).exports.Z;
let ChannelStore = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.getAllThreadsForParent).exports.Z;
let GuildChannelStore = Object.values(wpRequire.c).find(x => x?.exports?.ZP?.getSFWDefaultChannel).exports.ZP;
let FluxDispatcher = Object.values(wpRequire.c).find(x => x?.exports?.Z?.__proto__?.flushWaitQueue).exports.Z;
let api = Object.values(wpRequire.c).find(x => x?.exports?.tn?.get).exports.tn;

// 从QuestsStore中筛选任务
let quest = [...QuestsStore.quests.values()].find(x => x.id !== "1248385850622869556" && x.userStatus?.enrolledAt && !x.userStatus?.completedAt && new Date(x.config.expiresAt).getTime() > Date.now());
let isApp = typeof DiscordNative !== "undefined";

if (!quest) {
    console.log("您没有未完成的任务！");
} else {
    const pid = Math.floor(Math.random() * 30000) + 1000;

    const applicationId = quest.config.application.id;
    const applicationName = quest.config.application.name;
    const taskName = ["WATCH_VIDEO", "PLAY_ON_DESKTOP", "STREAM_ON_DESKTOP", "PLAY_ACTIVITY", "WATCH_VIDEO_ON_MOBILE"].find(x => quest.config.taskConfigV2.tasks[x] != null);
    const secondsNeeded = quest.config.taskConfigV2.tasks[taskName].target;
    let secondsDone = quest.userStatus?.progress?.[taskName]?.value ?? 0;

    if (taskName === "WATCH_VIDEO" || taskName === "WATCH_VIDEO_ON_MOBILE") {
        const maxFuture = 10, speed = 7, interval = 1;
        const enrolledAt = new Date(quest.userStatus.enrolledAt).getTime();

        let fn = async () => {
            while (true) {
                const maxAllowed = Math.floor((Date.now() - enrolledAt) / 1000) + maxFuture;
                const diff = maxAllowed - secondsDone;
                const timestamp = secondsDone + speed;
                
                if (diff >= speed) {
                    await api.post({ url: `/quests/${quest.id}/video-progress`, body: { timestamp: Math.min(secondsNeeded, timestamp + Math.random()) } });
                    secondsDone = Math.min(secondsNeeded, timestamp);
                }

                if (timestamp >= secondsNeeded) {
                    break;
                }
                await new Promise(resolve => setTimeout(resolve, interval * 1000));
            }
            console.log("任务完成！");
        };

        fn();
        console.log(`开始模拟播放视频，任务： ${applicationName}。`);
    } else if (taskName === "PLAY_ON_DESKTOP") {
        if (!isApp) {
            console.log("这种任务无法在浏览器中完成，请使用桌面版 Discord 来完成 ", applicationName, " 任务！");
        } else {
            api.get({ url: `/applications/public?application_ids=${applicationId}` }).then(res => {
                const appData = res.body[0];
                const exeName = appData.executables.find(x => x.os === "win32").name.replace(">", "");

                const fakeGame = {
                    cmdLine: `C:\\Program Files\\${appData.name}\\${exeName}`,
                    exeName,
                    exePath: `c:/program files/${appData.name.toLowerCase()}/${exeName}`,
                    hidden: false,
                    isLauncher: false,
                    id: applicationId,
                    name: appData.name,
                    pid: pid,
                    pidPath: [pid],
                    processName: appData.name,
                    start: Date.now(),
                };

                const realGames = RunningGameStore.getRunningGames();
                const fakeGames = [fakeGame];
                const realGetRunningGames = RunningGameStore.getRunningGames;
                const realGetGameForPID = RunningGameStore.getGameForPID;

                RunningGameStore.getRunningGames = () => fakeGames;
                RunningGameStore.getGameForPID = (pid) => fakeGames.find(x => x.pid === pid);
                FluxDispatcher.dispatch({ type: "RUNNING_GAMES_CHANGE", removed: realGames, added: [fakeGame], games: fakeGames });

                let fn = data => {
                    let progress = quest.config.configVersion === 1 
                        ? data.userStatus.streamProgressSeconds 
                        : Math.floor(data.userStatus.progress.PLAY_ON_DESKTOP.value);

                    console.log(`任务进度： ${progress}/${secondsNeeded}`);
                    
                    if (progress >= secondsNeeded) {
                        console.log("任务完成！");
                        
                        RunningGameStore.getRunningGames = realGetRunningGames;
                        RunningGameStore.getGameForPID = realGetGameForPID;
                        FluxDispatcher.dispatch({ type: "RUNNING_GAMES_CHANGE", removed: [fakeGame], added: [], games: [] });
                        FluxDispatcher.unsubscribe("QUESTS_SEND_HEARTBEAT_SUCCESS", fn);
                    }
                };

                FluxDispatcher.subscribe("QUESTS_SEND_HEARTBEAT_SUCCESS", fn);
                console.log(`模拟游戏：${applicationName}。还需等待 ${Math.ceil((secondsNeeded - secondsDone) / 60)} 分钟。`);
            });
        }
    } else if (taskName === "STREAM_ON_DESKTOP") {
        if (!isApp) {
            console.log("这种任务无法在浏览器中完成，请使用桌面版 Discord 来完成 ", applicationName, " 任务！");
        } else {
            let realFunc = ApplicationStreamingStore.getStreamerActiveStreamMetadata;
            ApplicationStreamingStore.getStreamerActiveStreamMetadata = () => ({
                id: applicationId,
                pid,
                sourceName: null
            });

            let fn = data => {
                let progress = quest.config.configVersion === 1 
                    ? data.userStatus.streamProgressSeconds 
                    : Math.floor(data.userStatus.progress.STREAM_ON_DESKTOP.value);

                console.log(`任务进度：${progress}/${secondsNeeded}`);
                
                if (progress >= secondsNeeded) {
                    console.log("任务完成！");
                    ApplicationStreamingStore.getStreamerActiveStreamMetadata = realFunc;
                    FluxDispatcher.unsubscribe("QUESTS_SEND_HEARTBEAT_SUCCESS", fn);
                }
            };

            FluxDispatcher.subscribe("QUESTS_SEND_HEARTBEAT_SUCCESS", fn);
            console.log(`你的直播将被模拟成 ${applicationName}。请在语音频道中等待 ${Math.ceil((secondsNeeded - secondsDone) / 60)} 分钟。`);
            console.log("请确保语音频道中至少还有一个人！");
        }
    } else if (taskName === "PLAY_ACTIVITY") {
        const channelId = ChannelStore.getSortedPrivateChannels()[0]?.id ?? Object.values(GuildChannelStore.getAllGuilds()).find(x => x != null && x.VOCAL.length > 0).VOCAL[0].channel.id;
        const streamKey = `call:${channelId}:1`;

        let fn = async () => {
            console.log("完成任务：", applicationName, "-", quest.config.messages.questName);

            while (true) {
                const res = await api.post({ url: `/quests/${quest.id}/heartbeat`, body: { stream_key: streamKey, terminal: false } });
                const progress = res.body.progress.PLAY_ACTIVITY.value;
                console.log(`任务进度：${progress}/${secondsNeeded}`);
                
                await new Promise(resolve => setTimeout(resolve, 20 * 1000));
                
                if (progress >= secondsNeeded) {
                    await api.post({ url: `/quests/${quest.id}/heartbeat`, body: { stream_key: streamKey, terminal: true } });
                    break;
                }
            }

            console.log("任务完成！");
        };

        fn();
    }
}
```
