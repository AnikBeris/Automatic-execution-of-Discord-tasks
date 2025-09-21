[English](/README.md) | [Русский](/README.ru_RU.md)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./media/logo-light.png">
    <img alt="Project Logo" src="./media/logo-light.png">
  </picture>
</p>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/AnikBeris)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](https://github.com/AnikBeris/AutoRoleChannelBot/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/your-repo?style=flat&logo=github&label=Звёзды&color=orange)](https://github.com/AnikBeris)

</div>

# Discord БОТ для очистки каналов и ролей

> **Отказ от ответственности:** Этот проект предназначен только для личного обучения и общения. Пожалуйста, не используйте его в незаконных целях и не применяйте в производственной среде.

**Если этот проект оказался полезным для вас, вы можете оценить его, поставив звёздочку.**:star2:

<p align="left">
  <a href="https://pay.cloudtips.ru/p/7249ba98" target="_blank">
    <img src="./media/buymeacoffe.png" alt="Image">
  </a>
</p>

Пожертвования горячо приветствуются, какими бы маленькими они ни были, и большое спасибо. 😌

- **Bitcoin (BTC)** - `1Dbwq9EP8YpF3SrLgag2EQwGASMSGLADbh`
- **Ethereum (ERC20)** - `0x22258ea591966e830199d27dea7c542f31ed5dc5`
- **Binance Smart Chain (BEP20)** - `0x22258ea591966e830199d27dea7c542f31ed5dc5`
- **Solana (SOL)** - `yYYXsiVTzsvfvsMnBxfxSZEWTGytjAViE2ojf3hbLeF`

## Возможности
- Удаление всех текстовых и голосовых каналов на сервере.
- Удаление всех ролей, кроме стандартной роли @everyone.
- Простая настройка через `config.json`.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./media/05-info-channel-del.gif">
    <img alt="Project Logo" src="./media/05-info-channel-del.gif">
  </picture>
</p>


# Установка

## Клонируем репозиторий
```bash
git clone https://github.com/AnikBeris/Auto-Discord-Cleaner.git
cd Auto-Discord-Cleaner
```

## Устанавливаем зависимости
```bash
pip install -r requirements.txt
```
## Запускаем бота
```bash
python bot.py
```

## 1. Создание Discord БОТА
1. Перейдите в [Портал Разработчиков Discord](https://discord.com/developers/applications).
2. Нажмите "New Application", введите название и сохраните.
3. Перейдите в "Bot" -> "Add Bot" -> Подтвердите.
4. Скопируйте **Токен** бота (он понадобится позже).
5. Включите **Привилегированные Интенты** (Присутствие, Участники сервера и Контент сообщений).

<details>
    <summary>🚨 Ошибка: PrivilegedIntentsRequired (недостаточно разрешений)</summary>

# Бот требует разрешений (privileged intents), которые не включены в панели разработчика.
---
## ✅ Как исправить?
### 1️⃣ Включите Privileged Intents в Discord Developer Portal
  1. Перейдите на Discord Developer Portal.
  2. Выберите ваше приложение (бота).
  3. Перейдите во вкладку "Bot" в левом меню.
  4. Найдите секцию "Privileged Gateway Intents" и включите:
     4.1. ✅ "PRESENCE INTENT" (необязательно)
     4.2. ✅ "SERVER MEMBERS INTENT" (обязательно)
     4.3. ✅ "MESSAGE CONTENT INTENT" (если используется анализ сообщений)
  5. "Save Changes".
### 2️⃣ Перезапустите бота
  1. Остановите работу бота (Ctrl + C в терминале).
  2. Запустите бота снова:

```bash
python bot+roles.py
```


</details>

---

## 2. Получение GUILD_ID
1. Включите режим разработчика в Discord (Настройки -> Расширенные -> Режим разработчика).
2. Кликните правой кнопкой по названию сервера и выберите "Копировать ID". Это ваш `GUILD_ID`.

---

## 3. Добавление бота на сервер
  1. Перейдите в **OAuth2** -> "URL Generator".
  2. Выберите **bot** и **applications.commands**.
  3. В разделе **Права Бота** выберите:
    - Управление ролями, управление каналами, чтение сообщений, отправка сообщений, подключение, разговор.
  4. Скопируйте сгенерированную ссылку и вставьте её в браузер.
  5. Выберите сервер и авторизуйте бота.

---

## 4. Настройка и запуск
  1. Откройте `config.json` и добавьте ваш **TOKEN** и **GUILD_ID**.
  2. Запустите бота:
   
```bash
   python bot.py
```
УСПЕХ! Бот начнёт очистку каналов и ролей!

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./media/05-info-channel-del.gif">
    <img alt="Project Logo" src="./media/05-info-channel-del.gif">
  </picture>
</p>



## License
This project is licensed under the [MIT License](https://github.com/your-repo/blob/main/LICENSE).

---

For detailed documentation, check out the [English README](/README.md) or [Русский README](/README_ru_RU.md).
