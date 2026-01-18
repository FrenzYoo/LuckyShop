# LuckyShop

LuckyShop is a modern and dynamic **GUI-based shop plugin** for Minecraft servers. Unlike traditional shops, it uses **randomized stock**, **time-based resets**, and a **single-menu buy & sell system** to create a more engaging and balanced economy.

---

## ✨ Features

* 🛒 **GUI Shop System** – Clean and simple inventory-based menu
* 🎲 **Randomized Stock** – Each item has a random stock between defined limits
* 💰 **Dynamic Economy** – Prices are based on a base value with configurable sell multipliers
* ⏰ **Automatic Market Resets** – Shop resets at specific times of the day
* 🔄 **Live Countdown** – Remaining time until next reset is shown in the menu
* 📦 **Stack-Based Trading** – Buy and sell items in predefined stack amounts
* 📖 **Info Book** – Built-in guide explaining how the shop works
* 🔊 **Sound Feedback** – Custom sounds for clicks, success, and errors
* 🌍 **Fully Configurable Messages** – Separate messages.yml with hex color support
* ⚡ **Lightweight & Performance Friendly**

---

## 🧠 How It Works

LuckyShop generates its shop items from a configurable **item pool**. For each reset:

* Items receive a **random stock amount**
* Prices are recalculated based on their base price
* The market is refreshed automatically at the configured reset times

Players interact with the shop using simple controls:

* **Left Click** → Buy items (stack-based)
* **Right Click** → Sell items
* **Shift + Right Click** → Sell all matching items from inventory

This system encourages strategic trading instead of unlimited buying and selling.

---

## ⚙️ Configuration

LuckyShop is fully configurable using YAML files.

### `config.yml`

* GUI size, title, and decoration
* Item pool and base prices
* Minimum & maximum stock values
* Stack size and item display amount
* Sell price multiplier
* Automatic reset times
* Sound settings

### `messages.yml`

* Prefix customization
* Player messages and errors
* Broadcast messages on market reset
* Full hex color code support

No coding knowledge is required to customize the plugin.

---

## 🎯 Use Cases

* Survival servers with controlled economies
* Skyblock servers with automated farming markets
* Servers that want a more realistic and dynamic shop system
* Economy-focused servers looking to prevent inflation

---

## 🛠️ Technologies Used

* Java
* Spigot / Paper API
* YAML Configuration

---

## 📌 Notes

* Designed to be simple for players and powerful for server owners
* Ideal replacement for static and unlimited shop systems

---

## 📄 License

This project is distributed under its own license. Please check the repository or resource page for usage terms.

---

Feel free to open issues or suggest improvements!
