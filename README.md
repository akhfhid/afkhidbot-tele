<<<<<<< HEAD
# afkhidbot-tele

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Telegraf](https://img.shields.io/badge/Telegraf-29B6F6?style=for-the-badge&logo=telegram&logoColor=white)

**afkhidbot-tele** is a lightweight, feature-rich Telegram bot built using Node.js and the Telegraf framework. It comes packed with various utilities, AI integrations, media downloaders, and fun features to enhance your Telegram experience.

## 🚀 Features

### 🤖 Artificial Intelligence
- **ChatGPT**: Chat with an advanced AI assistant.
- **Gemini**: Integration with Google's Gemini AI.
- **Flux & Text2Image**: Generate images from text descriptions.
- **Remini**: Enhance and clarify images.
- **Colorize**: Add color to black and white photos.

### 📥 Media Downloaders
- **YouTube**: Download MP3 and MP4 from YouTube.
- **TikTok**: Download TikTok videos without watermarks.
- **Instagram**: Download posts, reels, and stories.
- **Spotify**: Download music from Spotify.
- **Pinterest**: Download images and videos from Pinterest.
- **Twitter/X**: Download media from Twitter.
- **Facebook**: Download videos from Facebook.
- **SoundCloud**: Download tracks from SoundCloud.
- **Threads**: Download content from Threads.

### 🕵️ Stalking Tools
- **GitHub Stalker**: Get user profile information from GitHub.
- **Instagram Stalker**: View Instagram user details.
- **TikTok Stalker**: Analyze TikTok profiles.
- **Twitter Stalker**: Get Twitter user info.

### 🛠 Utilities & Tools
- **Anime Finder**: Search for anime information.
- **Gempa Info**: Get the latest earthquake info (BMKG).
- **Grow Garden**: Fun gardening mini-game/info.
- **Ping**: Check bot latency.
- **Uploader**: Upload files to the cloud.
- **Say**: Text-to-speech or message repeater.

### 🎮 XP & RPG System
- **Registration**: User registration system.
- **Profile**: View user stats and profile.
- **Limit**: Daily limit system for bot usage.
- **Unregister**: Delete user data.

## 🛠 Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/akhfhid/afkhidbot-tele.git
    cd afkhidbot-tele
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Configuration**
    - Rename `config.example.js` to `config.js`.
    - Open `config.js` and update the required fields (Bot Token, API Keys, etc.).

    ```javascript
    // config.js
    module.exports = {
        botToken: 'YOUR_TELEGRAM_BOT_TOKEN',
        ownerId: 'YOUR_TELEGRAM_USER_ID',
        // ... other configurations
    };
    ```

4.  **Start the bot**
    ```bash
    npm start
    ```

## ⚙️ Configuration

The bot is highly configurable via `config.js`. Make sure to provide valid API keys for the services you intend to use (e.g., OpenAI, Gemini, etc.).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

# afkhidbot-tele

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Telegraf](https://img.shields.io/badge/Telegraf-29B6F6?style=for-the-badge&logo=telegram&logoColor=white)

**afkhidbot-tele** is a lightweight, feature-rich Telegram bot built using Node.js and the Telegraf framework. It comes packed with various utilities, AI integrations, media downloaders, and fun features to enhance your Telegram experience.

## 🚀 Features

### 🤖 Artificial Intelligence
- **ChatGPT**: Chat with an advanced AI assistant.
- **Gemini**: Integration with Google's Gemini AI.
- **Flux & Text2Image**: Generate images from text descriptions.
- **Remini**: Enhance and clarify images.
- **Colorize**: Add color to black and white photos.

### 📥 Media Downloaders
- **YouTube**: Download MP3 and MP4 from YouTube.
- **TikTok**: Download TikTok videos without watermarks.
- **Instagram**: Download posts, reels, and stories.
- **Spotify**: Download music from Spotify.
- **Pinterest**: Download images and videos from Pinterest.
- **Twitter/X**: Download media from Twitter.
- **Facebook**: Download videos from Facebook.
- **SoundCloud**: Download tracks from SoundCloud.
- **Threads**: Download content from Threads.

### 🕵️ Stalking Tools
- **GitHub Stalker**: Get user profile information from GitHub.
- **Instagram Stalker**: View Instagram user details.
- **TikTok Stalker**: Analyze TikTok profiles.
- **Twitter Stalker**: Get Twitter user info.

### 🛠 Utilities & Tools
- **Anime Finder**: Search for anime information.
- **Gempa Info**: Get the latest earthquake info (BMKG).
- **Grow Garden**: Fun gardening mini-game/info.
- **Ping**: Check bot latency.
- **Uploader**: Upload files to the cloud.
- **Say**: Text-to-speech or message repeater.

### 🎮 XP & RPG System
- **Registration**: User registration system.
- **Profile**: View user stats and profile.
- **Limit**: Daily limit system for bot usage.
- **Unregister**: Delete user data.

## 🛠 Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/akhfhid/afkhidbot-tele.git
    cd afkhidbot-tele
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Configuration**
    - Rename `config.example.js` to `config.js`.
    - Open `config.js` and update the required fields (Bot Token, API Keys, etc.).

    ```javascript
    // config.js
    module.exports = {
        botToken: 'YOUR_TELEGRAM_BOT_TOKEN',
        ownerId: 'YOUR_TELEGRAM_USER_ID',
        // ... other configurations
    };
    ```

4.  **Start the bot**
    ```bash
    npm start
    ```

## ⚙️ Configuration

The bot is highly configurable via `config.js`. Make sure to provide valid API keys for the services you intend to use (e.g., OpenAI, Gemini, etc.).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the ISC License.

## 👤 Author

**Affan Khulafa Hidayah**
- 🌐 Website: [akhfhid.my.id](https://akhfhid.my.id)
=======
# afkhid-telebot

A modern Telegram bot built with Telegraf v4 (ESM), a modular plugin system, and a lightweight JSON database (LowDB). It includes hot‑reload for plugins and a tiny HTTP status endpoint.

## Highlights

- Node.js ESM + Telegraf v4
- Modular plugins in `plugins/` with hot-reload
- JSON database via bundled LowDB (no external DB)
- Role/permission helpers (owner, admin, premium)
- Daily command limit system (auto reset)
- Small HTTP status server with auto port selection

## Getting Started

### Requirements
- Node.js v20+
- A Telegram Bot Token from [@BotFather](https://t.me/BotFather)

### Quick start
1) Clone the repository
```powershell
git clone https://github.com/akhfhid/afkhidbot-tele.git
cd afkhidbot
```

2) Install dependencies
```powershell
npm install
```

3) Configure your bot
- Copy `config.example.js` to `config.js`
- Edit `config.js` and set at least:
  - `global.token` with your BotFather token
  - `global.ownername`, `global.ownerid` (comma/space separated or array)

