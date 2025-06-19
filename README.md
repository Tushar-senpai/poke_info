# poke_info
# 🐾 Pokémon Card Generator

A fun and visually engaging web app that dynamically displays cards of the first 150 Pokémon using the [PokéAPI](https://pokeapi.co/). Each card showcases the Pokémon's official artwork, name, ID, and type, styled with type-based background colors.

## 🔥 Demo



![image](https://github.com/user-attachments/assets/5718bc5c-2c60-428f-9380-8f69306d790d)


## 🚀 Features

- Fetches real-time data for the first 150 Pokémon
- Displays Pokémon name, ID, image, and type
- Dynamically styled cards based on Pokémon type
- Responsive and clean layout using basic HTML/CSS
- Easy-to-understand and well-commented JavaScript code

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript (ES6+)
- [PokéAPI](https://pokeapi.co/)

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/pokemon-card-generator.git
   cd pokemon-card-generator
   
Open the project:

Open index.html in your browser

That's it! The cards will load automatically.


## ⚡ How It Works
Fetches data from https://pokeapi.co/api/v2/pokemon/{id} for each Pokémon ID (1–150).

Creates a card with the Pokémon's:

Official artwork

ID (padded to 3 digits)

Capitalized name

Type (e.g., Fire, Water, Grass)

Applies a background color based on the primary type.

Appends the card to the page.


## 💡 Improvements You Can Make
Add search/filter functionality by Pokémon name or type

Implement pagination or lazy loading

Use a CSS framework like Tailwind or Bootstrap for better styling

Add loading animations or skeletons while cards are being fetched

🙌 Acknowledgements
PokéAPI for the incredible free Pokémon data

Pokémon sprites © Nintendo / Game Freak

📄 License
This project is open-source and available under the MIT License.
