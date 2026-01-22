# Pok-monCards
<!-- ===================== -->

<!--  ⭐ GitHub README.md  -->

<!-- ===================== -->

<div align="center">

# 🃏 Pokémon Cards Viewer

### Fetch Pokémon cards by **type** and **count** using the PokéAPI

<p>
  <img src="https://img.shields.io/badge/HTML-✔️-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CSS-✔️-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JavaScript-✔️-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/API-PokéAPI-success?style=for-the-badge" />
</p>

<p>
A clean and interactive Pokémon card generator where users can select a Pokémon **type**, choose how many Pokémon they want, and instantly fetch beautiful cards ✨  
Includes a 🌙 **Night Mode Toggle** for extra vibes.
</p>

<br/>

<img src="https://raw.githubusercontent.com/PokeAPI/media/master/logo/pokeapi_256.png" width="160" alt="PokeAPI Logo"/>

</div>

---

## 🚀 Features

✅ Fetch Pokémon cards dynamically from **PokéAPI**
✅ Choose number of Pokémon (**1 to 20**)
✅ Filter Pokémon by type:

* 🔥 Fire
* 🌊 Water
* 🌿 Grass
* ⚡ Electric
* 🔮 Psychic

✅ Displays for each Pokémon:

* Name
* Image sprite
* Types
* Base Experience

✅ 🌙 Toggle Night Mode (Dark theme)
✅ Responsive grid layout (auto adjusts based on screen size)

---

## 📸 Preview (Demo)

> You can add screenshots/gifs here after uploading them to your repo

Example:

```md
![Preview](./preview.png)
```

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (Grid Layout)
* **Vanilla JavaScript**
* **PokéAPI** (REST API)

---

## 📂 Project Structure

```bash
📁 pokemon-cards-viewer
 ┣ 📄 index.html
 ┗ 📄 README.md
```

---

## ⚙️ How It Works

### 🔍 Fetch Pokémon Data

When you click **"Get Pokémon"**, it:

1. Reads selected **type** + **count**
2. Calls:

   ```
   https://pokeapi.co/api/v2/type/{type}
   ```
3. Gets Pokémon list for that type
4. Fetches details for each Pokémon using its `url`
5. Creates UI cards dynamically

---

## 🧪 Run Locally

### ✅ Option 1: Simple Run

1. Download / clone this repo
2. Open `index.html` in browser

### ✅ Option 2: Run using Live Server (recommended)

If you're using VS Code:

1. Install **Live Server**
2. Right click `index.html`
3. Click **Open with Live Server**

---

## 🌙 Dark Mode Toggle

Click the button:

```html
<button id="toggleBtn">🌙 Toggle Night Mode</button>
```

It toggles the class:

```js
document.body.classList.toggle("dark-mode");
```

---

## 🔗 API Used

**PokéAPI** — free Pokémon REST API
📌 Docs: [https://pokeapi.co/](https://pokeapi.co/)

---

## 🚧 Error Handling

If API fails (e.g., no internet):
✅ UI shows:

> `Failed to fetch Pokémon! Check your Connection`

---

## ✨ Future Improvements (Optional Ideas)

* 🔎 Search Pokémon by name
* 🎴 Add card animations / hover effects
* ⭐ Add favorite Pokémon system
* 📦 Add loading spinner instead of plain text
* 🎨 More types (ice, dragon, ghost...)

---

## 🙌 Credits

* API: [PokéAPI](https://pokeapi.co/)
* Pokémon images via PokéAPI sprites

---

## 📜 License

This project is open-source and free to use for learning & personal projects.
If you like it, ⭐ the repo!

---

<div align="center">

### 🧠 Made with 💛 + JavaScript

**Gotta Fetch ’Em All!** 🐉⚡🔥🌊🌿

</div>