4) Run the bot
```powershell
npm start
```

On start you’ll see OS/RAM info, the HTTP status port, and the plugin summary. The status endpoint responds on `/` with a small JSON.

## Configuration

All settings live in `config.js` (see `config.example.js` for defaults).

- token: Telegram bot token string
- ownername: Your display name
- ownerid: Single ID or a list of owner IDs (string/array)
- premid: Premium user IDs (optional)
- botname: Public bot name used in messages
- prefix: Array of prefixes, e.g. `['/','.', '#','!']`
- wib: Time offset (hours) for some date/time helpers
- message: Common error/guard messages
- ports: List of ports the tiny HTTP server will try in order
- limit: Default daily command limit per user
- APIs / APIKeys: External API base URLs and keys, e.g. `ryzumi: https://api.ryzumi.vip`

Security tips
- Don’t commit secrets. Prefer editing `config.js` locally copied from `config.example.js`.
- Rotate tokens/keys if they ever leak.

## Database

- File: `database.json` (auto-created on first run)
- Backend: LowDB JSON file (bundled under `lib/lowdb/`)
- Auto-save interval: ~15s
- Daily limit reset: handled internally for each user

Back up `database.json` regularly if you care about the data.

## Plugin System

Plugins live in `plugins/` and are hot‑reloaded on change. A plugin can be a function export and may attach metadata used by the core handler.

Minimal plugin example
```js
// plugins/hello.js
export default async function (m, { conn }) {
  await m.reply('Hello World!')
}

// Optional metadata used by the handler
export const command = /^(hello|hi)$/i
export const tags = ['main'] // for your own grouping/menus
```

Supported fields (attach as named exports or properties on the default function):
- command: string | RegExp | (string | RegExp)[] — matcher for the command (required to trigger)
- customPrefix: string | RegExp | (string | RegExp)[] — override global prefixes
- before(m, extras): optional pre-hook; return false to skip
- after(m, extras): optional post-hook
- exp: number — XP awarded (default 17)
- limit: boolean | number — consume N limits (true = 1)
- rowner, owner, premium, group, private, admin: booleans to guard command

Handler parameters
- m: normalized message object with helpers like `m.reply(text)`
- extras: `{ conn, args, text, command, usedPrefix, isOwner, isPrems, isAdmin, isBotAdmin, participants }`

Explore existing examples in `plugins/`.

## HTTP Status Endpoint

`index.js` starts a tiny Express server and auto-picks the first open port from `global.ports`. Hitting `/` returns a small JSON to verify the bot is alive.

## Troubleshooting

- “Telegraf library is not installed”: run `npm install` again.
- Stuck on token error: ensure `global.token` in `config.js` is set and valid.
- Node version: must be 20+. Check with `node -v`.

## Attribution

This project is adapted and refactored for ESM and Telegraf v4 by Akhfhid.

Original author and repository (base work):
- ERLANRAHMAT — https://github.com/ERLANRAHMAT/telebot-wa

The codebase also references “Original Script by BETABOTZ” in logs. We extend thanks to the original authors and contributors.

## License

ISC License © Akhfhid.

>>>>>>> 0adeebb884d3a210190d89a1422cd43a7fa10b50
