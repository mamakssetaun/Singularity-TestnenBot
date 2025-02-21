Вот перевод документации:

---

# SINGULARITY TESTNET BOT
**Бот для тестовой сети Singularity**

## Содержание
- [SINGULARITY TESTNET BOT](#singularity-testnet-bot)
  - [Содержание](#содержание)
  - [Предварительные требования](#предварительные-требования)
  - [Присоединяйтесь к моему Telegram-каналу](#присоединяйтесь-к-моему-telegram-каналу)
  - [Тестовая сеть Singularity Finance](#тестовая-сеть-singularity-finance)
  - [Функционал бота](#функционал-бота)
  - [Установка и настройка бота](#установка-и-настройка-бота)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Обновление бота](#обновление-бота)
  - [ВАЖНОЕ ПРИМЕЧАНИЕ (ЭТО НЕ ПРОСТО ДЕКОРАЦИЯ)](#важное-примечание-это-не-просто-декорация)
  - [Как внести вклад](#как-внести-вклад)
  - [Поддержка](#поддержка)

---

## Предварительные требования
- Git
- Node.js (версия 22)

---

## Присоединяйтесь к моему Telegram-каналу

Создан новый Telegram-канал для обмена ботами или участия в airdrop. Присоединяйтесь:
[**https://t.me/skeldrophunt**](https://t.me/skeldrophunt).

---

## Тестовая сеть Singularity Finance

- **Новая тестовая сеть: Singularity Finance**
  - **Получить тестовые токены SFI**: [https://faucet-testnet.singularityfinance.ai/](https://faucet-testnet.singularityfinance.ai/)
  - **Подключить новый кошелек**: [https://singularityfinance.ai/testnet](https://singularityfinance.ai/testnet)
  - **Завершить задания Zealy**: [https://zealy.io/cw/singularityfinance/invite/RIfAE_1sqVY_2x-Z-Dtd5](https://zealy.io/cw/singularityfinance/invite/RIfAE_1sqVY_2x-Z-Dtd5)

  ### Ежедневные задачи:
  - Получение тестовых токенов SFI.
  - Обмен токенов SFI → wSFI или другие.
  - Стейкинг 50%.
  - Получение награды.
  - Мост SFI.
  - Выполнение ежедневных задач в цепочке и в социальных сетях.

---

## Функционал бота
- Поддержка нескольких аккаунтов.
- Поддержка прокси.
- Поддержка приватных ключей и seed-фраз.
- Ежедневный мост.
- Ежедневный обмен (wrap/unwrap).
- Ежедневный стейкинг/анстейкинг.
- Ежедневное получение наград за стейкинг.

---

## Установка и настройка бота

### Linux
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/mamakssetaun/Singularity-TestnenBot.git && cd singularity-testnet-bot
   ```
2. Установите зависимости:
   ```bash
   npm install && npm run setup
   ```
3. Настройте аккаунты:
   ```bash
   nano accounts/accounts.js
   ```
4. Настройте конфигурацию бота:
   ```bash
   nano config/config.js
   ```
5. Запустите бота:
   ```bash
   npm run start
   ```

---

### Windows
1. Откройте `Командную строку` или `PowerShell`.
2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Widiskel/singularity-testnet-bot.git
   ```
3. Перейдите в директорию проекта:
   ```bash
   cd singularity-testnet-bot
   ```
4. Установите зависимости:
   ```bash
   npm install && npm run setup
   ```
5. Настройте аккаунты:
   - Откройте файл `accounts/accounts.js` и добавьте данные ваших аккаунтов.
6. Настройте конфигурацию:
   - Откройте файл `config/config.js` и внесите необходимые изменения.
7. Запустите бота:
   ```bash
   npm run start
   ```

---

## Обновление бота
Чтобы обновить бота:
1. Выполните:
   ```bash
   git pull
   ```
   или:
   ```bash
   git pull --rebase
   ```
   Если возникла ошибка:
   ```bash
   git stash && git pull
   ```
2. Обновите зависимости:
   ```bash
   npm update
   ```
3. Перезапустите бота.
4. Если возникнут ошибки, проверьте файл логов:
   ```
   log/app.log
   ```

---

## ВАЖНОЕ ПРИМЕЧАНИЕ (ЭТО НЕ ПРОСТО ДЕКОРАЦИЯ)
- **DWYOR**: Делайте всё на свой страх и риск.
- Всегда используйте **новый кошелек** при работе с ботом. Автор не несет ответственности за потерю активов.
- Если возникнет ошибка SQL, удалите файл `database.db`.
- Ошибки во время транзакций будут автоматически повторяться до успешного выполнения.
- У панели управления Singularity большая задержка, просто запустите и оставьте бот работать.

---

## Как внести вклад
Чувствуйте себя свободно форкать и добавлять новые функции. Спасибо!

---

## Поддержка
Хотите поддержать разработчика для создания новых ботов?
- **Поставьте звезду этому репозиторию!**
- Или отправьте донат:
  - EVM: `0xB1CacA160f950Cf3aAD2e4Fcd4f40dBa3CB779eb`
  - SOLANA: `SDajF7UECdY1jRjJXR9HGuyFHnwqhzAwXLsE3xuDtB5`

---

Если вам нужно больше помощи с настройкой, дайте знать! 😊
